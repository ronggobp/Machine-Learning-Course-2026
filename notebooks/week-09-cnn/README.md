# Minggu 9: Advanced Neural Networks - CNN untuk Gambar 🖼️

## Tujuan Pembelajaran
1. Memahami mengapa MLP kurang efektif untuk data gambar skala besar.
2. Memahami operasi **Convolution**, **Padding**, dan **Stride**.
3. Memahami peran **Pooling Layer** dalam kompresi fitur.
4. Membangun arsitektur CNN sederhana untuk klasifikasi gambar berwarna.

## 1. Mengapa CNN?
Gambar memiliki pola spasial. Misalnya, telinga kucing tetaplah telinga kucing baik di pojok kiri maupun tengah gambar. CNN menggunakan "Filter" yang bergeser ke seluruh area gambar untuk menangkap pola lokal tersebut.



## 2. Komponen Utama CNN
1. **Convolutional Layer:** Menggunakan filter (kernel) untuk mengekstrak fitur (tepi, tekstur, bentuk).
2. **Activation (ReLU):** Memberikan sifat non-linear.
3. **Pooling Layer (Max Pooling):** Mengurangi dimensi gambar agar proses komputasi lebih ringan namun tetap mempertahankan fitur terpenting.
4. **Flattening:** Mengubah data 2D/3D menjadi 1D sebelum masuk ke lapisan klasifikasi akhir.
