# 🏦 Expert Scoring System using Matrix Multiplication
*Bridging Banking Risk Logic with Machine Learning Scalability*

## 📌 Project Overview
Proyek ini mentransformasikan pengalaman **Credit Analysis** selama 6 tahun ke dalam sistem penilaian otomatis. Fokus utama adalah pada **transparansi keputusan** dan mendefinisikan peran **"Strategic Operator"** di mana sistem tidak hanya memberikan skor, tapi juga mengidentifikasi ambigitas risiko.

## 🚀 Business Value & Strategic Insights
- **Predictable Outcomes**: Konsistensi bobot pakar diterapkan secara instan pada ribuan data.
- **Risk Quantification**: Menggunakan filter matematis untuk menghitung volume nasabah di zona risiko tertentu.
- **Strategic Decision Making**: Memisahkan nasabah menjadi tiga kategori: *Auto Approve*, *Auto Reject*, dan *Manual Review (Grey Area)*.

## 🛠 Tech Stack & Methodology
- **Linear Algebra (Diagonal Matrices)**: Optimasi pembobotan fitur (Expert Weights) secara paralel.
- **Normalization (Z-Score)**: Menyamakan skala fitur untuk menjaga integritas korelasi antar profil nasabah.
- **Visual Risk Mapping**:
    - **Threshold Line (`axvline(0)`)**: Batas jelas "Hidup dan Mati" aplikasi kredit dalam sistem otomatis.
    - **Grey Area Detection (`axvspan(-0.2, 0.2)`)**: Visualisasi "Zona Bahaya" di mana densitas nasabah memerlukan verifikasi manual karena skor yang terlalu marginal.

## 📊 Insight & Model Analysis
Sistem ini menjaga korelasi antara **Skor Mesin** dengan **Data Profil Asli** dalam satu tabel terpadu. Hal ini memungkinkan *Strategic Operator* untuk melakukan *deep dive* pada nasabah yang berada di rentang skor `-0.2` hingga `0.2` guna memitigasi *false decisions*.

## 📂 Project Structure
- `credit_final_cleaned.csv`: Dataset hasil data wrangling yang menjaga integritas profil asli.
- `Expert-Scoring-Model.ipynb`: Implementasi Python, kalkulasi skor, dan visualisasi distribusi risiko.

---
*Developed by Dean Andhika Ferrari | Product Manager | 5+ Yrs Experience | Data Driven Product Strategy, AI/ML & Python Automation*
