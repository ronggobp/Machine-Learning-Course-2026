## 📝 Tugas Minggu 9: Eksperimen Arsitektur CNN

**Instruksi:**
1. Gunakan Notebook `09_CNN_Image_Classification.ipynb`.
2. Lakukan modifikasi pada arsitektur CNN:
   - Tambahkan satu lapisan **Convolutional** dan **Pooling** tambahan.
   - Ubah jumlah filter (misal dari 32 menjadi 64).
   - Tambahkan **Dropout Layer** (misal `layers.Dropout(0.2)`) untuk mengurangi overfitting.
3. Bandingkan hasilnya di W&B: Apakah model dengan lebih banyak lapisan konvolusi belajar lebih baik?
4. Analisis di laporan: Cari satu gambar yang salah ditebak oleh model, lampirkan gambarnya, dan jelaskan mengapa model mungkin salah menebak (misal: "Model mengira kucing ini anjing karena bentuk telinganya mirip").
