### Deskripsi Proyek
Perusahaan taksi bernama Sweet Lift telah mengumpulkan data historis tentang pesanan taksi di bandara. Untuk menarik lebih banyak pengemudi pada jam sibuk, perlu memprediksi jumlah pesanan taksi untuk satu jam berikutnya. Buat model untuk prediksi seperti itu.

Metrik RMSE pada *test set* tidak boleh lebih dari 48.

### Tujuan
1. Menganalisis dataset untuk mendapatkan `insights` berupa fitur-fitur `time series` seperti analisis `tren`, `seasonality` dan `residu`.
2. Menguji `metrik RMSE` pada `semua model` menggunakan data `test`.
3. Membuat prediksi untuk bulan `september` tahun 2018 menggunakan `best model`.


### Tahapan
Data tersimpan di file `taxi.csv`. Jumlah pesanan di kolom `num_orders`.
1. Unduh data dan lakukan *resampling* dalam satu jam.
2. Analisis datanya.
3. Latih model yang berbeda dengan hiperparameter yang berbeda pula. Sampel tes harus 10% dari *dataset* awal.
4. Uji data menggunakan sampel tes dan berikan kesimpulan.


| Projek | Deskripsi | Modul |
| ------- | ------- | ------- |
| [Prediksi Pesanan Taksi Bandara](https://github.com) | Perbandingan `model machine learning` untuk memprediksi `jumlah pesanan` pada perusahaan taksi menggunakan `dataset seri waktu` untuk mendapatkan skor `RMSE` yang `tidak lebih besar dari 48` | *pandas*, *numpy*, *sklearn*, *matplotlib*, *seaborn*, *XGBoost*, *time*, *LightGBM*, *statsmodels* |

