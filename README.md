# 🎬 Sentiment Analysis on IMDb Movie Reviews using Naive Bayes  
# Analisis Sentimen pada Ulasan Film IMDb menggunakan Naive Bayes  

Proyek ini merupakan implementasi lengkap dari **Analisis Sentimen** menggunakan algoritma **Naive Bayes Classifier** pada dataset ulasan film IMDb. Semua proses dilakukan dalam Jupyter Notebook, mulai dari praproses data, ekstraksi fitur, pelatihan model, hingga evaluasi.  

## 📌 Sorotan Proyek  
- 🧠 Model Machine Learning: Multinomial Naive Bayes.  
- 🗣️ Teknik NLP: Tokenisasi, Penghapusan Stopword, TF-IDF.  
- 📊 Evaluasi: Confusion Matrix, Classification Report.  
- 📝 Bahasa: Python (Jupyter Notebook).

## 📁 Struktur File  
- `SentimentAnalysis_on_IMDbMovieReview_using_NaiveBayes.ipynb` — notebook utama.  
- `README.md` — file dokumentasi ini.

## 📦 Pustaka yang Digunakan  
- `pandas`, `numpy` — untuk manipulasi data.  
- `nltk` — untuk pemrosesan bahasa alami.  
- `scikit-learn` — untuk model machine learning dan metrik evaluasi.  
- `matplotlib` — untuk visualisasi data.

## 📂 Dataset  
Dataset yang digunakan adalah [IMDb Movie Reviews Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews), yang berisi 50.000 ulasan film dengan jumlah seimbang antara sentimen positif dan negatif.  
> **Catatan:** Anda perlu mengunduh file `IMDB_Dataset.csv` secara manual dan meletakkannya di folder yang sama dengan notebook.  

## 🎯 Tujuan Proyek  
Proyek ini bertujuan untuk:  
- Membangun model klasifikasi sentimen sederhana namun efektif menggunakan Naive Bayes.
- Melatih kemampuan dalam praproses teks menggunakan teknik NLP.
- Menganalisis performa model melalui metrik seperti akurasi, precision, recall, dan f1-score.
- Memberikan contoh proyek machine learning yang dapat digunakan pemula sebagai studi kasus.

## 📝 Catatan Penting  
- Pastikan Anda telah mengunduh dataset IMDB_Dataset.csv dari Kaggle.
- Notebook dapat dijalankan secara lokal menggunakan Jupyter Notebook atau Google Colab.
- Tidak diperlukan GPU untuk menjalankan proyek ini karena modelnya ringan.
- Hasil evaluasi dapat sedikit berbeda tergantung dari pembagian data (karena train_test_split acak).
