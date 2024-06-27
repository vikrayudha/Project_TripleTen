### Deskripsi Proyek
Toko online "Ice" yang menjual video game dari seluruh dunia. Data terkait ulasan pengguna dan ahli game, genre, platform (misalnya, Xbox atau PlayStation), dan data historis penjualan game tersedia dari open source. Identifikasi pola-pola yang menentukan apakah suatu game bisa dikatakan berhasil atau tidak. Dengan begitu, bisa ditenemukan game yang paling potensial dan merencanakan kampanye iklannya.
Terdapat data dari tahun 2016, dan akan merancang kampanye iklan untuk tahun 2017

Dataset ini memuat singkatan ESRB. ESRB merupakan singkatan dari Entertainment Software Rating Board, yaitu sebuah organisasi regulator mandiri yang mengevaluasi konten game dan memberikan rating usia seperti Remaja atau Dewasa.

### Tujuan
Beberapa Hipotesis:
1. Rata-rata rating pengguna platform Xbox One dan PC adalah sama. 
2. Rata-rata rating pengguna genre Action dan Sports berbeda.

### Tahapan
File path: `/datasets/games.csv`

Proyek ini terdiri dari tiga tahap:
 1. Tinjauan data
 2. Pra-pemrosesan data
 3. Melakukan Pemrofilan Pengguna
 4. Pengujian hipotesis

| Projek | Deskripsi | Modul |
| ------- | ------- | ------- |
| [Analisis Iklan Platform Game](https://github.com/vikrayudha/Project_TripleTen/blob/main/Project%2005%20-%20Analisis%20Iklan%20Game/Project%205.ipynb) | Menganalisis Data Penjualan game berdasarkan : `platform`, `genre`, `critic_score`, `user_score`, dan `rating`. | *pandas*, *seaborn*, *matplotlib*, *numpy*, *scipy*, *math*|
