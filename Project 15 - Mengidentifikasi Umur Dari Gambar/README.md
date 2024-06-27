### Deskripsi Proyek
Suatu `waralaba supermarket` bernama `Good Seed` ingin mengetahui apakah `Data Science` dapat membantu mereka mematuhi hukum dengan memastikan bahwa mereka tidak menjual produk yang memiliki `batasan usia` kepada pelanggan `di bawah umur`. Toko-toko dari waralaba ini dilengkapi dengan kamera di area kasir yang akan menampilkan sinyal ketika seseorang membeli produk dengan `batasan usia`. Metode `visi komputer` bisa digunakan untuk menentukan `usia seseorang` dari `foto`. Kita akan membuat dan melatih model untuk menyelesaikan projek ini dengan menggunakan `deep learning`. Kita akan menggunakan `Convolutional Neural Network (CNN)` yang populer untuk mengenali foto yaitu `ResNet50` dengan menggunakan parameter dari `imagenet`. Metrik yang digunakan untuk evaluasi model diantaranya metrik `loss` adalah `MSE`, dan metrik `scoring` adalah `MAE`. Untuk mendapatkan model dengan kualitas yang bagus, maka metrik `MAE-validation` harus dibawah `8`.

### Tujuan
1. Mengidentifikasi pelanggan berdasarkan umurnya

### Tahapan
1. Tinjauan Data
2. Analisis
3. Pemodelan
4. Pengujian


| Projek | Deskripsi | Modul |
| ------- | ------- | ------- |
| [Visi Komputer Menggunakan ResNet50](https://github.com/) | Membuat model `deep learning - CNN` menggunakan `ResNet50` untuk menentukan `usia seseorang` berdasarkan foto. Metrik untuk evaluasi model diantaranya metrik `loss` adalah `MSE`, dan metrik `scoring` adalah `MAE`. Skor untuk `MAE-validation` harus dibawah `8`. | *pandas*, *matplotlib*, *seaborn*, *tensorflow*, *keras*, *ResNet50* |
