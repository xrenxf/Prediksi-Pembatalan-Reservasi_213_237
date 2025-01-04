# Prediksi Pembatalan Reservasi Hotel

## Pendahuluan
Hotel menghadapi tantangan dalam mempertahankan tingkat reservasi akibat kesulitan memprediksi pembatalan yang dilakukan pelanggan. Masalah ini penting karena tingkat pembatalan yang tinggi dapat mengganggu perencanaan operasional, memengaruhi pendapatan, dan merusak pengalaman pelanggan secara keseluruhan. Penelitian ini bertujuan untuk memberikan wawasan mendalam terkait faktor-faktor yang memengaruhi pembatalan reservasi dan membangun model prediktif yang dapat membantu hotel mengelola tingkat pembatalan secara lebih efektif.

## Rencana & Pendekatan
Penelitian ini menggunakan pendekatan berbasis data dengan langkah-langkah berikut:
- Mengidentifikasi fitur-fitur utama yang memengaruhi pembatalan reservasi.	
- Membersihkan dan mempersiapkan data untuk analisis lebih lanjut.
- Membangun model prediktif menggunakan algoritma pembelajaran mesin.
- Mengevaluasi kinerja model dengan berbagai metrik untuk menentukan model terbaik.

## Metodologi
Metodologi penelitian ini terdiri dari beberapa tahap:
- Pengumpulan Data: Menggunakan dataset yang tersedia dengan fitur-fitur relevan seperti lead_time, deposit_type, market_segment, dan customer_type.	
- Preprocessing: Normalisasi data, penanganan nilai hilang, dan pembagian data.
- Pemodelan: Membangun model menggunakan algoritma seperti Random Forest, FFNN, dan DNN.
- Evaluasi Model: Menggunakan metrik seperti akurasi, MSE, dan R-squared.

## Teknik Analisis yang Digunakan
- Analisis Deskriptif: Memahami distribusi data dan pola-pola utama.
- Analisis Korelasi: Mengidentifikasi hubungan antar fitur.
- Analisis Prediktif: Menggunakan algoritma pembelajaran mesin untuk prediksi pembatalan.

## Manfaat Analisis
- Operasional: Membantu hotel memprediksi tingkat pembatalan dan mengoptimalkan alokasi sumber daya.
- Keuangan: Meningkatkan pendapatan dengan mengurangi dampak pembatalan.
- Strategi: Memberikan wawasan untuk pengambilan keputusan berbasis data.

## Struktur Proyek
1. Install dan Import Library
2. Load Data
3. EDA (Exploratory Data Analysis)
4. Preprocessing
5. Model:
- FFNN (Feedforward Neural Network)
- DNN (Deep Neural Network)
- Random Forest
6. Perbandingan Prediksi Model
7. Test Prediksi dengan Model

## Analisa Prediksi Pembatalan Reservasi Hotel
### Instalasi dan Persiapan
### Data Preparation
- Dataset mencakup fitur berikut:
- lead_time: Waktu antara pemesanan dan tanggal check-in.
- deposit_type: Jenis deposit yang digunakan pelanggan.
- market_segment: Segmen pasar tempat pelanggan berasal.
- customer_type: Jenis pelanggan (misalnya, pelanggan baru atau loyal).

### Proses Cleaning Data
1. Menghapus data duplikat.
2. Menangani nilai yang hilang dengan imputasi.
3. Menormalisasi data untuk skala fitur yang konsisten.

### Exploratory Data Analysis (EDA)
1. Distribusi Variabel: Memvisualisasikan distribusi fitur utama.
2. Korelasi: Menganalisis hubungan antar fitur menggunakan matriks korelasi.
3. Outlier: Mengidentifikasi outlier yang berpotensi memengaruhi hasil analisis.

### Pemodelan
- Feedforward Neural Network (FFNN) : Model FFNN digunakan sebagai baseline dengan arsitektur sederhana.
- Deep Neural Network (DNN) : Model DNN digunakan untuk menangkap hubungan non-linear antar variabel dengan lebih baik.
- Random Forest : Model Random Forest digunakan karena kemampuannya menangani variabel kategori dan kontinu dengan baik.

### Evaluasi Model
Model dievaluasi berdasarkan metrik berikut:
- Akurasi: Proporsi prediksi yang benar.
- Mean Squared Error (MSE): Rata-rata kesalahan kuadrat.
- R-squared: Proporsi variabilitas data yang dijelaskan oleh model.

### Kesimpulan
Penelitian ini memberikan solusi berbasis data untuk memprediksi pembatalan reservasi. Dengan memahami faktor-faktor utama, model prediktif yang dibangun dapat membantu hotel meningkatkan efisiensi operasional dan strategi bisnis mereka. Hasil menunjukkan bahwa model FFNN memiliki performa terbaik dalam skenario ini.
