### Deskripsi Proyek

Data yang dibutuhkan tersimpan dalam tiga file:
- `gold_recovery_train.csv`
- `gold_recovery_test.csv`
- `gold_recovery_full.csv`

Data ini diindeks sesuai dengan tanggal dan waktu perolehannya (fitur date). Terkait waktu, parameter yang letaknya bersebelahan umumnya bersifat mirip. Sebagian parameter tidak tersedia karena pengukuran dan/atau penghitungannya dilakukan jauh setelahnya sehingga beberapa fitur yang ada di training set mungkin tidak ada di test set. Test set-nya pun juga tidak memuat target. Dataset sumber memuat training dan test set dengan semua fitur-fiturnya.

Sebagai catatan, data yang ada adalah data mentah yang baru saja diunduh dari gudang data. Sebelum membuat model, periksa ketepatan data tsb. 

Proses teknologi
- Rougher feed — bahan mentah untuk proses flotasi
- Rougher additions (atau reagent additions) — reagen untuk flotasi: Xanthate, Sulphate, Depressant
- Xanthate — penggerak atau aktivator flotasi
- Sulphate — natrium sulfida, khusus untuk proses ini
- Depressant — natrium silikat
- Rougher process — flotasi
- Rougher tails — residu produk
- Float banks — unit flotasi
- Cleaner process — pemurnian
- Rougher Au — konsentrat emas yang lebih kasar
- Final Au — konsentrat emas akhir

Parameter dari setiap tahapan yang tersedia
- air amount — volume udara
- fluid levels
- feed size — ukuran partikel umpan
- feed rate

Penamaan fitur
Berikut merupakan cara untuk memberikan nama pada fitur-fitur yang ada:
[stage].[parameter_type].[parameter_name]
Contoh: rougher.input.feed_ag

Nilai yang memungkinkan untuk [stage]:
- rougher — flotasi
- primary_cleaner — pemurnian pertama
- secondary_cleaner — pemurnian kedua
- final — karakteristik akhir

Nilai yang memungkinkan untuk [parameter_type]:
- input — parameter bahan mentah
- output — parameter produk
- state — parameter yang menunjukkan karakteristik tahapan saat ini
- calculation — perhitungan karakteristik

### Tujuan
1. Mengetahui pengaruh konsentrasi logam (Au, Ag, Pb) pada tahap pemurniannya
2. Membandingkan distribusi ukuran partikel feed
3. Mengetahui model terbaik dengan nilai sMAPE yang baik

### Tahapan
Instruksi Proyek
1. Siapkan datanya
2. Lakukan pra-pemrosesan data.
3. Analisis datanya
- 3.1. Buat catatan terkait bagaimana konsentrasi logam (Au, Ag, Pb) berubah, tergantung pada tahap pemurniannya.
- 3.2. Bandingkan distribusi ukuran partikel feed dalam training set dan test set.
- 3.3. Pertimbangkan total konsentrasi semua substansi di tahap yang berbeda: feed mentah, konsentrasi yang lebih kasar, dan konsentrasi akhir. 
4. Buat modelnya
- 4.1. Buat sebuah fungsi yang digunakan untuk menghitung nilai sMAPE akhir.
- 4.2. Lakukan pelatihan pada model yang berbeda-beda. Evaluasi model-model tersebut menggunakan cross-validation. Pilih model terbaik dan uji model tersebut menggunakan sampel tes atau test sample.



| Projek | Deskripsi | Modul |
| ------- | ------- | ------- |
| [Prediksi Kualitas Logam Emas](https://github.com/) | Memprediksi kualitas logam emas berdasarkan tahapan produksinya: `rougher`, `primary_cleaner`, `secondary_cleaner` dan `final`. | *pandas*, *seaborn*, *numpy*, *matplotlib*, *scikit-learn*|
