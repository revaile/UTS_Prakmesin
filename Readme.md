📊 Proyek UTS Praktikum Machine Learning
Nama: Ade Ripaldi Nuralim
NIM: 1227050003
Mata Kuliah: Praktikum D#
Judul Proyek: Klasifikasi Kelayakan Kredit Komputer dengan Model Decision Tree

📌 Deskripsi Proyek
Proyek ini bertujuan untuk membangun model klasifikasi menggunakan algoritma Decision Tree guna memprediksi apakah seseorang layak atau tidak layak mendapatkan kredit komputer. Prediksi didasarkan pada sejumlah fitur seperti:

Usia

Penghasilan

Status Mahasiswa

Rating Kredit

Model ini dilatih dan diuji pada dataset yang disediakan, kemudian dievaluasi menggunakan metrik performa umum seperti akurasi, precision, recall, serta confusion matrix.

📁 Dataset
Dataset yang digunakan dapat diakses melalui tautan berikut:
Klik untuk mengunduh dataset

⚙️ Teknik dan Tools
Algoritma: Decision Tree Classifier

Criterion: Entropy (Information Gain)

Bahasa Pemrograman: Python

Library utama: scikit-learn, pandas, numpy, matplotlib

✅ Hasil Evaluasi Model
Model Decision Tree yang dibangun menunjukkan hasil evaluasi sebagai berikut:

Akurasi pada data uji: 80.5%

Classification Report:

Tidak Layak (0):

Precision: 0.70

Recall: 0.80

Layak (1):

Precision: 0.88

Recall: 0.81

Confusion Matrix:

57 benar klasifikasi "Tidak Layak"

104 benar klasifikasi "Layak"

14 salah klasifikasi "Tidak Layak" sebagai "Layak"

25 salah klasifikasi "Layak" sebagai "Tidak Layak"

🔍 Analisis dan Kesimpulan
Model mampu mengklasifikasikan data dengan cukup baik, terlihat dari akurasi yang mendekati 81%. Meskipun terdapat beberapa kesalahan klasifikasi, secara keseluruhan model memberikan hasil yang seimbang antara kedua kelas.

Selain itu, saat diuji dengan data baru, model memberikan prediksi “Tidak Layak” dengan probabilitas 1.00, yang menunjukkan tingkat kepercayaan sangat tinggi dari model. Hal ini bisa terjadi karena pola data serupa telah banyak muncul pada data pelatihan atau bisa jadi model terlalu spesifik karena overfitting.

💡 Kesimpulan Akhir
Decision Tree dengan kriteria entropy adalah metode yang cukup efektif untuk digunakan dalam kasus klasifikasi kelayakan kredit. Namun, untuk meningkatkan generalisasi model di masa depan, bisa dilakukan:

Pruning untuk menghindari overfitting

Eksperimen dengan algoritma lain seperti Random Forest atau SVM

Penambahan data dan fitur baru untuk memperkaya informasi

