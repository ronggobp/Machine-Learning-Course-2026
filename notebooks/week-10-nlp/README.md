# Minggu 10: Natural Language Processing (NLP) 🗣️

## Tujuan Pembelajaran
1. Memahami alur kerja Preprocessing Teks (Cleaning, Tokenization, Stemming/Lemmatization).
2. Mengubah teks menjadi angka menggunakan **Bag-of-Words** dan **TF-IDF**.
3. Membangun model **Sentiment Analysis** sederhana.

## Alur Kerja Preprocessing
Sebelum masuk ke model, teks harus "dimandikan" dulu:
1. **Case Folding:** Mengubah semua huruf menjadi kecil.
2. **Filtering/Stopwords:** Menghapus kata sambung yang tidak memiliki makna unik (dan, yang, di).
3. **Tokenization:** Memecah kalimat menjadi potongan kata.
4. **Vectorization:** Mengubah kata menjadi angka.
