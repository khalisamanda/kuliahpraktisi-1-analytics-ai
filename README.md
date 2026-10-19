# Implementasi Data Analytics dan Machine Learning untuk Analisis dan Prediksi Penjualan Retail

## Ringkasan

Proyek ini menganalisis transaksi retail untuk mengetahui tren penjualan, produk yang paling banyak terjual, serta membangun model machine learning sederhana untuk memprediksi penjualan harian berdasarkan data historis.

## Dataset

- **Nama:** Online Retail
- **Sumber resmi:** UCI Machine Learning Repository
- **Halaman dataset:** https://archive.ics.uci.edu/dataset/352/online+retail
- **Jumlah observasi:** 541.909 transaksi
- **Periode data:** Desember 2010–Desember 2011
- **Referensi:** Chen, D. (2015). *Online Retail*. UCI Machine Learning Repository. https://doi.org/10.24432/C5BW33

Notebook mengunduh dataset dari sumber publik dan mengolahnya menggunakan Python.

## Tujuan

1. Memeriksa struktur dan kualitas data transaksi.
2. Membersihkan data transaksi yang tidak valid dan transaksi pembatalan.
3. Menganalisis tren penjualan dari waktu ke waktu.
4. Mengidentifikasi produk dengan penjualan tertinggi.
5. Membangun model baseline untuk prediksi penjualan harian.
6. Mengevaluasi hasil prediksi menggunakan metrik regresi.

## Metode dan metrik

- Data cleaning dan pemeriksaan nilai tidak valid.
- Perhitungan nilai penjualan dari kuantitas dan harga satuan.
- Analisis tren penjualan harian.
- Visualisasi produk teratas.
- Pembuatan fitur historis (*lag features*).
- Pembagian data berdasarkan urutan waktu.
- Random Forest Regressor sebagai model baseline.
- Evaluasi menggunakan MAE, RMSE, dan R².

## Batasan dan penggunaan yang bertanggung jawab

- Dataset berasal dari satu retailer di Inggris, bukan pasar Indonesia.
- Data merupakan transaksi historis tahun 2010–2011 sehingga belum tentu mewakili kondisi bisnis saat ini.
- Hasil analisis menunjukkan pola data, bukan bukti hubungan sebab-akibat.
- Model prediksi merupakan baseline pembelajaran dan tidak menjamin akurasi pada data baru.
- Hasil dan metrik akhir harus diisi berdasarkan eksekusi notebook yang sebenarnya.
