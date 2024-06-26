### Deskripsi Proyek
Perusahaan Crankshaft List memiliki ratusan iklan kendaraan gratis ditayangkan di situs web perusahaan setiap harinya. Pelajari data yang telah dikumpulkan selama beberapa tahun terakhir guna menentukan faktor-faktor yang memengaruhi harga sebuah kendaraan.

### Tujuan
Menguji beberapa hipotesis:
1. Apakah iklan mobil yang ditayangkan paling lama ditayangkan pada 30 hari?
2. Apakah tipe kendaraan mempengaruhi jumlah promosi iklan?
3. Apakah mobil keluarga cenderung sering diiklankan?
4. Apakah kondisi dan usia kendaraan mempengaruhi harga jual kendaraan?
5. Apakah mobil dengan warna putih cenderung mempengaruhi jumlah iklan yang ditayangkan?

Data disimpan dalam file `'/datasets/vehicles_us.csv'`. Tidak ada informasi terkait kualitas data tersebut, karena itu diperlukan pemeriksaan terlebih dahulu sebelum menguji hipotesis.

Pertama-tama, kita akan mengevaluasi kualitas data dan melihat apakah masalahnya signifikan. Kemudian, kita akan mengatasi masalah yang paling serius.
 
Proyek ini terdiri dari beberapa tahap:
 1. Pra-pemrosesan data
 2. Memperbaiki kualitas data
 3. Mempelajari parameter inti
 4. Mempelajari dan menangani outliers
 5. Mepelajari parameter inti tanpa outliers
 4. Menguji data

| Projek | Deskripsi | Modul |
| ------- | ------- | ------- |
| [Analisis Faktor Penjualan Mobil](https://github.com/) | Analisis faktor-faktor yang mempengaruhi harga penjualan mobil. Beberapa faktor diantaranya `model_year`, `model`, `condition`, `cylinders`, `fuel`, `odometer`, `transmission`, `type`, `paint_color`, `is_4wd`. | *pandas*, *seaborn* *matplotlib* *numpy* |
