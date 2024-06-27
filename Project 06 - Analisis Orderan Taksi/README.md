### Deskripsi Proyek
Perusahaan Zuber mengeluarkan kebijakan berbagi tumpangan (ride-sharing) baru yang diluncurkan di Chicago. Tentukan pola pada informasi untuk memahami preferensi penumpang dan dampak faktor eksternal terhadap perjalanan.

### Tujuan
- Mengetahui apakah cuaca mempengrauhi jumlah penjemputan.
- Mengetahui lokasi terbanyak yang mendapatkan orderan.

### Tahapan
Database yang memuat informasi perjalanan taksi di Chicago:
`project_sql_result_01.csv`. File ini memuat data berikut:
- company_name: nama perusahaan taksi
- trips_amount: jumlah perjalanan untuk setiap perusahaan taksi pada tanggal 15-16 November 2017

`project_sql_result_04.csv`. File ini memuat data berikut:
- dropoff_location_name: nama wilayah di Chicago tempat perjalanan berakhir
- average_trips: jumlah rata-rata perjalanan yang berakhir di setiap wilayah pada bulan November 2017

`project_sql_result_07.csv` — hasil dari kueri terakhir. File ini memuat data perjalanan dari Loop ke Bandara Internasional O'Hare dengan kolom-kolom yang ada di tabel ini:
- start_ts -- tanggal dan waktu penjemputan
- weather_conditions -- kondisi cuaca saat perjalanan dimulai
- duration_seconds -- durasi perjalanan dalam satuan detik

| Projek | Deskripsi | Modul |
| ------- | ------- | ------- |
| [Analisis Perilaku Konsumen Taksi](https://github.com/vikrayudha/Project_TripleTen/blob/main/Project%2006%20-%20Analisis%20Orderan%20Taksi/Project_6.ipynb) | Menganalisis preferensi penumpang terhadap perjalnan berdasarkan : `dropoff_location_name`, `trips_amount`, dan `weather_conditions`. | *pandas*, *numpy*, *scipy*, *math*|
