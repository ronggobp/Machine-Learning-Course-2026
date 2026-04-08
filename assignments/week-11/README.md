# Minggu 11: Generative AI & RAG - Chat with Your PDF 🤖📚

## Deskripsi Tugas
Pada tugas ini, Anda akan membangun sistem **Retrieval-Augmented Generation (RAG)** sederhana. Anda akan memberikan "pengetahuan baru" kepada model bahasa besar (LLM) berupa dokumen PDF, sehingga AI mampu menjawab pertanyaan spesifik yang tidak ada di internet.

## Persyaratan Proyek
1. **LLM & Embedding:** Gunakan Google Gemini API (`gemini-1.5-flash`) dan Google Generative AI Embeddings.
2. **Framework:** Gunakan LangChain sebagai orkestrator sistem RAG.
3. **Vector Database:** Gunakan ChromaDB untuk menyimpan pengetahuan dari dokumen.
4. **Experiment Tracking:** Wajib menggunakan **Weights & Biases** untuk mencatat perbandingan antara jawaban AI murni vs AI dengan RAG.

## Fitur Wajib
- **PDF Loader:** Mampu membaca file PDF eksternal.
- **Text Splitting:** Mengatur ukuran potongan teks (*chunks*).
- **Source Citation:** Menunjukkan rujukan atau konteks dari dokumen asli (Opsional/Bonus).

## Keamanan (PENTING)
- **DILARANG HARDCODE API KEY.** Gunakan fitur **Secrets** di Google Colab atau file `.env` jika di lokal.
- Tambahkan `.env` ke `.gitignore` agar key Anda tidak terunggah ke publik.

## Referensi Kode
Anda dapat mempelajari struktur dasar RAG di: [https://github.com/ronggobp/pdf-ai-chatbot](https://github.com/ronggobp/pdf-ai-chatbot)
