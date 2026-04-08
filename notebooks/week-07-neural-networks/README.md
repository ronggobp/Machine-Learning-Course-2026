# Minggu 7: Intro to Neural Networks - Multi-Layer Perceptron (MLP) 🧠

## Tujuan Pembelajaran
1. Memahami analogi antara neuron biologis dan neuron tiruan (Perceptron).
2. Memahami arsitektur jaringan saraf: *Input Layer*, *Hidden Layer*, dan *Output Layer*.
3. Memahami peran **Activation Functions** (ReLU, Sigmoid, Softmax).
4. Mengenal proses belajar melalui **Forward Propagation** dan **Backpropagation**.

## 1. Apa itu Neural Network?
Neural Network adalah sekumpulan algoritma yang dirancang untuk mengenali pola. Ia meniru cara kerja otak manusia melalui lapisan-lapisan neuron tiruan.



### Komponen Utama:
* **Weights ($w$):** Kekuatan hubungan antar neuron.
* **Bias ($b$):** Nilai tambahan untuk menggeser fungsi aktivasi.
* **Activation Function:** Menentukan apakah neuron harus "aktif" atau tidak.
  * **ReLU:** $f(x) = \max(0, x)$ (Standar untuk lapisan tersembunyi).
  * **Sigmoid:** Memeras nilai ke rentang 0 sampai 1.

## 2. Multi-Layer Perceptron (MLP)
MLP adalah jenis jaringan saraf *feed-forward* yang memiliki setidaknya satu lapisan tersembunyi (*hidden layer*).

Proses belajar NN:
1. **Forward Pass:** Data masuk, dihitung dengan bobot, dan menghasilkan prediksi.
2. **Loss Calculation:** Menghitung seberapa jauh prediksi dari jawaban asli.
3. **Backward Pass (Backpropagation):** Memperbaiki bobot ($w$) dan bias ($b$) berdasarkan nilai kesalahan menggunakan *Gradient Descent*.

## 3. Parameter Penting (Hyperparameters)
Selain jumlah lapisan, "otak" ini memiliki tombol-tombol pengatur performa:
* **Learning Rate ($lr$):** Seberapa besar langkah yang diambil model untuk memperbaiki kesalahan. Terlalu besar akan membuat model "melompati" solusi, terlalu kecil membuat proses belajar sangat lambat.
* **Solver:** Algoritma yang melakukan optimasi bobot (misal: 'adam' yang adaptif atau 'sgd' yang klasik).
* **Alpha ($\alpha$):** Parameter regularisasi untuk mencegah model terlalu "menghafal" data (Overfitting).
