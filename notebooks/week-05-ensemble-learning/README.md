# Minggu 5: Advanced Ensemble & Handling Imbalanced Data 💳

## Tujuan Pembelajaran
1. Memahami perbedaan **Bagging** (Random Forest) dan **Boosting** (XGBoost/LightGBM).
2. Menangani masalah **Data Tidak Seimbang (Imbalanced Data)** pada kasus deteksi penipuan (Fraud).
3. Mengimplementasikan teknik **SMOTE** (Oversampling) dan Penyesuaian Bobot Kelas.
4. Mengevaluasi model menggunakan **AUPRC (Area Under Precision-Recall Curve)** alih-alih Akurasi.

## 1. Boosting: XGBoost & LightGBM
Jika Random Forest membuat banyak pohon secara paralel, **Boosting** membuat pohon secara berurutan. Setiap pohon baru mencoba memperbaiki kesalahan yang dibuat oleh pohon sebelumnya.
* **XGBoost:** Sangat cepat dan akurat, standar kompetisi Kaggle.
* **LightGBM:** Versi yang lebih ringan dan efisien untuk data dalam jumlah sangat besar.

## 2. Masalah Data Tidak Seimbang (Imbalance)
Pada kasus *Credit Card Fraud*, misalnya dari 100.000 transaksi, hanya 100 yang merupakan penipuan (0.1%). 
* **Bahaya Akurasi:** Jika AI menebak "Semua transaksi adalah normal", akurasinya mencapai 99.9%. Tapi AI tersebut **gagal total** karena tidak menemukan satu pun penipu.

## 3. Cara Menangani Imbalance
1. **Oversampling (SMOTE):** Menciptakan data "penipuan" buatan agar jumlahnya setara dengan transaksi normal.
2. **Undersampling:** Mengurangi jumlah data normal.
3. **Class Weights:** Memberikan "hukuman" lebih berat bagi AI jika salah menebak transaksi penipuan.
