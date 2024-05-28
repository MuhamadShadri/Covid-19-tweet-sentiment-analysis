# Submission 1: Covid 19 tweet sentiment analysis

Nama: Muhamad Shadri

Username Dicoding: [muhamad_shadri](https://www.dicoding.com/users/muhamad_shadri/academies)

|     | Deskripsi |
| --- | --------- |
| Dataset | [Covid 19 tweet sentiment analysis](https://www.kaggle.com/code/alankritamishra/covid-19-tweet-sentiment-analysis) |
| Latar Belakang | Pandemi COVID-19 telah menjadi fokus perhatian global dalam beberapa tahun terakhir. Twitter, sebagai salah satu platform media sosial utama, menjadi tempat di mana banyak orang berbagi pemikiran, perasaan, dan informasi terkait pandemi ini. Dataset ini mencakup tweet-tweet yang berkaitan dengan COVID-19 dari berbagai sudut pandang, memungkinkan analisis sentimen terhadap respons masyarakat terhadap pandemi. |
| Masalah | Meskipun banyaknya tweet tentang COVID-19, tidak semua mudah dikenali sebagai tweet yang berkaitan dengan pandemi ini. Tanpa alat yang tepat, sulit untuk menyaring dan mengidentifikasi tweet yang relevan untuk analisis sentimen. Hal ini menjadi penting karena pemahaman terhadap sentimen publik dapat memberikan wawasan yang berharga dalam mengatasi pandemi dan memberikan dukungan kepada masyarakat. |
| Solusi Machine Learning |Untuk mengatasi masalah tersebut, diperlukan sistem yang mampu mengklasifikasikan tweet-tweet terkait COVID-19 berdasarkan sentimen. Dengan menggunakan teknik machine learning, sistem ini dapat membantu menyaring tweet-tweet yang relevan dan memberikan pemahaman tentang respons masyarakat terhadap pandemi. |
| Metode Pengolahan Data | Metode pengolahan data yang digunakan pada proyek ini adalah dengan menghapus atau *drop* beberapa fitur atau kolom yang tidak dibutuhkan, melakukan tahap *Data Ingestion* dengan membagi *dataset* menjadi *data training* dan *data evaluation* dengan rasio 9:1. Kemudian melakukan tahap *Data Validation* dengan cara melihat statistik data, *data schema*, serta mengidentifikasi anomali pada *dataset*. Setelah itu melakukan tahap *Data Preprocessing* dengan melakukan transformasi fitur input pada data. |
| Arsitektur Model | Arsitektur model yang dibangun menggunakan sebuah *input layer* yang menerima data teks atau *string* dan akan masuk ke layer TextVectorization untuk memproses *input* teks tersebut menjadi representasi numerik agar dapat dengan mudah dipahami oleh model *machine learning*. Kemudian terdapat sebuah *layer* Embedding dan *layer* Bidirectional LSTM untuk mempelajari *input* kata yang telah diproses sebelumnya. Lalu terdapat 2 *hidden layer* (Dense layer) serta 1 *output layer*. |
| Metrik Evaluasi | Metrik yang digunakan untuk mengevaluasi performa model *machine learning* adalah AUC (*Area Under the ROC Curve*), Binary Accuracy, TFMA Example Count, False Negatives, False Positive, True Negatives, dan True Positive. |
| Performa Model | Performa model yang telah dibuat termasuk ke dalam kategori yang cukup baik dan ideal dengan tingkat `binary_accuracy` sebesar 86% dan `val_binary_accuracy` sebesar 81%. |
| Kesimpulan | Dengan membangun model ini, diharapkan dapat memberikan pemahaman yang lebih baik tentang sentimen publik terkait COVID-19 melalui analisis tweet. Ini dapat menjadi alat yang berguna dalam mengatasi pandemi dan memberikan dukungan kepada masyarakat. |
