# Laporan Praktikum Minggu 5: Advanced Ensemble & Handling Imbalance

**Informasi Mahasiswa:**
* **Nama:** [Isi Nama Anda]
* **NIM:** [Isi NIM Anda]
* **Link W&B Project:** [Paste Link Dashboard W&B Anda]

---

## 1. Analisis Awal: Masalah Imbalance
Berdasarkan pengecekan `value_counts()` pada dataset asli:
* Berapa jumlah transaksi Normal (Kelas 0)?
* Berapa jumlah transaksi Penipuan (Kelas 1)?
* **Analisis:** Mengapa metrik **Accuracy** tidak boleh digunakan sebagai acuan utama dalam dataset ini?

> **Jawaban:** (Tulis analisis Anda di sini)

---

## 2. Implementasi SMOTE (Synthetic Minority Over-sampling Technique)
Lampirkan perbandingan jumlah data sebelum dan sesudah SMOTE:

| Kondisi | Jumlah Data Kelas 0 | Jumlah Data Kelas 1 |
| :--- | :--- | :--- |
| Sebelum SMOTE | ... | ... |
| Sesudah SMOTE | ... | ... |



**Analisis:** Jelaskan bagaimana SMOTE bekerja "menciptakan" data baru untuk menyeimbangkan kelas penipuan.

---

## 3. Perbandingan Model: Bagging vs Boosting
Isi tabel perbandingan performa pada **Data Test**:

| Metrik | Random Forest (Bagging) | XGBoost (Boosting) |
| :--- | :--- | :--- |
| **Accuracy** | ... | ... |
| **AUPRC** | ... | ... |
| **Recall (Kelas 1)** | ... | ... |
| **Precision (Kelas 1)** | ... | ... |

**Pertanyaan Kritis:**
1. Model mana yang memiliki nilai **Recall** tertinggi untuk transaksi Fraud (Kelas 1)? Mengapa nilai Recall sangat krusial bagi sebuah Bank?
2. Berdasarkan hasil **AUPRC**, model mana yang paling stabil dalam membedakan penipu di tengah ribuan transaksi normal?

> **Jawaban:** (Tulis analisis perbandingan di sini)

---

## 4. Analisis Confusion Matrix
Lihat kuadran **False Negative** (Asli Fraud, tapi ditebak Normal) pada model terbaik Anda:
* Berapa jumlah penipu yang berhasil "lolos" dari deteksi model Anda?
* Jika Anda adalah manajer risiko bank, langkah apa yang akan Anda ambil untuk meminimalkan angka tersebut?



---

## 5. Kesimpulan & Dokumentasi W&B
* Apa kesimpulan Anda mengenai efektivitas SMOTE dalam meningkatkan kemampuan model mendeteksi penipuan?
* Lampirkan screenshot grafik AUPRC dari dashboard W&B Anda.

> **[Tempel Screenshot Dashboard W&B di Sini]**
