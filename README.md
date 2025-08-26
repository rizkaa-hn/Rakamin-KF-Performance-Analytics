# Kimia Farma - Performance Analytics 2020 - 2023

## About the Project
Projek ini merupakan bagian dari Final Task – Big Data Analyst Challenge oleh Rakamin Academy dan Kimia Farma. Tujuannya adalah membangun dashboard analitik komprehensif untuk menganalisis performa transaksi dan profit cabang Kimia Farma di seluruh Indonesia pada periode 2020–2023.

Dashboard dibuat berdasarkan data historis transaksi yang telah diproses dan dianalisis menggunakan Google BigQuery dan divisualisasikan melalui Google Looker Studio.

## Dataset yang Digunakan
Terdapat empat dataset utama yang di-_import_ ke Google BigQuerry:
1. Final Transaction = data transaksi
2. Product = Informasi produk dan kategori
3. Inventory = informasi inventaris produk
4. Kantor Cabang = Kategori dan cabang Kimia Farma di seluruh Indonesia

## Tabel Analisa
Untuk keperluan eksplorasi dan visualisasi, saya membangun sebuah tabel gabungan bernama tabel_analisis yang terdiri dari:
- Informasi transaksi (transaction_id, date, price, discount)
- Informasi produk (product_name)
- Informasi cabang (kota, provinsi, branch_name, rating_cabang)
- Kalkulasi :
    - nett_sales → harga setelah diskon
    - nett_profit → berdasarkan kategori harga
    - persentase_gross_laba
    - rating_transaksi

## Tools
Aplikasi yang digunakan dalam mengerjakan project ini:
1. Google BigQuerry
2. Google Looker Studio

## Dashboard
![Performance_Analytics_Kimia_Farma_2020_-_2023_page-0001](https://github.com/user-attachments/assets/25e7cfac-23da-4db2-a127-a59a87c9dc54)

## Hasil Analisis
Beberapa temuan utama dari analisis ini:
- Melihat Jawa Barat merupakan penyumbang pendapatan terbesar, Kimia Farma perlu mencermati kinerja cabang-cabang di provinsi lain. Strategi pemasaran yang efektif di Jawa Barat dapat diadaptasi dan diterapkan di wilayah lain untuk membantu meningkatkan pendapatan secara lebih merata di seluruh negeri.
- Produk paling menguntungkan berasal dari kategori _Psycholeptics_
- Ditemukan mismatch antara rating cabang dan rating transaksi pada beberapa kota — menunjukkan potensi untuk audit layanan
- Cabang-cabang yang berkinerja buruk — baik dari segi transaksi maupun laba — membutuhkan perhatian ekstra. Perusahaan dapat memberikan pelatihan staf dan meningkatkan sistem layanan untuk meningkatkan kinerja cabang-cabang tersebut.
- Penurunan pendapatan pada tahun 2021 dan 2023 perlu dicermati lebih lanjut. Penting bagi perusahaan untuk mengetahui faktor internal atau eksternal apa yang mungkin menyebabkan penurunan ini.


## Kontributor
- Nama :  Rizka Hasna Nabila
- Email : rizkahasna94@gmail.com
- Github : @rizkaa-hn
- Linkedin : https://www.linkedin.com/in/rizkahasnanabila/ 
