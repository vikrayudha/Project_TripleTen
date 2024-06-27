### Deskripsi Proyek
Operator seluler Megaline merasa tidak puas karena sebagian besar pelanggan mereka masih menggunakan paket lama. Perusahaan tersebut ingin mengembangkan sebuah model yang bisa menganalisis perilaku konsumen dan merekomendasikan salah satu dari kedua paket terbaru Megaline: Smart atau Ultra.
Data perilaku para pelanggan yang sudah beralih ke paket terbaru terdapat pada dataset baru yang dapat diakses. Dalam tugas klasifikasi ini, perlu dikembangkan sebuah model yang mampu memilih paket dengan tepat.
Untuk itu dibutuhkan sebuah model dengan tingkat accuracy yang setinggi-tingginya. Ambang batas untuk tingkat accuracy adalah `0,75`.

### Tujuan
Beberapa Hipotesis:
1. Mencari model terbaik dari beberapa model machine learning.
2. Mengetahui `sanity check` terhadap model terbaik.

### Tahapan
File path: `/datasets/users_behavior.csv`.
1. Tinjauan data
2. Pra-pemrosesan data
3. Pisahkan data sumber menjadi `training set`, `validation set`, dan `test set`.
4. Periksa kualitas model yang berbeda dengan mengubah hyperparameter. 
5. Periksa kualitas model menggunakan test set.

| Projek | Deskripsi | Modul |
| ------- | ------- | ------- |
| [Analisis Perilaku Pengguna Operator](https://github.com/) | Menganalisis perilaku pengguna provider Megaline berdasarkan : `calls`, `minutes`, `messages`, `mb_usage`, dan `is_ultimate`. | *pandas*, *numpy*, *scikit-learn*|
