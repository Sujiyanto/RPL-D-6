


## REKAYASA PERANGKAT LUNAK
### Software Design Description (SDD)
### Aplikasi Kredit Barang Koperasi Karyawan POLINDRA
![logo](/image/polindra.png)<br>
**1. Pendahuluan**

**1.1 Tujuan**

Tujuan dari dokumen ini adalah untuk menyajikan deskripsi rinci tentang aplikasi yang akan dibuat serta dokumen ini akan menjelaskan tentang tujuan dan fitur dari sistem yang akan dibangun beserta interface dari sistem.



## REKAYASA PERANGKAT LUNAK
### Software Design Description (SDD)
### Aplikasi Kredit Barang Koperasi Karyawan POLINDRA
![logo](/image/polindra.png)<br>
**1. Pendahuluan**

**1.1 Tujuan Penulisan Dokumen**

Tujuan pembuatan SDD (Software Design Description) ini adalah untuk menjelaskan langkah langkah desain dan proses-proses dalam pembuatan sistem yang akan diterapkan pada aplikasi Kredit Barang Koperasi Karyawan (AKBAR KOPKAR) POLINDRA, dan juga memberi definisi kebutuhan untuk sistem dan spesifikasi kebutuhan fungsional. Fungsi utama dari AKBAR KOPKAR ini adalah membantu pihak koperasi dalam melakukan sistem penjualan kredit barang.

**1.2 Lingkup Masalah**
		
Sistem Perangkat Lunak ini hanya akan menjadi aplikasi lokal, yang artinya aplikasi ini hanya akan dibuat untuk anggota yang terdaftar dalam koperasi karyawan Polindra. Sistem ini akan dirangcang untuk membantu admin koperasi dalam pemantauan penjualan serta angsuran pembayaran serta dapat membantu pihak anggota sebagai user yang menggunakan aplikasi ini untuk mempermudah melakukan transaksi pembelian barang dan peminjaman uang secara online. Dengan memaksimalkan sistem pada aplikasi ini maka akan memenuhi kebutuhan pihak koperasi dan tetap mudah dimengerti dalam hal penggunaan untuk semua user.
		
**1.3 Definisi dan Istilah**
		
| Istilah | Definisi                                       |
|---------|------------------------------------------------|
| Admin   | Orang yang mengelolah web server dari aplikasi |
| User    | Pemakai atau pengguna aplikasi                 |
| Koperasi | Organisasi ekonomi yang dimiliki dan dioperasikan oleh beberapa orang demi kepentingan bersama

**1. 4 Referensi**<br>

https://www.slideshare.net/rivaldysetiawan7/srs-example-webapp-33986122 <br>
http://www.san.uri.br/~pbetencourt/engsoftII/IEEE-P1016-d50.PDF

**1.5 Iktisar Dokumen**
SDD ini berisikan penjabaran rancangan dari perangkat lunak yang akan dibuat, sehingga pada tahap implementasi perangkat lunak tersebut memiliki spesifikasi yang jelas dengan tetap menjadikan dokumen ini sebagai acuan.
|BAB| Isi |
|--|--|
|**BAB I**| **Pendahuluan** |
|**BAB II**| **Deskripsi Perancangan Global** |
|**BAB III**| **Deskripsi Perancangan Rinci**


**3. Penjelasan dekomposisi**<br>
**3.1 Diagram Konteks**<br>
![Diagram konteks](/image/Diagram%20konteks.png)<br>
**3.2 DFD Level 0**<br>
![DFD Level 0](/image/DFD%20Level%200.jpeg)<br>
**3.2.1 DFD Level 0 Admin** <br>
![DFD Level0 Admin](/image/DFD%20level0%20Admin.JPG) <br>
**3.3 DFD Level 1**<br>
![enter image description here](/image/DFD%20level1%20Admin.PNG) <br>
**3.3.1 DFD Level 1 Data Member**<br>
![DFD LvL 1 Data Member](/image/DFD%20lvl%201%20Data%20Member.png)
		
**1.2 Lingkup**
		
Sistem Perangkat Lunak ini hanya akan menjadi aplikasi lokal, yang artinya aplikasi ini hanya akan dibuat untuk anggota yang terdaftar dalam koperasi karyawan Polindra. Sistem ini akan dirangcang untuk membantu admin koperasi dalam pemantauan penjualan serta angsuran pembayaran serta dapat membantu pihak anggota sebagai user yang menggunakan aplikasi ini untuk mempermudah melakukan transaksi pembelian barang dan peminjaman uang secara online. Dengan memaksimalkan sistem pada aplikasi ini maka akan memenuhi kebutuhan pihak koperasi dan tetap mudah dimengerti dalam hal penggunaan untuk semua user.
		
**1.3 Definisi, akronim dan singkatan**
		
| Istilah | Definisi                                       |
|---------|------------------------------------------------|
| Admin   | Orang yang mengelolah web server dari aplikasi |
| User    | Pemakai atau pengguna aplikasi                 |

**2. Referensi**<br>

https://www.slideshare.net/rivaldysetiawan7/srs-example-webapp-33986122 <br>

**3. Penjelasan dekomposisi**<br>
**3.1 Diagram Konteks**<br>
![diagram konteks](/image/Diagram%20konteks.jpeg)<br>
**3.2 DFD Level 0**<br>
![DFD level 0](/image/DFD%20Level%200.jpeg)<br>
**3.3 DFD Level 1**<br>
**3.3.1 DFD Level 1 Data Member**<br>
![DFD LvL 1 Data Member](/image/DFD%20lvl%201%20Data%20Member.png)

**3.3.2 DFD Level 1 Data Barang**<br>
![DFD LvL 1 Data Barang](/image/DFD%20lvl%201%20Data%20Barang.png)

**3.3.3 DFD Level 1 Data Order**<br>
![DFD LEVEL 1 DATA ORDER](/image/DFD%20lvl%201%20Data%20Order.png)
