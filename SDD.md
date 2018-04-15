
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

**3. Penjelasan dekomposisi**<br>

**3.1 Diagram Konteks**<br>

<img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/Diagram%20konteks.png"><br>

**3.2 DFD Level 0**<br>

<img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/DFD%20level%200.JPG"><br>

**3.3 DFD Level 1**<br>

**3.3.1 DFD Level 1 Data Member**<br>

<img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/DFD%20lvl%201%20Data%20Member.png">

**3.3.2 DFD Level 1 Data Barang**<br>

<img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/DFD%20lvl%201%20Data%20Barang.png">

**3.3.3 DFD Level 1 Data Order**<br>

<img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/DFD%20Level%201%20Data%20Order.jpg">

**3.3.4 DFD Level 1 Data Admin** <br>
<img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/DFD%20lvl1%20data%20admin.png">
</html>

