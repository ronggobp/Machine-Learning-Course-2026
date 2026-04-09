# 📑 Laporan Praktikum Minggu 6: Unsupervised Learning - Segmentasi Pasar

**Informasi Mahasiswa:**

* **Nama:** [Isi Nama Anda]
* **NIM:** [Isi NIM Anda]
* **Link W&B Project:** [Paste Link Dashboard W&B Anda]

---

## 1. Pemahaman Konsep

Jelaskan dengan bahasa Anda sendiri:

1. Apa perbedaan utama antara **Supervised Learning** (Minggu 1-5) dan **Unsupervised Learning** (Minggu 6)?
2. Dalam algoritma K-Means, apa yang dimaksud dengan **Centroid** dan bagaimana pengaruhnya terhadap pembentukan cluster?

> **Jawaban:** (Tulis penjelasan Anda di sini)

---

## 2. Penentuan Jumlah Cluster (Elbow Method)

Berdasarkan grafik WCSS (*Within-Cluster Sum of Square*) yang Anda hasilkan pada Blok 2:

* Pada nilai $k$ berapakah Anda melihat bentuk "siku" (titik di mana penurunan WCSS mulai melambat)?
* Berapa jumlah cluster ($k$) yang akhirnya Anda pilih untuk model ini? Jelaskan alasannya.

> **Jawaban:** (Tulis analisis Elbow Method Anda di sini)

---

## 3. Profiling Pelanggan (Inti Analisis)

Setelah menjalankan K-Means dengan jumlah $k$ pilihan Anda, berikan nama profil dan karakteristik untuk setiap cluster.

*Contoh Format:*

* **Cluster 0 (Hemat):** Pendapatan rendah, pengeluaran rendah.
* **Cluster 1 (Loyal/Target):** Pendapatan tinggi, pengeluaran tinggi.
* **Cluster ... :** [Lanjutkan sesuai hasil Anda]

**Tugas Kritis:** Berikan satu saran strategi pemasaran yang spesifik untuk salah satu cluster yang menurut Anda paling potensial untuk meningkatkan profit mall tersebut.

> **Jawaban:** (Tulis profil dan strategi bisnis di sini)

---

## 4. Reduksi Dimensi dengan PCA

Pada Blok 4, Anda melakukan reduksi dimensi menggunakan **PCA (Principal Component Analysis)**.

1. Mengapa kita perlu menggunakan PCA sebelum memvisualisasikan data yang memiliki lebih dari 3 fitur?
2. Apakah visualisasi hasil PCA memudahkan Anda dalam melihat pemisahan antar cluster dibandingkan grafik 2D biasa? Jelaskan.

> **Jawaban:** (Tulis analisis PCA Anda di sini)

---

## 5. Dokumentasi Weights & Biases (W&B)

Lampirkan *screenshot* dari *dashboard* W&B Anda yang menampilkan grafik **WCSS_Curve** (Elbow Method) dan hasil scatter plot cluster Anda.

> **[Tempel Screenshot W&B Anda di Sini]**

---

## 6. Kesimpulan & Refleksi

* Apa kesulitan terbesar dalam menentukan jumlah cluster yang "benar" pada data yang tidak memiliki label?
* Bagaimana Unsupervised Learning dapat membantu perusahaan dalam mengambil keputusan tanpa harus memiliki data historis yang sudah dilabeli secara manual?

---

### Instruksi Pengumpulan:

1. Isi laporan ini dengan analisis yang tajam dan berbasis data.
2. Simpan sebagai file **PDF** atau **Markdown** (`.md`).
3. Kumpulkan melalui **Pull Request** ke repositori utama sebelum batas waktu yang ditentukan.

---
