# UAS Machine Learning: Analisis Segmentasi Pelanggan Retail

Repositori ini berisi pengerjaan Ujian Akhir Semester (UAS) mata kuliah Machine Learning. Proyek ini melakukan segmentasi pelanggan (customer segmentation) dari dataset Online Retail II.

-   **Nama:** Aura Aulia Al Khomisi
-   **NIM:** 227006516044
-   **Dataset:** Online Retail II (UCI Machine Learning Repository)

---

## 🎯 Tujuan & Algoritma

* **Tujuan Analisis:** Mengelompokkan pelanggan ke dalam segmen-segmen yang berbeda berdasarkan perilaku pembelian mereka. Ini dilakukan dengan menggunakan **Analisis RFM (Recency, Frequency, Monetary)** untuk mengukur nilai setiap pelanggan. Tujuannya adalah agar perusahaan dapat membuat strategi pemasaran yang lebih efektif dan personal.

* **Algoritma yang Digunakan:** **K-Means Clustering**. Algoritma ini dipilih karena kemampuannya yang sangat baik dalam menemukan kelompok (cluster) secara alami di dalam data tanpa memerlukan label (unsupervised learning). K-Means efisien dan hasilnya mudah diinterpretasikan untuk memahami karakteristik setiap segmen pelanggan.

---

## 💻 Cara Menjalankan Program

Proyek ini dikerjakan menggunakan **Google Colab** untuk kemudahan penggunaan dan menghindari masalah instalasi.

1.  **Buka Google Colab:** Buat notebook baru di [colab.research.google.com](https://colab.research.google.com/).
2.  **Siapkan Kode:** Proyek ini menggunakan dua blok kode terpisah: satu untuk upload file, dan satu lagi untuk analisis. Salin dan tempel kedua blok kode dari repositori ini ke dalam dua sel terpisah di notebook Colab Anda.
3.  **Upload Dataset:** Jalankan **Blok 1 (Upload File)**. Sebuah tombol "Choose Files" akan muncul. Pilih kedua file dataset (`online_retail_II.xlsx - Year 2009-2010.csv` dan `online_retail_II.xlsx - Year 2010-2011.csv`) dari komputer Anda.
4.  **Jalankan Analisis:** Setelah file berhasil di-upload, jalankan **Blok 2 (Analisis Data)**. Program akan memproses data dan menampilkan hasilnya, termasuk tabel karakteristik dan plot visualisasi.

---

## 📊 Hasil Analisis dan Interpretasi

Setelah menjalankan program, ditemukan 4 segmen pelanggan yang berbeda dengan karakteristik unik.

### Karakteristik Segmen
