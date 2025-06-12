# Prediksi Nilai Akademik Mahasiswa Menggunakan Algoritma K-Nearest Neighbors (KNN) Berdasarkan Pola Perilaku Belajar

## 📌 Deskripsi Proyek

Proyek ini bertujuan untuk memprediksi nilai akademik mahasiswa berdasarkan berbagai pola perilaku belajar, seperti gaya belajar, kehadiran, jam belajar, dan penggunaan teknologi edukasi. Proyek ini menggunakan algoritma **K-Nearest Neighbors (KNN)** yang diimplementasikan dari nol tanpa library pemodelan (sesuai aturan tugas), dan dievaluasi menggunakan **K-Fold Cross Validation** untuk meningkatkan keandalan model.

---

## 👩‍💻 Anggota Kelompok 13

| NIM            | Nama                    |
|----------------|-------------------------|
| 103022300014   | Rahmah Aisyah           |
| 103022300071   | Dewanta Rahma Satria    |

---

## 🧭 Struktur Project di Google Colab

1. **Read the Data**  
2. **Data Understanding**  
3. **Cleaning Data**  
4. **Exploratory Data Analysis (EDA)** 
5. **Data Preparation**  
   - Encoding fitur kategorikal (Gender, Participation, dsb.)
   - Transformasi label menjadi biner 
   - Split data menjadi data latih dan data uji
6. **Modeling**  
   - Implementasi algoritma **pembuatan funtion model KNN**
   - Evaluasi akurasi model menggunakan:
     - Data Training
     - Data Testing
     - Menghitung metrik evaluasi: `Accuracy`, `Sensitivity`, `Specificity`, `Precision`, `F1-Score`
     
7. **Pengujian Data Tunggal**  
   - Menyediakan hasil prediksi untuk satu input data secara manual

8. **Model Evaluation**  
   - MEnggunakan metode evaluasi model **K-Fold Cross Validation**
   - Menghitung metrik evaluasi: `Accuracy`, `Sensitivity`, `Specificity`, `Precision`, `F1-Score`
   - Visualisasi evaluasi model bentuk diagram batang akurasi per fold dan boxplot akurasi menunjukkan sebaran nilai akurasi 

---

## 🛠 Teknologi yang Digunakan

- Python (Google Colab)
- Pandas, NumPy, Matplotlib

---

## 🧠 Catatan Teknis

- Algoritma diimplementasikan **dari awal**, tanpa bantuan fungsi-fungsi KNN dari pustaka eksternal.
- Dataset diambil dari [Kaggle - Student Performance and Learning Style](https://www.kaggle.com/datasets/adilshamim8/student-performance-and-learning-style)
- Proyek mengikuti aturan Project-Based Learning dari mata kuliah **Kecerdasan Buatan - S1 RPL**

---

## 🧾 Disusun oleh Kelompok 13
