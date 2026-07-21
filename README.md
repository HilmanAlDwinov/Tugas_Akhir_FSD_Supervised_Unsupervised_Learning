# ❤️ Heart Disease Prediction using Supervised & Unsupervised Learning

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)
![Gradio](https://img.shields.io/badge/Gradio-Web%20Interface-green)
![License](https://img.shields.io/badge/License-Academic-lightgrey)

## 📌 Deskripsi Proyek

Repository ini merupakan **Tugas Akhir Mata Kuliah Fundamental Sains Data** yang mengimplementasikan dua pendekatan Machine Learning:

- **Supervised Learning** untuk memprediksi kemungkinan penyakit jantung.
- **Unsupervised Learning** untuk mengelompokkan pasien berdasarkan karakteristik kesehatan mereka.

Selain implementasi Machine Learning, proyek ini juga menyediakan **antarmuka berbasis Gradio** sehingga model prediksi dapat digunakan secara interaktif.

---

# 👥 Kelompok

| Nama | NIM |
|------|-----|
| Hilman Al Dwinov | 24523216 |
| Ibrahim Ivanka | 24523279 |

---

# 🎯 Tujuan

Tujuan proyek ini adalah:

- Memahami proses Data Science secara end-to-end.
- Melakukan Exploratory Data Analysis (EDA).
- Melakukan preprocessing data.
- Membangun model klasifikasi penyakit jantung.
- Mengevaluasi performa model.
- Melakukan clustering menggunakan algoritma unsupervised learning.
- Membuat aplikasi sederhana menggunakan Gradio.

---

# 📂 Dataset

**Nama Dataset**

Heart Disease Prediction Dataset

**Sumber**

https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset

Dataset berisi informasi kesehatan pasien yang digunakan untuk memprediksi apakah seseorang memiliki penyakit jantung.

---

# 📊 Fitur Dataset

Dataset memiliki beberapa atribut kesehatan, diantaranya:

- Age
- Sex
- Chest Pain Type (cp)
- Resting Blood Pressure (trestbps)
- Cholesterol (chol)
- Fasting Blood Sugar (fbs)
- Resting ECG (restecg)
- Maximum Heart Rate (thalach)
- Exercise Induced Angina (exang)
- ST Depression (oldpeak)
- Slope
- Number of Major Vessels (ca)
- Thal
- Target (Heart Disease)

---

# ⚙️ Teknologi yang Digunakan

- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Joblib
- Gradio

---

# 📑 Tahapan Analisis

## 1. Import Library

Mengimpor seluruh library yang dibutuhkan.

## 2. Load Dataset

Membaca dataset menggunakan Pandas.

## 3. Deskripsi Dataset

Melakukan identifikasi:

- jumlah data
- jumlah fitur
- tipe data
- statistik deskriptif

## 4. Exploratory Data Analysis (EDA)

Visualisasi data menggunakan:

- Histogram
- Boxplot
- Countplot
- Heatmap
- Scatter Plot

Tujuannya untuk memahami pola dan hubungan antar variabel.

## 5. Data Preprocessing

Tahapan preprocessing meliputi:

- Missing Value Handling
- Duplicate Removal
- Outlier Handling
- Encoding
- Feature Scaling

---

# 🤖 Supervised Learning

Model digunakan untuk memprediksi apakah pasien memiliki penyakit jantung.

Tahapan:

- Feature Selection
- Train Test Split
- Model Training
- Prediction
- Evaluation

Evaluasi dilakukan menggunakan:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

# 📈 Unsupervised Learning

Menggunakan algoritma clustering untuk mengelompokkan pasien berdasarkan karakteristik kesehatannya.

Tahapan:

- Feature Selection
- Standardization
- Clustering
- Cluster Visualization

Evaluasi dilakukan menggunakan:

- Elbow Method
- Silhouette Score

---

# 🖥️ Gradio Interface

Proyek menyediakan aplikasi sederhana menggunakan **Gradio**.

Fitur aplikasi:

- Input data pasien
- Prediksi penyakit jantung
- Menampilkan hasil prediksi secara langsung

---

# 📁 Struktur Repository

```
.
├── FSD_Kelompok_Heart_Disease_Prediction.ipynb
├── heart.csv
├── requirements.txt
├── README.md
├── model.pkl               # jika model disimpan
└── assets/
```

---

# 🚀 Cara Menjalankan Project

## 1. Clone Repository

```bash
git clone
```

Masuk ke folder project

```bash
cd REPOSITORY
```

---

## 2. Membuat Virtual Environment (Opsional)

Windows

```bash
python -m venv venv
venv\Scripts\activate
```

Linux / macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## 3. Install Dependency

Jika terdapat file `requirements.txt`

```bash
pip install -r requirements.txt
```

Jika belum ada, install manual

```bash
pip install pandas
pip install numpy
pip install matplotlib
pip install seaborn
pip install scikit-learn
pip install gradio
pip install joblib
```

atau sekaligus

```bash
pip install pandas numpy matplotlib seaborn scikit-learn gradio joblib
```

---

## 4. Menjalankan Notebook

Jalankan menggunakan

- Jupyter Notebook

```bash
jupyter notebook
```

atau

- Google Colab

Upload file

```
FSD_Kelompok_Heart_Disease_Prediction.ipynb
```

Kemudian jalankan seluruh cell dari atas hingga selesai.

---

## 5. Menjalankan Gradio

Apabila notebook memiliki bagian Gradio, jalankan cell terakhir.

Contoh:

```python
demo.launch()
```

atau

```python
iface.launch()
```

Setelah berhasil dijalankan akan muncul alamat seperti

```
Running on local URL:
http://127.0.0.1:7860
```

Buka alamat tersebut melalui browser.

---

# 📊 Hasil

Pada proyek ini dilakukan:

- Analisis karakteristik pasien.
- Implementasi preprocessing data.
- Pelatihan model klasifikasi.
- Evaluasi performa model.
- Clustering pasien.
- Visualisasi cluster.
- Implementasi aplikasi Gradio.

---

# 📚 Referensi

Heart Disease Dataset

https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset

Scikit-Learn Documentation

https://scikit-learn.org/

Gradio Documentation

https://www.gradio.app/

Pandas Documentation

https://pandas.pydata.org/

---

# 📄 Lisensi

Repository ini dibuat untuk keperluan akademik sebagai **Final Project Mata Kuliah Fundamental Sains Data** di Universitas Islam Indonesia.
