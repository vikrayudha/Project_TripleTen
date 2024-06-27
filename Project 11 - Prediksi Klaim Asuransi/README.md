### Deskripsi Proyek
Perusahaan asuransi bernama "Sure Tomorrow" ingin menyelesaikan beberapa masalah dengan bantuan *machine learning*. Evaluasi kemungkinan tersebut.

### Tujuan
- Tugas 1: Temukan klien yang mirip dengan kriteria klien tertentu. Tugas ini akan memudahkan perusahaan untuk melakukan pemasaran.
- Tugas 2: Prediksi apakah klien baru kemungkinan akan mengambil klaim asuransi. Apakah prediksi model lebih baik daripada prediksi model *dummy*?
- Tugas 3: Prediksi besaran klaim asuransi yang mungkin diterima klien baru menggunakan model regresi linear.
- Tugas 4: Lindungi data pribadi klien tanpa merusak model dari tugas sebelumnya. Sangatlah penting untuk mengembangkan algoritme transformasi data yang dapat mencegah penyalahgunaan informasi pribadi klien jika data tersebut jatuh ke tangan yang salah. Hal ini disebut penyembunyian data atau pengaburan data. Namun, prosedur perlindungan datanya pun perlu diperhatikan agar kualitas *model machine* learning tidak menurun. Perhatikan bahwa algoritme sudah bekerja secara akurat.

### Tahapan
1. Inisialisasi Data
2. Analisa Data
3. Menemukan Klien yang mirip dengan kriteria tertentu
4. Memprediksi kemungkinan klien baru mengambil asuransi
5. Memprediksi klaim asuransi yang mungkin diterima
6. Melindungi data pribadi klien
   
| Projek | Deskripsi | Modul |
| ------- | ------- | ------- |
| [Prediksi Klaim Asuransi](https://github.com/vikrayudha/Project_TripleTen/blob/main/Project%2011%20-%20Prediksi%20Klaim%20Asuransi/Project_11.ipynb) | Model prediksi `klaim asuransi` pada `perusahaan asuransi` menggunakan algoritma `k-nearest neighbor` dan `linear regression`. Pengaburan data (`data protection`) dilakukan untuk menjaga privasi klien jika terjadi kebocoran data. | *pandas*, *numpy*, *sklearn*, *matplotlib*, *seaborn*, *math*, $\LaTeX$ |
