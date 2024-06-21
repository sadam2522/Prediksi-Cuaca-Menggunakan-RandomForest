# Prediksi-Cuaca-Menggunakan-RandomForest

Deskripsi
Proyek ini bertujuan untuk memprediksi kondisi cuaca menggunakan algoritma RandomForest. Dengan memanfaatkan data historis cuaca seperti suhu, kelembaban udara, kecepatan angin, dan kondisi langit, proyek ini mengimplementasikan machine learning untuk menghasilkan perkiraan cuaca di masa depan. Model yang dibangun akan belajar dari pola-pola dalam data historis untuk dapat melakukan prediksi cuaca dengan tingkat akurasi yang tinggi.

# Langkah-langkah Proyek
1. Pengumpulan Data

- Data cuaca historis diambil dari sumber yang terpercaya atau menggunakan dataset publik yang tersedia. <br>

2. Persiapan Data

- Data dimuat dan dipersiapkan untuk analisis dengan melakukan konversi suhu dari Celsius ke Fahrenheit, mengekstrak informasi bulan dan tahun dari tanggal, serta membersihkan data dari nilai NaN dan data sebelum tahun 1850. <br>

3. Visualisasi dan Eksplorasi Data 
- Dilakukan visualisasi untuk memahami hubungan antara variabel-variabel cuaca menggunakan heatmap korelasi. <br>

4. Pemisahan Data untuk Pelatihan dan Validasi
- Data dibagi menjadi data pelatihan dan data validasi dengan perbandingan 75:25 untuk menguji performa model. <br>

5. Pelatihan Model
- Model RandomForestRegressor dibuat dengan menggunakan pipeline yang mencakup pengisian nilai yang hilang, pemilihan fitur terbaik, standardisasi data, dan penerapan algoritma RandomForest untuk pelatihan. <br>

6. Evaluasi Model
- Performa model dievaluasi menggunakan Mean Absolute Percentage Error (MAPE) untuk mengukur tingkat akurasi prediksi terhadap data validasi.
