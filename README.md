**Capstone Project Modul 2**

**Nama : Edward Fajar Binsar Halomoan Hutapea**

**Dataset : Supermarket Customers**

**Audience:**
Board of Director (sebagai pengambilan keputusan bisnis)

**Business Problems:** 
1. Churn Rate
2. Nilai transaksi

**Goals**
1. Churn Rate menurun
2. Nilai transaksi meningkat

**Business Questions**
1.	Berapa Customer Churn rate?
2.	Seberapa efektif discount mempengaruhi tingkat pembelian?
3.	Apakah kampanye promosi efektif dalam meningkatkan jumlah transaksi?
4.	Produk apa yang memiliki nilai transaksi tertinggi dan terendah?
5.	Metode Transaksi apa yang paling banyak dan sedikit dipilih customer?
6.	Bagaimana komposisi usia pelanggan?
7.	Berapa income untuk masing-masing kategori usia pelanggan?
8.	Berapa usia customer yang memiliki jumlah transaksi tertinggi dan terendah?
9.	Berapa usia customer yang memiliki nilai transaksi tertinggi dan terendah?
10.	Untuk masing-masing produk, berapa usia customer yang memiliki nilai transaksi tertinggi dan terendah?
11.	Untuk masing-masing lokasi transaksi, berapa usia customer yang memiliki jumlah transaksi tertinggi dan terendah?
12.	Untuk kategori pendidikan dan status pernikahan,  berapa distribusi nilai transaksi untuk semua produk?

**Dataset : Supermarket Customer**
source: https://drive.google.com/drive/folders/1WodnBbuYTvsF0-6HTuQABQ0KCS31lqbK

**Step 1: Import Package**

**Step 2: Import Data**

**Step 3: Data Wrangling**
-	Pengecekan Tipe Data
-	Pengecekan Anomali Data: Drop missing value, Drop duplikat data, Drop outliers dari kolom tertentu,
-	Konversi Kolom bertipe Tanggal.
-	Deskriptif Data Statistik
-	Penampilan Data Summary

**Step 4: Analisa Data dan Insight Untuk setiap Business Question (1 s/d 12)**

**Step 5: Actionable Recommendation untuk setiap Goals**

**5.1 Goal 1 – Churn Rate Menurun**

Actionable Recommendation :
- Memberikan diskon yang hanya berlaku sampai 1 bulan setelah transaksi terakhir dilakukan. Hal ini akan mendorong pelanggan untuk menggunakan promo diskon tersebut sebelum masa berlakunya habis ==> pelanggan akan melakukan transaksi berikutnya dalam 1 bulan.
- Merespon setiap complain dari pelanggan dengan cepat. "Respon yang lama" bisa menjadi faktor yang membuat terjadinya customer churn.
- Memberikan loyalti bonus secara berkala, seperti setiap 3 bulan, 6 bulan atau setiap tahun untuk memelihara loyalitas pelaggan. Bonus ini bisa berupa pemberian tambahan produk secara gratis kepada pelanggan. 

Menampilkan juga perbandingan ketika supermarket berhasil melakukan Actionable Recommendation (BEFORE dan AFTER).

**5.2 Goal 2 – Nilai Transaksi Meningkat**

*A. KAMPANYE PROMOSI*
Actionable Recommendation :
- Mengoptimalkan program discount langsung di kampanye pertama, supaya lebih banyak pelanggan yang langsung membeli produk diskon tanpa menunggu tahapan kampanye berikutnya.

*B. JENIS PRODUK*
Actionable Recommendation :
- Meningkatkan promos dan penawaran khusus bagi pelanggan yang membeli produk FRUITS, SWEET, FISH dan GOLD. Kampanye marketing ini bisa berupa paket pembelian bundling.\
- Menambah variasi sub-produk untuk masing-masing produk, sehingga pelanggan tidak perlu pergi ke supermarket kompetitor.

*C. METODE/LOKASI TRANSAKSI*
Actionable Recommendation :
- Mengurangi biaya tambahan (seperti biaya admin, dll) yang terdapat di transaksi online melalui website supermarket. Biaya tambahan ini mungkin juga menjadi penyeban churn.

*D. USIA PELANGGAN*
Actionable Recommendation : Memberikan promo khusus kepada spesifik pelanggan, dengan ketentuan sebagai berikut:
- Pelanggan berusia 21-30 dan 66-70 (mencakup 13% jumlah pelanggan) : discount 5% + promo ulang tahun + point reward (yang dapat dikonversi menjadi discount tambahan)  
- Pelanggan berusia 31-35, 51-55 dan 61-65 tahun (mencakup 28% jumlah pelanggan) : discount 5% + promo ulang tahun
