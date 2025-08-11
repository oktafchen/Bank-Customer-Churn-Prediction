# 📊 Customer Churn Prediction

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk memprediksi pelanggan yang berpotensi melakukan **churn** (berhenti berlangganan) menggunakan berbagai metode machine learning, seperti **Logistic Regression** dan **XGBoost**.  
Analisis ini meliputi **EDA (Exploratory Data Analysis)**, pemodelan, evaluasi, dan perbandingan performa model.

---

## 📂 Struktur Repo
📂 churn-prediction/
├── data/ # Dataset (jika boleh diupload)
│ └── bank_churn_dataset.csv
├── Customer_prediction_churn.ipynb # Notebook Google Colab
├── README.md # File ini
└── requirements.txt # (Opsional) Library yang digunakan

---

## 📊 Tahapan Analisis
1. **Data Understanding & Cleaning**
   - Memeriksa missing values, duplikasi, dan tipe data.
   - Menangani outlier dan nilai kosong.
   
2. **Exploratory Data Analysis (EDA)**
   - Analisis univariat, bivariat, dan multivariat.
   - Visualisasi hubungan fitur numerik & kategorikal dengan target churn.
   
3. **Feature Engineering**
   - Encoding variabel kategorikal.
   - Normalisasi/standarisasi variabel numerik.
   
4. **Modeling**
   - **Logistic Regression**
   - **XGBoost**
   
5. **Evaluasi**
   - ROC-AUC, Precision, Recall, F1-score.
   - Precision-Recall Curve.
   - Perbandingan hasil antar model.

---

## 📈 Hasil Utama
### 🔹 Logistic Regression
- **AUC (Test)**: 0.92
- **Recall (Churn)**: 0.82
- **Accuracy**: 85%

### 🔹 XGBoost
- **AUC (Test)**: 0.99
- **Recall (Churn)**: 0.91
- **Accuracy**: 96%

**Kesimpulan:** XGBoost memberikan performa yang lebih baik dibanding Logistic Regression pada semua metrik utama, sehingga direkomendasikan untuk digunakan pada kasus ini.

---

## 🚀 Cara Menjalankan Notebook
1. Clone repositori ini:
   ```bash
   git clone [https://github.com/username/churn-prediction.git](https://github.com/oktafchen/Bank-Customer-Churn-Prediction)



📦 Library yang Digunakan

    pandas
    numpy
    matplotlib
    seaborn
    scikit-learn
    xgboost



📜 Lisensi

Proyek ini dibuat untuk keperluan pembelajaran dan analisis data.


---
