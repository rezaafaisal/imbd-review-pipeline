# Submission 1: Troll Binary Classification
Nama: Reza Faisal

Username dicoding: rezaafaisal

| | Deskripsi |
| ----------- | ----------- |
| Dataset | [IMDB Movie Reviews (Binary Sentiment)](https://www.kaggle.com/datasets/thedevastator/imdb-large-movie-review-dataset-binary-sentiment) |
| Masalah | Dalam dunia hiburan khususnya film terkadang kita melihat cuplikan yang membuat kita menjadi sentimen dalam menilai film tersebut meski belum menonton film itu secara full, projek ini memudahkan orang dalam menilai apakah film tersebut baik atau tidak berdasarkan sentimen komentar orang-orang yang telah menontonnya |
| Solusi machine learning | Maka dari itu dibutuhkan sebuah sistem machine learning yang dapat mendeteksi kalimat memiliki makna negatif ataupun positif |
| Metode pengolahan | Metode pengolahan data yang digunakan pada proyek ini berupa tokenisasi fitur input (text dari sebuah kalimat) yang awalnya berupa text diubah menjadi susunan angka yang merepresentasikan text tersebut agar dapat dengan mudah dimengerti oleh model |
| Arsitektur model | Model yang dibangun menggunakan layer TextVectorization sebagai layer yang akan memproses input string kedalam bentuk susunan angka, kemudian layer Embedding yang bertugas untuk mempelajari kedekatan atau kemiripan dari sebuah kata yang berguna untuk mengetahui apakah kata tersebut merupakan kata negatif atau kata positif. Lalu terdapat 2 hidden layer dan 1 output layer. |
| Metrik evaluasi | Metric yang digunakan pada model yaitu BinaryAccuracy, TruePositive, FalsePositive, TrueNegative, FalseNegative untuk mengevaluasi performa model dalam menentukan klasifikasi|
| Performa model | Model yang dibuat menghasilkan performa yang cukup baik dalam memberikan prediksi untuk text berita yang diinputkan, dan dari pelatihan yang dilakukan model menghasilkan binary_accuracy dan val_binary_accuracy di sekitar 86.76% |