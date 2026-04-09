# 📑 Laporan Praktikum Minggu 10: Natural Language Processing (NLP)

**Informasi Mahasiswa:**
* **Nama:** [Isi Nama Anda]
* **NIM:** [Isi NIM Anda]
* **Link W&B Project:** [Paste Link Dashboard W&B Anda]

---

## 1. Analisis Preprocessing Teks
Berdasarkan fungsi `advanced_clean` yang Anda jalankan:
1. Mengapa tahap **Lemmatization** lebih disarankan dibandingkan hanya melakukan *Stemming* dalam analisis sentimen film?
2. Berikan satu contoh kata dari dataset yang berubah setelah melalui proses Lemmatization dan jelaskan mengapa perubahan tersebut membantu model belajar lebih efisien.

> **Jawaban:** (Tulis penjelasan Anda di sini)

---

## 2. Eksperimen Fitur: N-Grams (Unigrams vs Bigrams)
Dalam kode optimalisasi, kita menggunakan `ngram_range=(1, 2)`.
1. Jelaskan perbedaan antara *Unigram* dan *Bigram*.
2. Mengapa penggunaan *Bigram* sangat penting untuk mendeteksi kalimat negasi (contoh: "not good")?

> **Jawaban:** (Tulis analisis N-Grams Anda di sini)

---

## 3. Perbandingan Model
Bandingkan hasil antara model awal (Naive Bayes) dengan model optimal (Logistic Regression + Lemmatization).

| Metrik | Naive Bayes (Baseline) | Logistic Regression (Optimized) |
| :--- | :--- | :--- |
| **Accuracy** | [Isi nilai, misal 0.84] | [Isi nilai baru] |
| **Vocab Size** | 5000 | 10000 |
| **Preprocessing** | Basic Cleaning | Cleaning + Lemmatization |

**Analisis:** Mengapa Logistic Regression cenderung memberikan performa lebih baik pada fitur teks berdimensi tinggi dibandingkan Naive Bayes?

---

## 4. Analisis Kesalahan (Error Analysis)
Cari **satu ulasan** di data uji yang salah ditebak oleh model (misal: ulasan asli Negatif tapi ditebak Positif).
* **Teks Ulasan:** "..."
* **Analisis:** Mengapa model salah menebak? Apakah ada unsur sarkasme atau kata-kata ambigu yang membingungkan AI?

---

## 5. Dokumentasi Weights & Biases (W&B)
Lampirkan *screenshot* dari *dashboard* W&B Anda yang menampilkan grafik akurasi dan *Confusion Matrix* hasil optimalisasi.

> **[Tempel Screenshot W&B Anda di Sini]**

---

# 🚀 Tugas Tambahan: In-depth Exploration

Tugas ini bersifat opsional untuk nilai tambahan, namun sangat disarankan untuk memahami isi model Anda secara mendalam.

### Tugas 1: Interpretasi Model (Fitur Terkuat)
Gunakan koefisien dari model Logistic Regression untuk menemukan kata-kata yang paling memengaruhi keputusan AI.
1. Gunakan kode `model.coef_` untuk mengambil bobot kata.
2. Temukan 5 kata teratas dengan bobot positif tertinggi (Indikator ulasan Positif).
3. Temukan 5 kata teratas dengan bobot negatif terendah (Indikator ulasan Negatif).
4. **Pertanyaan:** Apakah kata-kata tersebut memang secara logika manusia menggambarkan sentimen?

### Tugas 2: Tantangan Sarkasme
Uji model Anda secara manual dengan memasukkan kalimat berikut: 
> *"This movie was so good that I fell asleep after 5 minutes."*
1. Apakah model Anda menebak kalimat ini sebagai Positif atau Negatif?
2. Berdasarkan pengetahuan Anda tentang TF-IDF, mengapa AI sering kali gagal mendeteksi sarkasme semacam ini?

---
