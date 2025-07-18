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
1.   Bagaimana demografi dari pengguna  ?
  *   Apa saja kelompok umur pengguna ?
  *   Distribusi pengguna berdasarkan jenis kelamin ?
  *   Metode transaksi yang paling banyak digunakan ?

2. Bagaimana analisis kepadatan pengguna transjakarta ?
  *   Bagaimana perbandingan pengguna saat hari kerja dan akhir pekan?
  *   Bagaimana pola saat rush hour dan non rush hour?
  *   Bagaimana pola pengguna setiap jam?
  *   Bagaimana pola harian pengguna?


2. Bagaimana pola perilaku pengguna saat rush hour ?
  *   Apakah terdapat perbedaan pola berdasarkan usia atau jenis kelamin?
  *   Perbedaan jumlah penumpang saat rush hour dan non rush hour
  *   Koridor mana saja yang mengalami kepadatan saat rush hour ?
  *   Halte mana saja yang paling banyak Tap In
  *   Halte mana saja yang paling banyak Tap Out

3. Bagaimana pengaruh rush hour pada efisiensi koridor ?
  *   Bagaimana durasi perjalanan saat rush hour?

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

- Untuk meningkatkan penggunaan Transjakarta oleh seluruh kelompok umur, dapat meningkatkan fasilitas, kemudahan akses, dan kampanye edukasi.
- Untuk mencapai keseimbangan pengguna Transjakarta antara perempuan dan laki-laki, perlu ada peningkatan keamanan dan kenyamanan untuk perempuan, perubahan paradigma sosial yang bias gender, serta kebijakan yang mendukung kesetaraan gender.
- Untuk meratakan penggunaan transaksi di Transjakarta, solusi yang bisa dilakukan antara lain meningkatkan promosi metode pembayaran, memastikan ketersediaan di halte, memberikan insentif, melatih petugas, dan mengembangkan aplikasi agar lebih mudah digunakan.
- Untuk mengatasi disparitas jumlah penumpang Transjakarta antara hari kerja dan akhir, dapat diterapkan peningkatan frekuensi layanan, penyesuaian rute, serta peningkatan fasilitas dan informasi. Selain itu, edukasi dan promosi penggunaan Transjakarta juga penting untuk meningkatkan kesadaran masyarakat. 
- Untuk meratakan kepadatan di koridor Transjakarta, bisa diterapkan optimalisasi waktu operasional, penambahan armada, perluasan rute, peningkatan integrasi antar moda, serta edukasi dan sosialisasi kepada penumpang. 
- Untuk meratakan distribusi "tap in" di Transjakarta, solusi meliputi peningkatan mesin tap in di halte, sosialisasi tentang "tap in" dan "tap out", serta integrasi sistem pembayaran seperti QRIS.
- Solusi untuk mengurangi durasi perjalanan Transjakarta saat jam sibuk adalah dengan meningkatkan frekuensi layanan dan memperbanyak armada bus.

# Link Tableau
[Tableau](https://public.tableau.com/views/TransjakartaAnalysis_17527741748260/HomeDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
