Karakter Data
Dataset yang digunakan dalam project ini berisi informasi terkait pemesanan hotel, mencakup 40 variabel yang terdiri dari fitur numerik dan kategorikal. Dataset ini memiliki lebih dari 80.000 entri, yang mewakili pemesanan dari dua jenis hotel: City Hotel dan Resort Hotel. Beberapa variabel kunci dalam dataset mencakup:

- lead_time: Durasi waktu antara pemesanan dilakukan hingga tanggal kedatangan.
- adr (average daily rate): Harga harian rata-rata yang dibayar per reservasi.
- agent: Sumber pemesanan seperti agen perjalanan atau platform online.
- country: Negara asal pelanggan.
- is_canceled: Target variabel biner yang menunjukkan apakah pemesanan dibatalkan (1) atau tidak (0).

Dataset ini juga mencakup informasi terkait jumlah tamu, durasi menginap, tanggal pemesanan, dan perubahan pemesanan. Sebelum analisis, dilakukan langkah data cleaning, termasuk menangani missing values, menghapus fitur redundan, dan memastikan dataset bebas dari kebocoran data (data leakage).

Problem Analysis

Masalah utama yang ditangani dalam project ini adalah memahami faktor-faktor yang memengaruhi pembatalan pemesanan hotel dan membangun model prediktif untuk meminimalkan tingkat pembatalan. Pembatalan pemesanan dapat berdampak signifikan pada pendapatan hotel, pengelolaan sumber daya, dan tingkat hunian. Melalui analisis ini, fokusnya adalah:

1. Mendeteksi pola pembatalan:

- Apakah pembatalan dipengaruhi oleh waktu pemesanan (lead time)?
- Apakah harga harian rata-rata memengaruhi pembatalan?
- Apakah agen perjalanan tertentu atau negara asal pelanggan memiliki tingkat pembatalan yang tinggi?
  
2. Membangun model prediktif:

- Menggunakan algoritma machine learning seperti Logistic Regression, Random Forest, XGBoost, dan LightGBM untuk memprediksi pembatalan.
- Memilih model terbaik berdasarkan recall pada kelas minoritas untuk memastikan kemampuan model mendeteksi pembatalan.

3.Menghasilkan insight bisnis:

- Mengidentifikasi fitur utama seperti lead_time, adr, dan agent yang memengaruhi pembatalan.
- Memberikan rekomendasi strategis untuk mengurangi tingkat pembatalan dan meningkatkan kepuasan pelanggan.
Project ini tidak hanya memberikan solusi prediktif tetapi juga membantu dalam memahami dinamika pemesanan hotel secara mendalam, mendukung pengambilan keputusan berbasis data untuk manajemen hotel.
