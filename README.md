# Data Science Pipeline for Classification

Proyek ini mencakup langkah-langkah pemrosesan data, eksplorasi, dan implementasi model Machine Learning menggunakan Random Forest dan Logistic Regression.

## 🚀 Data Loading & Preprocessing
- Membaca file CSV.
- Encoding variabel kategorikal (misalnya, pada variabel Gender dan TB/U).
- Menangani missing values dan outlier menggunakan Winsorization dan median replacement.

## 📊 Exploratory Data Analysis (EDA)
- Membuat boxplot untuk variabel numerik.
- Membuat pie chart untuk distribusi kelas.

## 🔍 Feature Engineering & Data Preparation
- Memilih fitur yang relevan (Age, Weight, Height, Birth Weight, Birth Height, gender encoded, status encoded).
- Menangani class imbalance menggunakan SMOTE.

## 🏆 Machine Learning Pipeline
- Menggunakan **Random Forest** dan **Logistic Regression**.
- Implementasi **K-Fold Cross Validation** untuk evaluasi model.

## 📈 Evaluation
- Metrik yang digunakan: **precision, recall, f1-score, accuracy**.
- Analisis per-fold dan rata-rata makro.
