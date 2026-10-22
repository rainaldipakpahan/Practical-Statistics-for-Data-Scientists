# Practical Statistics for Data Scientists

Repository ini berisi implementasi kode dan ringkasan materi dari buku *Practical Statistics for Data Scientists, 2nd Edition*, yang mencakup Chapter 1 sampai Chapter 6.

## Identitas

**Nama:** Rainaldi Pakpahan  
**NIM:** 101032300084

**Nama:** Firdaus Arif Ramadhani  
**NIM:** 101032300131

## Deskripsi

Repository ini dibuat untuk memenuhi tugas reproduksi kode dan pemahaman konsep dari buku *Practical Statistics for Data Scientists*.

Setiap chapter berisi:
- Penjelasan konsep dan teori statistik.
- Implementasi kode menggunakan Python.
- Visualisasi data dan hasil pengolahan.
- Hasil analisis dari metode yang digunakan.
- Interpretasi output untuk memahami hasil setiap percobaan.

Pembahasan disusun berdasarkan materi pada buku dengan menggunakan Google Colab agar kode dapat dijalankan dan dipelajari kembali.

## Daftar Chapter

### Chapter 1 — Exploratory Data Analysis

Membahas proses eksplorasi data, statistik deskriptif, ukuran penyebaran, distribusi data, outlier, data kategorikal, korelasi, dan hubungan antarvariabel. Chapter ini menjadi dasar untuk memahami karakteristik dataset sebelum dilakukan analisis lebih lanjut.

File:  
`01_Exploratory_Data_Analysis.ipynb`

### Chapter 2 — Data and Sampling Distributions

Membahas population dan sample, random sampling, sampling distribution, standard error, bootstrap, confidence interval, normal distribution, t-distribution, binomial distribution, dan Poisson distribution.

File:  
`02_Data_and_Sampling_Distributions.ipynb`

### Chapter 3 — Statistical Experiments and Significance Testing

Membahas A/B testing, hypothesis testing, permutation test, p-value, t-test, ANOVA, dan chi-square test. Materi ini digunakan untuk memahami cara menguji hipotesis dan menentukan apakah perbedaan hasil pengamatan signifikan secara statistik.

File:  
`03_Statistical_Experiments_and_Significance_Testing.ipynb`

### Chapter 4 — Regression and Prediction

Membahas simple linear regression, multiple linear regression, prediksi, residual, R-squared, RMSE, serta perbandingan nilai aktual dan hasil prediksi. Analisis digunakan untuk mengetahui hubungan antarvariabel dan mengukur kemampuan model dalam melakukan prediksi.

File:  
`04_Regression_and_Prediction.ipynb`

### Chapter 5 — Classification

Membahas metode klasifikasi untuk memprediksi kategori atau kelas berdasarkan karakteristik data. Materinya mencakup Naive Bayes, probabilitas Bayesian, Linear Discriminant Analysis (LDA), Logistic Regression, Generalized Linear Models (GLM), dan Odds Ratio.

Selain itu, chapter ini membahas evaluasi model klasifikasi menggunakan Confusion Matrix, Accuracy, Precision, Recall, F1-Score, ROC Curve, AUC, dan Precision–Recall Curve. Penanganan data tidak seimbang juga dibahas melalui undersampling, oversampling, serta cost-based classification.

File:  
`05_Classification.ipynb`

### Chapter 6 — Statistical Machine Learning

Membahas penerapan algoritma machine learning untuk klasifikasi dan prediksi, dimulai dari K-Nearest Neighbors (KNN), pengukuran jarak antarobservasi, standardisasi data, pemilihan nilai K, dan *curse of dimensionality*.

Selanjutnya membahas Decision Tree, Gini Impurity, Entropy, Regression Tree, Bagging, Random Forest, Out-of-Bag (OOB) Evaluation, Feature Importance, AdaBoost, Gradient Boosting, serta XGBoost.

Chapter ini juga mencakup evaluasi dan perbandingan beberapa algoritma untuk memahami pengaruh pemilihan model serta hyperparameter terhadap hasil prediksi.

File:  
`06_Statistical_Machine_Learning.ipynb`

## Tools

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- XGBoost

## Cara Menjalankan

1. Buka salah satu file `.ipynb` pada repository.
2. Pilih **Open in Colab** atau upload notebook ke Google Colab.
3. Jalankan setiap cell secara berurutan dari atas ke bawah menggunakan menu **Runtime → Run all**.
4. Pastikan seluruh kode berjalan dan menghasilkan output serta visualisasi.
5. Baca penjelasan dan interpretasi pada setiap bagian untuk memahami hasil analisis.

Hasil yang ditampilkan dapat sedikit berbeda bergantung pada versi library, pembagian dataset, atau proses yang melibatkan pengacakan.

## Referensi

Bruce, P., Bruce, A., & Gedeck, P. (2020).  
*Practical Statistics for Data Scientists: 50+ Essential Concepts Using R and Python*.  
2nd Edition. O'Reilly Media.

Repository kode dan dataset resmi:  
https://github.com/gedeck/practical-statistics-for-data-scientists
