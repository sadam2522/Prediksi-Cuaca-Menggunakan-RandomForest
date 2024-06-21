# Prediksi-Cuaca-Menggunakan-RandomForest

## Deskripsi <br>
Proyek ini bertujuan untuk memprediksi kondisi cuaca menggunakan algoritma RandomForest. Dengan memanfaatkan data historis cuaca seperti suhu, kelembaban udara, kecepatan angin, dan kondisi langit, proyek ini mengimplementasikan machine learning untuk menghasilkan perkiraan cuaca di masa depan. Model yang dibangun akan belajar dari pola-pola dalam data historis untuk dapat melakukan prediksi cuaca dengan tingkat akurasi yang tinggi.

# Langkah-langkah Proyek
### 1. Pengumpulan Data

- Data cuaca historis diambil dari sumber yang terpercaya atau menggunakan dataset publik yang tersedia. <br>

### 2. Persiapan Data

- Data dimuat dan dipersiapkan untuk analisis dengan melakukan konversi suhu dari Celsius ke Fahrenheit, mengekstrak informasi bulan dan tahun dari tanggal, serta membersihkan data dari nilai NaN dan data sebelum tahun 1850. <br>

### 3. Visualisasi dan Eksplorasi Data 
- Dilakukan visualisasi untuk memahami hubungan antara variabel-variabel cuaca menggunakan heatmap korelasi. <br>

### 4. Pemisahan Data untuk Pelatihan dan Validasi
- Data dibagi menjadi data pelatihan dan data validasi dengan perbandingan 75:25 untuk menguji performa model. <br>

### 5. Pelatihan Model
- Model RandomForestRegressor dibuat dengan menggunakan pipeline yang mencakup pengisian nilai yang hilang, pemilihan fitur terbaik, standardisasi data, dan penerapan algoritma RandomForest untuk pelatihan. <br>

### 6. Evaluasi Model
- Performa model dievaluasi menggunakan Mean Absolute Percentage Error (MAPE) untuk mengukur tingkat akurasi prediksi terhadap data validasi.

# Penggunaan
Untuk menggunakan proyek ini, pastikan Anda memiliki Python yang terpasang bersama dengan pustaka-pustaka seperti scikit-learn, pandas, dan numpy. Berikut adalah langkah-langkah umum untuk menjalankan proyek:

1. Clone repositori ini ke dalam komputer lokal Anda.
2. Instal semua dependensi yang diperlukan dengan menjalankan perintah pip install -r requirements.txt.
3. Persiapkan data cuaca historis atau gunakan dataset yang sudah ada.
4. Jalankan notebook atau script untuk memproses data, melatih model, dan mengevaluasi hasil prediksi.
5. Analisis hasil prediksi dan modifikasi model jika diperlukan untuk meningkatkan akurasi.
