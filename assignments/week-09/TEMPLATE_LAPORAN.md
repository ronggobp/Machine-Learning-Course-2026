# 📑 Laporan Praktikum Minggu 9: Advanced Convolutional Neural Networks (CNN) & Model Optimization

**Informasi Mahasiswa:**
* **Nama:** [Isi Nama Anda]
* **NIM:** [Isi NIM Anda]
* **Link W&B Project:** [Paste Link Dashboard W&B Anda]

---

## 1. Analisis Arsitektur Baseline
Berdasarkan hasil `model.summary()` pada arsitektur awal (sebelum optimasi):
1. **Penyusutan Dimensi:** Jelaskan mengapa ukuran data menyusut dari $32 \times 32$ menjadi $15 \times 15$ setelah lapisan *MaxPooling2D* pertama. Apa implikasinya terhadap jumlah parameter?
2. **Kalkulasi Parameter:** Lapisan *Dense* pertama memiliki jumlah parameter yang sangat besar. Jelaskan bagaimana angka tersebut dihitung dari hasil *Flatten* lapisan sebelumnya.

> **Jawaban:** (Tulis analisis arsitektur Anda di sini)

---

## 2. Eksplorasi Proses Belajar (Baseline)
Analisis grafik **epoch/loss** dan **epoch/accuracy** di W&B untuk model awal:
1. **Indikasi Overfitting:** Apakah akurasi data latih jauh lebih tinggi daripada akurasi data validasi? Tunjukkan selisihnya dan jelaskan mengapa ini terjadi pada dataset gambar berwarna.
2. **Kestabilan:** Apakah kurva *loss* menurun secara halus?

---

## 3. Tugas Utama: Implementasi Model Optimization
Modifikasi kode Anda dengan menambahkan teknik berikut ke dalam arsitektur CNN:

### A. Dropout Layer
* **Posisi:** Tambahkan `layers.Dropout(0.25)` setelah lapisan pooling atau lapisan dense.
* **Analisis:** Bagaimana pengaruh Dropout terhadap selisih antara akurasi training dan akurasi validation?

### B. Batch Normalization
* **Posisi:** Tambahkan `layers.BatchNormalization()` setelah lapisan konvolusi.
* **Analisis:** Apakah proses training menjadi lebih stabil dan cepat mencapai akurasi tinggi dibandingkan model baseline?

### C. Learning Rate Scheduler (Bonus Challenge)
* **Metode:** Gunakan `tf.keras.callbacks.LearningRateScheduler` atau `ReduceLROnPlateau`.
* **Analisis:** Mengapa menurunkan Learning Rate saat grafik *loss* mulai melandai sangat membantu model menemukan titik optimal?

---

## 4. Perbandingan Hasil Eksperimen
Isi tabel perbandingan berdasarkan log di dashboard W&B Anda:

| Metrik | Model Baseline | Model Optimized (Dropout+BN+LR) |
| :--- | :--- | :--- |
| **Akurasi Data Latih** | ... | ... |
| **Akurasi Data Uji** | ... | ... |
| **Loss Akhir** | ... | ... |
| **Gap Overfitting** | (Tinggi/Rendah) | (Tinggi/Rendah) |

---

## 5. Analisis Kritis: Error Analysis (Visual)
Cari **satu gambar** dari data uji yang salah ditebak oleh model yang sudah dioptimasi.
* **Teks Prediksi:** (Misal: "Model mengira Kucing, aslinya Anjing")
* **Analisis:** Lampirkan gambarnya. Mengapa menurut Anda model masih melakukan kesalahan tersebut meskipun sudah dioptimasi? Apakah karena pencahayaan, posisi objek, atau keterbatasan resolusi $32 \times 32$?

---

## 6. Dokumentasi Weights & Biases (W&B)
Tempelkan screenshot perbandingan grafik **Accuracy** dan **Loss** antara model Baseline dan model yang sudah dioptimasi.

> **[Tempel Screenshot Perbandingan W&B di Sini]**

---

## 7. Kesimpulan & Refleksi
* Teknik optimasi mana yang memberikan dampak paling signifikan pada model Anda?
* Mengapa akurasi 100% pada data training hampir selalu merupakan indikasi buruk dalam klasifikasi gambar di dunia nyata?

---

### Instruksi Pengumpulan:
1. Isi laporan dengan analisis teknis yang mendalam (bukan sekadar narasi singkat).
2. Simpan laporan ini dalam format **Markdown** (.md) atau **PDF**.
3. Pastikan link proyek W&B Anda bersifat **Public** agar bisa dinilai.
4. Kumpulkan melalui Pull Request ke repositori kelas.

---
