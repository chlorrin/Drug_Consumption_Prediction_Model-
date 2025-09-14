# Drug Consumption Classification

## Deskripsi

Proyek ini merupakan bagian dari **Final Exam Odd Semester 2024/2025** pada program studi **Information System**. Tujuan dari analisis ini adalah untuk membangun model **machine learning** yang mampu memprediksi kemungkinan seseorang mengonsumsi narkoba berdasarkan data psikologi dan demografi.

## Dataset

Dataset yang digunakan adalah **Drug Consumption Classification** yang tersedia di [Kaggle](https://www.kaggle.com/datasets/mexwell/drug-consumption-classification).
Kriteria dataset:

* Memiliki lebih dari 1.000 baris dan 10 kolom.
* Tidak lebih dari 5 tahun.
* Format CSV.

Dataset mencakup:

* Skor kepribadian (Neuroticism, Extraversion, Openness, Agreeableness, Conscientiousness).
* Impulsivitas dan Sensation Seeking.
* Variabel target: konsumsi narkoba.

## Metode

1. **Preprocessing Data**

   * Mengecek duplikasi dan missing values.
   * Menangani outlier dengan metode IQR.
   * Normalisasi data menggunakan **MinMaxScaler**.

2. **Pemisahan Data**

   * Train-test split untuk pelatihan dan evaluasi model.

3. **Model Machine Learning**

   * Logistic Regression.
   * Support Vector Machine (SVM).
   * Random Forest Classifier.

4. **Evaluasi**

   * Accuracy Score.
   * Confusion Matrix.
   * Classification Report (Precision, Recall, F1-score).

## Hasil

Model yang dibangun mampu mengklasifikasikan apakah seseorang termasuk pengguna narkoba atau bukan, berdasarkan faktor psikologi dan demografi.
Evaluasi menunjukkan hasil prediksi yang cukup baik dengan kombinasi **akurasi** dan **F1-score** yang seimbang pada model Logistic Regression, SVM, dan Random Forest.

## Kesimpulan

Analisis ini menunjukkan bahwa data kepribadian dan psikologi dapat digunakan sebagai indikator dalam membangun model prediksi konsumsi narkoba. Model dapat membantu penelitian dan edukasi terkait faktor risiko penyalahgunaan narkoba.
