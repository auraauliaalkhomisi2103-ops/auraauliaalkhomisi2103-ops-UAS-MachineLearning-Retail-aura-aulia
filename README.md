### Karakteristik Segmen
    Recency Frequency Monetary      
       mean      mean     mean count
Cluster

0         438.3       1.4    159.3   284
1          68.0       3.9    306.3   525
2         505.0      21.0  74807.0     1
3           5.0     150.0   7795.0     1


### Visualisasi Hasil Analisis
*Berikut adalah visualisasi hasil segmentasi dan perbandingan detail untuk setiap segmen.*

**Gambar 1: Hasil Utama Segmentasi**
![Hasil Utama Segmentasi](https://i.imgur.com/your-main-plot-link.png) **Gambar 2: Perbandingan Detail Karakteristik RFM antar Segmen**
![Perbandingan Detail RFM](https://i.imgur.com/your-detail-plot-link.png) ### Penjelasan dan Interpretasi Hasil

Berdasarkan tabel dan visualisasi di atas, kita dapat memberikan interpretasi dan strategi bisnis untuk setiap segmen:

#### **Cluster 1: Pelanggan Potensial / Setia (Potential/Loyal Customers)**
* **Anggota:** 525 pelanggan.
* **Karakteristik:** Ini adalah segmen terbesar dan paling representatif. Mereka memiliki `Recency` yang cukup rendah (rata-rata 68 hari), artinya mereka belum lama ini berbelanja. Frekuensi dan nilai belanja mereka tergolong sedang.
* **Interpretasi:** Ini adalah tulang punggung pelanggan perusahaan. Mereka aktif dan loyal, namun masih memiliki potensi besar untuk dikembangkan.
* **Rekomendasi Strategi:**
    * Tawarkan program loyalitas (poin, tingkatan keanggotaan).
    * Kirimkan rekomendasi produk yang dipersonalisasi berdasarkan riwayat pembelian.
    * Berikan diskon untuk pembelian berikutnya untuk mendorong mereka menjadi pelanggan VIP.

#### **Cluster 0: Pelanggan Pasif / Hilang (Lapsed/Lost Customers)**
* **Anggota:** 284 pelanggan.
* **Karakteristik:** Segmen ini memiliki `Recency` yang sangat tinggi (rata-rata 438 hari atau lebih dari setahun), dengan frekuensi dan nilai belanja yang sangat rendah.
* **Interpretasi:** Ini adalah pelanggan yang sudah lama sekali tidak aktif. Kemungkinan besar mereka sudah pindah ke kompetitor atau tidak lagi membutuhkan produknya.
* **Rekomendasi Strategi:**
    * Kirimkan kampanye "re-engagement" melalui email dengan penawaran "Kami Merindukanmu!" yang sangat menarik.
    * Lakukan survei untuk mencari tahu alasan mengapa mereka berhenti berbelanja.
    * Fokuskan upaya pemasaran pada segmen lain jika biaya untuk menarik mereka kembali terlalu tinggi.

#### **Cluster 3 & 2: Pelanggan Juara & Outlier Unik**
* **Anggota:** Hanya 1 pelanggan di setiap cluster.
* **Karakteristik Cluster 3 (Pelanggan Juara/VIP):** Pelanggan ini sempurna. `Recency` sangat rendah (5 hari), `Frequency` sangat tinggi (150 transaksi), dan `Monetary` sangat tinggi (Rp 7,795).
* **Karakteristik Cluster 2 (Outlier Unik):** Pelanggan ini anomali. `Recency` sangat tinggi (505 hari), namun `Frequency` dan `Monetary`-nya juga sangat tinggi. Ini mungkin pelanggan korporat besar yang melakukan pembelian massal sekali waktu dan tidak pernah kembali.
* **Interpretasi:** Karena jumlah anggotanya hanya satu, mereka bukanlah "segmen" melainkan *outlier* individu yang sangat menonjol. Algoritma K-Means memisahkan mereka karena perilaku mereka yang sangat ekstrem dibandingkan pelanggan lain.
* **Rekomendasi Strategi:**
    * **Untuk Pelanggan Juara (Cluster 3):** Perlakukan sebagai VIP. Berikan layanan personal, akses awal ke produk baru, dan hadiah eksklusif. Mereka adalah aset paling berharga.
    * **Untuk Outlier Unik (Cluster 2):** Coba hubungi secara personal untuk mencari tahu mengapa mereka tidak kembali. Ada potensi besar jika mereka bisa diaktifkan kembali.
