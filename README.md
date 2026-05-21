# Analisis Sentimen Tweet Judi Online di Indonesia
Project tugas akhir mata kuliah Natural Language Processing (NLP) yang berfokus pada analisis sentimen opini masyarakat Indonesia terhadap fenomena judi online menggunakan data Twitter/X.

Project ini menerapkan teknik Natural Language Processing (NLP) dan algoritma Machine Learning untuk mengklasifikasikan sentimen tweet ke dalam kategori positif dan negatif.

---

# Project Overview
Judi online menjadi salah satu isu sosial yang banyak diperbincangkan di media sosial, khususnya Twitter/X.
Melalui project ini dilakukan analisis sentimen untuk mengetahui kecenderungan opini masyarakat terhadap judi online berdasarkan data tweet berbahasa Indonesia.

Project mencakup seluruh tahapan NLP, mulai dari:
- Crawling Data
- Pelabelan Sentimen
- Ekstraksi Fitur TF-IDF
- Klasifikasi Machine Learning
- Visualisasi Data

---

# Features
- Crawling tweet Twitter/X menggunakan `tweet-harvest`
- Preprocessing teks bahasa Indonesia
- Stopwords removal menggunakan `Sastrawi`
- Tokenization & stemming
- Visualisasi WordCloud
- Pelabelan sentimen menggunakan `Vader` + `SentiWords_ID`
- Ekstraksi fitur menggunakan `TF-IDF`
- Klasifikasi sentimen menggunakan:
  - Naive Bayes
  - Support Vector Machine
- Evaluasi model menggunakan:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Confusion Matrix

---

# Dataset
Dataset diperoleh melalui proses crawling data Twitter/X menggunakan keyword:
```python
korban judi online lang:id
```
Dataset berisi tweet berbahasa Indonesia terkait pembahasan judi online.

# Hasil
Model berhasil mengklasifikasikan sentimen tweet menjadi:
- Positif
- Negatif
Evaluasi model dilkaukan menggunakan metrik Accuracy, Precision, Recall, dan F1-Score.
