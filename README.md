# UAS Machine Learning: Analisis Segmentasi Pelanggan Retail

Repositori ini berisi pengerjaan Ujian Akhir Semester (UAS) mata kuliah Machine Learning.

- **Nama:** [Isi Nama Lengkap Kamu]
- **NIM:** [Isi NIM Kamu]
- **Dataset:** Online Retail II

---

## Tujuan Analisis & Algoritma

* **Tujuan:** Melakukan segmentasi pelanggan (customer segmentation) berdasarkan perilaku pembelian mereka menggunakan metode RFM (Recency, Frequency, Monetary).
* **Algoritma:** K-Means Clustering digunakan untuk mengelompokkan pelanggan ke dalam segmen-segmen yang berbeda berdasarkan skor RFM mereka.

---

## Cara Menjalankan Program

### 1. Download Dataset
Dataset **tidak** di-upload ke repositori ini karena ukurannya yang sangat besar. Silakan unduh dataset (`online_retail_II.zip`) dari link resmi berikut:

* **Link Download:** [https://archive.ics.uci.edu/dataset/162/forest+fires](https://archive.ics.uci.edu/dataset/502/online+retail+ii)

### 2. Setup
* Ekstrak file ZIP yang sudah diunduh. Di dalamnya akan ada file `online_retail_II.csv`.
* Letakkan file `online_retail_II.csv` di dalam folder yang sama dengan file `analisis_retail.py`.

### 3. Jalankan
* Buka terminal atau command prompt, masuk ke direktori proyek, dan jalankan perintah:
    ```bash
    python analisis_retail.py
    ```
* Program akan membuat folder `output` dan menyimpan gambar hasil segmentasi di dalamnya.

---

## Contoh Hasil Output

*(Program akan menghasilkan plot seperti di bawah ini, yang menunjukkan pengelompokan pelanggan)*

![Contoh Hasil Plot](https://i.imgur.com/8E2Z8gH.png)
