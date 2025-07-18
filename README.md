# CapstoneModule2
Capstone Module 2 (Python Notebook & Tableau) : Optimasi Layanan Transjakarta Berbasis Analisis Kepadatan, Pola Pembayaran, dan Efisiensi Koridor

# Deskripsi Project
Proyek ini menganalisis data penumpang Transjakarta secara komprehensif untuk mengidentifikasi pola kepadatan pada jam sibuk (_rush hour_), perbedaan perilaku perjalanan antara hari kerja dan akhir pekan, efisiensi koridor dan halte, serta tren perilaku pembayaran.  
Tujuan utamanya adalah menghasilkan insight berbasis data yang dapat digunakan untuk optimalisasi layanan, penjadwalan armada, serta rekomendasi strategis dalam pengelolaan Transjakarta.

# Tujuan 
- Mengidentifikasi jam-jam sibuk dan perbedaan pola perjalanan penumpang pada weekday vs weekend.
- Mengevaluasi kepadatan serta efisiensi koridor dan halte utama Transjakarta.
- Menganalisis perilaku pembayaran pengguna pada waktu, usia, dan koridor yang berbeda.
- Memberikan rekomendasi actionable berbasis data untuk peningkatan kualitas dan efisiensi layanan Transjakarta.

# Pernyataan Masalah

# Data yang Digunakan
Data original dapat dilihat **[disini](https://drive.google.com/drive/folders/1S04hk5uHfHYe6J1S6fVqDunuja1Lk1Lo)**

Penjelasan dataset :

- transID: ID transaksi unik untuk setiap transaksi.
- payCardID: Identifikasi utama pelanggan, yaitu kartu yang digunakan sebagai tiket untuk masuk dan keluar.
- payCardBank: Nama bank penerbit kartu pelanggan.
- payCardName: Nama pelanggan yang tertanam di dalam kartu.
- payCardSex: Jenis kelamin pelanggan yang tertanam di dalam kartu.
- payCardBirthDate: Tahun lahir pelanggan.
- corridorID: ID koridor/rute sebagai kunci untuk pengelompokan rute.
- corridorName: Nama koridor/rute yang mencantumkan titik awal dan akhir setiap rute.
- direction: 0 untuk Pergi, 1 untuk Pulang. Menunjukkan arah perjalanan.
- tapInStops: ID halte masuk untuk mengidentifikasi nama halte tempat pelanggan masuk.
- tapInStopsName: Nama halte masuk tempat pelanggan melakukan tap masuk.
- tapInStopsLat: Garis lintang (latitude) dari halte masuk.
- tapInStopsLon: Garis bujur (longitude) dari halte masuk.
- stopStartSeq: Urutan halte, misalnya halte pertama, halte kedua, dll., yang terkait dengan arah perjalanan.
- tapInTime: Waktu pelanggan melakukan tap masuk (tanggal dan waktu).
- tapOutStops: ID halte keluar untuk mengidentifikasi nama halte tempat pelanggan keluar.
- tapOutStopsName: Nama halte keluar tempat pelanggan melakukan tap keluar.
- tapOutStopsLat: Garis lintang (latitude) dari halte keluar.
- tapOutStopsLon: Garis bujur (longitude) dari halte keluar.
- stopEndSeq: Urutan halte, misalnya halte pertama, halte kedua, dll., yang terkait dengan arah perjalanan.
- tapOutTime: Waktu pelanggan melakukan tap keluar (tanggal dan waktu).
- payAmount: Jumlah biaya yang dibayarkan pelanggan. Beberapa perjalanan mungkin gratis, beberapa lainnya berbayar.

# Rekomendasi
