<p align="center"><h1>Software Requirements Specification</h1></p>
<p align="center"> Version 1.0</p>
<p align="center">22 Februari 2018</p>

<p align="center"><img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/POLINDRA.png"></p><br>

<p align="center"><b>AKBAR KOPKAR</b>
<p align="center"><b>(Aplikasi Kredit Barang Koperasi Karyawan) POLINDRA</b>

Anggota 
 1. Nur Inayatun Mahmuda (1603109)
 2. Muhammad Fauji Al Fariz (1603107)
 3. Sujiyanto (1603112)<br>

<p align="center">Jurusan Teknik Informatika
<p align="center">Polireknik Negeri Indramayu


### 1. Pendahuluan
**1.1 Tujuan**<br>
		<p>Tujuan dari dokumen ini adalah untuk menyajikan deskripsi rinci tentang aplikasi yang akan dibuat serta dokumen ini akan menjelaskan tentang tujuan dan fitur dari sistem yang akan dibangun beserta interface dari sistem.</p><br>
**1.2 Lingkup Proyek**<br>
		Sistem Perangkat Lunak ini hanya akan menjadi aplikasi lokal, yang artinya aplikasi ini hanya akan dibuat untuk anggota yang terdaftar dalam koperasi karyawan Polindra. Sistem ini akan dirangcang untuk membantu admin koperasi dalam pemantauan penjualan serta angsuran pembayaran serta dapat membantu pihak anggota sebagai user yang menggunakan aplikasi ini untuk mempermudah melakukan transaksi pembelian barang dan peminjaman uang secara online. Dengan memaksimalkan sistem pada aplikasi ini maka akan memenuhi kebutuhan pihak koperasi dan tetap mudah dimengerti dalam hal penggunaan untuk semua user.<br>
**1.3 Definisi, Akronim, Singkatan**<br>

| Istilah |Definisi                                       |
|---------|------------------------------------------------|
| Admin   | Orang yang mengelolah web server dari aplikasi |
| User    | Pemakai atau pengguna aplikasi                 |
<br>
**1.4 Referensi**
		
**1.5 Overview**<br>
Bab 2, bagian Uraian Keseluruhan, dari dokumen ini memberikan sebuah gambaran fungsionalitas produk. Bab 3, Bagian Persyaratan Spesifikasi, dari dokumen ini ditulis terutama untuk menjelaskan secara teknis rinciannya fungsionalitas produk. Kedua bagian dokumen tersebut menggambarkan produk perangkat lunak yang sama secara keseluruhan, namun ditujukan untuk khalayak yang berbeda.<br>

### 2. DESKRIPSI UMUM PERANGKAT LUNAK

  **2.1 Perspektif Produk**
<br>AKBAR Kopkar Polindra adalah aplikasi kredit barang di Koperasi Karyawan Politeknik Negeri Indramayu. Secara umum aplikasi ini berfungsi sebagai aplikasi penjualan yang berbasis android. Tujuannya untuk mempermudah  pihak koperasi dalam melakukan penjualan barang serta membantu pihak karyawan yang tergabung dalam anggota koperasi untuk melakukan pembelian barang karena pembayarannya dilakukan dengan sistem kredit tanpa menggunakan kartu kredit. Aplikasi ini berpacu pada aplikasi yang sudah ada sebelumnya yaitu aplikasi “Akulaku” namun aplikasi yang kita buat hanya ditujukan khusus untuk penjualan satu toko yaitu kopkar polindra dan hanya karyawan yang terdaftar yang bisa menggunakan aplikasi tersebut. Serta aplikasi ini memiliki fungsi tambahan untuk pengajuan peminjaman uang.<br>
	
**2.1.1 Antarmuka Sistem**<br>
<p align="center"><img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Use%20Case%20Diagram.png"></p>
<br>
**2.1.2 Mockup**<br>
<img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Dashboard.png"><img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Account.png"><img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Elektronik.png">
<img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Bill.png"><img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Edit%20Account.png"><img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Login%20User.png"><img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Daftar%20User.png"><img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Elektronik%20(pilih%20angsuran).png"><img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Elektronik%20(waktu%20pembayaran).png">
<p align="center">
<img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Login%20Admin.png"></p> 
<p align="center">
<img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Dasboard%20Admin.png"></p>

**2.1.3 Antarmuka Hardware** <br>
 ![Antarmuka Hardware](/image/Antarmuka%20Hardware.png)
 <br>
 **2.2 Fungsi-Fungsi Produk**<br>
 
 **USER**

 - Dapat Melakukan Transaksi
 - Melihat List Barang
 - Login
 
 **ADMIN**
 
 - Dapat Menambahkan Barang
 - Melihat laporan
 - Login
 - Melihat Barang

 **2.3 Karakteristik Pengguna**
 
 Hanya Ada 2 Karakteristik Pengguna
 1. Admin
 2. Pengguna / User
 
 **2.4 Batasan-Batasan**
 Batasan Sistem Aplikasi dalam dokumen SRS ini adalah sebagai berikut:  
 
1. Aplikasi ini dilengkapi dengan pemberian hak akses masing  – masing user.
2. Sistem Aplikasi yang berupa data anggota, transaksi pinjaman, angsuran pinjaman.
3. Anggota koperasi dan Staff  harus melakukan login terlebih dahulu untuk mendapat hak akses ke menu selanjutnya. 
4. Dalam transaksi simpan pinjam, koperasi hanya dapat melayani transaksi kepada anggotanya saja sehingga yang bukan anggota koperasi tidak diperbolehkan. 
5. Untuk non anggota harus melakukan regristrasi terlebih dahulu menjadi anggota dan mendapatkan user dan password.  
