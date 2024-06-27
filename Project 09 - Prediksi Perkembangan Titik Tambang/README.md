### Deskripsi Proyek
OilyGiant adalah perusahaan tambang dan sedang mencari tempat terbaik untuk mengembangkan 200 titik sumur minyak baru. 

Data eksplorasi geologi untuk ketiga wilayah disimpan dalam beberapa file:
1. `geo_data_0.csv`
2. `geo_data_1.csv`
3. `geo_data_2.csv`
4. id — ID unik sumur minyak
5. f0, f1, f2 — tiga fitur titik wilayah (makna spesifiknya sebenarnya tidak penting, tetapi fitur itu sendiri sangat penting) product — volume cadangan di dalam sumur minyak (1 unit = 1.000 barel).

### Tujuan
1. Mencari titik lokasi terbaik untuk dilakukan pengembangan
2. Mengestimasi keuntungan yang dihasilkan
3. Menghitung resiko keuntungan dan kerugian

### Tahapan
Untuk menyelesaikan tugas ini, langkah-langkah yang harus dilakukan adalah sebagai berikut:
1. Baca file dengan parameter yang dikumpulkan dari sumur-sumur minyak di wilayah terpilih: kualitas minyak dan volume cadangannya;
2. Buat sebuah model untuk memprediksi volume cadangan di sumur-sumur baru;
3. Pilih sumur minyak yang memiliki nilai estimasi tertinggi;
4. Pilih wilayah dengan total keuntungan tertinggi dari sumur minyak yang dipilih,
5. Ada data sampel minyak dari tiga wilayah dan parameter setiap sumur minyak di wilayah tersebut sudah diketahui. Buat sebuah model yang akan membantu memilih wilayah dengan margin keuntungan tertinggi. Gunakan teknik bootstrapping untuk menganalisis potensi keuntungan dan risiko.

Instruksi Proyek
1. Unduh dan siapkan datanya. Jelaskan prosedur yang kamu lakukan.
2. Latih dan uji model untuk setiap wilayah
3. Lakukan persiapan untuk menghitung laba
4. Buat sebuah fungsi untuk menghitung laba dari kumpulan sumur minyak terpilih dan prediksi model:
5. Hitung keuntungan untuk volume pemesanan yang diterima

Kondisi:
1. Hanya regresi linear yang bisa digunakan untuk pelatihan model.
2. Anggaran untuk pengembangan 200 sumur minyak ini adalah 100 juta dolar.
3. Satu barel minyak mentah menghasilkan pendapatan sebesar 4,5 dolar. Nah, pendapatan dari satu unit produk adalah $4.500 (volume cadangan ditulis dalam ribuan barel).

Setelah menganalisis risiko yang ada, hanya wilayah yang memiliki risiko kerugian kurang dari 2,5% dipertahankan. Di antara semua yang sesuai dengan kriteria, akan dipilih wilayah dengan keuntungan rata-rata tertinggi.


| Projek | Deskripsi | Modul |
| ------- | ------- | ------- |
| [Prediksi Pengembangan Lokasi Tambang](https://github.com/vikrayudha/Project_TripleTen/blob/main/Project%2009%20-%20Prediksi%20Perkembangan%20Titik%20Tambang/Project_9.ipynb)) | Memprediksi lokasi untuk pengembangan titik lokasi tambang tidak berdasarkan lokasi : `geo0`, `geo1` dan `geo2`. | *pandas*, *seaborn*, *numpy*, *matplotlib*, *scikit-learn*|
