# Pemodelan Prediksi Curah Hujan sebagai Strategi Penanggulangan Banjir Provinsi Kalimantan Selatan 🔎⛈

## Deskripsi Singkat
Proyek ini bertujuan untuk mengidentifikasi dan memahami karakteristik banjir serta curah hujan di Provinsi Kalimantan Selatan. Selain itu, proyek ini mengembangkan dan membandingkan berbagai model prediksi untuk menentukan model terbaik dalam memprediksi curah hujan sebagai strategi mitigasi banjir.

## Tujuan Proyek
- Mengidentifikasi dan memahami karakteristik banjir serta curah hujan di Provinsi Kalimantan Selatan.
- Mengembangkan dan membandingkan berbagai model prediksi curah hujan.
- Memberikan rekomendasi untuk mendukung pengambilan keputusan dalam mitigasi banjir.

## Latar Belakang
Banjir merupakan salah satu bencana alam yang sering terjadi di Provinsi Kalimantan Selatan. Untuk mengurangi dampak banjir, diperlukan strategi mitigasi yang efektif, salah satunya dengan memprediksi curah hujan.

## Dataset yang Digunakan
- Penelitian ini menggunakan data curah hujan dalam satuan milimeter (mm) untuk Provinsi Kalimantan Selatan, yang tersedia dari tahun 2003 hingga 2017. Data ini diperoleh dari Badan Pusat Statistik (BPS) Kalimantan Selatan dan dapat diakses melalui tautan berikut: [BPS Kalimantan Selatan - Iklim](https://kalsel.bps.go.id/subject/151/iklim.html#subjekViewTab3).

## Tantangan
Pemodelan hanya menggunakan 4 library yaitu ***numpy, pandas, matplotlib***, dan ***seaborn***.

## Metodologi atau Pendekatan
- Menggunakan metode statistik yaitu ***Pegels Classification*** dan ***Holt Winter***. Sedangkan machine learning menggunakan *Decision Tree Regression* untuk memodelkan dan memprediksi curah hujan.
- Beberapa model prediksi dibandingkan untuk menentukan model terbaik dalam memprediksi curah hujan. Menggunakan teknik ***Expanding Window Cross Validation*** untuk mendapatkan gambaran penuh kemampuan peramalan metode
- Visualisasi data digunakan untuk memahami distribusi kejadian banjir berdasarkan jenis bencana dan wilayah administratif.

## Hasil dan Temuan
Hasil penelitian menunjukkan bahwa metode machine learning ***Decision Tree Regression*** dengan parameter terbaik memiliki rata-rata RMSE terendah dibandingkan dua model lainnya. Pada data uji, ***RMSE sebesar 57,97*** diperoleh, menunjukkan kemampuan eksploratif model dalam menggambarkan pola pada data latih dan uji dengan baik. Model ini dinilai layak sebagai acuan untuk prediksi curah hujan di Kalimantan Selatan. \
Selanjutnya, model Decision Tree Regression digunakan untuk memprediksi curah hujan pada tahun 2018, dengan hasil prediksi rata-rata sebesar 221,19 mm, curah hujan tertinggi pada bulan Januari sebesar 447,33 mm, dan terendah pada bulan Agustus dan September sebesar 49,42 mm.

## 📝 Lainnya
Saya juga membuat artikel yang komperhensif membahas analisis ini. Dapat diakses pada [medium saya](https://medium.com/@mahardinalendra)

atau langsung pada [link artikel berikut](https://medium.com/@mahardinalendra/analisis-data-time-series-dengan-metode-holt-winters-klasifikasi-pegels-dan-decision-tree-88b48010b0fc)

## 🥇 Penghargaan 
Analisis ini berhasil mendapatkan Juara 1 dan mendapatkan kategori Best Code Quality pada perlombaan Python Based Data Analysis Universitas Lambung Mangkurat 2024/

*Mahasiswa Departemen Matematika UGM Raih Prestasi di Kompetisi Python-Based Data Analysis 2024* - [Pemberitaan Departemen Matematika UGM](https://math.fmipa.ugm.ac.id/id/mahasiswa-departemen-matematika-ugm-raih-prestasi-di-kompetisi-python-based-data-analysis-2024/)
