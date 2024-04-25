# **Analisis Supermarket Customers**
Untuk mengetahui strategi apa yang diambil untuk meningkatan pendapatan, menarik pelanggan baru dan meningkatkan retensi pelanggan di tahun yang akan datang.

## Stakeholder
Marketing Manager perusahaan Supermarket

## Analisis 
Dilakukan analisis jenis produk berdasarkan beberapa parameter seperti Age, Education, Marital Status, dan juga Total People.

## Data
### Keterangan dari data set

Keterangan dari tiap tiap kolom pada dataset adalah sebagai berikut :

**People**

| **No** | **Column Name** |                               **Description**                              | **Data Type** |
|:------:|:---------------:|:--------------------------------------------------------------------------:|:-------------:|
|   1.   |        ID       |              Pengenal pelanggan (Unik untuk setiap pelanggan)              |     Object    |
|   2.   |    Year Birth   |                          Tahun kelahiran pelanggan                         |    Integer    |
|   3.   |    Education    |                    Jenjang pendidikan terakhir pelanggan                   |     Object    |
|   4.   |  Marital Status |                         Status pernikahan pelanggan                        |     Object    |
|   5.   |      Income     |                        Pendapatan tahunan pelanggan                        |     Float     |
|   6.   |     Kid Home    |                     Jumlah anak-anak dirumah pelanggan                     |    Integer    |
|   7.   |    Teen Home    |                       Jumlah remaja dirumah pelanggan                      |    integer    |
|   8.   |   Dt Customer   |               Tanggal pelanggan terdaftar di supermarket ini               |    Datetime   |
|   9.   |     Recency     |              Jumlah hari semenjak transaksi terakhir pelanggan             |    Integer    |
|   10.  |     Complain    | 1 jika pelanggan pernah komplain dalam 2 tahun terakhir, 0 jika sebaliknya |    Integer    |

**Products**

| **No** | **Column Name** |                             **Description**                            | **Data Type** |
|:------:|:---------------:|:----------------------------------------------------------------------:|:-------------:|
|   1.   |      Wines      |      Total uang yang dikeluarkan untuk wine dalam 2 tahun terakhir     |    Integer    |
|   2.   |      Fruits     |      Total uang yang dikeluarkan untuk buah dalam 2 tahun terakhir     |    Integer    |
|   3.   |  Meat Products  | Total uang yang dikeluarkan untuk produk daging dalam 2 tahun terakhir |    Integer    |
|   4.   |  Fish Products  |      Total uang yang dikeluarkan untuk ikan dalam 2 tahun terakhir     |    Integer    |
|   5.   |  Sweet Products | Total uang yang dikeluarkan untuk makanan manis dalam 2 tahun terakhir |    Integer    |
|   6.   |  Gold Products  |      Total uang yang dikeluarkan untuk emas dalam 2 tahun terakhir     |    Integer    |

**Promotion**

| **No** |   **Column Name**   |                                        **Description**                                       | **Data Type** |
|:------:|:-------------------:|:--------------------------------------------------------------------------------------------:|:-------------:|
|   1.   | Num Deals Purchases |                         Jumlah pembelian yang dilakukan dengan diskon                        |    Integer    |
|   2.   |      Campaign1      |          1 jika pelanggan menerima tawaran promo yang pertama, 0 jika tidak menerima         |    Integer    |
|   3.   |      Campaign2      |           1 jika pelanggan menerima tawaran promo yang kedua, 0 jika tidak menerima          |    Integer    |
|   4.   |      Campaign3      |          1 jika pelanggan menerima tawaran promo yang ketiga, 0 jika tidak menerima          |    Integer    |
|   5.   |      Campaign4      |          1 jika pelanggan menerima tawaran promo yang keempat, 0 jika tidak menerima         |    Integer    |
|   6.   |      Campaign5      |          1 jika pelanggan menerima tawaran promo yang kelima, 0 jika tidak menerima          |    Integer    |
|   7.   |       Response      | 1 jika pelanggan menerima tawaran promo yang terakhir kali ditawarkan, 0 jika tidak menerima |    Integer    |

**Place**

| **No** |    **Column Name**    |                                    **Description**                                   | **Data Type** |
|:------:|:---------------------:|:------------------------------------------------------------------------------------:|:-------------:|
|   1.   |   Num Web Purchases   |                    Jumlah transaksi yang dilakukan melalui website                   |    Integer    |
|   2.   | Num Catalog Purchases |                    Jumlah transaksi yang dilakukan melalui katalog                   |    Integer    |
|   3.   |  Num Store Purchases  |                    Jumlah transaksi yang dilakukan langsung ditoko                   |    Integer    |
|   4.   |  Num Web Visit Month  | Jumlah visit ke website perusahaan yang dilakukan oleh pelanggan satu bulan terakhir |    Integer    |

## Tableau Public
https://public.tableau.com/app/profile/imam.hidayat/viz/AnalisisSupermarketCustomers/Dashboard1?publish=yes
