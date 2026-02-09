# 📊 Data Inventory & Resources

Halaman ini berisi daftar lengkap dataset yang digunakan dalam mata kuliah Machine Learning 2026. 

## 📝 Kebijakan Dataset
Untuk menjaga efisiensi repositori, kita **tidak mengunggah file data besar (.csv/.zip)** secara langsung ke GitHub. Mahasiswa diharapkan mengunduh melalui link di bawah atau memanggilnya langsung via kode Python di Google Colab.

## 📅 Daftar Dataset per Minggu

| Minggu | Topik | Nama Dataset | Sumber / Link |
| :--- | :--- | :--- | :--- |
| **01** | Intro to ML | Scikit-learn Toy Data | [Built-in Library](https://scikit-learn.org/stable/datasets/toy_dataset.html) |
| **02** | Data Wrangling | Titanic: Machine Learning from Disaster | [Kaggle](https://www.kaggle.com/c/titanic) |
| **03** | Regression | House Prices - Advanced Regression | [Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) |
| **04** | Classification | Telco Customer Churn | [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) |
| **05** | Ensemble | Credit Card Fraud Detection | [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) |
| **06** | Clustering | Mall Customer Segmentation | [Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python) |
| **07** | Neural Networks| MNIST Digit Database | [Yann LeCun Official](http://yann.lecun.com/exdb/mnist/) |
| **09** | Computer Vision| Fashion MNIST | [Zalando Research / PyTorch](https://pytorch.org/vision/stable/datasets.html) |
| **10** | NLP Foundations| Indonesian Sentiment Analysis | [Hugging Face - IndoNLP](https://huggingface.co/datasets/indonlp/indonlp) |
| **11** | GenAI & RAG | SQuAD (Stanford Question Answering) | [Hugging Face - SQuAD](https://huggingface.co/datasets/rajpurkar/squad) |

---

## ⚠️ Lisensi
Seluruh dataset di atas digunakan untuk tujuan edukasi akademik. Harap merujuk pada lisensi masing-masing penyedia data (Kaggle/Hugging Face) sebelum penggunaan komersial.

---

## 🛠️ Cara Memanggil Data di Colab
Gunakan cuplikan kode berikut untuk dataset berbasis URL:

```python
import pandas as pd

# Contoh memanggil dataset Titanic dari link publik
url = "[https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)"
df = pd.read_csv(url)
print(df.head())

**Catatan:** Untuk dataset berukuran besar (>50MB), jangan diunggah ke folder ini. Gunakan link download langsung di dalam Notebook.

