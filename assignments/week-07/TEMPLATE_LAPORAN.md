 # 📑 Laporan Praktikum Minggu 7: Multi-Layer Perceptron (MLP)

**Informasi Mahasiswa:**

* **Nama:** [Isi Nama Anda]
* **NIM:** [Isi NIM Anda]
* **Link W&B Project:** [Paste Link Dashboard W&B Anda]

---

## 1. Pemahaman Arsitektur Jaringan Saraf

Berdasarkan kode yang dijalankan pada Blok 3:

1. Berapa jumlah **Hidden Layers** yang Anda gunakan dan berapa jumlah **Neuron** di masing-masing layer tersebut?
2. Apa fungsi dari tahap **Normalisasi** (membagi data pixel dengan 255) sebelum data dimasukkan ke dalam model?

> **Jawaban:** (Tulis penjelasan Anda di sini)

---

## 2. Analisis Proses Belajar (Loss Curve)

Buka *dashboard* W&B Anda dan perhatikan grafik **Loss**.

1. Jelaskan apa yang terjadi pada nilai *Loss* seiring bertambahnya jumlah *Epoch* (iterasi). Apa artinya bagi kemampuan model?
2. Apakah grafik *Loss* Anda sudah melandai secara sempurna atau masih terlihat menukik tajam pada iterasi ke-20? Menurut Anda, apakah model butuh waktu belajar lebih lama?

> **Jawaban:** (Tulis analisis Loss Curve Anda di sini)

---

## 3. Hasil Evaluasi Model

Tuliskan performa akhir model MLP Anda:

* **Final Accuracy:** [Isi nilai akurasi, misal 0.9724]
* **Digit yang paling sulit dikenali:** (Lihat *Classification Report*, cari digit dengan F1-Score terendah)

---

## 4. Analisis Kesalahan (Confusion Matrix)

Perhatikan grafik *Confusion Matrix* yang dihasilkan di Blok 5.

1. Sebutkan sepasang angka yang paling sering membuat model Anda "bingung" (sering tertukar). Misal: Angka 4 sering ditebak sebagai angka 9.
2. Secara visual (berdasarkan pengetahuan manusia), mengapa kedua angka tersebut bisa membuat Jaringan Saraf Tiruan salah menebak?

> **Jawaban:** (Tulis analisis Confusion Matrix di sini)

---

## 5. Eksperimen Mandiri (Hyperparameter Tuning)

Lakukan perubahan pada parameter `hidden_layer_sizes, learning_rate_init & alpha` (misal menjadi hanya satu layer `(32,)` atau ditambah menjadi tiga layer `(256, 128, 64)`). 
Isi tabel di bawah ini berdasarkan hasil eksplorasi Anda:

| Eksperimen | Arsitektur (Layers) | Learning Rate | Alpha | Akurasi Akhir | Catatan (Cepat/Lambat?) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Baseline | (128, 64) | 0.001 | 0.0001 | ... | ... |
| Eksperimen 1 | ... | ... | ... | ... | ... |
| Eksperimen 2 | ... | ... | ... | ... | ... |
| Eksperimen 3 | ... | ... | ... | ... | ... |
| Eksperimen 4 | ... | ... | ... | ... | ... |
| Eksperimen 5 | ... | ... | ... | ... | ... |
| Eksperimen 6 | ... | ... | ... | ... | ... |
| Eksperimen 7 | ... | ... | ... | ... | ... |
| Eksperimen 8 | ... | ... | ... | ... | ... |
| Eksperimen 9 | ... | ... | ... | ... | ... |
| Eksperimen 10 | ... | ... | ... | ... | ... |

**Analisis Hasil Eksplorasi:**
1. Apa yang terjadi pada grafik **Loss** jika Learning Rate disetel terlalu besar?
2. Dari semua kombinasi yang Anda coba, manakah yang memberikan hasil terbaik (Akurasi tertinggi dengan waktu training wajar)?

---

## 6. Dokumentasi Weights & Biases (W&B)

Tempelkan tangkapan layar (*screenshot*) dari *dashboard* W&B Anda yang menampilkan grafik **Loss vs Epoch**.

> **[Tempel Screenshot W&B Anda di Sini]**

---

## 7. Kesimpulan & Refleksi

Apa perbedaan paling mendasar yang Anda rasakan saat menggunakan Neural Network dibandingkan dengan algoritma klasik seperti Decision Tree atau Logistic Regression yang dipelajari pada minggu-minggu sebelumnya?

---

### Instruksi Pengumpulan:

1. Isi laporan dengan analisis yang jujur berdasarkan hasil eksperimen Anda.
2. Simpan sebagai file **PDF** atau **Markdown** (`.md`).
3. Kumpulkan melalui **Pull Request** ke repositori utama sesuai dengan *deadline* yang ditentukan.

---
