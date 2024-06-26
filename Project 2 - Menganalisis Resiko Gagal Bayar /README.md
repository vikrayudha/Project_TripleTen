### Deskripsi Proyek
Tugas kali ini adalah menyiapkan laporan untuk divisi kredit suatu bank. Dicari tahu pengaruh status perkawinan seorang nasabah dan jumlah anak yang dimilikinya terhadap probabilitas gagal bayar dalam pelunasan pinjaman. Pihak bank sudah memiliki beberapa data mengenai kelayakan kredit nasabah.

Laporanmu akan dipertimbangkan pada saat membuat **penilaian kredit** untuk calon nasabah. **Penilaian kredit** digunakan untuk mengevaluasi kemampuan calon peminjam untuk melunasi pinjaman mereka.

### Tujuan: 
Menguji empat hipotesis:
1. Mengetahui hubungan antara memiliki anak dan probabilitas seseorang melakukan gagal bayar pinjaman
2. Mengetahui hubungan antara status perkawinan dan probabilitas seseorang melakukan gagal bayar pinjaman
3. Mengetahui hubungan antara tingkat pendapatan dan probabilitas seseorang melakukan gagal bayar pinjaman
4. Mengetahui tujuan pinjaman memengaruhi probabilitas seseorang melakukan gagal bayar pinjaman

### Tahapan
Data terkait pengguna disimpan dalam file `/datasets/credit_scoring_eng.csv`. Tidak ada informasi terkait kualitas data tersebut, karena itu kamu perlu memeriksanya terlebih dahulu sebelum menguji hipotesis.

Pertama-tama, kamu akan mengevaluasi kualitas data dan melihat apakah masalahnya signifikan. Kemudian, selama pra-pemrosesan data, kamu akan mencoba mengatasi masalah yang paling serius.
 
Proyek ini terdiri dari tiga tahap:
 1. Mengeksplorasi data
 2. Mentransformasi data
 3. Mengategorikan data
 4. Melakukan pengujian hipotesis

| Projek | Deskripsi | Modul |
| ------- | ------- | ------- |
| [Analisis Gagal Bayar Nasabah](https://github.com/) | Mengetahui seberapa besar resiko `gagal bayar` nasabah berdasarkan kriteria: `tingkat pendapatan`, `status keluarga`, `tujuan cicilan` dan `jumlah anak` untuk menilai calon nasabah. | *pandas*, *numpy* |
