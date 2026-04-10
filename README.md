# Project-Based-Internship-Rakamin-X-ID-X-Partners

# 📊 Loan Risk Prediction - Capstone Project

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk membangun model machine learning dalam memprediksi risiko pinjaman (loan risk), yaitu mengklasifikasikan apakah suatu pinjaman termasuk GOOD LOAN atau BAD LOAN berdasarkan data historis.

Model ini diharapkan dapat membantu institusi keuangan dalam:
- Mengidentifikasi potensi kredit bermasalah  
- Mengurangi risiko kerugian  
- Mendukung pengambilan keputusan kredit  

---

## 📂 Dataset
Dataset yang digunakan merupakan data pinjaman yang berisi informasi terkait:
- Profil peminjam  
- Kondisi keuangan  
- Riwayat kredit  
- Status pinjaman  

---

## ⚙️ Tahapan Proyek

### 1. Data Preprocessing
- Menghapus fitur yang tidak relevan (ID, URL, dll)
- Menangani missing values:
  - Numerik → median  
  - Diskrit → 0  
  - Kategorikal → mode  
- Encoding data kategorikal  
- Feature scaling untuk model tertentu  

### 2. Feature Engineering
- Transformasi target menjadi:
  - GOOD LOAN (0)
  - BAD LOAN (1)  
- Penyederhanaan berbagai status pinjaman menjadi klasifikasi biner  

### 3. Modeling
Algoritma yang digunakan:
- Logistic Regression  
- Random Forest  
- Decision Tree  
- K-Nearest Neighbors (KNN)  
- Gradient Boosting  

### 4. Evaluasi Model
Evaluasi dilakukan menggunakan:
- Accuracy
- ROC-AUC Score

| Model               | ROC-AUC | Accuracy |
|---------------------|--------|----------|
| Random Forest       | 0.9653 | 0.976    |
| Logistic Regression | 0.9623 | 0.9737   |
| Decision Tree       | 0.9019 | 0.9561   |
| KNN                 | 0.855  | 0.9398   |

---

## 📊 Hasil dan Insight
- Random Forest memberikan performa terbaik  
- Model mampu mengklasifikasikan risiko pinjaman dengan sangat baik (ROC-AUC > 0.96)  
- Dataset memiliki class imbalance, sehingga ROC-AUC menjadi metrik utama  

---

## 🎯 Kesimpulan
Model machine learning yang dibangun mampu memprediksi risiko pinjaman secara akurat. Model terbaik yang diperoleh adalah Random Forest, yang dapat digunakan sebagai dasar dalam sistem penilaian kredit.

---

## 🚀 Teknologi yang Digunakan
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  

---

## 📁 Struktur Project
