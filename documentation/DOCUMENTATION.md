# Dashboard Data Analysis Documentation

## 1. Project Overview

Project ini merupakan proses pengolahan dan analisis data transaksi yang divisualisasikan dalam bentuk dashboard interaktif menggunakan Google Looker Studio.

Tujuan utama project ini adalah mengolah data mentah menjadi informasi yang lebih terstruktur dan mudah dipahami, sehingga dapat digunakan untuk melihat performa penjualan berdasarkan berbagai kategori seperti lokasi, usia pelanggan, metode pembayaran, dan brand.

## 2. Objectives

Project ini bertujuan untuk:

* Membersihkan dan mempersiapkan dataset sebelum digunakan untuk analisis.
* Mengolah data agar dapat digunakan dalam proses visualisasi.
* Membuat dashboard interaktif untuk menyajikan informasi secara lebih mudah dipahami.
* Mengidentifikasi pola dan insight dari data transaksi.
* Menyajikan hasil analisis dalam bentuk visualisasi yang informatif.

## 3. Dataset

Dataset yang digunakan merupakan data transaksi yang memiliki beberapa atribut terkait transaksi, pelanggan, produk, lokasi, dan pembayaran.

Beberapa informasi yang digunakan dalam analisis meliputi:

* Transaction
* Customer
* Location
* Age
* Age Group
* Brand
* Revenue
* Discount
* Payment Method
* Cancellation
* Product/Transaction Category

Dataset terlebih dahulu diproses sebelum digunakan sebagai sumber data dashboard.

## 4. Data Cleaning

Tahap data cleaning dilakukan untuk memastikan data memiliki kualitas yang baik sebelum digunakan dalam proses analisis.

Tahapan yang dilakukan meliputi:

* Memeriksa data yang memiliki nilai kosong atau tidak sesuai.
* Memeriksa data duplikat.
* Memastikan format data sudah sesuai dengan jenis datanya.
* Menyesuaikan format kolom yang diperlukan untuk proses analisis.
* Memastikan nilai numerik dapat digunakan dalam perhitungan.
* Memeriksa konsistensi kategori pada data.

Setelah proses cleaning selesai, dataset yang telah dibersihkan digunakan sebagai sumber data untuk tahap berikutnya.

## 5. Data Transformation

Setelah proses cleaning, dilakukan transformasi data untuk menghasilkan beberapa atribut yang diperlukan dalam analisis dan visualisasi.

Transformasi yang dilakukan antara lain:

* Membuat kelompok usia (*age group*).
* Mengelompokkan lokasi berdasarkan kategori yang diperlukan.
* Menyiapkan atribut revenue untuk analisis penjualan.
* Menyiapkan atribut discount untuk analisis pemberian diskon.
* Menyiapkan atribut cancellation untuk menghitung cancellation rate.
* Menyesuaikan format beberapa atribut agar dapat digunakan dalam perhitungan dan visualisasi.

## 6. Dashboard Development

Dashboard dibuat menggunakan Google Looker Studio dengan dataset yang telah melalui proses cleaning dan transformation.

Dashboard digunakan untuk menampilkan informasi dalam bentuk:

* KPI
* Bar Chart
* Pie/Donut Chart
* Time Series
* Tabel
* Filter interaktif

Beberapa indikator yang ditampilkan dalam dashboard meliputi:

* Total Revenue
* Total Transaction
* Total Discount
* Cancellation Rate
* Revenue berdasarkan Age Group
* Revenue berdasarkan Payment Method
* Revenue berdasarkan Brand
* Cancellation Rate berdasarkan Location
* Informasi transaksi berdasarkan kategori lainnya

## 7. Analysis

Dashboard digunakan untuk menjawab beberapa pertanyaan analisis bisnis, seperti:

1. Berapa jumlah dan persentase cancellation rate berdasarkan nominal transaksi (*by amount*) berdasarkan kategori lokasi?

2. Pada kelompok usia (*age group*) manakah revenue tertinggi dihasilkan?

3. Berapa revenue yang dihasilkan melalui metode pembayaran Kartu Kredit?

4. Berapa total diskon yang diberikan untuk brand Riang Apparel?

Pertanyaan tersebut digunakan sebagai dasar dalam menentukan visualisasi dan calculated field yang diperlukan pada dashboard.

## 8. Key Insights

Berdasarkan hasil pengolahan dan visualisasi data, dashboard dapat digunakan untuk memperoleh beberapa insight terkait performa transaksi.

Insight yang diperoleh mencakup:

* Perbandingan performa revenue antar kelompok usia.
* Kontribusi masing-masing metode pembayaran terhadap revenue.
* Besarnya diskon yang diberikan pada setiap brand.
* Perbandingan cancellation rate berdasarkan lokasi.
* Identifikasi kategori yang memiliki kontribusi terbesar terhadap revenue.

Hasil analisis dapat digunakan untuk membantu memahami pola transaksi dan performa penjualan berdasarkan karakteristik yang tersedia dalam dataset.

## 9. Tools & Technologies

Tools yang digunakan dalam project ini:

* **Google Sheets** — Data cleaning dan preprocessing.
* **Google Looker Studio** — Data visualization dan dashboard development.
* **GitHub** — Dokumentasi dan penyimpanan file pendukung project.

## 10. Project Workflow

Alur pengerjaan project:

```text
Raw Dataset
     ↓
Data Cleaning
     ↓
Data Transformation
     ↓
Data Analysis
     ↓
Dashboard Development
     ↓
Visualization & Insights
```

## 11. Dashboard

Dashboard dibuat menggunakan Google Looker Studio dan dapat digunakan untuk melakukan eksplorasi data secara interaktif melalui berbagai filter dan visualisasi.

> Dashboard Link: [(https://datastudio.google.com/u/0/reporting/0bbb3e99-88c1-45ce-81e2-512939a58190/page/65x6F)]

## 12. Conclusion

Project ini menunjukkan proses pengolahan data mulai dari dataset mentah hingga menghasilkan dashboard interaktif.

Melalui proses cleaning, transformation, analysis, dan visualization, data transaksi dapat diubah menjadi informasi yang lebih mudah dipahami dan digunakan untuk memperoleh insight mengenai performa penjualan, pelanggan, metode pembayaran, diskon, dan cancellation rate.

Project ini juga menjadi implementasi dasar dari proses **data analytics workflow**, khususnya dalam tahap data preparation, exploratory analysis, dan data visualization.
