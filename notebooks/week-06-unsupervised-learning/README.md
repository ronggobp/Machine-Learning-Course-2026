# Minggu 6: Unsupervised Learning - Segmentasi Pasar 🛍️

## Tujuan Pembelajaran
1. Memahami perbedaan antara Supervised dan Unsupervised Learning.
2. Mengimplementasikan **K-Means Clustering** untuk pengelompokan data.
3. Menentukan jumlah cluster optimal menggunakan **Elbow Method**.
4. Memahami reduksi dimensi menggunakan **PCA (Principal Component Analysis)**.

## 1. K-Means Clustering
Algoritma ini mengelompokkan data berdasarkan jarak terdekat ke titik pusat kelompok (Centroid). Jarak yang digunakan biasanya adalah **Euclidean Distance**:
$$d(p, q) = \sqrt{\sum_{i=1}^{n} (p_i - q_i)^2}$$

Untuk mencari jumlah kelompok ($k$) terbaik, kita menggunakan **Elbow Method** dengan melihat nilai WCSS (*Within-Cluster Sum of Square*).

## 2. PCA (Principal Component Analysis)
Bayangkan Anda punya 10 fitur (kolom) tentang pelanggan. Sulit untuk melihatnya dalam grafik 2D. **PCA** bekerja dengan cara memproyeksikan fitur-fitur tersebut ke dalam sumbu baru (Principal Components) tanpa kehilangan banyak informasi penting, sehingga data 10 dimensi bisa kita "peras" menjadi 2 dimensi untuk divisualisasikan.
