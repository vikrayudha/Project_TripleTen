### Deskripsi Proyek
Perusahaan operator telekomunikasi bernama Megaline menawarkan kliennya dua jenis paket prabayar, yaitu paket Surf dan paket Ultimate. Departemen periklanan ingin mengetahui paket prabayar mana yang menghasilkan lebih banyak pendapatan, sehingga mereka bisa membuat anggaran iklan yang sesuai.
Akan dilakukan analisis awal untuk paket-paket prabayar tersebut berdasarkan sampel klien yang berukuran relatif kecil. Terdapat 500 data klien Megaline, yang berisi informasi seperti: siapa mereka, dari mana asalnya, jenis paket apa yang mereka gunakan, serta jumlah panggilan dan pesan yang mereka kirim di tahun 2018. Tugas Anda adalah untuk menganalisis perilaku para pengguna, lalu menentukan paket prabayar manakah yang lebih menguntungkan.

### Tujuan
Dataset yang dimiliki perusahaan Megaline diantaranya berisi `calls`, `internet`, `messages`, `plans` dan `users` yang semuanya memiliki informasi yang penting untuk analisis projek ini. Tujuan dari projek ini adalah selain untuk mencari pendapatan terbanyak dari kedua paket prabayar tersebut namun juga menganalisis prilaku pengguna seperti durasi telepon, jumlah sms dan jumlah penggunaan data internet terhadap kedua paket prabayar tersebut. Beberapa hipotesis diajukan sebagai berikut:
1. Benarkah untuk kategori durasi telepon terbanyak dalam satu bulan dimiliki oleh Paket Ultimate?
2. Benarkah untuk kategori jumlah sms terbanyak dalam satu bulan dimiliki oleh Paket Ultimate?
3. Berapakah rata-rata penggunaan kisaran jumlah data internet per bulan untuk kedua tipe Paket Prabayar?
4. Benarkah jumlah pendapatan terbanyak dari pengguna per bulan dimiliki oleh Paket Ultimate?
5. Benarkah Pendapatan Rata-rata dari Pengguna Paket Prabayar Ultimate dan Surf Berbeda?
7. Benarkah Pendapatan Rata-rata dari Pengguna di Wilayah NY-NJ dengan Wilayah Lain adalah Berbeda?

### Tahapan
data tersimpan dalam beberapa file path: 
1. `/datasets/megaline_calls.csv`
2. `/datasets/megaline_internet.csv` 
3. `/datasets/megaline_messages.csv` 
4. `/datasets/megaline_plans.csv` 
5. `/datasets/megaline_users.csv`

Proyek ini terdiri dari beberapa tahap:
 1. Pra-pemrosesan data
 2. Analisis Syarat dan Ketentuan
 3. Pengujian hipotesis

| Projek | Deskripsi | Modul |
| ------- | ------- | ------- |
| [Analisis Pemilihan Kartu Prabayar](https://github.com/vikrayudha/Project_TripleTen/blob/main/Project%2004%20-%20Pemilihan%20Paket%20Kartu%20Prabayar/Project_4.ipynb) | Menganalisis prilaku pengguna terhadap kedua paket prabayar berdasarkan kriteria: `calls`, `messages`, `internet`, dan  `user_amount`. | *pandas*, *seaborn*, *matplotlib*, *numpy*, *scipy*, *math*|
