📌 Title Project

"Sentiment Classification Analysis on Customer Reviews Using SVM and Logistic Regression for Strategic Decision Making"

🧭 Project Overview

Dalam era digital saat ini, review pelanggan menjadi sumber informasi yang sangat berharga bagi perusahaan. Proyek ini bertujuan untuk mengklasifikasikan sentimen dari ulasan pelanggan menjadi **positif** atau **negatif** menggunakan dua algoritma machine learning: **Support Vector Machine (SVM)** dan **Logistic Regression (LR)**.

Tujuan utama dari proyek ini adalah untuk:
- Mengidentifikasi pola sentimen pelanggan terhadap produk atau layanan
- Membantu perusahaan dalam mendeteksi lebih awal permasalahan yang sering dikeluhkan konsumen
- Mendukung pengambilan keputusan strategis berbasis data pelanggan

🔗 Raw Dataset Link

Dataset yang digunakan tersedia di dalam repositori ini dengan nama file:
[`reviews.csv`](./reviews.csv) dan [`reviews_clean.csv`](./reviews_clean.csv)
File ini telah melalui proses pembersihan (cleaning) secara lokal dan siap digunakan untuk pelatihan model.

🔍 Insight & Findings
- Sebagian besar ulasan bersentimen positif, berdasarkan distribusi data dan nilai recall yang tinggi untuk label positif.
- Model SVM menunjukkan performa terbaik dengan akurasi mencapai 94% dan f1-score tinggi untuk kedua label.
- Ulasan negatif cenderung menggunakan kata-kata seperti: "buruk", "gagal", "tidak berfungsi", yang membantu model mengenali sentimen negatif.
- Ulasan positif sering mengandung kata-kata seperti: "mantap", "puas", "berfungsi baik", yang diklasifikasikan dengan sangat baik oleh model.

🤖 AI Support Explanation

Proyek ini memanfaatkan pendekatan Artificial Intelligence berbasis *Natural Language Processing (NLP)* dan *Machine Learning*. Dengan memanfaatkan teknik seperti:
- *TF-IDF Vectorization* untuk representasi numerik dari teks
- Model klasifikasi SVM dan Logistic Regression untuk membedakan sentimen positif dan negatif

Teknologi AI ini memungkinkan analisis ribuan review dalam waktu singkat dan akurat, sehingga perusahaan bisa:
- Menghemat waktu analisis manual
- Mendeteksi tren dan isu produk secara otomatis
- Mengoptimalkan layanan berdasarkan umpan balik pelanggan secara real-time
