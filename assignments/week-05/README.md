# Tugas Minggu 5: Battle of Ensembles - Credit Card Fraud Detection 💳

## Deskripsi Tugas
Pada tugas ini, Anda akan berperan sebagai seorang *Data Scientist* di sebuah Bank ternama. Anda ditantang untuk membangun sistem deteksi penipuan (Fraud) menggunakan algoritma **Ensemble Learning** tercanggih: **Random Forest (Bagging)** dan **XGBoost (Boosting)**.

Masalah utama yang harus Anda pecahkan adalah **Data Imbalance**, di mana transaksi penipuan hanya berjumlah ~0.17% dari total transaksi.

## Tujuan Pembelajaran
1. Mengatasi ketimpangan data menggunakan teknik **SMOTE**.
2. Membandingkan performa model **Bagging vs Boosting**.
3. Mengevaluasi model menggunakan **AUPRC** (Area Under Precision-Recall Curve) dan **Recall**.

## Instruksi Pengerjaan
1. **Dataset:** Gunakan dataset Credit Card Fraud dari OpenML (ID: 1597) seperti yang dipraktikkan di kelas.
2. **Eksperimen 1:** Latih model **Random Forest** dengan data asli (timpang) vs data hasil **SMOTE**.
3. **Eksperimen 2:** Latih model **XGBoost** dan bandingkan hasilnya dengan Random Forest.
4. **Visualisasi:** Wajib menampilkan grafik *Confusion Matrix* dan tingkat kepentingan fitur (*Feature Importance*).
5. **W&B:** Log semua metrik (AUPRC, Recall, Precision) ke project W&B Anda.

## Kriteria Penilaian
- Keberhasilan mengimplementasikan SMOTE untuk menyeimbangkan data.
- Analisis kritis pada laporan mengenai mengapa akurasi 99% bisa dianggap "Gagal" dalam kasus ini.
- Kerapian kode dan dokumentasi di Weights & Biases.
