# analisis-regresi-logistik-
Proyek ini menerapkan regresi logistik untuk memprediksi kemungkinan gangguan mental berdasarkan skor peristiwa hidup. Analisis mencakup pembuatan model, perhitungan manual fungsi sigmoid, log-likelihood, turunan parsial, serta estimasi parameter menggunakan metode Newton-Raphson, dan visualisasi kurva.

## 📊 Dataset
Dataset kecil yang digunakan terdiri dari:
- `Life Event (X1)`: Skor peristiwa hidup yang dialami seseorang
- `Mental Impair (Y)`: Label biner (0 atau 1) yang menunjukkan apakah seseorang mengalami gangguan mental

## 🧪 Langkah-Langkah Analisis

1. **Menampilkan Data dan Informasi Tipe Kolom**
2. **Pemisahan Data ke X_train dan y_train**
3. **Pembangunan Model Logistik dengan statsmodels**
4. **Identifikasi Variabel Numerik dan Kategorik**
5. **Perhitungan Fungsi Kepadatan Probabilitas (Logistic Function)**
6. **Perhitungan Log-Likelihood**
7. **Eksponensial Komponen Log-Likelihood**
8. **Perhitungan Log-Likelihood Simbolik dan Estimasi Maksimum**
9. **Turunan Parsial Log-Likelihood**
10. **Estimasi Parameter dengan Newton-Raphson (regulerisasi ditambahkan)**
11. **Visualisasi Kurva Regresi Logistik**

## 🛠️ Library yang Digunakan

- `pandas`
- `numpy`
- `statsmodels`
- `matplotlib`
- `sklearn.model_selection`
- `sympy`

## 📈 Output Utama

- Model regresi logistik yang menjelaskan probabilitas `Y=1` terhadap nilai `X1`
- Nilai parameter β₀ dan β₁ hasil estimasi
- Nilai log-likelihood
- Visualisasi kurva sigmoid/logistik
