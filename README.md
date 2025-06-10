# 📊 Analisis Data QS World University Rankings 2025

## 👥 Kelompok 11
1. Dafanov Dixie Einkinderen  23031554201
2. Nafila Hanum Al Hasaniy    23031554109
3. Berlianti Debby Maharani   23031554006
4. Nisrina Afaf               23031554165

---

## 📁 Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis dan mengeksplorasi data **QS World University Rankings 2025**. Kami melakukan proses _Exploratory Data Analysis (EDA)_, _data preprocessing_, visualisasi, dan transformasi data untuk memahami faktor-faktor yang memengaruhi peringkat universitas secara global.

---

## 🧰 Tools & Library yang Digunakan
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-Learn
- XGBoost
- Plotly

---

## 🔍 Tahapan Analisis

### 1. Exploratory Data Analysis (EDA)
- Menampilkan informasi umum dan missing value
- Bar chart distribusi fokus riset per region
- Heatmap fokus universitas riset berdasarkan region
- Barplot Top 20 universitas berdasarkan Overall Score
- Bar chart negara dengan jumlah universitas terbanyak
- Peta sebaran skor universitas berdasarkan negara (Plotly)
- Korelasi antar skor dengan heatmap
- Scatterplot dan KDE antar berbagai skor

### 2. Data Preprocessing
- Menghapus dan mengisi missing value
- Konversi tipe data `RANK_2024` dan `RANK_2025` ke numerik
- Menambahkan kolom `Rank_Change`
- Perbaikan data region yang tidak diklasifikasikan
- Menghapus karakter tidak relevan dari kolom rank
- Normalisasi skor dan rank agar arah metrik seragam
- One-Hot Encoding kolom kategorik

---
## 3 Modeling

Kami menggunakan tiga algoritma regresi:

1. **Linear Regression**
   - Model baseline yang sederhana.
   - Mengasumsikan hubungan linier antara fitur dan target.

2. **Random Forest Regressor**
   - Model ensambel berbasis decision tree.
   - Cocok untuk hubungan non-linear dan menangani overfitting dengan baik.

3. **XGBoost Regressor**
   - Gradient boosting framework yang sangat powerful.
   - Menyediakan kontrol regularisasi dan kecepatan pelatihan tinggi.

---

## 4 Evaluasi

Metrik evaluasi yang digunakan:

- **R² Score**: Seberapa baik model menjelaskan variasi data.
- **Mean Squared Error (MSE)**: Rata-rata kuadrat selisih antara prediksi dan nilai asli.

## 📌 Insight Menarik
- Banyak universitas riset berada di region Eropa dan Asia.
- `Academic_Reputation_Score` dan `Employer_Reputation_Score` sangat berkorelasi.
- Skor keberlanjutan (`Sustainability_Score`) menunjukkan kontribusi yang cukup terhadap overall score universitas.
- Universitas dengan skor reputasi tinggi cenderung memiliki outcome kerja yang baik.

---

## 📎 Sumber Data
Dataset: [QS World University Rankings 2025](https://www.kaggle.com/datasets/melissamonfared/qs-world-university-rankings-2025)

---

## ✍️ Referensi Khusus
Untuk penyesuaian region Eastern Mediterranean University:
- Gűrsoy & Kunt (2019). _Culture and Psychology_
- Nourafkan et al. (2020). _SJOM_
- [EMU Official Site](https://www.emu.edu.tr/en/about-emu/accreditations-recognitions-rankings-memberships/597)

---

## 📈 Output Visualisasi
Terdapat lebih dari 10 visualisasi dalam proyek ini, mencakup:
- Scatterplot, Heatmap, Barplot, KDE, dan Choropleth Map.

---

## ✅ Status
Selesai ✔️  
Tahapan selanjutnya : Pembuatan Poster

---

## 🏁 Lisensi
Proyek ini dibuat untuk keperluan edukasi dalam mata penambangan data.

