## 📝 Tugas Minggu 7: Eksperimen Arsitektur Saraf

**Instruksi:**
1. Gunakan Notebook `07_MLP_Digit_Recognition.ipynb`.
2. Lakukan eksperimen dengan mengubah **Hyperparameters**:
   - Ubah `hidden_layer_sizes`. Apa yang terjadi jika Anda hanya menggunakan 1 layer kecil (misal: 10 neuron) dibandingkan 3 layer besar (misal: 256, 128, 64)?
   - Coba ubah `activation` dari 'relu' ke 'tanh' atau 'logistic'.
3. Selain mengubah jumlah layer, lakukan eksperimen berikut:
   - **The Learning Rate Trap:** Ubah `learning_rate_init` menjadi sangat besar (misal: 0.5) dan sangat kecil (misal: 0.000001). Amati grafik **Loss** di W&B. Apakah model tetap bisa mencapai akurasi tinggi?
   - **Regularization Power:** Ubah `alpha` menjadi besar (misal: 1.0). Perhatikan apakah akurasi pada data training dan testing menjadi lebih seimbang atau justru menurun keduanya.
   - **Solver Battle:** Bandingkan `solver='adam'` dengan `solver='sgd'`. Mana yang lebih cepat mencapai nilai Loss rendah dalam 20 iterasi?
4. Amati grafik **Loss Curve** di W&B. Semakin cepat grafik turun, semakin cepat model belajar.
5. Tuliskan dalam laporan: Arsitektur mana yang paling akurat untuk mengenali tulisan tangan?
