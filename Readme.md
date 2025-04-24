# 📊 UTS Praktikum Machine Learning: Klasifikasi Kelayakan Kredit Komputer dengan Decision Tree

## 📌 Identitas
- **Nama:** Ade Ripaldi Nuralim  
- **NIM:** 1227050003  
- **Mata Kuliah:** Praktikum D#  

## 🎯 Deskripsi Proyek
Proyek ini membangun model klasifikasi menggunakan algoritma **Decision Tree** untuk memprediksi kelayakan kredit komputer berdasarkan fitur:
- Usia
- Penghasilan
- Status Mahasiswa
- Rating Kredit  

Model dievaluasi dengan metrik akurasi, precision, recall, dan confusion matrix.

## 📁 Dataset
Dataset tersedia di: [Klik untuk mengunduh dataset](https://drive.google.com/file/d/1krLRWedghy_ysJ2N6i-1GJ-ZQUmnu6eu/view) *(pastikan tautan valid)*    

## ⚙️ Teknik dan Tools
- **Algoritma:** Decision Tree Classifier  
- **Kriteria Split:** Entropy (Information Gain)  
- **Bahasa Pemrograman:** Python  
- **Library:** scikit-learn, pandas, numpy, matplotlib  

## 📊 Hasil Evaluasi Model
### 🔢 Performa Model
- **Akurasi:** 80.5% (data uji)  
- **Classification Report:**  

| Kelas       | Precision | Recall |
|-------------|-----------|--------|
| Tidak Layak (0) | 0.70      | 0.80   |
| Layak (1)       | 0.88      | 0.81   |

### 📉 Confusion Matrix
|                  | Prediksi 0 | Prediksi 1 |
|------------------|------------|------------|
| **Aktual 0**     | 57         | 14         |
| **Aktual 1**     | 25         | 104        |

## 🔍 Analisis dan Kesimpulan
### 💡 Temuan Utama
1. Model menunjukkan performa seimbang dengan akurasi **81%**.  
2. Prediksi "Layak" lebih presisi (**precision 88%**) dibanding "Tidak Layak".  
3. Terdapat **25 false negatives** (prediksi "Tidak Layak" padahal seharusnya "Layak").  

### ⚠️ Potensi Masalah
- **Overfitting:** Probabilitas 1.00 pada data baru mengindikasikan model mungkin terlalu spesifik.  
- **Ketidakseimbangan Data:** Perlu dicek distribusi kelas dalam dataset.  

### 🚀 Rekomendasi Pengembangan
1. **Optimasi Model:**  
   - Pruning untuk mengurangi overfitting.  
   - Eksperimen dengan algoritma lain (Random Forest, SVM).  
2. **Peningkatan Data:**  
   - Penambahan sampel atau fitur relevan.  
   - Handling imbalance class (jika ada).  

---

© 2024 Ade Ripaldi Nuralim | Proyek UTS Machine Learning  