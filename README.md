# Prediksi Harga Saham Tesla & BYD dengan Algoritma LSTM
Proses ini merupakan subbagian dari Supervised Learning pada Machine Learning karena dilakukan pada data yang telah berlabel. Proses penyusunan prediksi dilakukan dengan metode CRIPS-DM (Cross-Industry Standard Process for Data Mining) yang terdiri dari beberapa tahapan sebagai berikut:
1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Data Modelling
5. Evaluation
6. Predicting


## 1. BUSINESS UNDERSTANDING
Tesla dan BYD adalah dua perusahaan produsen mobil listrik. Meningkatnya minat terhadap penggunaan mobil listrik menjadi salah satu faktor yang mendorong peningkatan harga saham dari kedua perusahaan tersebut. Oleh karena itu, dengan melihat perusahaan Tesla dan BYD sebagai dua perusahaan dengan tingkat penjualan paling tinggi dan paling bersaing saat ini, maka prediksi harga saham menjadi hal yang dapat membantu investor maupun calon investor dalam membeli maupun menjual saham pada perusahaan tersebut.

## 2. DATA UNDERSTANDING
Tahap ini mencakup persiapan data, menilai kebutuhan data, dan mengumpulkan data. Data yang akan digunakan sebagai indikator prediksi adalah harga penutupan saham harian (Close Price) perusahaan Tesla dan BYD diambil dari situs Yahoo Finance. 

## 3. DATA PREPARATION
Persiapan data mencakup identifikasi, penyeleksian data, dan pembersihan data.

## 4. DATA MODELLING
Proses mempersiapkan model LSTM yang akan digunakan untuk memprediksi harga saham. Terdiri dari proses scaling dan normalisasi data, membagi dataset menjadi data latih dan data uji, dan pembuatan model LSTM. Dataset yang telah dipersiapkan kemudian diimplementasikan pada model yang telah dibangun. 

## 5. EVALUATION
Model yang telah diimplementasikan kemudian dievaluasi untuk menilai akurasi model sebelum digunakan untuk memprediksi.

## 6. PREDICTING
Setelah uji validitas model dilakukan, maka selanjutnya dilakukan prediksi harga saham masa depan dari Tesla dan BYD. Prediksi dilakukan untuk 1, 60, dan 100 hari ke depan.
