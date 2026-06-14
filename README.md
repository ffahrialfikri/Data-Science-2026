
**Nama:** Fikri Alfahri  
**Kelas:** IF405  
**NIM:** 250401020144  
**Program Studi:** PJJ Informatika  

---

## Deskripsi Repository

Repository ini merupakan dokumentasi lengkap mengenai pembeljaran **Data Science** semester ini. Tujuan saya belajar Data Science adalah untuk memahami bagaimana mengolah data mentah menjadi informasi yang bernilai, serta menguasai teknik-teknik analisis data dan machine learning yang dapat diterapkan dalam dunia kerja.

Repository ini berisi **Jupyter Notebook** dari Pertemuan 1 hingga Pertemuan 7 mencakup fundamental Python untuk Data Science, eksplorasi dan visualisasi data, data preprocessing, hingga penerapan algoritma machine learning. 

---
## List Link Pertemuan
Pertemuan 1: https://colab.research.google.com/drive/1shDpL31tz9mGwJc-65jf3RGE4oEADuWb?usp=sharing
Pertemuan 2: https://colab.research.google.com/drive/1eihoXnGecWGigGnpkp4NY4-TmxhvHv2g?usp=sharing
Pertemuan 3: https://colab.research.google.com/drive/15K9AIuVJjamBexOCXWjmlrqUm3psEOsj?usp=sharing
Pertemuan 4: https://colab.research.google.com/drive/1kty_6O-zo6aR8wjHfN4MN_UjF1CmIpcC?usp=sharing
Pertemuan 5: https://colab.research.google.com/drive/1itAEwNFGAmFdAiPpm93Oupgnu9P1Ka8v?usp=sharing
Pertemuan 6: https://colab.research.google.com/drive/1p2Xj4JwOOj-OAr1yHfvc9IrCfI8myiqP?usp=sharing
Pertemuan 7: https://colab.research.google.com/drive/1mp-klmt72zMc036IlPqLeihQLR1MgkJg?usp=sharing

## Tools & Library yang Digunakan

Berikut adalah tools dan library Python yang digunakan sepanjang pembelajaran:

### **Programming Environment**
- **Python 3.x** - Bahasa pemrograman utama
- **Google Colab** - Platform Jupyter Notebook berbasis cloud
- **Jupyter Notebook** - Interactive development environment
- **GitHub** - Version control dan dokumentasi

### **Data Manipulation & Analysis**
- **Pandas** - Manipulasi dan analisis data tabular
- **NumPy** - Komputasi numerik dan array operations

### **Data Visualization**
- **Matplotlib** - Library visualisasi fundamental
- **Seaborn** - Visualisasi statistik yang elegan
- **Missingno** - Visualisasi missing values

### **Machine Learning**
- **scikit-learn** - Machine learning dan preprocessing
  - `LinearRegression` - Regresi linear
  - `train_test_split` - Pemisahan data train-test
  - `StandardScaler` - Feature scaling
  - Metrics: `mean_absolute_error`, `mean_squared_error`, `r2_score`

### **Statistical Analysis**
- **SciPy** - Analisis statistik lanjutan

---

## Ringkasan Perjalanan Belajar (Pertemuan 1-7)

### **Pertemuan 1: Python Fundamentals for Data Science**
Memahami dasar-dasar pemrograman Python yang menjadi fondasi Data Science, termasuk variabel, tipe data, struktur kontrol (perulangan), dan fungsi. Praktik pembuatan fungsi sederhana untuk perkenalan dan operasi matematika dasar.

**Key Learning:** Sintaks Python, penggunaan fungsi, dan list operations.

---

### **Pertemuan 2: NumPy & Pandas Basics**
Pengenalan library fundamental untuk Data Science: NumPy untuk array operations dan komputasi numerik, serta Pandas untuk manipulasi data tabular. Praktik membuat array, DataFrame, filtering data, dan operasi dasar Series.

**Key Learning:**
- Array operations dengan NumPy (zeros, ones, arange, linspace)
- DataFrame operations (indexing, filtering, describe)
- Perbedaan Series vs DataFrame

---

### **Pertemuan 3: Data Cleaning & Missing Values Handling**
Belajar mendeteksi, menganalisis, dan menangani missing values menggunakan dataset housing_dirty.csv. Eksplorasi berbagai strategi imputasi (mean, median, mode, forward/backward fill) dan dropping data yang tidak relevan.

**Key Learning:**
- Deteksi missing values dengan `isnull()` dan `missingno`
- Strategi imputasi: median untuk data skewed, mean untuk distribusi normal
- Dropping kolom dengan missing values > 40%
- Visualisasi pola missing dengan missingno (matrix, heatmap, bar)

---

### **Pertemuan 4: Exploratory Data Analysis (EDA) & Statistical Analysis**
Analisis mendalam dataset Iris dengan statistik deskriptif, analisis distribusi, dan visualisasi. Mempelajari konsep mean, median, standar deviasi, skewness, kurtosis, serta korelasi antar variabel.

**Key Learning:**
- Statistik deskriptif: mean, median, std, skewness, kurtosis
- Visualisasi distribusi: histogram, KDE, boxplot, violin plot
- Analisis korelasi Pearson dan heatmap
- Scatter plot untuk melihat hubungan antar fitur

---

### **Pertemuan 5: Data Visualization Dashboard**
Membuat dashboard analisis visual yang komprehensif menggunakan dataset Diamonds. Implementasi multi-panel visualization dengan GridSpec untuk menyajikan berbagai jenis plot dalam satu figure.

**Key Learning:**
- Layout management dengan `matplotlib.gridspec`
- Kombinasi plot: histogram, countplot, boxplot, scatter plot
- Regression line dengan `sns.regplot()`
- Export visualisasi ke file PNG dengan resolusi tinggi

---

### **Pertemuan 6: Data Preprocessing for Machine Learning**
Persiapan data Titanic untuk machine learning, mencakup handling missing values, encoding variabel kategorikal, train-test split dengan stratifikasi, dan feature scaling.

**Key Learning:**
- One-Hot Encoding dengan `pd.get_dummies(drop_first=True)`
- Stratified train-test split untuk menjaga proporsi kelas
- StandardScaler: fit pada training set, transform pada test set
- Menghindari data leakage dalam preprocessing

---

### **Pertemuan 7: Linear Regression & Model Evaluation**
Implementasi end-to-end machine learning: dari pembuatan dataset sintetis prediksi gaji, preprocessing, training model Linear Regression, hingga evaluasi dengan berbagai metrik.

**Key Learning:**
- Regresi Linear dengan scikit-learn
- Interpretasi koefisien regresi (β)
- Metrik evaluasi: MAE (Mean Absolute Error), RMSE (Root Mean Squared Error), R² Score
- Visualisasi evaluasi: Actual vs Predicted plot, Residual plot
- Deteksi outlier dari selisih RMSE-MAE

---

## Kesimpulan Umum Perjalanan Belajar

Perjalanan belajar Data Science dari Pertemuan 1 hingga 7 memberikan pemahaman yang solid tentang **end-to-end data science workflow**, mulai dari penguasaan fundamental Python, manipulasi data dengan Pandas dan NumPy, hingga implementasi algoritma machine learning. Saya belajar bahwa **data cleaning dan preprocessing** merupakan tahapan krusial yang menentukan kualitas model - konsep "garbage in, garbage out" benar-benar terbukti dalam praktik.

Kemampuan melakukan **Exploratory Data Analysis (EDA)** dengan visualisasi yang efektif terbukti sangat penting untuk memahami pola data sebelum membuat model. Saya juga memahami pentingnya **evaluasi model yang komprehensif** - tidak cukup hanya melihat satu metrik, tetapi perlu kombinasi MAE, RMSE, dan R² untuk mendapatkan gambaran lengkap performa model.

Yang paling berkesan adalah memahami bahwa Data Science bukan hanya tentang coding dan algoritma, tetapi tentang **memahami data, mengajukan pertanyaan yang tepat, dan mengkomunikasikan insight secara visual**. Pembelajaran ini menjadi fondasi yang kuat untuk eksplorasi lebih lanjut dalam deep learning, big data, dan aplikasi Data Science di dunia industri.

---

## Struktur Repository

```
Data-Science-2026/
├── README.md
├── pertemuan1_fikrialfahri_250401020144.ipynb  # Python Fundamentals
├── pertemuan2_fikrialfahri_250401020144.ipynb  # NumPy & Pandas
├── pertemuan3_fikrialfahri_250401020144.ipynb  # Data Cleaning
├── pertemuan4_fikrialfahri_250401020144.ipynb  # EDA & Statistics
├── pertemuan5_fikrialfahri_250401020144.ipynb  # Visualization Dashboard
├── pertemuan6_fikrialfahri_250401020144.ipynb  # Preprocessing for ML
└── pertemuan7_fikrialfahri_250401020144.ipynb  # Linear Regression
```

---

## Cara Menggunakan Repository

1. **Clone repository ini:**
   ```bash
   git clone https://github.com/ffahrialfikri/Data-Science-2026.git
   ```

2. **Buka notebook di Google Colab:**
   - Klik badge "Open in Colab" di setiap notebook
   - Atau upload file `.ipynb` ke Google Colab secara manual

3. **Install dependencies (jika perlu):**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn missingno scipy
   ```

4. **Jalankan cell secara berurutan** untuk melihat hasil analisis dan visualisasi.

---

