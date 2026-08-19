
**Nama:** Fikri Alfahri  
**Kelas:** IF405  
**NIM:** 250401020144  
**Program Studi:** PJJ Informatika  

---

## Deskripsi Repository

Repository ini merupakan dokumentasi lengkap mengenai pembelajaran **Data Science** semester ini. Tujuan saya belajar Data Science adalah untuk memahami bagaimana mengolah data mentah menjadi informasi yang bernilai, serta menguasai teknik-teknik analisis data dan machine learning yang dapat diterapkan dalam dunia kerja.

Repository ini berisi **Jupyter Notebook** dari Pertemuan 1 hingga Pertemuan 13, mencakup fundamental Python untuk Data Science, eksplorasi dan visualisasi data, data preprocessing, penerapan berbagai algoritma machine learning (supervised & unsupervised), association rules mining, hingga pengantar Neural Network dan Natural Language Processing (NLP).

---
## List Link Pertemuan
Pertemuan 1: https://colab.research.google.com/drive/1shDpL31tz9mGwJc-65jf3RGE4oEADuWb?usp=sharing
Pertemuan 2: https://colab.research.google.com/drive/1eihoXnGecWGigGnpkp4NY4-TmxhvHv2g?usp=sharing
Pertemuan 3: https://colab.research.google.com/drive/15K9AIuVJjamBexOCXWjmlrqUm3psEOsj?usp=sharing
Pertemuan 4: https://colab.research.google.com/drive/1kty_6O-zo6aR8wjHfN4MN_UjF1CmIpcC?usp=sharing
Pertemuan 5: https://colab.research.google.com/drive/1itAEwNFGAmFdAiPpm93Oupgnu9P1Ka8v?usp=sharing
Pertemuan 6: https://colab.research.google.com/drive/1p2Xj4JwOOj-OAr1yHfvc9IrCfI8myiqP?usp=sharing
Pertemuan 7: https://colab.research.google.com/drive/1mp-klmt72zMc036IlPqLeihQLR1MgkJg?usp=sharing
Pertemuan 9: https://colab.research.google.com/drive/1F7UsS8rCfghbUAJ_7LhfHEzQiIlmf3wr?usp=sharing
Pertemuan 10: https://colab.research.google.com/drive/1p5FnUk9HQYxiKnZ-LvDJhoRLGHzGcJwW?usp=sharing
Pertemuan 11: https://colab.research.google.com/drive/1nJId9iZpPpm4oZHJGg0uGhQ94z4zya9H?usp=sharing
Pertemuan 12: https://colab.research.google.com/drive/1Atpf5b-uNmRsVMDR9aGZqjRNUHRWEKqC?usp=sharing
Pertemuan 13: https://colab.research.google.com/drive/1Bn-62QzHzSeWhwXuMEuF3hfigfOCbcym?usp=sharing

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
  - `LogisticRegression` - Klasifikasi biner dan multi-kelas
  - `DecisionTreeClassifier` - Pohon keputusan
  - `RandomForestClassifier` - Ensemble learning dengan Random Forest
  - `KMeans` - Algoritma clustering K-Means
  - `train_test_split` - Pemisahan data train-test
  - `StandardScaler` - Feature scaling
  - Metrics: `mean_absolute_error`, `mean_squared_error`, `r2_score`, `accuracy_score`, `precision_score`, `recall_score`, `f1_score`, `roc_auc_score`, `silhouette_score`

### **Deep Learning & NLP**
- **TensorFlow / Keras** - Framework deep learning untuk Neural Network
  - `Sequential` - Model arsitektur sequential
  - `Dense` - Fully-connected layer
- **scikit-learn NLP**
  - `TfidfVectorizer` - Ekstraksi fitur teks (TF-IDF)

### **Association Rules Mining**
- **mlxtend** - Implementasi algoritma Apriori dan pembentukan Association Rules
  - `apriori` - Menemukan frequent itemsets
  - `association_rules` - Membentuk aturan asosiasi

### **Statistical Analysis**
- **SciPy** - Analisis statistik lanjutan
  - `scipy.cluster.hierarchy` - Hierarchical clustering dan dendrogram

---

## Ringkasan Perjalanan Belajar (Pertemuan 1-13)

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

### **Pertemuan 9: Logistic Regression & Decision Tree**
Implementasi dan perbandingan dua algoritma klasifikasi supervised learning menggunakan dataset Breast Cancer dari scikit-learn. Logistic Regression digunakan untuk klasifikasi biner berbasis probabilitas, sedangkan Decision Tree untuk klasifikasi berbasis aturan pohon keputusan.

**Key Learning:**
- Logistic Regression: training, analisis koefisien fitur paling berpengaruh
- Decision Tree dengan `max_depth` untuk mencegah overfitting, visualisasi pohon keputusan
- Evaluasi komprehensif: confusion matrix, accuracy, precision, recall, F1-score
- Perbandingan performa model: Logistic Regression (akurasi 98.2%) vs Decision Tree (akurasi 93.9%)

---

### **Pertemuan 10: Random Forest & Customer Churn Prediction**
Penerapan algoritma ensemble Random Forest untuk memprediksi customer churn menggunakan dataset Telco Customer Churn dari IBM. Belajar menangani dataset imbalanced dan interpretasi probabilitas prediksi.

**Key Learning:**
- Random Forest Classifier dengan 300 estimator
- Penanganan imbalanced dataset dengan parameter `class_weight="balanced"`
- Evaluasi dengan classification report dan ROC-AUC score (0.8246)
- Prediksi probabilitas churn untuk peringkat risiko pelanggan

---

### **Pertemuan 11: K-Means Clustering & Hierarchical Clustering**
Penerapan algoritma unsupervised learning untuk segmentasi pelanggan menggunakan dataset sintetis. Metode Elbow digunakan untuk menentukan jumlah cluster optimal, dilengkapi dengan Hierarchical Clustering sebagai pembanding.

**Key Learning:**
- K-Means Clustering: metode Elbow untuk menentukan K optimal
- Evaluasi clustering dengan WCSS dan Silhouette Score (0.695)
- Interpretasi segmen pelanggan: 'Hemat', 'Menengah', 'Boros/Premium'
- Hierarchical Clustering dan visualisasi dendrogram
- Perbandingan K-Means vs Hierarchical Clustering

---

### **Pertemuan 12: Association Rules Mining (Apriori Algorithm)**
Implementasi Association Rules Mining menggunakan algoritma Apriori untuk menemukan pola pembelian dalam data transaksi toko. Belajar konsep support, confidence, dan lift untuk mengukur kekuatan aturan asosiasi.

**Key Learning:**
- One-Hot Encoding transaksi ke format matriks biner
- Algoritma Apriori untuk menemukan frequent itemsets
- Pembentukan association rules dengan metrik: support, confidence, lift
- Interpretasi aturan asosiasi untuk rekomendasi produk (contoh: Roti → Selai)

---

### **Pertemuan 13: Neural Network & Natural Language Processing (NLP)**
Pengantar Deep Learning menggunakan TensorFlow/Keras untuk klasifikasi data non-linear, serta implementasi NLP sederhana dengan TF-IDF dan Logistic Regression untuk klasifikasi sentimen teks.

**Key Learning:**
- Neural Network dengan Keras Sequential API dan Dense layers
- Klasifikasi data non-linear menggunakan dataset `make_moons`
- TF-IDF (Term Frequency-Inverse Document Frequency) untuk representasi teks
- Klasifikasi sentimen teks dengan Logistic Regression
- Memahami perbedaan pendekatan traditional ML vs Deep Learning untuk klasifikasi

---

## Kesimpulan Umum Perjalanan Belajar

Perjalanan belajar Data Science dari Pertemuan 1 hingga 13 memberikan pemahaman yang komprehensif tentang **end-to-end data science workflow**, mulai dari penguasaan fundamental Python, manipulasi data dengan Pandas dan NumPy, eksplorasi dan visualisasi data, hingga penerapan berbagai algoritma machine learning baik supervised maupun unsupervised. Saya belajar bahwa **data cleaning dan preprocessing** merupakan tahapan krusial yang menentukan kualitas model — konsep "garbage in, garbage out" benar-benar terbukti dalam praktik.

Dari sisi **Supervised Learning**, saya telah mempraktikkan spektrum algoritma yang luas: dari Linear Regression untuk prediksi nilai kontinu, Logistic Regression dan Decision Tree untuk klasifikasi biner, hingga Random Forest sebagai model ensemble yang lebih powerful. Masing-masing algoritma memiliki kelebihan dan konteks penggunaan yang berbeda, sehingga kemampuan membandingkan dan memilih model yang tepat menjadi keterampilan penting.

Di sisi **Unsupervised Learning**, K-Means dan Hierarchical Clustering membuka perspektif baru tentang bagaimana menemukan pola tersembunyi dalam data tanpa label — sangat relevan untuk segmentasi pelanggan dan analisis bisnis. Association Rules Mining dengan algoritma Apriori juga menunjukkan bagaimana data transaksi dapat diubah menjadi rekomendasi produk yang actionable.

Puncak perjalanan belajar ini adalah pengantar **Deep Learning dan NLP**, yang membuka wawasan bahwa neural network mampu menangani data kompleks (non-linear, teks) yang sulit dipecahkan oleh algoritma ML tradisional. Pemahaman ini menjadi fondasi yang kuat untuk eksplorasi lebih lanjut dalam deep learning, computer vision, large language models, dan penerapan Data Science di dunia industri.

---

## Struktur Repository

```
Data-Science-2026/
├── README.md
├── pertemuan1_fikrialfahri_250401020144.ipynb   # Python Fundamentals
├── pertemuan2_fikrialfahri_250401020144.ipynb   # NumPy & Pandas
├── pertemuan3_fikrialfahri_250401020144.ipynb   # Data Cleaning
├── pertemuan4_fikrialfahri_250401020144.ipynb   # EDA & Statistics
├── pertemuan5_fikrialfahri_250401020144.ipynb   # Visualization Dashboard
├── pertemuan6_fikrialfahri_250401020144.ipynb   # Preprocessing for ML
├── pertemuan7_fikrialfahri_250401020144.ipynb   # Linear Regression
├── pertemuan9_fikrialfahri_250401020144.ipynb   # Logistic Regression & Decision Tree
├── pertemuan10_fikrialfahri_250401020144.ipynb  # Random Forest & Churn Prediction
├── pertemuan11_fikrialfahri_250401020144.ipynb  # K-Means & Hierarchical Clustering
├── pertemuan12_fikrialfahri_250401020144.ipynb  # Association Rules (Apriori)
└── pertemuan13_fikrialfahri_250401020144.ipynb  # Neural Network & NLP
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

