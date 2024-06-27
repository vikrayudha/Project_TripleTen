### Deskripsi Proyek
Nasabah Bank Beta pergi meninggalkan perusahaan: sedikit demi sedikit, jumlah mereka berkurang setiap bulannya. Para pegawai bank menyadari bahwa akan lebih menghemat biaya jika perusahaan fokus untuk mempertahankan nasabah lama mereka yang setia daripada menarik nasabah baru.
Pada kasus ini, akan diprediksi apakah seorang nasabah akan segera meninggalkan bank atau tidak. Dataset berisikan ata terkait perilaku para klien di masa lalu dan riwayat pemutusan kontrak mereka dengan bank.

Model dengan skor F1 semaksimal mungkin. Untuk bisa dinyatakan lulus dari peninjauan, diperlukan skor F1 minimal `0,59` untuk test dataset.
Selain itu, akan diukur metrik `AUC-ROC` dan bandingkan metrik tersebut dengan skor F1.

### Tujuan
1. Menentukan model terbaik diantara beberapa model yang dipilih.
2. Melakukan uji F1 dan AUC-ROC terhadap model.

### Tahapan
Data yang butuhkan bisa ditemukan di file `/datasets/Churn.csv`.

1. Unduh dan siapkan datanya. 
2. Periksa keseimbangan setiap kelas (class balance).  
3. Tingkatkan kualitas model. Pastikan menggunakan setidaknya dua pendekatan untuk memperbaiki ketidakseimbangan kelas (imbalance class).
4. Gunakan training dan validation set untuk menemukan model terbaik serta kumpulan parameter terbaik. Jelaskan temuanmu secara singkat. 
5. Gunakan training set untuk memilih parameter terbaik. Tingkatkan kualitas model dengan memperhatikan ketidakseimbangan kelas (imbalance class) Latih beberapa model yang berbeda dan temukan yang terbaik.
6. Jalankan pengujian terakhir.

| Projek | Deskripsi | Modul |
| ------- | ------- | ------- |
| [Analisis Churn Nasabah Bank](https://github.com/) | Memprediksi apakah seorang nasabah akan segera meninggalkan bank atau tidak berdasarkan : `creditscore`, `tenure`, `isactivemember` dan `exited`. | *pandas*, *seaborn*, *numpy*, *scikit-learn*|
