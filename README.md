Ujian Akhir Semester (UAS) Machine Learning
Nama: Annisa Fitriana

NIM: 227006516064

Kelas: Machine Learning

Dataset: Dataset 4 - Intel Berkeley Lab Sensor Data

1. Tujuan Proyek
Tujuan dari proyek ini adalah untuk melakukan analisis mendalam pada dataset sensor dari Intel Berkeley Lab. Fokus utama adalah membangun sebuah model machine learning yang mampu meramalkan (forecasting) suhu di masa depan berdasarkan data historis dari sensor itu sendiri dan variabel lingkungan lainnya seperti kelembapan dan cahaya.

2. Algoritma yang Digunakan dan Alasan Pemilihan
Algoritma: LightGBM (Light Gradient Boosting Machine)

Alasan:
LightGBM dipilih karena beberapa keunggulan utamanya yang sangat relevan untuk dataset ini:

Performa Tinggi: LightGBM dikenal sangat cepat dan efisien dalam penggunaan memori, yang cocok untuk dataset berukuran besar seperti ini (lebih dari 2 juta baris data).

Akurasi Tinggi: Sebagai algoritma gradient boosting, ia mampu menangkap hubungan yang kompleks dan non-linear antara fitur-fitur (suhu, waktu, cahaya, dll.) untuk menghasilkan prediksi yang sangat akurat.

Penanganan Fitur: Mampu menangani berbagai jenis fitur (numerik dan kategorikal) secara efektif tanpa memerlukan pra-pemrosesan yang rumit.

3. Hasil Analisis
Analisis data eksplorasi menunjukkan adanya pola harian (musiman) yang kuat pada data suhu dan cahaya, yang berkorelasi dengan siklus siang-malam dan aktivitas di dalam lab. Model yang telah dilatih berhasil menangkap pola ini dengan sangat baik, dibuktikan dengan nilai Mean Absolute Error (MAE) yang rendah, yang berarti rata-rata kesalahan prediksi model hanya sepersekian derajat Celsius.
