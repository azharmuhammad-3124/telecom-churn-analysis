# Telecom Customer Churn

## Repository Outline
Repositori ini terdiri dari dua file utama:

1. File Python Notebook (.ipynb)
File ini berisi keseluruhan proses analisis data, mulai dari eksplorasi data, pembersihan, hingga visualisasi dan interpretasi hasil. Semua langkah analisis dilakukan secara terstruktur dengan penjelasan naratif yang mendampingi setiap bagian kode.

2. File Data (.csv)
Merupakan file sumber data yang digunakan dalam analisis. Data ini berisi informasi pelanggan yang mencakup berbagai variabel seperti demografi, layanan yang digunakan, status churn, dan alasan di balik churn.

## Problem Background
Proyek ini berangkat dari kebutuhan untuk memahami tingkat churn pelanggan dalam suatu perusahaan layanan. Churn adalah kondisi ketika pelanggan berhenti menggunakan layanan suatu perusahaan. Tingginya angka churn dapat menjadi indikator masalah dalam layanan, pengalaman pelanggan, atau keunggulan kompetitor. Oleh karena itu, proyek ini bertujuan untuk:

-   Mengukur seberapa besar persentase pelanggan yang churn.

-   Mengidentifikasi faktor-faktor yang paling memengaruhi keputusan pelanggan untuk berhenti berlangganan.

## Project Output
1. Dashboard Interaktif di Tableau Public
Dashboard ini menyajikan hasil visualisasi dari analisis data secara interaktif, memudahkan pengguna dalam mengeksplorasi insight berdasarkan demografi, wilayah, alasan churn, dan lainnya.

2. Notebook Analisis (.ipynb)
Notebook ini berisi penjabaran teknis dari seluruh proses analisis, termasuk pembersihan data, perhitungan statistik deskriptif, analisis inferensial (seperti uji Chi-Square), serta insight berbasis data yang ditemukan.

## Data
Dataset yang digunakan sudah dalam kondisi sangat baik dan bersih, dengan hanya sedikit nilai null yang ditemukan. Nilai-nilai null tersebut tidak dihapus atau diisi karena berdasarkan pertimbangan analisis, null tersebut bisa memiliki makna tersendiri atau memengaruhi hubungan antar tabel jika dimodifikasi secara sembarangan.
Sumber data diambil dari situs Maven Analytics Playground.

## Method
Metodologi yang digunakan dalam proyek ini cukup sederhana namun efektif. Beberapa pendekatan yang dilakukan antara lain:

-   Statistika Deskriptif: Untuk memahami distribusi dan karakteristik data seperti rata-rata, median, modus, standar deviasi, dll.

-   Statistika Inferensial: Menggunakan uji seperti Chi-Square untuk melihat hubungan antar variabel, misalnya antara alasan churn dan lokasi geografis pelanggan.

-   Visualisasi Data: Disajikan dalam bentuk tabel dan grafik menggunakan pustaka Python seperti matplotlib dan seaborn, serta dalam bentuk dashboard interaktif di Tableau.

## Stacks
Teknologi dan alat yang digunakan dalam proyek ini meliputi:

-   Bahasa Pemrograman: Python

-   Library Python:

    -   pandas – untuk manipulasi dan analisis data

    -   matplotlib & seaborn – untuk visualisasi data

    -   scipy.stats – untuk analisis statistik inferensial

-   Visualisasi Interaktif: Tableau Public digunakan untuk membangun dashboard yang menyajikan insight dari data secara lebih menarik dan mudah dipahami oleh pengguna non-teknis.

## Links
- [Sumber Data](https://mavenanalytics.io/data-playground?page=8&pageSize=5)
- [Dashboard Tableau](https://public.tableau.com/app/profile/azhar.muhammad8474/viz/TelecomCustomerChurn_17454220565550/DashboardMS?publish=yes)
- Dashboard tableau dapat diubah datanya berdasarkan generasi. (Klik generasi yang ingin dilihat datanya di pie chart 'Churn Persentage per Generations')