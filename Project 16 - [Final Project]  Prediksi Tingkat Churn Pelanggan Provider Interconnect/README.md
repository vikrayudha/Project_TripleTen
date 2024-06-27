### Deskripsi Proyek
Operator telekomunikasi bernama Interconnect ingin meramalkan tingkat churn klien mereka. Jika diketahui bahwa seorang klien berencana untuk berhenti, klien tersebut akan ditawari kode promosi dan opsi paket khusus. Tim pemasaran Interconnect telah mengumpulkan beberapa data pribadi klien, termasuk informasi tentang paket data yang dipilih dan kontrak mereka.

Layanan Interconnect
* Interconnect menyediakan dua jenis layanan utama:
- Jaringan telepon rumah. Telepon bisa disambungkan ke beberapa saluran secara bersamaan.
- Internet. Jaringan internet dapat diatur melalui saluran telepon (DSL, digital subscriber line) atau melalui kabel serat optik.

Beberapa layanan lain yang disediakan Interconnect meliputi:
- Keamanan Internet: perangkat lunak antivirus (DeviceProtection) dan pemblokir situs web berbahaya (OnlineSecurity)
- Jalur dukungan teknis khusus (TechSupport)
- Penyimpanan cloud untuk file dan backup data (OnlineBackup)
- Streaming TV (StreamingTV) dan direktori film (StreamingMovies)

Klien dapat memilih untuk melakukan pembayaran secara bulanan atau menandatangani kontrak untuk berlangganan selama 1 atau 2 tahun. Mereka bisa menggunakan beragam metode pembayaran dan menerima tagihan elektronik setelah melakukan transaksi.

### Tujuan
1. Mengetahui tingkat churn klien
2. Mengetahui layanan apa saja yang digemari klien
3. Mengetahui Metode pembayaran dan tipe paket yang digemari pelanggan
4. mengetahui kemungkinan alasan pelanggan berhenti berlangganan
5. Mencari model terbaik untuk prediksi churn klien

### Tahapan
Data yang tersedia terdiri dari beberapa file yang didapat dari sumber berbeda:
- contract.csv — 󠀰informasi kontrak
- personal.csv — 󠀰data personal klien
- internet.csv — informasi tentang layanan Internet
- phone.csv — informasi tentang layanan telepon

Pada setiap file, ada kolom customerID dengan kode unik yang ditetapkan untuk setiap klien. Informasi kontrak berlaku per tanggal 1 Februari 2020.

1. Mempersiapkan Data
2. Analisa Data
3. Melatih model
Model-model yang digunakan diantaranya: `Logistic Regression`, `Random Forest`,`Gradient Boosting`, `Support Vektor Machine`, `Artificial Neural Network`

| Projek | Deskripsi | Modul |
| ------- | ------- | ------- |
| [Analisis Prediksi Churn Pelanggan Provider Interconnect](https://github.com/) | Model prediksi akan menganalisis tingkat churn pelanggan dengan menggunakan model `Logistic Regression`, `Random Forest`,`Gradient Boosting`, `Support Vektor Machine`, `Artificial Neural Network` | *pandas*, *numpy*, *sklearn*, *matplotlib*, *seaborn*, *tensorflow*, *joblib, *datetime* | 

