# Model Prediksi Penyakit Jantung Menggunakan ANN 🫀
> Heart Disease Prediction Model Using Artificial Neural Network

## 📚 Informasi Akademik
| Detail           | Keterangan                                |
|-----------------|-------------------------------------------|
| Nama            | Miftakhul Rahman                          |
| NIM             | 24.66.1012                               |
| Kelas           | Student Exchange                          |
| Mata Kuliah     | Big Data & Data Mining                    |
| Dosen Pengampu  | Hendri Kurniawan Prakosa, S.Kom., M.Cs   |

## 📝 Deskripsi Proyek
Proyek ini mengimplementasikan model prediksi penyakit jantung menggunakan metode Artificial Neural Network (ANN). Model ini dikembangkan untuk mengklasifikasikan risiko penyakit jantung berdasarkan berbagai parameter kesehatan pasien. Implementasi menggunakan arsitektur deep learning modern dengan teknik regularisasi untuk mencegah overfitting.

## 🔍 Fitur Utama
- Data preprocessing otomatis dengan penanganan missing values
- Label encoding untuk variabel kategorikal
- Feature selection menggunakan SelectKBest untuk memilih 8 fitur terpenting
- Arsitektur ANN dengan 3 hidden layer dan dropout
- Early stopping untuk mencegah overfitting
- Visualisasi performa model dan metrics evaluasi
- Penyimpanan model dan scaler untuk penggunaan masa depan

## 🛠️ Teknologi yang Digunakan
- Python 3.x
- TensorFlow/Keras untuk pembuatan model ANN
- Pandas untuk manipulasi data
- NumPy untuk operasi numerik
- Scikit-learn untuk preprocessing dan evaluasi
- Seaborn & Matplotlib untuk visualisasi
- Pickle untuk penyimpanan model

## 📊 Dataset
Dataset yang digunakan adalah `heart.csv` yang memiliki fitur-fitur berikut:
- Variabel Kategorikal: Sex, ChestPainType, RestingECG, ExerciseAngina, ST_Slope
- Variabel Numerik: Age, RestingBP, Cholesterol, MaxHR, Oldpeak
- Target: HeartDisease (binary classification)
Dataset di peroleh dari kaggle : https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction

## 📈 Hasil dan Evaluasi
Penelitian ini berhasil mengembangkan model prediksi risiko penyakit jantung menggunakan Artificial Neural Network dengan tingkat akurasi 86.41%. Model menunjukkan performa yang seimbang dalam mengidentifikasi kasus positif dan negatif, yang dibuktikan dengan nilai F1-score yang konsisten untuk kedua kelas (0.84 dan 0.88).Keberhasilan implementasi model ini memberikan potensi signifikan dalam mendukung proses screening awal penyakit jantung. Dengan kemampuan generalisasi yang baik dan tingkat error yang relatif rendah, model dapat menjadi alat bantu yang valuable bagi praktisi medis dalam melakukan assessment risiko penyakit jantung

## 👨‍💻 Kontribusi
Proyek ini merupakan tugas akademik individual.

## 📞 Kontak
- Email: miftakhulr@student.unuha.ac.id

---
*Dikembangkan sebagai proyek mata kuliah Big Data & Data Mining*
