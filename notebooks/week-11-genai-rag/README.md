# Minggu 11: Generative AI & Retrieval-Augmented Generation (RAG) 🤖📚

## Tujuan Pembelajaran
1. Memahami konsep dasar **Large Language Models (LLM)**.
2. Memahami masalah **Hallucination** pada AI dan cara mengatasinya.
3. Mengimplementasikan arsitektur **RAG** untuk memberi "ingatan" baru pada AI.
4. Mengenal **Vector Databases** dan **Embeddings**.

## 1. Apa itu Generative AI?
Generative AI (seperti Gemini atau GPT) adalah model yang dilatih untuk memprediksi kata berikutnya dalam sebuah urutan. Model ini menggunakan arsitektur **Transformer** yang memiliki mekanisme *Attention* untuk memahami konteks kalimat yang panjang.



## 2. Retrieval-Augmented Generation (RAG)
LLM memiliki pengetahuan yang terbatas pada tanggal terakhir mereka dilatih (Knowledge Cut-off). **RAG** adalah teknik untuk memberikan dokumen eksternal (PDF, Database, Website) kepada AI sebelum ia menjawab, sehingga jawabannya lebih akurat dan faktual.

### Alur Kerja RAG:
1. **Load:** Mengambil dokumen (PDF/Teks).
2. **Split:** Memecah dokumen menjadi potongan kecil (Chunks).
3. **Embed:** Mengubah teks menjadi koordinat angka (Vectors).
4. **Store:** Menyimpan di Vector Database.
5. **Retrieve:** Mencari potongan teks paling relevan dengan pertanyaan user.
6. **Augment:** Mengirim teks tersebut ke LLM sebagai referensi jawaban.



## 3. Cara Membuat API Key Gemini

Untuk saat ini, pembuatan API Key paling mudah dilakukan melalui **Google AI Studio**. Berikut langkah-langkahnya:

1.  **Kunjungi Google AI Studio:** Buka laman [aistudio.google.com](https://aistudio.google.com/).
2.  **Login:** Masuk menggunakan akun Google Anda (disarankan menggunakan akun yang sama untuk keperluan akademik).
3.  **Get API Key:** Pada menu di bilah samping (sidebar) sebelah kiri, klik tombol **"Get API key"**.
4.  **Buat Key Baru:** Klik tombol **"Create API key in new project"** atau pilih proyek Google Cloud yang sudah ada.
5.  **Simpan Key Anda:** Setelah muncul, salin API Key tersebut. **Peringatan:** Dilarang mengunggah API Key ke repositori publik di GitHub agar tidak disalahgunakan orang lain.

## Referensi Kode
Anda dapat mempelajari struktur dasar RAG di: [https://github.com/ronggobp/pdf-ai-chatbot](https://github.com/ronggobp/pdf-ai-chatbot)
