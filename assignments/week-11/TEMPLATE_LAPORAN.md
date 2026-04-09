# 📑 Laporan Praktikum Minggu 11: Generative AI & RAG

**Informasi Mahasiswa:**
* **Nama:** [Isi Nama Anda]
* **NIM:** [Isi NIM Anda]
* **Link W&B Project:** [Paste Link Dashboard W&B Anda]
* **Link Repositori Proyek:** [Link GitHub Anda]

---

## 1. Konsep Large Language Models (LLM)
Jelaskan dengan bahasa Anda sendiri:
1. Apa yang dimaksud dengan fenomena **Hallucination** pada AI dan mengapa hal itu terjadi?
2. Bagaimana mekanisme **Retrieval-Augmented Generation (RAG)** mampu menutupi kelemahan LLM dalam hal data yang bersifat privat atau terbaru?

> **Jawaban:** (Tulis penjelasan Anda di sini)

---

## 2. Eksperimen Preprocessing (Chunking Strategy)
Dalam RAG, dokumen harus dipecah menjadi potongan kecil. Jelaskan pengaruh parameter berikut terhadap kualitas jawaban AI:
1. **Chunk Size:** Apa yang terjadi jika ukuran chunk terlalu besar atau terlalu kecil?
2. **Chunk Overlap:** Mengapa kita membutuhkan overlap antar potongan teks?

> **Jawaban:** (Tulis analisis chunking Anda di sini)

---

## 3. Analisis Hasil: Baseline vs RAG
Tuliskan perbandingan jawaban AI untuk pertanyaan yang sama berdasarkan file PDF yang Anda gunakan.

**Pertanyaan:** [Isi pertanyaan spesifik dari isi PDF Anda]

| Kategori | Jawaban Model (Tanpa RAG) | Jawaban Model (Dengan RAG) |
| :--- | :--- | :--- |
| **Konten** | [Copy jawaban AI] | [Copy jawaban AI] |
| **Kebenaran** | (Benar/Salah/Mengarang) | (Benar/Salah) |

**Analisis Kritis:** Jelaskan perubahan kualitas jawaban yang Anda amati. Apakah AI masih mengalami halusinasi meskipun sudah diberi data pendukung?

---

## 4. Eksplorasi Relevansi (Top-K)
Coba ubah nilai `k` (jumlah potongan dokumen yang diambil untuk satu pertanyaan).
* **Nilai K yang dicoba:** [Misal 3, 5, atau 10]
* **Dampak:** Apakah mengambil lebih banyak dokumen selalu membuat jawaban AI lebih baik, atau justru membuatnya bingung?

---

## 5. Dokumentasi Weights & Biases (W&B)
Lampirkan *screenshot* dari *dashboard* W&B Anda yang menampilkan log tabel perbandingan pertanyaan dan jawaban.

> **[Tempel Screenshot W&B Anda di Sini]**

---

## 6. Kesimpulan & Refleksi
1. Apa kendala terbesar Anda saat menghubungkan dokumen PDF ke dalam model AI?
2. Bagaimana teknologi RAG ini dapat diimplementasikan untuk membantu mahasiswa di kampus dalam mencari informasi akademik?

---

### Instruksi Pengumpulan:
1. Pastikan repositori GitHub Anda rapi dan menyertakan file PDF sampel.
2. Kirimkan Pull Request (PR) ke repositori utama sebelum batas waktu.
