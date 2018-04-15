
<html>
<h2 align="center">Software Design Description<br>
APLIKASI KREDIT BARANG KOPERASI KARYAWAN (AKBAR KOPKAR) POLINDRA</h2>
<h3 align="center">Version 1.0</h3>
<h3 align="center">15 April 2018</h3>
<br>
<p align="center"><img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/POLINDRA.png"></p>
<br>
<h4 align="center">Anggota<br>
- Nur Inayatun Mahmuda (1603109)<br>
- Astri Alisah (1603091)<br>
- Muhammad Fauji Al Fariz (1603107)<br>
- Sujiyanto (1603112)</h4>
<br>
<h4 align="center">Kelompok 5<br>
D3TI2D</h4>
<h2 align="center">TEKNIK INFORMATIKA<br>
POLITEKNIK NEGERI INDRAMAYU</h2>

**1. Pendahuluan**

**1.1 Tujuan Penulisan Dokumen**

Tujuan pembuatan SDD (Software Design Description) ini adalah untuk menjelaskan langkah langkah desain dan proses-proses dalam pembuatan sistem yang akan diterapkan pada aplikasi Kredit Barang Koperasi Karyawan (AKBAR KOPKAR) POLINDRA, dan juga memberi definisi kebutuhan untuk sistem dan spesifikasi kebutuhan fungsional. Fungsi utama dari AKBAR KOPKAR ini adalah membantu pihak koperasi dalam melakukan sistem penjualan kredit barang. Aplikasi ini hanya digunakan oleh member yang terdaftar pada koperasi karyawan polindra.

**1.2 Lingkup Masalah**
		
Sistem Perangkat Lunak ini hanya akan menjadi aplikasi lokal, yang artinya aplikasi ini hanya akan dibuat untuk anggota yang terdaftar dalam koperasi karyawan Polindra. Sistem ini akan dirangcang untuk membantu admin koperasi dalam pemantauan penjualan serta angsuran pembayaran serta dapat membantu pihak anggota sebagai user yang menggunakan aplikasi ini untuk mempermudah melakukan transaksi pembelian barang dan peminjaman uang secara online. Dengan memaksimalkan sistem pada aplikasi ini maka akan memenuhi kebutuhan pihak koperasi dan tetap mudah dimengerti dalam hal penggunaan untuk semua user.
		
**1.3 Definisi dan Istilah**
		
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

**1.4 Aturan Penamaan dan penomoran**

**1.5 Referensi**<br>

- https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0ahUKEwjd7pWs6LvaAhUFto8KHShUDGsQFggoMAA&url=http%3A%2F%2Fwww.san.uri.br%2F~pbetencourt%2FengsoftII%2FIEEE-P1016-d50.PDF&usg=AOvVaw0-Aa9INJSSPZeNBCHHyNms
- https://www.slideshare.net/rivaldysetiawan7/srs-example-webapp-33986122
- http://www.san.uri.br/~pbetencourt/engsoftII/IEEE-P1016-d50.PDF

**1.6 Iktisar Dokumen**<br>

SDD ini berisikan penjabaran rancangan dari perangkat lunak yang akan dibuat, sehingga pada tahap implementasi perangkat lunak tersebut memiliki spesifikasi yang jelas dengan tetap menjadikan dokumen ini sebagai acuan.

|BAB        |Isi                             |
|-----------|--------------------------------|
|**BAB I**  |**Pendahuluan**                 |
|**BAB II** |**Deskripsi Perancangan Global**|
|**BAB III**|**Deskripsi Perancangan Rinci** |

**2. Deskripsi Perancangan Global**<br>

**2.1 Rancangan Lingkungan Implementasi**<br>

Lingkungan implementasi yang akan digunakan untuk perancangan sistem Aplikasi Kredit Barang Koperasi Karyawan Polindra ini adalah :
<br>
<table>
	<tr>
		<td>Sistem Operasi</td>
		<td>Windows 10</td>
	</tr>
	<tr>
		<td>DBMS</td>
		<td>MySQL</td>
	</tr>
	<tr>
		<td>Development Tools</td>
		<td>Sublime Text, Android Studio, Balsamiq, Xampp</td>
	</tr>
	<tr>
		<td>Bahasa Pemrograman</td>
		<td>HTML, PHP, Java</td>
	</tr>
</table>


**2.2 Deskripsi Data**<br>

- Tabel Bayar
<table>
	<tr>
		<th>Nama Field</th>
		<th>Jenis</th>
		<th>Volume</th>
		<th>Laju</th>
		<th>Primary Key</th>
		<th>Constraint Integrity</th>
		<th>Deskripsi</th>
	</tr>
	<tr>
		<td>id_bayar</td>
		<td>integer</td>
		<td>3</td>
		<td>Primary Key</td>
		<td>Iya</td>
		<td>Auto_Increment</td>
		<td>Identitas pembayaran</td>
	</tr>
	<tr>
		<td>id_credit</td>
		<td>int</td>
		<td>3</td>
		<td>Foreign_key</td>
		<td>Tidak</td>
		<td>-</td>
		<td>Identitas kredit</td>
	</tr>
	<tr>
		<td>tgl_bayar</td>
		<td>date</td>
		<td>-</td>
		<td>Tidak</td>
		<td>Tidak</td>
		<td>-</td>
		<td>Tanggal pembayaran</td>
	</tr>
	<tr>
		<td>cicilan</td>
		<td>varchar</td>
		<td>15</td>
		<td>Tidak</td>
		<td>Tidak</td>
		<td>-</td>	
		<td>Nominal yang dibayar</td>
	</tr>
	<tr>
		<td>jumlah</td>
		<td>varchar</td>
		<td>15</td>
		<td>Tidak</td>
		<td>Tidak</td>
		<td>-</td>
		<td>Total kredit</td>
	</tr>
	<tr>
		<td>sisa</td>
		<td>varchar</td>
		<td>15</td>
		<td>Tidak</td>
		<td>Tidak</td>
		<td>-</td>
		<td>Sisa yang belum dibayar</td>
	</tr>
	<tr>
		<td>keterangan</td>
		<td>varchar</td>
		<td>15</td>
		<td>Tidak</td>
		<td>Tidak</td>
		<td>-</td>
		<td>Lunas/Belum</td>
	</tr>
</table>

- Tabel Kredit
<table>
	<tr>
		<th>Nama Field</th>
		<th>Jenis</th>
		<th>Volume</th>
		<th>Laju</th>
		<th>Primary Key</th>
		<th>Constraint Integrity</th>
		<th>Deskripsi</th>
	</tr>
	<tr>
		<td>id</td>
		<td>integer</td>
		<td>3</td>
		<td>Tidak</td>
		<td>Tidak</td>
		<td>Auto_increment</td>
		<td>Identitas penomoran</td>
	</tr>
	<tr>
		<td>id_credit</td>
		<td>int</td>
		<td>3</td>
		<td>Primary Key</td>
		<td>Iya</td>
		<td>Auto_Increment</td>
		<td>Identitas kredit</td>
	</tr>
	<tr>
		<td>id_member</td>
		<td>int</td>
		<td>3</td>
		<td>Foreign Key</td>
		<td>Tidak</td>
		<td>Auto_increment</td>
		<td>Identitas member</td>
	</tr>
	<tr>
		<td>id_barang</td>
		<td>int</td>
		<td>3</td>
		<td>Foreign Key</td>
		<td>Tidak</td>
		<td>Auto_increment</td>
		<td>Identitas barang</td>
	</tr>
	<tr>
		<td>tgl</td>
		<td>date</td>
		<td>-</td>
		<td>Tidak</td>
		<td>Tidak</td>
		<td>-</td>
		<td>Tanggal melakukan pengambilan kredit</td>
	</tr>
	<tr>
		<td>jangka</td>
		<td>varchar</td>
		<td>10</td>
		<td>Tidak</td>
		<td>Tidak</td>
		<td>-</td>
		<td>Jangka waktu pembayaran</td>
	</tr>
</table>

- Tabel Barang
<table>
	<tr>
		<th>Nama Field</th>
		<th>Jenis</th>
		<th>Volume</th>
		<th>Laju</th>
		<th>Primary Key</th>
		<th>Constraint Integrity</th>
		<th>Deskripsi</th>
	</tr>
	<tr>
		<td>id</td>
		<td>integer</td>
		<td>3</td>
		<td>Tidak</td>
		<td>Tidak</td>
		<td>Auto_increment</td>
		<td>Identitas penomoran</td>
	</tr>
	<tr>
		<td>id_barang</td>
		<td>int</td>
		<td>3</td>
		<td>Primary Key</td>
		<td>Iya</td>
		<td>Auto_increment</td>
		<td>Identitas kredit</td>
	</tr>
	<tr>
		<td>nama_barang</td>
		<td>varchar</td>
		<td>50</td>
		<td>Tidak</td>
		<td>Tidak</td>
		<td>-</td>
		<td>Nama barang</td>
	</tr>
	<tr>
		<td>harga</td>
		<td>varchar</td>
		<td>15</td>
		<td>Tidak</td>
		<td>Tidak</td>
		<td>-</td>
		<td>Harga barang</td>
	</tr>
	<tr>
		<td>uang_muka</td>
		<td>vharchar</td>
		<td>15</td>
		<td>Tidak</td>
		<td>Tidak</td>
		<td>-</td>
		<td>Uang muka yang harus dibayar</td>
	</tr>
	<tr>
		<td>stok</td>
		<td>int</td>
		<td>3</td>
		<td>Tidak</td>
		<td>Tidak</td>
		<td>-</td>
		<td>Stok barang</td>
	</tr>
	<tr>
		<td>kategori</td>
		<td>varchar</td>
		<td>15</td>
		<td>Tidak</td>
		<td>Tidak</td>
		<td>-</td>
		<td>Kategori barang</td>
	</tr>
</table>

- Tabel Member
<table>
	<tr>
		<th>Nama Field</th>
		<th>Jenis</th>
		<th>Volume</th>
		<th>Laju</th>
		<th>Primary Key</th>
		<th>Constraint Integrity</th>
		<th>Deskripsi</th>
	</tr>
	<tr>
		<td>id_member</td>
		<td>integer</td>
		<td>3</td>
		<td>Primary Key</td>
		<td>Iya</td>
		<td>Auto_increment</td>
		<td>Identitas member</td>
	</tr>
	<tr>
		<td>nik</td>
		<td>int</td>
		<td>10</td>
		<td>Tidak</td>
		<td>Tidak</td>
		<td>-</td>
		<td>Nomor Induk Kepegawaian</td>
	</tr>
	<tr>
		<td>nama_member</td>
		<td>varchar</td>
		<td>50</td>
		<td>Tidak</td>
		<td>Tidak</td>
		<td>-</td>
		<td>Nama member</td>
	</tr>
	<tr>
		<td>jk</td>
		<td>varchar</td>
		<td>15</td>
		<td>Tidak</td>
		<td>Tidak</td>
		<td>-</td>
		<td>Jenis kelamin</td>
	</tr>
	<tr>
		<td>tmp_lahir</td>
		<td>vharchar</td>
		<td>15</td>
		<td>Tidak</td>
		<td>Tidak</td>
		<td>-</td>
		<td>Tempat lahir</td>
	</tr>
	<tr>
		<td>tgl_lahir</td>
		<td>date</td>
		<td>-</td>
		<td>Tidak</td>
		<td>Tidak</td>
		<td>-</td>
		<td>Tanggal lahir</td>
	</tr>
	<tr>
		<td>alamat</td>
		<td>varchar</td>
		<td>50</td>
		<td>Tidak</td>
		<td>Tidak</td>
		<td>-</td>
		<td>Alamat member</td>
	</tr>
	<tr>
		<td>no_telp</td>
		<td>varchar</td>
		<td>15</td>
		<td>Tidak</td>
		<td>Tidak</td>
		<td>-</td>
		<td>Info Kontak</td>
	</tr>
	<tr>
		<td>email</td>
		<td>varchar</td>
		<td>25</td>
		<td>Tidak</td>
		<td>Tidak</td>
		<td>-</td>
		<td>Email</td>
	</tr>
</table>

- Tabel Kategori
<table>
	<tr>
		<th>Nama Field</th>
		<th>Jenis</th>
		<th>Volume</th>
		<th>Laju</th>
		<th>Primary Key</th>
		<th>Constraint Integrity</th>
		<th>Deskripsi</th>
	</tr>
	<tr>
		<td>id</td>
		<td>integer</td>
		<td>3</td>
		<td>Tidak</td>
		<td>Tidak</td>
		<td>Auto_increment</td>
		<td>Identitas kategori</td>
	</tr>
	<tr>
		<td>nama_kategori</td>
		<td>varchar</td>
		<td>15</td>
		<td>Tidak</td>
		<td>Tidak</td>
		<td>-</td>
		<td>Nama Kategori</td>
	</tr>
</table>

- Tabel Admin
<table>
	<tr>
		<th>Nama Field</th>
		<th>Jenis</th>
		<th>Volume</th>
		<th>Laju</th>
		<th>Primary Key</th>
		<th>Constraint Integrity</th>
		<th>Deskripsi</th>
	</tr>
	<tr>
		<td>id_admin</td>
		<td>integer</td>
		<td>3</td>
		<td>Primary Key</td>
		<td>Iya</td>
		<td>Auto_increment</td>
		<td>Identitas admin</td>
	</tr>
	<tr>
		<td>nama_nadmin</td>
		<td>varchar</td>
		<td>50</td>
		<td>Tidak</td>
		<td>Tidak</td>
		<td>-</td>
		<td>Nama Admin</td>
	</tr>
</table>

- Tabel Login
<table>
	<tr>
		<th>Nama Field</th>
		<th>Jenis</th>
		<th>Volume</th>
		<th>Laju</th>
		<th>Primary Key</th>
		<th>Constraint Integrity</th>
		<th>Deskripsi</th>
	</tr>
	<tr>
		<td>id_login</td>
		<td>integer</td>
		<td>3</td>
		<td>Primary Key</td>
		<td>Iya</td>
		<td>Auto_increment</td>
		<td>Identitas login</td>
	</tr>
	<tr>
		<td>username</td>
		<td>varchar</td>
		<td>15</td>
		<td>Tidak</td>
		<td>Tidak</td>
		<td>-</td>
		<td>Username</td>
	</tr>
	<tr>
		<td>password</td>
		<td>varchar</td>
		<td>6</td>
		<td>Tidak</td>
		<td>Tidak</td>
		<td>-</td>
		<td>Password</td>
	</tr>
</table>

**2.2.1 Definisi Domain/Type**

**2.2.2 Conceptual Data Model**

**2.2.3 Physical Data Model**

**2.2.4 Daftar Tabel Aplikasi**

**2.3 Deskripsi Modul**

<table>
	<tr>
		<th>No.</th>
		<th>Nama Modul</th>
		<th>Keterangan</th>
	</tr>
	<tr>
		<td>1.</td>
		<td>Otentikasi</td>
		<td>Modul yang di gunakan untuk vailidasi akses masuk ke sistem</td>
	</tr>
	<tr>
		<td>2.</td>
		<td>Barang</td>
		<td>Modul yang mencakup input, edit, delete dan update semua data barang</td>
	</tr>
	<tr>
		<td>3.</td>
		<td>Supplier</td>
		<td>Modul yang mencakup input, edit, delete dan update semua data supplier</td>
	</tr>
	<tr>
		<td>4.</td>
		<td>Member</td>
		<td>Modul yang mencakup input, edit, delete dan update semua data member</td>
	</tr>
	<tr>
		<td>5.</td>
		<td>Transaksi Pembelian</td>
		<td>Modul yang digunakan untuk mencatat pembelian barang dari supplier</td>
	</tr>
	<tr>
		<td>6.</td>
		<td>Transaksi Penjualan</td>
		<td>Modul yang digunakan untuk menerima transaki dari user</td>
	</tr>
	<tr>
		<td>7.</td>
		<td>Cicilan Pembayaran</td>
		<td>Modul yang digunakan untuk melihat cicilan pembayaran untuk user</td>
	</tr>
	<tr>
		<td>8.</td>
		<td>Laporan Keuntungan</td>
		<td>Modul yang digunakan untuk melihat laporan keuntungan bagi admin</td>
	</tr>
</table>


**3. Penjelasan dekomposisi**

**3.1 Diagram Konteks**

**3.1.1 DFD Level 0**

**3.1.2 DFD Level 1 Prosen ..**

**3.1.3 DFD Level 1 Prosen ..**

**3.1.4 DFD Level 1 Prosen ..**

**3.1.5 DFD Level 1 Prosen ..**

**3.1.6 DFD Level 1 Prosen ..**

**3.1.7 DFD Level 1 Prosen ..**

**3.1.8 DFD Level 1 Prosen ..**

**3.2 Deskripsi Rinci Tabel**

**3.2.1 Data User Admin dan Member**
<table>
	<tr>
		<th>Data</th>
		<th>Keterangan</th>
	</tr>
	<tr>
		<td>NIK</td>
		<td>Digunakan untuk Login</td>
	</tr>
</table>

**3.3 Deskripsi Rinci Modul**

**3.4 Matriks Keturunan**
