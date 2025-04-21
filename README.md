# 🏠 EDA Boston Housing

Exploratory Data Analysis (EDA) ini dilakukan pada dataset **Boston Housing** untuk memahami faktor-faktor yang memengaruhi harga rumah di daerah Boston. Analisis ini bertujuan untuk mengidentifikasi pola, hubungan antar variabel, serta insight menarik dari data.

## 📁 Dataset

Dataset yang digunakan berasal dari `sklearn.datasets.load_boston()` (meskipun sudah deprecated, tetap banyak digunakan untuk studi analisis).  
Dataset ini berisi informasi seperti:
- Jumlah kamar
- Jarak ke fasilitas umum
- Tingkat kejahatan
- Pajak properti
- Dan variabel-variabel lain yang memengaruhi harga rumah

## 📊 Tools & Libraries

Proyek ini dibangun menggunakan tools dan library berikut:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 🔍 Analisis yang Dilakukan

- Data Cleaning (handling missing values, tipe data)
- Univariate Analysis
- Bivariate Analysis (korelasi antar fitur)
- Visualisasi distribusi dan outliers
- Heatmap korelasi
- Insight dari pola data

## 📌 Insight Utama

- Fitur **RM (jumlah kamar)** memiliki korelasi positif yang tinggi dengan harga rumah.
- Fitur **LSTAT (persentase populasi berstatus rendah)** berkorelasi negatif kuat dengan harga rumah.
- **Tingkat kejahatan (CRIM)** cenderung berbanding terbalik dengan harga.
- Visualisasi menunjukkan adanya outliers dan skewed distributions pada beberapa fitur.

## 📁 File

- `EDA_Boston_Housing.ipynb` – notebook utama yang berisi seluruh proses analisis data.

## ✅ Status

📌 Project ini bersifat edukatif dan terbuka untuk kontribusi, pembaruan, atau pengembangan lebih lanjut.

---

## ✍️ Author

Firman Maulana Putra  
GitHub: [@firmanmaulana123](https://github.com/firmanmaulana123)  
Add initial README for Boston Housing EDA
