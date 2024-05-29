# Submission 1: Real / Fake Job Posting Prediction

Nama: Muhamad Shadri

Username Dicoding: [muhamad_shadri](https://www.dicoding.com/users/muhamad_shadri/academies)

|     | Deskripsi |
| --- | --------- |
| Dataset | [Real / Fake Job Posting Prediction](https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction) |
| Latar Belakang | Pencarian kerja melalui platform online telah menjadi salah satu metode utama bagi banyak orang untuk mencari pekerjaan. Namun, seiring dengan meningkatnya jumlah lowongan pekerjaan yang diposting secara daring, jumlah iklan pekerjaan palsu juga meningkat. Iklan pekerjaan palsu ini dapat menipu pencari kerja, menyebabkan kerugian finansial, dan membuang-buang waktu yang berharga. Oleh karena itu, sangat penting untuk memiliki kemampuan untuk mengidentifikasi apakah suatu iklan pekerjaan itu asli atau palsu. |
| Masalah | Berdasarkan latar belakang di atas, ditemukan masalah yang signifikan terkait meningkatnya jumlah posting pekerjaan palsu. Hal ini menimbulkan kesulitan bagi pencari kerja untuk membedakan antara posting pekerjaan yang asli dan yang palsu. Tanpa alat yang tepat, pencari kerja dapat dengan mudah tertipu oleh posting pekerjaan palsu, yang dapat mengakibatkan kerugian finansial dan waktu yang signifikan, serta dampak emosional yang merugikan. |
| Solusi Machine Learning | Untuk mengatasi masalah ini, diperlukan sistem yang dapat mengklasifikasikan posting pekerjaan apakah asli atau palsu. Dengan menggunakan teknik machine learning, sistem ini dapat membantu menyaring posting pekerjaan yang relevan dan mengidentifikasi posting pekerjaan yang mencurigakan. Ini akan membantu pencari kerja untuk fokus pada lowongan pekerjaan yang sah dan menghindari penipuan. |
| Metode Pengolahan Data | Proses pengolahan data dalam proyek ini dimulai dengan menghilangkan atau menghapus beberapa atribut yang tidak relevan, lalu dilanjutkan dengan langkah pengambilan data (Data Ingestion) yang membagi dataset menjadi data training dan evaluasi dengan perbandingan 9:1. Langkah berikutnya adalah validasi data (Data Validation) yang melibatkan pemeriksaan statistik, skema data, serta deteksi anomali dalam dataset. Selanjutnya, dilakukan tahapan pra-pemrosesan data (Data Preprocessing) dengan melakukan transformasi fitur pada input data. Dengan demikian, data siap untuk digunakan dalam proses analisis lebih lanjut. |
| Arsitektur Model | Struktur model yang dirancang terdiri dari serangkaian lapisan untuk mengolah data teks. Pertama, terdapat lapisan masukan (input layer) yang menerima teks atau string sebagai input, yang kemudian diproses oleh lapisan TextVectorization untuk mengonversi teks menjadi representasi numerik. Selanjutnya, terdapat lapisan Embedding dan Bidirectional LSTM untuk mempelajari pola dan hubungan antar kata dalam teks. Selain itu, model memiliki dua lapisan tersembunyi (hidden layer) yang terdiri dari Dense layer, diikuti oleh satu lapisan keluaran (output layer). Dengan struktur ini, model mampu memahami dan menginterpretasikan informasi dari teks dengan lebih baik untuk tujuan klasifikasi. |
| Metrik Evaluasi | Metrik yang digunakan untuk mengevaluasi performa model machine learning adalah AUC (Area Under the ROC Curve), Binary Accuracy, TFMA Example Count, False Negatives, False Positive, True Negatives, dan True Positive. |
| Performa Model | Performa model yang telah dibuat cukup baik dan optimal dengan tingkat `binary_accuracy` sebesar 97% dan `val_binary_accuracy` sebesar 98%. |
| Kesimpulan | Dengan membangun model ini, diharapkan dapat memberikan pemahaman yang lebih baik tentang apakah suatu postingan pekerjaan online asli atau palsu. Hal ini menjadi penting dalam melindungi pencari kerja dari penipuan dan kerugian finansial yang mungkin timbul akibat menerima tawaran pekerjaan palsu. Dengan menggunakan teknik machine learning untuk mengklasifikasikan postingan pekerjaan, model ini dapat menjadi alat yang berguna dalam memitigasi risiko penipuan dalam pasar kerja online dan memberikan perlindungan kepada masyarakat yang mencari pekerjaan secara daring. |
