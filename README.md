# Capstone-Project
SiDeJan: Aplikasi Deteksi Dini Potensi Penyakit Jantung Berbasis Faktor Risiko Gaya Hidup dan Gejala Awal


Deskripsi Proyek

Proyek ini bertujuan untuk mengembangkan model machine learning berbasis Logistic Regression untuk mendeteksi potensi penyakit jantung pada masyarakat umum berdasarkan faktor risiko gaya hidup dan gejala awal yang sering diabaikan. Model ini diharapkan dapat membantu meningkatkan kesadaran dan memicu tindakan preventif pada masyarakat, terutama mereka yang sering menyalahartikan gejala awal penyakit jantung.

Fitur

- Model Logistic Regression untuk klasifikasi biner (berisiko sakit jantung atau tidak berisiko)
- Menggunakan data identitas dan gaya hidup, gejala yang dirasakan, dan hasil pemeriksaan kesehatan dasar
- Antarmuka pengguna yang mudah digunakan untuk memasukkan data dan mendapatkan hasil prediksi

Teknologi yang Digunakan

- Bahasa pemrograman: Python dan TypeScript
- Framework: Next.js dan Flask
- Library/Tools: scikit-learn, joblib, pandas, numpy, gunicorn
- Dataset: Dataset gejala penderita sakit jantung

Cara Menggunakan

1. Clone repository ini ke komputer lokal Anda
2. Instal dependensi yang diperlukan menggunakan pip dan npm
3. Jalankan aplikasi menggunakan perintah python app.py dan npm start
4. Buka antarmuka pengguna di browser Anda dan masukkan data yang diperlukan
5. Dapatkan hasil prediksi potensi penyakit jantung berdasarkan data yang Anda masukkan

Untuk mereplikasi langkah-langkah ini, Anda dapat mengikuti urutan sel dalam notebook ini. Kode tersebut mencakup langkah-langkah untuk:

1. Menginstal dependensi yang diperlukan (diasumsikan sudah diinstal atau dapat ditambahkan).
2. Mengunduh data dari Kaggle atau memuatnya dari Google Drive.
3. Melakukan langkah-langkah pra-pemrosesan data (penanganan duplikat, penghapusan fitur, pemetaan nilai kategorikal, pembuatan target, konversi huruf kecil).
4. Mendefinisikan dan melatih model Logistic Regression menggunakan pipeline scikit-learn.
5. Mendefinisikan, mengkompilasi, dan melatih model Keras untuk klasifikasi biner, termasuk adaptasi langkah-langkah preprocessing ke lapisan Keras dan penanganan ketidakseimbangan kelas.
6. Mengevaluasi kedua model menggunakan metrik klasifikasi standar.
7. Mengekspor model Keras dalam format SavedModel.
8. Mengkonversi SavedModel ke format TensorFlow.js menggunakan tensorflowjs_converter.
9. Struktur notebook mengikuti alur kerja umum proyek machine learning, mulai dari pengunduhan data hingga pelatihan dan evaluasi model. Fungsi yang dapat digunakan kembali (seperti summarize_dataframe dan show_unique_values) disediakan untuk analisis data. Jalur file untuk menyimpan dataset dan model perantara juga ditentukan untuk pengelolaan proyek yang lebih baik.

Untuk penggunaan di lingkungan lain atau untuk kolaborasi, disarankan untuk:

1. Menyertakan requirements.txt atau daftar pustaka Python yang digunakan.
2. Menyediakan detail cara mengakses dataset jika tidak diunduh langsung dari Kaggle (misalnya, instruksi untuk menyiapkan Google Drive atau sumber data alternatif).
3. Menambahkan penjelasan lebih lanjut tentang arsitektur model Keras dan parameter pelatihan jika diperlukan.
4. Mengoptimalkan pipeline preprocessing TensorFlow/Keras dan proses pelatihan untuk meningkatkan performa model Keras.


Kontribusi

Kami sangat terbuka untuk kontribusi dari komunitas. Jika Anda ingin berkontribusi pada proyek ini, silakan fork repository ini dan kirimkan pull request.
