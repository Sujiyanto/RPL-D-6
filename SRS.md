<html>
<h2 align="center">SOFTWARE REQUIREMENT SPESIFICATION<br>
APLIKASI KREDIT BARANG KOPERASI KARYAWAN (AKBAR KOPKAR) POLINDRA</h2>
<h3 align="center">Version 1.0</h3>
<h3 align="center">14 April 2018</h3>
<br>
<p align="center"><img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/c57b058e837a1b18b1c8bef3a68767f1c5d0e4eb/image/polindra.png"></p>
<br>
<h4 align="center">Anggota :<br>
Nur Inayatun Mahmuda (1603109)<br>
Astri Alisah (1603091)<br>
Muhammad Fauji Al Fariz (1603107)<br>
Sujiyanto (1603112)</h4>

<h4 align="center">Kelompok 5<br>
D3TI2D</h4>

<h2 align="center">TEKNIK INFORMATIKA<br>
POLITEKNIK NEGERI INDRAMAYU</h2>

### 1. PENDAHULUAN

**1.1 Tujuan**<br>

Tujuan dari dokumen ini adalah untuk memberikan penjelasan rinci tentang persyaratan untuk "Aplikasi Kredit Barang Koperasi Karyawan Polindra" (AKBAR KOPKAR POLINDRA). Ini akan menggambarkan tujuan dan deklarasi lengkap untuk pengembangan sistem. Ini juga akan menjelaskan batasan sistem, antarmuka dan interaksi dengan aplikasi eksternal lainnya. Dokumen ini terutama ditujukan untuk diajukan ke pelanggan untuk persetujuan dan referensi untuk mengembangkan versi pertama dari sistem untuk tim pengembangan.<br>

**1.2 Lingkup Proyek**<br>

Sistem Perangkat Lunak ini hanya akan menjadi aplikasi lokal, yang artinya aplikasi ini hanya akan dibuat untuk anggota yang terdaftar dalam koperasi karyawan Polindra. Sistem ini akan dirangcang untuk membantu admin koperasi dalam pemantauan penjualan serta angsuran pembayaran serta dapat membantu anggota sebagai user yang menggunakan aplikasi ini untuk mempermudah melakukan transaksi pembelian barang dan peminjaman uang secara online. Dengan memaksimalkan sistem pada aplikasi ini maka akan memenuhi kebutuhan pihak koperasi dan tetap mudah dimengerti dalam hal penggunaan untuk semua user.<br>

**1.3 Definisi, Akronim, Singkatan**<br>

<table>
	<tr>
		<th>Istilah</th>
		<th>Definisi</th>
	</tr>
	<tr>
		<td>Kredit</td>
		<td>Melakukan pembayaran dengan cara mengangsur</td>
	</tr>
	<tr>
		<td>Koperasi</td>
		<td>Organisasi ekonomi yang dimiliki dan dioperasikan oleh beberapa orag demi kepentingan bersama</td>
	</tr>
	<tr>
		<td>User</td>
		<td>Pemakai atau pengguna aplikasi</td>
	</tr>
	<tr>
		<td>Admin</td>
		<td>Orang yang mengelolah web server dari aplikasi</td>
	</tr>
</table>

**1.4 Referensi** <br>

 - IEEE Software Engineering Standards Committee, “IEEE Std 830-1998, IEEE Recommended Practice for Software Requirements Specifications”, October 20, 1998.
 - https://www.slideshare.net/rivaldysetiawan7/srs-example-webapp-33986122
 - https://www.google.co.id/url?sa=t&rct=j&q=&esrc=s&source=web&cd=4&ved=0ahUKEwitpsi807jaAhUHqo8KHS0SAMEQFghLMAM&url=http%3A%2F%2Fwww.cse.chalmers.se%2F~feldt%2Fcourses%2Freqeng%2Fexamples%2Fsrs_example_2010_group2.pdf&usg=AOvVaw1sbUrO_cREj3g8sqm8driM
 - https://www.google.co.id/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&ved=0ahUKEwitpsi807jaAhUHqo8KHS0SAMEQFggoMAA&url=https%3A%2F%2Fwww.utdallas.edu%2F~chung%2FRE%2FPresentations07S%2FTeam_1_Doc%2FDocuments%2FSRS4.0.doc&usg=AOvVaw2zaGGnBB9yNttcKsuBifee

**1.5 Overview**<br>

Bab berikutnya, bagian Uraian Keseluruhan, dari dokumen ini memberikan sebuah ikhtisar fungsionalitas produk. Ini menggambarkan persyaratan informal dan digunakan untuk menetapkan konteks untuk spesifikasi persyaratan teknis di bab berikutnya. Bab ketiga, bagian Spesifikasi Kebutuhan, dari dokumen ini ditulis terutama untuk para pengembang dan menjelaskan dalam istilah teknis rincian fungsionalitas produk. Kedua bagian dokumen menggambarkan produk perangkat lunak yang sama secara keseluruhan.<br>

### 2. GAMBARAN UMUM

**2.1 Perspektif Produk** <br>

AKBAR Kopkar Polindra adalah aplikasi kredit barang di Koperasi Karyawan Politeknik Negeri Indramayu. Secara umum aplikasi ini berfungsi sebagai aplikasi penjualan yang berbasis android. Tujuannya untuk mempermudah  pihak koperasi dalam melakukan penjualan barang serta membantu pihak karyawan yang tergabung dalam anggota koperasi untuk melakukan pembelian barang karena pembayarannya dilakukan dengan sistem kredit tanpa menggunakan kartu kredit. Aplikasi ini berpacu pada aplikasi yang sudah ada sebelumnya yaitu aplikasi “Akulaku” namun aplikasi yang kita buat hanya ditujukan khusus untuk penjualan satu toko yaitu kopkar polindra dan hanya karyawan yang terdaftar yang bisa menggunakan aplikasi tersebut, kelebihan dari aplikasi ini mudah dioperasikan dan dipahami Serta aplikasi ini memiliki fungsi tambahan untuk pengajuan peminjaman uang. <br>
	
**2.1.1 Antarmuka Sistem**<br>
<img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/d74525e3fc3fb5db286801c34a9e99385d9f542f/image/Antarmuka%20Sistem.png"><br>
**2.1.2 Mockup**<br>
<table>
	<tr>
		<td><img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Login.png"><br>Mockup Tampilan Login </td>
		<td><img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Dashboard%20Admin.png"><br>Mockup Tampilan Dashboard Admin</td>
		<td><img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Barang%20Masuk.png"><br>Mockup Tampilan Data Barang Masuk</td>
	</tr>
	<tr>
		<td><img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Barang%20keluar.png"><br>Mockup Tampilan Data Barang Keluar</td>
		<td><img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Supplier.png"><br>Mockup Tampilan Data Supplier</td>
		<td><img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/member.png"><br>Mockup Tampilan Data Member</td>
	</tr>
	<tr>
		<td><img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/pembayaran.png"><br>Mockup Tampilan Data Pembayaran</td>
		<td><img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Dashboard%20user.png"><br>Mockup Tampilan Dashboard User</td>
		<td><img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Elektronik.png">Mockup Tampilan Barang Elektronik</td>
	</tr>
	<tr>
		<td><img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Sembako.png"><br>Mockup Tampilan Barang Sembako</td>
		<td><img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Kredit'.png"><br>Mockup Tampilan Pengajuan Kredit</td>
		<td><img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/about.png"><br>Mockup Tampilan About Aplikasi</td>
	</tr>
	<tr>
		<td><img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Personal.png"><br>Mockup Tampilan Data Pribadi Member</td>
		<td><img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/tagihan.png"><br>Mockup Tampilan Tagihan Pembayaran</td>
		<td><img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Help.png"><br>Mockup Tampilan Bantuan Menggunakan Aplikasi Untuk User</td>
	</tr>
</table><br>

**2.1.3 Antarmuka Hardware**<br>

<img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Antarmuka%20hardware.png"><br>

**2.1.4 Antarmuka Perangkat Lunak**<br>

Aplikasi Kredit Barang Koperasi Karyawan Polindra (AKBAR KOPKAR) ini berbasis website dan dapat digunakan dengan menggunakan browser apa saja.

**2.1.5 Antarmuka Komunikasi**<br>

Admin dan user harus tersambung internet terutama untuk admin untuk mengupload data barang dan mengelola data seperti laporan pembayaran yang akan diterima oleh user, dan untuk melakukan transaksi pembelian dan perkreditan barang secara online.

**2.1.6 Batasan Memori**<br>

Karena Aplikasi ini berbasis website dan tidak harus didownload maka tidak ada batasan penggunaan memori dalam aplikasi ini.

**2.1.7 Operasi - Operasi**<br>

<table>
	<tr>
		<th>ID_Operasi</th>
		<th>Operasi</th>
		<th>Fungsi</th>
	</tr>
	<tr>
		<td>OP01</td>
		<td>Registrasi User</td>
		<td>Untuk melakukan registrasi bagi user yang akan menggunakan aplikasi ini</td>
	</tr>
	<tr>
		<td>OP02</td>
		<td>Login</td>
		<td>Untuk masuk akses aplikasi</td>
	</tr>
	<tr>
		<td>OP03</td>
		<td>Tambah Barang Masuk</td>
		<td>Untuk menambahkan data barang yang masuk dari supplier</td>
	</tr>
	<tr>
		<td>OP04</td>
		<td>Edit</td>
		<td>Untuk mengubah data yang telah diinputkan</td>
	</tr>
	<tr>
		<td>OP08</td>
		<td>Simpan</td>
		<td>Untuk data yang telah selesai diedit</td>
	</tr>
	<tr>
		<td>OP05</td>
		<td>Hapus</td>
		<td>Untuk menghapus data yang sudah ada atau telah diinputkan</td>
	</tr>
	<tr>
		<td>OP06</td>
		<td>Search</td>
		<td>Untuk mencari data dari setiap tabel</td>
	</tr>
	<tr>
		<td>OP07</td>
		<td>Beli</td>
		<td>Untuk melakukan transaksi pembelian bagi user</td>
	</tr>
	<tr>
		<td>OP08</td>
		<td>Logout</td>
		<td>Untuk keluar dari akses aplikasi</td>
	</tr>
</table>

  **2.2 Spesifikasi Kebutuhan Fungsional**<br>

<img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Use%20Case%20keseluruhan.png"><br>

 - Deskripsi
 <table>
	<tr>
		<th>No</th>
		<th>Deskripsi Fungsional</th>
	</tr>
	<tr>
		<td>1.</td>
		<td>Admin dapat melakukan login aplikasi</td>
	</tr>
	<tr>
		<td>2.</td>
		<td>User dapat melakukan login aplikasi</td>
	</tr>
	<tr>
		<td>3.</td>
		<td>Admin dapat mengelolah data barang</td>
	</tr>
	<tr>
		<td>4.</td>
		<td>User dapat melihat data barang</td>
	</tr>
	<tr>
		<td>5.</td>
		<td>Admin dapat mengelolah data user</td>
	</tr>
	<tr>
		<td>6.</td>
		<td>User dapat melakukan transaksi pembelian</td>
	</tr>
	<tr>
		<td>7.</td>
		<td>User dapat melihat laporan pembayaran</td>
	</tr>
	<tr>
		<td>8.</td>
		<td>Admin dapat membuat laporan keuntungan</td>
	</tr>
</table>
<br>

**2.2.1 Use Case Admin**<br>

 - Login
<img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Use%20Case%20Admin%20Login.png"><br>
 Langkah-langkah :
1. Masuk ke halaman login
2. Masukan Username
3. Masukan Password
4. Klik Login

 - Mengelolah data barang
 <img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Use%20Case%20Admin%20Mengelolah%20data%20barang.png"><br>
 Langkah-langkah :
 1. Masuk ke halaman data barang
 2. Klik Tambah Barang untuk menambahkan barang baru
 3. Klik Edit untuk mengubah data yang telah diinputkan
 4. Klik Hapus untuk menghapus data yang sudah ada
 5. Sistem menyimpan ke database
 
 - Mengelola data user
 <img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Use%20Case%20Admin%20Mengelolah%20Data%20User.png"><br>
 Langkah-langkah :
 1. Masuk ke halaman data user
 2. Klik Tambah User untuk menambahkan user baru
 3. Klik Edit untuk mengubah data yang telah diinputkan
 4. Klik Hapus untuk menghapus data yang sudah ada
 5. Sistem menyimpan ke database

 - Mengelola Data Supplier
 <img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Use%20Case%20Admin%20Mengelola%20Data%20Supplier.png"><br>
 Langkah-langkah :
 1. Masuk ke halaman data supplier
 2. Klik Tambah Supplier untuk menambahkan supplier baru
 3. Klik Edit untuk mengubah data yang telah diinputkan
 4. Klik Hapus untuk menghapus data yang sudah ada
 5. Sistem menyimpan ke database

**2.2.2 Use Case User**<br>

 - Registrasi
 <img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Use%20Case%20User%20Registrasi.png"><br>
 Langkah-langkah :
1. Masuk ke halaman login
2. Klik Create Account
3. Isi Semua Data Dalam Form
4. Klik Register

 - Login
 <img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Use%20Case%20User%20Login.png"><br>
 Langkah-langkah :
1. Masuk ke halaman login
2. Masukan Username
3. Masukan Password
4. Klik Login

 - Lihat data barang
 <img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Use%20Case%20User%20Lihat%20Data%20Barang.png"><br>
 Langkah-langkah :
 1. Masuk ke halaman dashboard
 2. Pilih kategori barang
 3. Pilih barang
 4. Sistem menampilkan data barang
 
 - Transaksi Pembelian
  <img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Use%20Case%20User%20Transaksi%20Pembelian.png"><br>
 Langkah-langkah :
 1. Masuk ke halaman dashboard
 2. Pilih kategori barang
 3. Pilih barang
 4. Sistem menampilkan data barang
 5. Klik Beli untuk melanjutkan transaksi
 6. Pilih angsuran pembayaran
 7. Klik Ajukan untuk melakukan transaksi

 - Lihat laporan pembayaran
 <img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Use%20Case%20User%20Lihat%20Laporan%20Pembayaran.png"><br>
 Langkah-langkah :
 1. Masuk ke halaman Tagihan
 2. Sistem menampilkan laporan pembayaran

**2.3 Spesifikasi Kebutuhan non-Fungsional**<br>

 1. Sistem dapat dijalankan oleh beberapa software web browser
 2. Proses dari pengguna membuka aplikasi dan menampilkan beberapa menu didalamnya berlangsung tidak akan lama
 3. Sistem harus dapat memastikan bahwa data yang digunakan dalam sistem harus terlindung dari akses yang tidak berwenang
 4. Sistem memiliki tampilan (antar mukan) yang mudah dipahami <br>

**2.4 Karakteristik Pengguna** <br>

Dengan adanya aplikasi ini diharapkan dapat membantu admin mengelolah data perkreditan barang yang dijual dan peminjaman uang yang dilakukan oleh anggota. Kemudian untuk pengguna sendiri diharapkan bisa membantu mempermudah melakukan transaksi menggunakan aplikasi mobile ini.<br>

**2.5 Batasan-Batasan**<br>

Batasan pada produk :
1. Hanya menangani kredit penjualan barang atau peminjaman uang pada KOPKAR POLINDRA.
2.	Aplikasi akan dibuat dengan modul dan fungsionalitas sesuai dengan kebutuhan.
3.	Aplikasi dibangun dengan Java di Android Studio dan Firebase sebagai database


### 3. SPESIFIKASI KEBUTUHAN

**3.1 Kebutuhan Antarmuka Eksternal**<br>

Aplikasi kredit barang koperasi karyawan polindra ini berbasis android untuk anggota koperasi sebagai user dan menggunakan website untuk admin, untuk pengelolaan user interface digunakan aplikasi sublime text dimana tampilan website didesain sesuai kebutuhan admin dan user interface untuk anggota didesain menggunakan balsamiq dan diimplementasikan dengan android studio dan fungsi yang ada sesuai kebutuhan pengguna. aplikasi ini dilengkapi dengan beberapa fungsi yang disediakan. interaksi antara pengguna dan perangkat lunak dilakukan dengan smartphone dan interaksi antara admin dan website dilakukan baik dengan keyboard dan mouse.<br>

**3.2 Kebutuhan Fungsional**<br>

**3.2.1. Login**
<table>
	<tr>
		<th>Nama Fungsi</th>
		<th>Login</th>
	</tr>
	<tr>
		<td>Ref</td>
		<td>Bag. 2.1.2</td>
	</tr>
	<tr>
		<td>Trigger</td>
		<td>Membuka halaman login</td>
	</tr>
	<tr>
		<td>Precondition</td>
		<td>Tidak ada</td>
	</tr>
	<tr>
		<td>Basic Path</td>
		<td>Untuk mengakses aplikasi</td>
	</tr>
	<tr>
		<td>Alternative</td>
		<td>Tidak ada</td>
	</tr>
	<tr>
		<td>Post Condition</td>
		<td>Halaman dashboard</td>
	</tr>
	<tr>
		<td>Exception Push</td>
		<td>Tidak ada</td>
	</tr>
</table>

**3.2.2. Dashboard Admin**
<table>
	<tr>
		<th>Nama Fungsi</th>
		<th>Dashboard Admin</th>
	</tr>
	<tr>
		<td>Ref</td>
		<td>Bag. 2.1.2</td>
	</tr>
	<tr>
		<td>Trigger</td>
		<td>Masuk ke halaman dashboard admin</td>
	</tr>
	<tr>
		<td>Precondition</td>
		<td>Login</td>
	</tr>
	<tr>
		<td>Basic Path</td>
		<td>Untuk melihat laporan keuntungan</td>
	</tr>
	<tr>
		<td>Alternative</td>
		<td>Tidak ada</td>
	</tr>
	<tr>
		<td>Post Condition</td>
		<td>Halaman dashboard admin</td>
	</tr>
	<tr>
		<td>Exception Push</td>
		<td>Tidak ada</td>
	</tr>
</table>

**3.2.3. Barang Masuk**
<table>
	<tr>
		<th>Nama Fungsi</th>
		<th>Data Barang Masuk</th>
	</tr>
	<tr>
		<td>Ref</td>
		<td>Bag. 2.1.2</td>
	</tr>
	<tr>
		<td>Trigger</td>
		<td>Masuk ke halaman Barang Masuk</td>
	</tr>
	<tr>
		<td>Precondition</td>
		<td>Dashboard</td>
	</tr>
	<tr>
		<td>Basic Path</td>
		<td>Untuk mengelolah data barang masuk</td>
	</tr>
	<tr>
		<td>Alternative</td>
		<td>Tidak ada</td>
	</tr>
	<tr>
		<td>Post Condition</td>
		<td>Halaman Barang Masuk</td>
	</tr>
	<tr>
		<td>Exception Push</td>
		<td>Tidak ada</td>
	</tr>
</table>

**3.2.4. Barang Keluar**
<table>
	<tr>
		<th>Nama Fungsi</th>
		<th>Data Barang Keluar</th>
	</tr>
	<tr>
		<td>Ref</td>
		<td>Bag. 2.1.2</td>
	</tr>
	<tr>
		<td>Trigger</td>
		<td>Masuk ke halaman Barang Keluar</td>
	</tr>
	<tr>
		<td>Precondition</td>
		<td>Dashboard</td>
	</tr>
	<tr>
		<td>Basic Path</td>
		<td>Untuk mengelolah data barang keluar</td>
	</tr>
	<tr>
		<td>Alternative</td>
		<td>Tidak ada</td>
	</tr>
	<tr>
		<td>Post Condition</td>
		<td>Halaman Barang Keluar</td>
	</tr>
	<tr>
		<td>Exception Push</td>
		<td>Tidak ada</td>
	</tr>
</table>

**3.2.5. Supplier**


<table>
	<tr>
		<th>Nama Fungsi</th>
		<th>Data Supplier</th>
	</tr>
	<tr>
		<td>Ref</td>
		<td>Bag. 2.1.2</td>
	</tr>
	<tr>
		<td>Trigger</td>
		<td>Masuk ke halaman Data Supplier</td>
	</tr>
	<tr>
		<td>Precondition</td>
		<td>Dashboard</td>
	</tr>
	<tr>
		<td>Basic Path</td>
		<td>Untuk mengelolah data Supplier</td>
	</tr>
	<tr>
		<td>Alternative</td>
		<td>Tidak ada</td>
	</tr>
	<tr>
		<td>Post Condition</td>
		<td>Halaman Data Supplier</td>
	</tr>
	<tr>
		<td>Exception Push</td>
		<td>Tidak ada</td>
	</tr>
</table>

**3.2.6. Data Member**


<table>
	<tr>
		<th>Nama Fungsi</th>
		<th>Data Member</th>
	</tr>
	<tr>
		<td>Ref</td>
		<td>Bag. 2.1.2</td>
	</tr>
	<tr>
		<td>Trigger</td>
		<td>Masuk ke halaman Data Member</td>
	</tr>
	<tr>
		<td>Precondition</td>
		<td>Dashboard</td>
	</tr>
	<tr>
		<td>Basic Path</td>
		<td>Untuk mengelolah Data Member</td>
	</tr>
	<tr>
		<td>Alternative</td>
		<td>Tidak ada</td>
	</tr>
	<tr>
		<td>Post Condition</td>
		<td>Halaman Data Member</td>
	</tr>
	<tr>
		<td>Exception Push</td>
		<td>Tidak ada</td>
	</tr>
</table>

**3.2.7. Pembayaran**


<table>
	<tr>
		<th>Nama Fungsi</th>
		<th>Data Pembayaranr</th>
	</tr>
	<tr>
		<td>Ref</td>
		<td>Bag. 2.1.2</td>
	</tr>
	<tr>
		<td>Trigger</td>
		<td>Masuk ke halaman Data Pembayaran</td>
	</tr>
	<tr>
		<td>Precondition</td>
		<td>Dashboard</td>
	</tr>
	<tr>
		<td>Basic Path</td>
		<td>Untuk mengelolah Data Pembayaran</td>
	</tr>
	<tr>
		<td>Alternative</td>
		<td>Tidak ada</td>
	</tr>
	<tr>
		<td>Post Condition</td>
		<td>Halaman Data Pembayaran</td>
	</tr>
	<tr>
		<td>Exception Push</td>
		<td>Tidak ada</td>
	</tr>
</table>

**3.2.8. Dashboard User**
<table>
	<tr>
		<th>Nama Fungsi</th>
		<th>Dashboard User</th>
	</tr>
	<tr>
		<td>Ref</td>
		<td>Bag. 2.1.2</td>
	</tr>
	<tr>
		<td>Trigger</td>
		<td>Masuk ke halaman Dashboard User</td>
	</tr>
	<tr>
		<td>Precondition</td>
		<td>Login</td>
	</tr>
	<tr>
		<td>Basic Path</td>
		<td>Untuk melihat kategori barang yang tersedia</td>
	</tr>
	<tr>
		<td>Alternative</td>
		<td>Tidak ada</td>
	</tr>
	<tr>
		<td>Post Condition</td>
		<td>Halaman Dashboard User</td>
	</tr>
	<tr>
		<td>Exception Push</td>
		<td>Tidak ada</td>
	</tr>
</table>

**3.2.9. Barang Elektronik**
<table>
	<tr>
		<th>Nama Fungsi</th>
		<th>Elektronik</th>
	</tr>
	<tr>
		<td>Ref</td>
		<td>Bag. 2.1.2</td>
	</tr>
	<tr>
		<td>Trigger</td>
		<td>Masuk ke halaman kategori barang Elektronik</td>
	</tr>
	<tr>
		<td>Precondition</td>
		<td>Dashboard</td>
	</tr>
	<tr>
		<td>Basic Path</td>
		<td>Untuk melihat barang Elektronik yang tersedia</td>
	</tr>
	<tr>
		<td>Alternative</td>
		<td>Tidak ada</td>
	</tr>
	<tr>
		<td>Post Condition</td>
		<td>Halaman Elektronik</td>
	</tr>
	<tr>
		<td>Exception Push</td>
		<td>Tidak ada</td>
	</tr>
</table>

**3.2.10. Barang Sembako**
<table>
	<tr>
		<th>Nama Fungsi</th>
		<th>Sembako</th>
	</tr>
	<tr>
		<td>Ref</td>
		<td>Bag. 2.1.2</td>
	</tr>
	<tr>
		<td>Trigger</td>
		<td>Masuk ke halaman kategori barang Sembako</td>
	</tr>
	<tr>
		<td>Precondition</td>
		<td>Dashboard</td>
	</tr>
	<tr>
		<td>Basic Path</td>
		<td>Untuk melihat barang Sembako yang tersedia</td>
	</tr>
	<tr>
		<td>Alternative</td>
		<td>Tidak ada</td>
	</tr>
	<tr>
		<td>Post Condition</td>
		<td>Halaman Sembako</td>
	</tr>
	<tr>
		<td>Exception Push</td>
		<td>Tidak ada</td>
	</tr>
</table>

**3.2.11. Kredit**
<table>
	<tr>
		<th>Nama Fungsi</th>
		<th>Kredit</th>
	</tr>
	<tr>
		<td>Ref</td>
		<td>Bag. 2.1.2</td>
	</tr>
	<tr>
		<td>Trigger</td>
		<td>Masuk ke halaman Pengajuan Kredit</td>
	</tr>
	<tr>
		<td>Precondition</td>
		<td>Dashboard</td>
	</tr>
	<tr>
		<td>Basic Path</td>
		<td>Untuk melakukan pengajuan kredit</td>
	</tr>
	<tr>
		<td>Alternative</td>
		<td>Tidak ada</td>
	</tr>
	<tr>
		<td>Post Condition</td>
		<td>Halaman Kredit</td>
	</tr>
	<tr>
		<td>Exception Push</td>
		<td>Tidak ada</td>
	</tr>
</table>

**3.2.12. About**
<table>
	<tr>
		<th>Nama Fungsi</th>
		<th>About</th>
	</tr>
	<tr>
		<td>Ref</td>
		<td>Bag. 2.1.2</td>
	</tr>
	<tr>
		<td>Trigger</td>
		<td>Masuk ke halaman About</td>
	</tr>
	<tr>
		<td>Precondition</td>
		<td>Dashboard</td>
	</tr>
	<tr>
		<td>Basic Path</td>
		<td>Untuk melihat keterangan mengenai aplikasi</td>
	</tr>
	<tr>
		<td>Alternative</td>
		<td>Tidak ada</td>
	</tr>
	<tr>
		<td>Post Condition</td>
		<td>Halaman About</td>
	</tr>
	<tr>
		<td>Exception Push</td>
		<td>Tidak ada</td>
	</tr>
</table>

**3.2.13. Personal**
<table>
	<tr>
		<th>Nama Fungsi</th>
		<th>Personal</th>
	</tr>
	<tr>
		<td>Ref</td>
		<td>Bag. 2.1.2</td>
	</tr>
	<tr>
		<td>Trigger</td>
		<td>Masuk ke halaman Personal</td>
	</tr>
	<tr>
		<td>Precondition</td>
		<td>Dashboard</td>
	</tr>
	<tr>
		<td>Basic Path</td>
		<td>Untuk melihat keterangan data diri</td>
	</tr>
	<tr>
		<td>Alternative</td>
		<td>Tidak ada</td>
	</tr>
	<tr>
		<td>Post Condition</td>
		<td>Halaman Personal</td>
	</tr>
	<tr>
		<td>Exception Push</td>
		<td>Tidak ada</td>
	</tr>
</table>

**3.2.14. Tagihan**
<table>
	<tr>
		<th>Nama Fungsi</th>
		<th>Tagihan</th>
	</tr>
	<tr>
		<td>Ref</td>
		<td>Bag. 2.1.2</td>
	</tr>
	<tr>
		<td>Trigger</td>
		<td>Masuk ke halaman Tagihan</td>
	</tr>
	<tr>
		<td>Precondition</td>
		<td>Dashboard</td>
	</tr>
	<tr>
		<td>Basic Path</td>
		<td>Untuk melihat laporan pembayaran yang telah dilakukan</td>
	</tr>
	<tr>
		<td>Alternative</td>
		<td>Tidak ada</td>
	</tr>
	<tr>
		<td>Post Condition</td>
		<td>Halaman Tagihan</td>
	</tr>
	<tr>
		<td>Exception Push</td>
		<td>Tidak ada</td>
	</tr>
</table>

**3.2.15. Help**
<table>
	<tr>
		<th>Nama Fungsi</th>
		<th>Help</th>
	</tr>
	<tr>
		<td>Ref</td>
		<td>Bag. 2.1.2</td>
	</tr>
	<tr>
		<td>Trigger</td>
		<td>Masuk ke halaman Help</td>
	</tr>
	<tr>
		<td>Precondition</td>
		<td>Dashboard</td>
	</tr>
	<tr>
		<td>Basic Path</td>
		<td>Untuk melihat cara menggunakan aplikasi</td>
	</tr>
	<tr>
		<td>Alternative</td>
		<td>Tidak ada</td>
	</tr>
	<tr>
		<td>Post Condition</td>
		<td>Halaman Help</td>
	</tr>
	<tr>
		<td>Exception Push</td>
		<td>Tidak ada</td>
	</tr>
</table>

**3.3 Detail Persyaratan non-Fungsional** <br>

**3.3.1 Logika Struktur Data**

<img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/ERD.jpg"><br>

 - Tabel Bayar

<table>
	<tr>
		<th>Data Item</th>
		<th>Type</th>
		<th>Deskripsi</th>
	</tr>
	<tr>
		<td>id</td>
		<td>integer</td>
		<td>Identitas pembayaran</td>
	</tr>
	<tr>
		<td>id_credit</td>
		<td>int</td>
		<td>Identitas kredit</td>
	</tr>
	<tr>
		<td>tgl_bayar</td>
		<td>date</td>
		<td>Tanggal pembayaran</td>
	</tr>
	<tr>
		<td>cicilan</td>
		<td>varchar</td>
		<td>Nominal yang dibayar</td>
	</tr>
	<tr>
		<td>jumlah</td>
		<td>varchar</td>
		<td>Total kredit</td>
	</tr>
	<tr>
		<td>sisa</td>
		<td>varchar</td>
		<td>Sisa yang belum dibayar</td>
	</tr>
	<tr>
		<td>keterangan</td>
		<td>varchar</td>
		<td>Lunas/Belum</td>
	</tr>
</table>

 - Tabel Kredit

<table>
	<tr>
		<th>Data Item</th>
		<th>Type</th>
		<th>Deskripsi</th>
	</tr>
	<tr>
		<td>id</td>
		<td>integer</td>
		<td>Identitas penomoran</td>
	</tr>
	<tr>
		<td>id_credit</td>
		<td>int</td>
		<td>Identitas kredit</td>
	</tr>
	<tr>
		<td>id_member</td>
		<td>int</td>
		<td>Identitas member</td>
	</tr>
	<tr>
		<td>id_barang</td>
		<td>int</td>
		<td>Identitas barang</td>
	</tr>
	<tr>
		<td>tgl</td>
		<td>date</td>
		<td>Tanggal melakukan pengambilan kredit</td>
	</tr>
	<tr>
		<td>jangka</td>
		<td>varchar</td>
		<td>Jangka waktu pembayaran</td>
	</tr>
</table>

 - Tabel Barang

<table>
	<tr>
		<th>Data Item</th>
		<th>Type</th>
		<th>Deskripsi</th>
	</tr>
	<tr>
		<td>id</td>
		<td>integer</td>
		<td>Identitas penomoran</td>
	</tr>
	<tr>
		<td>id_barang</td>
		<td>int</td>
		<td>Identitas kredit</td>
	</tr>
	<tr>
		<td>nama_barang</td>
		<td>varchar</td>
		<td>Nama barang</td>
	</tr>
	<tr>
		<td>harga</td>
		<td>varchar</td>
		<td>Harga barang</td>
	</tr>
	<tr>
		<td>uang_muka</td>
		<td>vharchar</td>
		<td>Uang muka yang harus dibayar</td>
	</tr>
	<tr>
		<td>stok</td>
		<td>int</td>
		<td>Stok barang</td>
	</tr>
	<tr>
		<td>kategori</td>
		<td>varchar</td>
		<td>Kategori barang</td>
	</tr>
</table>

 - Tabel Member

<table>
	<tr>
		<th>Data Item</th>
		<th>Type</th>
		<th>Deskripsi</th>
	</tr>
	<tr>
		<td>id_member</td>
		<td>integer</td>
		<td>Identitas member</td>
	</tr>
	<tr>
		<td>nik</td>
		<td>int</td>
		<td>Nomor Induk Kepegawaian</td>
	</tr>
	<tr>
		<td>nama_member</td>
		<td>varchar</td>
		<td>Nama member</td>
	</tr>
	<tr>
		<td>jk</td>
		<td>varchar</td>
		<td>Jenis kelamin</td>
	</tr>
	<tr>
		<td>tmp_lahir</td>
		<td>vharchar</td>
		<td>Tempat lahir</td>
	</tr>
	<tr>
		<td>tgl_lahir</td>
		<td>date</td>
		<td>Tanggal lahir</td>
	</tr>
	<tr>
		<td>alamat</td>
		<td>varchar</td>
		<td>Alamat member</td>
	</tr>
	<tr>
		<td>no_telp</td>
		<td>varchar</td>
		<td>Info Kontak</td>
	</tr>
	<tr>
		<td>email</td>
		<td>varchar</td>
		<td>Email</td>
	</tr>
</table>

 - Tabel Kategori

<table>
	<tr>
		<th>Data Item</th>
		<th>Type</th>
		<th>Deskripsi</th>
	</tr>
	<tr>
		<td>id</td>
		<td>integer</td>
		<td>Identitas kategori</td>
	</tr>
	<tr>
		<td>nama_kategori</td>
		<td>varchar</td>
		<td>Nama Kategori</td>
	</tr>
</table>

 - Tabel Admin

<table>
	<tr>
		<th>Data Item</th>
		<th>Type</th>
		<th>Deskripsi</th>
	</tr>
	<tr>
		<td>id_admin</td>
		<td>integer</td>
		<td>Identitas admin</td>
	</tr>
	<tr>
		<td>nama_nadmin</td>
		<td>varchar</td>
		<td>Nama Admin</td>
	</tr>
</table>

 - Tabel Login

<table>
	<tr>
		<th>Data Item</th>
		<th>Type</th>
		<th>Deskripsi</th>
	</tr>
	<tr>
		<td>id_login</td>
		<td>integer</td>
		<td>Identitas login</td>
	</tr>
	<tr>
		<td>username</td>
		<td>varchar</td>
		<td>Username</td>
	</tr>
	<tr>
		<td>password</td>
		<td>varchar</td>
		<td>Password</td>
	</tr>
</table>

</html>
