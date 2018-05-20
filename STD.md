
<html>
<h2 align="center">SOFTWARE TESTING DOCUMENT</h2>
<h3 align="center">APLIKASI KREDIT BARANG KOPERASI KARYAWAN POLITEKNIK NEGERI INDRAMAYU<br>
(AKBAR KOPKAR POLINDRA)</h3>

<h4 align="center">Version 1.0</h4>
<h4 align="center">20 Mei 2018</h4>

<br>
<p align="center"><img src="https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/POLINDRA.png"></p>
<br>

<h4 align="center">Anggota<br>
 1. Nur Inayatun Mahmuda (1603109)<br>
 2. Astri Alisah (1603091)<br>
 3. Muhammad Fauji Al Fariz (1603107)<br>
 4. Sujiyanto (1603112)

</h4>
<h4 align="center">Kelompok 5<br>
D3TI2D</h4>
<h2 align="center">TEKNIK INFORMATIKA<br>
POLITEKNIK NEGERI INDRAMAYU</h2>

<h3 align="center">BAB I<br>PENDAHULUAN</h3>

<h4> 1.1. Tujuan Pembuatan Dokumen</h4>
- Untuk mengidentifikasi dan mengungkapkan sebagai kesalahan sebanyak mungkin dalam perangkat lunak yang diuji.<br>
- Untuk membawa perangkat lunak diuji, setelah memperbaiki kesalahan yang diidentifikasi dan melakukan pengujian ulang, pada tingkat kualitas yang memadai.<br>
- Untuk melakukan tes yang diperlakukan secara efisien dan efektif, dalam keterbatasan penjadwalan. <br>


<h4>1.2. Deskripsi Umum SIstem</h4>
Perangkat lunak yang akan diuji adalah “Aplikasi Kredit Barang Koperasi Karyawan Polindra”. Perangkat lunak ini adalah perangkat lunak yang digunakan untuk melakukan transaksi kredit barang maupun uang di koperasi POLINDRA. Sistem ini diimplementasikan melalui komunikasi dan di media antara User dan admin dengan sistem.


<h4>1.3. Deskripsi Dokumen</h4>
Dalam dokumen ini berisi 3 bagian utama yaitu Pendahuluan, Identifikasi dan Rencana Pengujian, Deskripsi dan Uji Hasil.

<h4>1.4. Daftar Singkatan </h4>

<table>
<tr>
<td>Istilah</td>
<td>Definisi</td>
</tr>
<tr>
<td>Kredit</td>
<td>Melakukan pembayaran dengan cara mengangsur</td>
</tr>
<tr>
<td>Koperasi</td>
<td>Organisasi ekonomi yang dimiliki dan dioperasikan oleh bebeapa orang demi kepentingan bersama.</td>
</tr>
<tr>
<td>User</td>
<td>Pemakai atau pengguna aplikasi</td>
</tr>
<tr>
<td>Admin</td>
<td>Orang yang mengelola web server dari aplikasi</td>
</tr>
<tr>
<td>AKBAR KOPKAR</td>
<td>(Aplikasi Kredit Barang ) merupakan aplikasi yang digunakan untuk kredit barang.</td>
</tr>
<tr>
<td>SDD</td>
<td>Software Design Description merupakan dokumen project software yang berisi tentang deskripsi design software yang akan dirancang/dibuat.</td>
</tr>
<tr>
<td>SPMP</td>
<td>Software Project Manajemen Plan merupakan dokumen projek software yang berisi tentang perancangan pembangunan atau pengembangan software aplikasi secara umum.</td>
</tr>
<tr>
<td>SRS</td>
<td>Software Requirement Specification merupakan dokumen perangkat lunak yang berisi tentang requirement spesifikasi atau spesifikasi yang ada pada perangkat lunak yang akan dibangun atau dirancang.</td>
</tr>
</table>

<h4> 1.5. Dokumen Referensi </h4>

 - http://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0ahUKEwjd7pWs6LvaAhUFto8KHShUDGsQFggoMAA&url=http%3A%2F%2Fwww.san.uri.br%2F~pbetencourt%2FengsoftII%2FIEEE-P1016-d50.PDF&usg=AOvVaw0-Aa9INJSSPZeNBCHHyNms
 - http://www.slideshare.net/rivaldysetiawan7/srs-example-webapp-33986122
 - IEEE Software Engineering Standards Committee, “IEEE Std 830-1998, IEEE  Recommended Practice for Software Requirements Specifications”, October 20, 1998.<br>
 - https://www.google.co.id/url?sa=t&rct=j&q=&esrc=s&source=web&cd=4&ved=0ahUKEwitpsi807jaAhUHqo8KHS0SAMEQFghLMAM&url=http%3A%2F%2Fwww.cse.chalmers.se%2F~feldt%2Fcourses%2Freqeng%2Fexamples%2Fsrs_example_2010_group2.pdf&usg=AOvVaw1sbUrO_cREj3g8sqm8driM<br>
 - https://www.google.co.id/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&ved=0ahUKEwitpsi807jaAhUHqo8KHS0SAMEQFggoMAA&url=https%3A%2F%2Fwww.utdallas.edu%2F~chung%2FRE%2FPresentations07S%2FTeam_1_Doc%2FDocuments%2FSRS4.0.doc&usg=AOvVaw2zaGGnBB9yNttcKsuBifee<br>

<h3 align="center">BAB II <br>LINGKUNGAN PENGUJIAN PERANGKAT LUNAK</h3>

<h4> 2.1 Perangkat Lunak Pengujian</h4>
Perangkat lunak ini diujikan dengan beberapa perangkat lunak lain, yaitu:<br>
- Sistem Operasi Windows 8<br>
- Bahasa pemrograman: PHP<br>
- Database: XAMPP<br>
<h4> 2.2 Perangkat Keras Pengujian</h4>
Perangkat keras yang diperlukan untuk menguji aplikasi AKBAR KOPKAR ini adalah<br>
- Prosessor: Intel Core i3<br>
- Memory: 2GB<br>
- Hardisk : 1 Tera<br>
<h4>2.3 Material Pengujian</h4>
Pada program “Aplikasi Kredit Barang Koperasi Politeknik Negeri Indramayu” ini memudahkan anggota koperasi untuk melakukan peminjaman baik berupa uang dan barang.<br>
<h4>2.4 Sumber Daya Manusia</h4>
Persyaratan sumber daya manusia yang akan terlibat dalam proses pengujian perangkat lunak ini adalah:<br>
- Memaami konsep pemrograman berorientasi objek dalam Bahasa PHP.<br>
- Memahami proses pengujian perangkat lunak berorientasi objek.
- Memahami konsep pemrograman  database XAMPP.<br>
<h4>2.5 Prosedur Umum Pengujian<br>2.5.1. Pengenalan dan Latihan</h4>
Pengujian aplikasi ini hanya diberikan latihan kembali tentang SQL, dan pengenalan lebih lanjut tentang Html dan PHP. Pada dasarnya penguji telah memiliki pengetahuan pengetahuan tentang hal yang disebutkan sebelumnya tetapi latihan pengetahuan tentang hal yang disebutkan sebelumnya tetapi latihan yang diberikan hanya bersifat penyegaran kembali.
<h4>2.5.2 Persiapan Awal</h4>
<h4>2.5.2.1. Persiapan Prosedural</h4>
Pengujian ini dilakukan di luar lingkungan kampus. Dimana pengujian ini dilakukan oleh tim penguji yang telah di tentukan oleh anggota kelompok. Alat yang digunakan 1 buah laptop dengan software yang telah di instalasi.
<h4>2.5.2.2. Persiapan Perangkat Keras</h4>
Perangkat keras yang perlu dipersiapkan adalah sebuah perangkat laptop yang dilengkapi dengan:
- Prosessor: Intel Core i3
- Memory: 2GB
- Hardisk: 1Tera
<h4>2.5.2.3. Persiapan Perangkat Lunak</h4>
Persiapan yang harus dilakukan untuk menyiapkan perangkat lunak untuk diuji di lingkungan sistem operasi Microsoft Windows 8 adalah sebagai berikut:
- Persiapan sistem operasi Microsoft Windows. <br>
- Perangkat lunak yang akan diuji di copy ke sebuah direktori, misalnya C:\XAMPP\htdocs.<br>
- Browser Google Chrome.<br>
- Database di import ke phpMyAdmin (database)<br>
- Sublime atau notepad untuk melihat source code.<br>
<h4>2.5.2.4. Pelaksanaan </h4>
Pelaksanaan pengujian dilakukan dengan mengeksekusi perangkat lunak SPEK dengan mengikuti scenario tertentu yang dibuat berdasarkan scenario yang terdapat pada dokumen SPMP dan SRS.
<h4> Pelaporan Hasil </h4>
 Dokumen hasil uji dari aplikasi ini akan diberikan kepada anggota kelompok dan dievaluasi oleh anggota kelompok lain yang bertindak sebagai klien dari kelompok kami. Sehingga aplikasi mendapatkan umpan balik dalam pengembangan perangkat lunak ini selanjunya.
 
<h3 align="center">BAB III <br>IDENTIFIKASI DAN RENCANA PENGUJIAN</h3>

<table border="1" align="center" width="1000px">
	<tr>
		<td align="center" rowspan="2" width="150px">Kelas Uji</td>
		<td align="center" rowspan="2" width="250px">Butir Uji</td>
		<td align="center" colspan="2">Identifikasi</td>
		<td align="center" rowspan="2" width="130px">Tingkat Pengujian</td>
		<td align="center" rowspan="2">Jenis Pengujian</td>
		<td align="center" rowspan="2">Penguji</td>
	</tr>
	<tr>
		<td width="100px" align="center">SRS/SDD</td>
		<td width="100px" align="center">STD</td>
	</tr>
	<tr>
		<td rowspan="3">Pengujian login admin</td>
		<td>Pengujian login dengan akun yang sudah terdaftar didatabase</td>
		<td align="center">SRS - 2.2.1</td>
		<td align="center">STD - 01</td>
		<td align="center">Pengujian Sistem</td>
		<td align="center">Black Box</td>
		<td rowspan="3" align="center">Nur Inayatun Mahmuda</td>
	</tr>
	<tr>
		<td>Pengujian login dengan akun yang belum terdaftar didatabase</td>
		<td align="center">SRS - 2.2.1</td>
		<td align="center">STD - 02</td>
		<td align="center">Pengujian Sistem</td>
		<td align="center">Black Box</td>
	</tr>
	<tr>
		<td>Pengujian login dengan mengosongkan username dan password</td>
		<td align="center">SRS - 2.2.1</td>
		<td align="center">STD - 03</td>
		<td align="center">Pengujian Sistem</td>
		<td align="center">Black Box</td>
	</tr>	
	<tr>
		<td rowspan="3">Pengujian tambah barang</td>
		<td>Pengujian input data barang dengan data yang lengkap</td>
		<td align="center">SRS - 2.2.1</td>
		<td align="center">STD - 04</td>
		<td align="center">Pengujian Sistem</td>
		<td align="center">Black Box</td>
		<td rowspan="3" align="center">Nur Inayatun Mahmuda</td>
	</tr>
	<tr>
		<td>Pengujian input data barang dengan data kosong</td>
		<td align="center">SRS - 2.2.1</td>
		<td align="center">STD - 05</td>
		<td align="center">Pengujian Sistem</td>
		<td align="center">Black Box</td>
	</tr>
	<tr>
		<td>Pengujian input data barang dengan data yang sudah terdapat dalam database</td>
		<td align="center">SRS - 2.2.1</td>
		<td align="center">STD - 06</td>
		<td align="center">Pengujian Sistem</td>
		<td align="center">Black Box</td>
	</tr>
	<tr>
		<td rowspan="3">Pengujian tambah data member</td>
		<td>Pengujian input data member dengan data yang lengkap</td>
		<td align="center">SRS - 2.2.1</td>
		<td align="center">STD - 07</td>
		<td align="center">Pengujian Sistem</td>
		<td align="center">Black Box</td>
		<td rowspan="3" align="center">Astri Alisah</td>
	</tr>
	<tr>
		<td>Pengujian input data member dengan data kosong</td>
		<td align="center">SRS - 2.2.1</td>
		<td align="center">STD - 08</td>
		<td align="center">Pengujian Sistem</td>
		<td align="center">Black Box</td>
	</tr>
	<tr>
		<td>Pengujian input data member dengan data yang sudah terdapat dalam database</td>
		<td align="center">SRS - 2.2.1</td>
		<td align="center">STD - 09</td>
		<td align="center">Pengujian Sistem</td>
		<td align="center">Black Box</td>
	</tr>
	<tr>
		<td rowspan="3">Pengujian tambah data supplier</td>
		<td>Pengujian input data supplier dengan data yang lengkap</td>
		<td align="center">SRS - 2.2.1</td>
		<td align="center">STD - 10</td>
		<td align="center">Pengujian Sistem</td>
		<td align="center">Black Box</td>
		<td rowspan="3" align="center">Astri Alisah</td>
	</tr>
	<tr>
		<td>Pengujian input data supplier dengan data kosong</td>
		<td align="center">SRS - 2.2.1</td>
		<td align="center">STD - 11</td>
		<td align="center">Pengujian Sistem</td>
		<td align="center">Black Box</td>
	</tr>
	<tr>
		<td>Pengujian input data supplier dengan data yang sudah terdapat dalam database</td>
		<td align="center">SRS - 2.2.1</td>
		<td align="center">STD - 12</td>
		<td align="center">Pengujian Sistem</td>
		<td align="center">Black Box</td>
	</tr>
	<tr>
		<td rowspan="3">Pengujian register</td>
		<td>Pengujian registrasi dengan data yang lengkap</td>
		<td align="center">SRS - 2.2.2</td>
		<td align="center">STD - 13</td>
		<td align="center">Pengujian Sistem</td>
		<td align="center">Black Box</td>
		<td rowspan="3" align="center">M. Fauji Al Faris</td>
	</tr>
	<tr>
		<td>Pengujian registrasi dengan data yang kosong</td>
		<td align="center">SRS - 2.2.2</td>
		<td align="center">STD - 14</td>
		<td align="center">Pengujian Sistem</td>
		<td align="center">Black Box</td>
	</tr>
	<tr>
		<td>Pengujian registrasi dengan data yang sudah teregistrasi</td>
		<td align="center">SRS - 2.2.2</td>
		<td align="center">STD - 15</td>
		<td align="center">Pengujian Sistem</td>
		<td align="center">Black Box</td>
	</tr>
	<tr>
		<td rowspan="3">Pengujian login member</td>
		<td>Pengujian login dengan akun yang sudah terdaftar didatabase</td>
		<td align="center">SRS - 2.2.2</td>
		<td align="center">STD - 16</td>
		<td align="center">Pengujian Sistem</td>
		<td align="center">Black Box</td>
		<td rowspan="3" align="center">M. Fauji Al Faris</td>
	</tr>
	<tr>
		<td>Pengujian login dengan akun yang belum terdaftar didatabase</td>
		<td align="center">SRS - 2.2.2</td>
		<td align="center">STD - 17</td>
		<td align="center">Pengujian Sistem</td>
		<td align="center">Black Box</td>
	</tr>
	<tr>
		<td>Pengujian login dengan mengosongkan username dan password</td>
		<td align="center">SRS - 2.2.2</td>
		<td align="center">STD - 18</td>
		<td align="center">Pengujian Sistem</td>
		<td align="center">Black Box</td>
	</tr>
	<tr>
		<td rowspan="3">Pengujian transaksi pembelian barang dari member</td>
		<td>Pengujian mengisis form pembelian dengan data yang sesuai</td>
		<td align="center">SRS - 2.2.2</td>
		<td align="center">STD - 19</td>
		<td align="center">Pengujian Sistem</td>
		<td align="center">Black Box</td>
		<td rowspan="3" align="center">Sujiyanto</td>
	</tr>
	<tr>
		<td>Pengujian mengisi form pembelian dengan data kosong</td>
		<td align="center">SRS - 2.2.2</td>
		<td align="center">STD - 20</td>
		<td align="center">Pengujian Sistem</td>
		<td align="center">Black Box</td>
	</tr>
	<tr>
		<td>Pengujian mengisi form pembelian dengan data yang sama</td>
		<td align="center">SRS - 2.2.2</td>
		<td align="center">STD - 21</td>
		<td align="center">Pengujian Sistem</td>
		<td align="center">Black Box</td>
	</tr>
</table>

<h3 align="center">BAB IV<br>DESKRIPSI HASIL UJI</h3>

<table border="1" align="center" width="1000px">
	<tr>
		<td>Identifikasi</td>
		<td colspan="3">STD - 01</td>
	</tr>
	<tr>
		<td>Nama Butir Uji</td>
		<td colspan="3">Pengujian login dengan akun yang sudah terdaftar didatabase</td>
	</tr>
	<tr>
		<td>Tujuan</td>
		<td colspan="3">Memeriksa apakah user bisa masuk ke sistem aplikasi</td>
	</tr>
	<tr>
		<td>Kondisi Awal</td>
		<td colspan="3">Membuka halaman login pada website</td>
	</tr>
	<tr>
		<td>Tanggal pengujian</td>
		<td colspan="3">19 - 05 - 2018</td>
	</tr>
	<tr>
		<td>Penguji</td>
		<td colspan="3">Nur Inayatun Mahmuda</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Skenario</td>
	</tr>
	<tr>
		<td colspan="4">
		1. Masukan Username<br>
		2. Masukan Password<br>
		3. Klik Login
		</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Hasil</td>
	</tr>
	<tr>
		<td align="center" width="250px">Data yang diberikan</td>
		<td align="center" width="250px">Yang diharapkan</td>
		<td align="center" width="250px">Pengamatan</td>
		<td align="center" width="250px">Kesimpulan</td>
	</tr>
	<tr>
		<td>
		Username : admin <br>
		Password : admin
		</td>
		<td>Masuk ke halaman dashboard admin</td>
		<td>Username dan password harus sesuai dengan akun yang telah terdaftar di database</td>
		<td>Berhasil masuk ke halaman dashboard admin</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Catatan</td>
	</tr>
	<tr>
		<td colspan="4"><br><br></td>
	</tr>
</table>

<br><br>

<!-- ===================================================================================================================================================== -->

<table border="1" align="center" width="1000px">
	<tr>
		<td>Identifikasi</td>
		<td colspan="3">STD - 02</td>
	</tr>
	<tr>
		<td>Nama Butir Uji</td>
		<td colspan="3">Pengujian login dengan akun yang belum terdaftar didatabase</td>
	</tr>
	<tr>
		<td>Tujuan</td>
		<td colspan="3">Memeriksa apakah user bisa masuk ke sistem aplikasi</td>
	</tr>
	<tr>
		<td>Kondisi Awal</td>
		<td colspan="3">Membuka halaman login pada website</td>
	</tr>
	<tr>
		<td>Tanggal pengujian</td>
		<td colspan="3">19 - 05 - 2018</td>
	</tr>
	<tr>
		<td>Penguji</td>
		<td colspan="3">Nur Inayatun Mahmuda</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Skenario</td>
	</tr>
	<tr>
		<td colspan="4">
		1. Masukan Username<br>
		2. Masukan Password<br>
		3. Klik Login
		</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Hasil</td>
	</tr>
	<tr>
		<td align="center" width="250px">Data yang diberikan</td>
		<td align="center" width="250px">Yang diharapkan</td>
		<td align="center" width="250px">Pengamatan</td>
		<td align="center" width="250px">Kesimpulan</td>
	</tr>
	<tr>
		<td>
		Username : adminah <br>
		Password : adminah
		</td>
		<td>Tidak dapat masuk ke halaman dashboard admin</td>
		<td>Username dan password harus sesuai dengan akun yang telah terdaftar di database</td>
		<td>Gagal masuk ke halaman dashboard admin</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Catatan</td>
	</tr>
	<tr>
		<td colspan="4"><br><br></td>
	</tr>
</table>

<br><br>

<!-- ===================================================================================================================================================== -->

<table border="1" align="center" width="1000px">
	<tr>
		<td>Identifikasi</td>
		<td colspan="3">STD - 03</td>
	</tr>
	<tr>
		<td>Nama Butir Uji</td>
		<td colspan="3">Pengujian login dengan mengosongkan username dan password</td>
	</tr>
	<tr>
		<td>Tujuan</td>
		<td colspan="3">Memeriksa apakah user bisa masuk ke sistem aplikasi</td>
	</tr>
	<tr>
		<td>Kondisi Awal</td>
		<td colspan="3">Membuka halaman login pada website</td>
	</tr>
	<tr>
		<td>Tanggal pengujian</td>
		<td colspan="3">19 - 05 - 2018</td>
	</tr>
	<tr>
		<td>Penguji</td>
		<td colspan="3">Nur Inayatun Mahmuda</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Skenario</td>
	</tr>
	<tr>
		<td colspan="4">
		1. Masukan Username<br>
		2. Masukan Password<br>
		3. Klik Login
		</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Hasil</td>
	</tr>
	<tr>
		<td align="center" width="250px">Data yang diberikan</td>
		<td align="center" width="250px">Yang diharapkan</td>
		<td align="center" width="250px">Pengamatan</td>
		<td align="center" width="250px">Kesimpulan</td>
	</tr>
	<tr>
		<td>
		Username :  <br>
		Password : 
		</td>
		<td>Tidak dapat masuk ke halaman dashboard admin</td>
		<td>Username dan password harus dilengkapi</td>
		<td>Gagal masuk ke halaman dashboard admin</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Catatan</td>
	</tr>
	<tr>
		<td colspan="4"><br><br></td>
	</tr>
</table>

<br><br>

<!-- ===================================================================================================================================================== -->

<table border="1" align="center" width="1000px">
	<tr>
		<td>Identifikasi</td>
		<td colspan="3">STD - 04</td>
	</tr>
	<tr>
		<td>Nama Butir Uji</td>
		<td colspan="3">Pengujian input data barang dengan data yang lengkap</td>
	</tr>
	<tr>
		<td>Tujuan</td>
		<td colspan="3">Memeriksa apakah data baru yang ditambahkan terekam ke tabel barang</td>
	</tr>
	<tr>
		<td>Kondisi Awal</td>
		<td colspan="3">- Halaman Data Barang <br> - Masuk ke halaman form tambah barang</td>
	</tr>
	<tr>
		<td>Tanggal pengujian</td>
		<td colspan="3">19 - 05 - 2018</td>
	</tr>
	<tr>
		<td>Penguji</td>
		<td colspan="3">Nur Inayatun Mahmuda</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Skenario</td>
	</tr>
	<tr>
		<td colspan="4">
		1. Isi semua data pada form tambah barang<br>
		3. Klik tombol simpan jika data sudah diinputkan
		</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Hasil</td>
	</tr>
	<tr>
		<td align="center" width="250px">Data yang diberikan</td>
		<td align="center" width="250px">Yang diharapkan</td>
		<td align="center" width="250px">Pengamatan</td>
		<td align="center" width="250px">Kesimpulan</td>
	</tr>
	<tr>
		<td>
		ID Barang 		: Tidak Perlu Diisi <br>
		Nama Barang 	: Samsung WW65J3033LW Mesin Cuci 6.5 Kg Front Loading <br>
		Supplier 		: -- Pilih Supplier -- <br>
		Harga			: 3899000 <br>
		Uang muka 		: 399000 <br>
		Stok			: 1 <br>
		Satuan			: Unit <br>
		Keterangan		: PO 
		</td>
		<td>Data yang telah diinputkan berhasil masuk ke tabel Data Barang</td>
		<td>Semua data yang diinputkan harus sesuai dengan format yang ditentukan</td>
		<td>Berhasil menyimpan data</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Catatan</td>
	</tr>
	<tr>
		<td colspan="4"><br><br></td>
	</tr>
</table>

<br><br>

<!-- ===================================================================================================================================================== -->

<table border="1" align="center" width="1000px">
	<tr>
		<td>Identifikasi</td>
		<td colspan="3">STD - 05</td>
	</tr>
	<tr>
		<td>Nama Butir Uji</td>
		<td colspan="3">Pengujian input data barang dengan data kosong</td>
	</tr>
	<tr>
		<td>Tujuan</td>
		<td colspan="3">Memeriksa apakah data baru yang ditambahkan terekam ke tabel barang</td>
	</tr>
	<tr>
		<td>Kondisi Awal</td>
		<td colspan="3">- Halaman Data Barang <br> - Masuk ke halaman form tambah barang</td>
	</tr>
	<tr>
		<td>Tanggal pengujian</td>
		<td colspan="3">19 - 05 - 2018</td>
	</tr>
	<tr>
		<td>Penguji</td>
		<td colspan="3">Nur Inayatun Mahmuda</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Skenario</td>
	</tr>
	<tr>
		<td colspan="4">
		1. Isi semua data pada form tambah barang<br>
		3. Klik tombol simpan jika data sudah diinputkan
		</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Hasil</td>
	</tr>
	<tr>
		<td align="center" width="250px">Data yang diberikan</td>
		<td align="center" width="250px">Yang diharapkan</td>
		<td align="center" width="250px">Pengamatan</td>
		<td align="center" width="250px">Kesimpulan</td>
	</tr>
	<tr>
		<td>
		ID Barang 		: Tidak Perlu Diisi <br>
		Nama Barang 	: <br>
		Supplier 		: <br>
		Harga			: <br>
		Uang muka 		: <br>
		Stok			: <br>
		Satuan			: <br>
		Keterangan		:  
		</td>
		<td>Muncul pesan error dan memberikan keterangan bahwa data harus dilengkapi</td>
		<td>Semua data yang diinputkan harus dilengkapi</td>
		<td>Gagal menyimpan data</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Catatan</td>
	</tr>
	<tr>
		<td colspan="4"><br><br></td>
	</tr>
</table>

<br><br>

<!-- ===================================================================================================================================================== -->

<table border="1" align="center" width="1000px">
	<tr>
		<td>Identifikasi</td>
		<td colspan="3">STD - 06</td>
	</tr>
	<tr>
		<td>Nama Butir Uji</td>
		<td colspan="3">Pengujian input data barang dengan data yang sudah terdapat dalam database</td>
	</tr>
	<tr>
		<td>Tujuan</td>
		<td colspan="3">Memeriksa apakah data baru yang ditambahkan terekam ke tabel barang</td>
	</tr>
	<tr>
		<td>Kondisi Awal</td>
		<td colspan="3">- Halaman Data Barang <br> - Masuk ke halaman form tambah barang</td>
	</tr>
	<tr>
		<td>Tanggal pengujian</td>
		<td colspan="3">19 - 05 - 2018</td>
	</tr>
	<tr>
		<td>Penguji</td>
		<td colspan="3">Nur Inayatun Mahmuda</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Skenario</td>
	</tr>
	<tr>
		<td colspan="4">
		1. Isi semua data pada form tambah barang<br>
		3. Klik tombol simpan jika data sudah diinputkan
		</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Hasil</td>
	</tr>
	<tr>
		<td align="center" width="250px">Data yang diberikan</td>
		<td align="center" width="250px">Yang diharapkan</td>
		<td align="center" width="250px">Pengamatan</td>
		<td align="center" width="250px">Kesimpulan</td>
	</tr>
	<tr>
		<td>
		ID Barang 		: Tidak Perlu Diisi <br>
		Nama Barang 	: Samsung WW65J3033LW Mesin Cuci 6.5 Kg Front Loading <br>
		Supplier 		: -- Pilih Supplier -- <br>
		Harga			: 3899000 <br>
		Uang muka 		: 399000 <br>
		Stok			: 1 <br>
		Satuan			: Unit <br>
		Keterangan		: PO 
		</td>
		<td>Data yang telah diinputkan gagal masuk ke tabel Data Barang</td>
		<td>Semua data yang diinputkan tidak boleh sama dengan data yang telah terdaftar sebelumnya</td>
		<td>Gagal menyimpan data</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Catatan</td>
	</tr>
	<tr>
		<td colspan="4"><br><br></td>
	</tr>
</table>

<br><br>

<!-- ===================================================================================================================================================== -->

<table border="1" align="center" width="1000px">
	<tr>
		<td>Identifikasi</td>
		<td colspan="3">STD - 07</td>
	</tr>
	<tr>
		<td>Nama Butir Uji</td>
		<td colspan="3">Pengujian input data member dengan data yang lengkap</td>
	</tr>
	<tr>
		<td>Tujuan</td>
		<td colspan="3">Memeriksa apakah data baru yang ditambahkan terekam ke tabel member</td>
	</tr>
	<tr>
		<td>Kondisi Awal</td>
		<td colspan="3">- Halaman Data Member <br> - Masuk ke halaman form tambah member</td>
	</tr>
	<tr>
		<td>Tanggal pengujian</td>
		<td colspan="3">19 - 05 - 2018</td>
	</tr>
	<tr>
		<td>Penguji</td>
		<td colspan="3">Astri Alisah</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Skenario</td>
	</tr>
	<tr>
		<td colspan="4">
		1. Isi semua data pada form tambah member<br>
		3. Klik tombol simpan jika data sudah diinputkan
		</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Hasil</td>
	</tr>
	<tr>
		<td align="center" width="250px">Data yang diberikan</td>
		<td align="center" width="250px">Yang diharapkan</td>
		<td align="center" width="250px">Pengamatan</td>
		<td align="center" width="250px">Kesimpulan</td>
	</tr>
	<tr>
		<td>
		ID Member 	: Tidak perlu diisi <br>
		NIK 		: 1603091 <br>
		Nama 		: Astri Alisah <br>
		No. Hp 		: 089123456789 <br>
		Email		: astrialisah@gmail.com <br>
		Alamat		: Indramayu <br>
		Username 	: astri <br>
		Password 	: 123
		</td>
		<td>Data yang telah diinputkan berhasil masuk ke tabel Data Member</td>
		<td>Semua data yang diinputkan harus sesuai dengan format yang ditentukan</td>
		<td>Berhasil menyimpan data</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Catatan</td>
	</tr>
	<tr>
		<td colspan="4"><br><br></td>
	</tr>
</table>

<br><br>

<!-- ===================================================================================================================================================== -->

<table border="1" align="center" width="1000px">
	<tr>
		<td>Identifikasi</td>
		<td colspan="3">STD - 08</td>
	</tr>
	<tr>
		<td>Nama Butir Uji</td>
		<td colspan="3">Pengujian input data member dengan data kosong</td>
	</tr>
	<tr>
		<td>Tujuan</td>
		<td colspan="3">Memeriksa apakah data baru yang ditambahkan terekam ke tabel member</td>
	</tr>
	<tr>
		<td>Kondisi Awal</td>
		<td colspan="3">- Halaman Data Member <br> - Masuk ke halaman form tambah member</td>
	</tr>
	<tr>
		<td>Tanggal pengujian</td>
		<td colspan="3">19 - 05 - 2018</td>
	</tr>
	<tr>
		<td>Penguji</td>
		<td colspan="3">Astri Alisah</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Skenario</td>
	</tr>
	<tr>
		<td colspan="4">
		1. Isi semua data pada form tambah member<br>
		3. Klik tombol simpan jika data sudah diinputkan
		</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Hasil</td>
	</tr>
	<tr>
		<td align="center" width="250px">Data yang diberikan</td>
		<td align="center" width="250px">Yang diharapkan</td>
		<td align="center" width="250px">Pengamatan</td>
		<td align="center" width="250px">Kesimpulan</td>
	</tr>
	<tr>
		<td>
		ID Member 	: Tidak perlu diisi <br>
		NIK 		: <br>
		Nama 		: <br>
		No. Hp 		: <br>
		Email		: <br>
		Alamat		: <br>
		Username 	: <br>
		Password 	: 
		</td>
		<td>Muncul pesan error dan memberikan keterangan bahwa data harus dilengkapi</td>
		<td>Semua data yang diinputkan harus diisi sesuai dengan format yang ditentukan</td>
		<td>Gagal menyimpan data</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Catatan</td>
	</tr>
	<tr>
		<td colspan="4"><br><br></td>
	</tr>
</table>

<br><br>

<!-- ===================================================================================================================================================== -->

<table border="1" align="center" width="1000px">
	<tr>
		<td>Identifikasi</td>
		<td colspan="3">STD - 09</td>
	</tr>
	<tr>
		<td>Nama Butir Uji</td>
		<td colspan="3">Pengujian input data member dengan data yang sudah terdapat dalam database</td>
	</tr>
	<tr>
		<td>Tujuan</td>
		<td colspan="3">Memeriksa apakah data baru yang ditambahkan terekam ke tabel member</td>
	</tr>
	<tr>
		<td>Kondisi Awal</td>
		<td colspan="3">- Halaman Data Member <br> - Masuk ke halaman form tambah member</td>
	</tr>
	<tr>
		<td>Tanggal pengujian</td>
		<td colspan="3">19 - 05 - 2018</td>
	</tr>
	<tr>
		<td>Penguji</td>
		<td colspan="3">Astri Alisah</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Skenario</td>
	</tr>
	<tr>
		<td colspan="4">
		1. Isi semua data pada form tambah member<br>
		3. Klik tombol simpan jika data sudah diinputkan
		</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Hasil</td>
	</tr>
	<tr>
		<td align="center" width="250px">Data yang diberikan</td>
		<td align="center" width="250px">Yang diharapkan</td>
		<td align="center" width="250px">Pengamatan</td>
		<td align="center" width="250px">Kesimpulan</td>
	</tr>
	<tr>
		<td>
		ID Member 	: Tidak perlu diisi <br>
		NIK 		: 1603091 <br>
		Nama 		: Astri Alisah <br>
		No. Hp 		: 089123456789 <br>
		Email		: astrialisah@gmail.com <br>
		Alamat		: Indramayu <br>
		Username 	: astri <br>
		Password 	: 123
		</td>
		<td>Data yang telah diinputkan gagal masuk ke tabel Data Member</td>
		<td>Semua data yang diinputkan tidak boleh sama dengan data yang telah terdaftar sebelumnya</td>
		<td>Gagal menyimpan data</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Catatan</td>
	</tr>
	<tr>
		<td colspan="4"><br><br></td>
	</tr>
</table>

<br><br>

<!-- ===================================================================================================================================================== -->

<table border="1" align="center" width="1000px">
	<tr>
		<td>Identifikasi</td>
		<td colspan="3">STD - 10</td>
	</tr>
	<tr>
		<td>Nama Butir Uji</td>
		<td colspan="3">Pengujian input data supplier dengan data yang lengkap</td>
	</tr>
	<tr>
		<td>Tujuan</td>
		<td colspan="3">Memeriksa apakah data baru yang ditambahkan terekam ke tabel supplier</td>
	</tr>
	<tr>
		<td>Kondisi Awal</td>
		<td colspan="3">- Halaman Data Supplier <br> - Masuk ke halaman form tambah supplier</td>
	</tr>
	<tr>
		<td>Tanggal pengujian</td>
		<td colspan="3">19 - 05 - 2018</td>
	</tr>
	<tr>
		<td>Penguji</td>
		<td colspan="3">Astri Alisah</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Skenario</td>
	</tr>
	<tr>
		<td colspan="4">
		1. Isi semua data pada form tambah supplier<br>
		3. Klik tombol simpan jika data sudah diinputkan
		</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Hasil</td>
	</tr>
	<tr>
		<td align="center" width="250px">Data yang diberikan</td>
		<td align="center" width="250px">Yang diharapkan</td>
		<td align="center" width="250px">Pengamatan</td>
		<td align="center" width="250px">Kesimpulan</td>
	</tr>
	<tr>
		<td>
		ID Supplier 	: Tidak perlu diisi <br>
		Nama 			: PT Samsung Electronics Indonesia <br>
		No. Telp 		: (021) 89837114 <br>
		Alamat 			: Jl. Jababeka Raya Blok F. 29 No.31, Harja Mekar, Cikarang Utara, Bekasi, Jawa Barat 17530 
		</td>
		<td>Data yang telah diinputkan berhasil masuk ke tabel Data Supplier</td>
		<td>Semua data yang diinputkan harus sesuai dengan format yang ditentukan</td>
		<td>Berhasil menyimpan data</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Catatan</td>
	</tr>
	<tr>
		<td colspan="4"><br><br></td>
	</tr>
</table>

<br><br>

<!-- ===================================================================================================================================================== -->

<table border="1" align="center" width="1000px">
	<tr>
		<td>Identifikasi</td>
		<td colspan="3">STD - 11</td>
	</tr>
	<tr>
		<td>Nama Butir Uji</td>
		<td colspan="3">Pengujian input data supplier dengan data kosong</td>
	</tr>
	<tr>
		<td>Tujuan</td>
		<td colspan="3">Memeriksa apakah data baru yang ditambahkan terekam ke tabel supplier</td>
	</tr>
	<tr>
		<td>Kondisi Awal</td>
		<td colspan="3">- Halaman Data Supplier <br> - Masuk ke halaman form tambah supplier</td>
	</tr>
	<tr>
		<td>Tanggal pengujian</td>
		<td colspan="3">19 - 05 - 2018</td>
	</tr>
	<tr>
		<td>Penguji</td>
		<td colspan="3">Astri Alisah</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Skenario</td>
	</tr>
	<tr>
		<td colspan="4">
		1. Isi semua data pada form tambah supplier<br>
		3. Klik tombol simpan jika data sudah diinputkan
		</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Hasil</td>
	</tr>
	<tr>
		<td align="center" width="250px">Data yang diberikan</td>
		<td align="center" width="250px">Yang diharapkan</td>
		<td align="center" width="250px">Pengamatan</td>
		<td align="center" width="250px">Kesimpulan</td>
	</tr>
	<tr>
		<td>
		ID Supplier 	: Tidak perlu diisi <br>
		Nama 			: <br>
		No. Telp 		: <br>
		Alamat 			:  
		</td>
		<td>Muncul pesan error dan memberikan keterangan bahwa data harus dilengkapi</td>
		<td>Semua data yang diinputkan harus diisi sesuai dengan format yang ditentukan</td>
		<td>Gagal menyimpan data</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Catatan</td>
	</tr>
	<tr>
		<td colspan="4"><br><br></td>
	</tr>
</table>

<br><br>

<!-- ===================================================================================================================================================== -->

<table border="1" align="center" width="1000px">
	<tr>
		<td>Identifikasi</td>
		<td colspan="3">STD - 12</td>
	</tr>
	<tr>
		<td>Nama Butir Uji</td>
		<td colspan="3">Pengujian input data supplier dengan data yang sudah terdapat dalam database</td>
	</tr>
	<tr>
		<td>Tujuan</td>
		<td colspan="3">Memeriksa apakah data baru yang ditambahkan terekam ke tabel supplier</td>
	</tr>
	<tr>
		<td>Kondisi Awal</td>
		<td colspan="3">- Halaman Data Supplier <br> - Masuk ke halaman form tambah supplier</td>
	</tr>
	<tr>
		<td>Tanggal pengujian</td>
		<td colspan="3">19 - 05 - 2018</td>
	</tr>
	<tr>
		<td>Penguji</td>
		<td colspan="3">Astri Alisah</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Skenario</td>
	</tr>
	<tr>
		<td colspan="4">
		1. Isi semua data pada form tambah supplier<br>
		3. Klik tombol simpan jika data sudah diinputkan
		</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Hasil</td>
	</tr>
	<tr>
		<td align="center" width="250px">Data yang diberikan</td>
		<td align="center" width="250px">Yang diharapkan</td>
		<td align="center" width="250px">Pengamatan</td>
		<td align="center" width="250px">Kesimpulan</td>
	</tr>
	<tr>
		<td>
		ID Supplier 	: Tidak perlu diisi <br>
		Nama 			: PT Samsung Electronics Indonesia <br>
		No. Telp 		: (021) 89837114 <br>
		Alamat 			: Jl. Jababeka Raya Blok F. 29 No.31, Harja Mekar, Cikarang Utara, Bekasi, Jawa Barat 17530 
		</td>
		<td>Data yang telah diinputkan gagal masuk ke tabel Data Supplier</td>
		<td>Semua data yang diinputkan tidak boleh sama dengan data yang telah terdaftar sebelumnya</td>
		<td>Gagal menyimpan data</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Catatan</td>
	</tr>
	<tr>
		<td colspan="4"><br><br></td>
	</tr>
</table>

<br><br>

<!-- ===================================================================================================================================================== -->

<table border="1" align="center" width="1000px">
	<tr>
		<td>Identifikasi</td>
		<td colspan="3">STD - 13</td>
	</tr>
	<tr>
		<td>Nama Butir Uji</td>
		<td colspan="3">Pengujian registrasi member dengan data yang lengkap</td>
	</tr>
	<tr>
		<td>Tujuan</td>
		<td colspan="3">Memeriksa apakah registrasi terekam ke tabel member</td>
	</tr>
	<tr>
		<td>Kondisi Awal</td>
		<td colspan="3">- Halaman Login <br> - Masuk ke halaman Create Acount</td>
	</tr>
	<tr>
		<td>Tanggal pengujian</td>
		<td colspan="3">19 - 05 - 2018</td>
	</tr>
	<tr>
		<td>Penguji</td>
		<td colspan="3">M. Fauji Al Faris</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Skenario</td>
	</tr>
	<tr>
		<td colspan="4">
		1. Isi semua data pada form registrasi member<br>
		3. Klik tombol register jika data sudah diinputkan
		</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Hasil</td>
	</tr>
	<tr>
		<td align="center" width="250px">Data yang diberikan</td>
		<td align="center" width="250px">Yang diharapkan</td>
		<td align="center" width="250px">Pengamatan</td>
		<td align="center" width="250px">Kesimpulan</td>
	</tr>
	<tr>
		<td>
		NIK 		: 1603107 <br>
		Nama 		: M. Fauji Al Faris <br>
		No. Hp 		: 081987654321 <br>
		Email		: alfaris@gmail.com <br>
		Alamat		: Indramayu <br>
		Username 	: faris <br>
		Password 	: qwe
		</td>
		<td>Data yang telah diinputkan berhasil masuk ke tabel Data Member</td>
		<td>Semua data yang diinputkan harus sesuai dengan format yang ditentukan</td>
		<td>Berhasil melakukan registrasi</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Catatan</td>
	</tr>
	<tr>
		<td colspan="4"><br><br></td>
	</tr>
</table>

<br><br>

<!-- ===================================================================================================================================================== -->

<table border="1" align="center" width="1000px">
	<tr>
		<td>Identifikasi</td>
		<td colspan="3">STD - 14</td>
	</tr>
	<tr>
		<td>Nama Butir Uji</td>
		<td colspan="3">Pengujian registrasi dengan data yang kosong</td>
	</tr>
	<tr>
		<td>Tujuan</td>
		<td colspan="3">Memeriksa apakah registrasi terekam ke tabel member</td>
	</tr>
	<tr>
		<td>Kondisi Awal</td>
		<td colspan="3">- Halaman Login <br> - Masuk ke halaman Create Acount</td>
	</tr>
	<tr>
		<td>Tanggal pengujian</td>
		<td colspan="3">19 - 05 - 2018</td>
	</tr>
	<tr>
		<td>Penguji</td>
		<td colspan="3">M. Fauji Al Faris</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Skenario</td>
	</tr>
	<tr>
		<td colspan="4">
		1. Isi semua data pada form registrasi member<br>
		3. Klik tombol register jika data sudah diinputkan
		</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Hasil</td>
	</tr>
	<tr>
		<td align="center" width="250px">Data yang diberikan</td>
		<td align="center" width="250px">Yang diharapkan</td>
		<td align="center" width="250px">Pengamatan</td>
		<td align="center" width="250px">Kesimpulan</td>
	</tr>
	<tr>
		<td>
		NIK 		: <br>
		Nama 		: <br>
		No. Hp 		: <br>
		Email		: <br>
		Alamat		: <br>
		Username 	: <br>
		Password 	: 
		</td>
		<td>Muncul pesan error dan memberikan keterangan bahwa data harus dilengkapi</td>
		<td>Semua data yang diinputkan harus diisi sesuai dengan format yang ditentukan</td>
		<td>Gagal registrasi</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Catatan</td>
	</tr>
	<tr>
		<td colspan="4"><br><br></td>
	</tr>
</table>

<br><br>

<!-- ===================================================================================================================================================== -->

<table border="1" align="center" width="1000px">
	<tr>
		<td>Identifikasi</td>
		<td colspan="3">STD - 15</td>
	</tr>
	<tr>
		<td>Nama Butir Uji</td>
		<td colspan="3">Pengujian registrasi dengan data yang sudah teregistrasi</td>
	</tr>
	<tr>
		<td>Tujuan</td>
		<td colspan="3">Memeriksa apakah registrasi terekam ke tabel member</td>
	</tr>
	<tr>
		<td>Kondisi Awal</td>
		<td colspan="3">- Halaman Login <br> - Masuk ke halaman Create Acount</td>
	</tr>
	<tr>
		<td>Tanggal pengujian</td>
		<td colspan="3">19 - 05 - 2018</td>
	</tr>
	<tr>
		<td>Penguji</td>
		<td colspan="3">M. Fauji Al Faris</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Skenario</td>
	</tr>
	<tr>
		<td colspan="4">
		1. Isi semua data pada form registrasi member<br>
		3. Klik tombol register jika data sudah diinputkan
		</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Hasil</td>
	</tr>
	<tr>
		<td align="center" width="250px">Data yang diberikan</td>
		<td align="center" width="250px">Yang diharapkan</td>
		<td align="center" width="250px">Pengamatan</td>
		<td align="center" width="250px">Kesimpulan</td>
	</tr>
	<tr>
		<td>
		NIK 		: 1603107 <br>
		Nama 		: M. Fauji Al Faris <br>
		No. Hp 		: 081987654321 <br>
		Email		: alfaris@gmail.com <br>
		Alamat		: Indramayu <br>
		Username 	: faris <br>
		Password 	: qwe
		</td>
		<td>Data yang telah diinputkan gagal masuk ke tabel Data Member</td>
		<td>Semua data yang diinputkan tidak boleh sama dengan data yang telah teregistrasi</td>
		<td>Gagal registrasi</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Catatan</td>
	</tr>
	<tr>
		<td colspan="4"><br><br></td>
	</tr>
</table>

<br><br>

<!-- ===================================================================================================================================================== -->

<table border="1" align="center" width="1000px">
	<tr>
		<td>Identifikasi</td>
		<td colspan="3">STD - 16</td>
	</tr>
	<tr>
		<td>Nama Butir Uji</td>
		<td colspan="3">Pengujian login dengan akun yang sudah terdaftar didatabase</td>
	</tr>
	<tr>
		<td>Tujuan</td>
		<td colspan="3">Memeriksa apakah user bisa masuk ke sistem aplikasi</td>
	</tr>
	<tr>
		<td>Kondisi Awal</td>
		<td colspan="3">Membuka halaman login pada website</td>
	</tr>
	<tr>
		<td>Tanggal pengujian</td>
		<td colspan="3">19 - 05 - 2018</td>
	</tr>
	<tr>
		<td>Penguji</td>
		<td colspan="3">M. Fauji Al Faris</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Skenario</td>
	</tr>
	<tr>
		<td colspan="4">
		1. Masukan Username<br>
		2. Masukan Password<br>
		3. Klik Login
		</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Hasil</td>
	</tr>
	<tr>
		<td align="center" width="250px">Data yang diberikan</td>
		<td align="center" width="250px">Yang diharapkan</td>
		<td align="center" width="250px">Pengamatan</td>
		<td align="center" width="250px">Kesimpulan</td>
	</tr>
	<tr>
		<td>
		Username : faris <br>
		Password : qwe
		</td>
		<td>Masuk ke halaman dashboard member</td>
		<td>Username dan password harus sesuai dengan akun yang telah terdaftar di database</td>
		<td>Berhasil masuk ke halaman dashboard member</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Catatan</td>
	</tr>
	<tr>
		<td colspan="4"><br><br></td>
	</tr>
</table>

<br><br>

<!-- ===================================================================================================================================================== -->

<table border="1" align="center" width="1000px">
	<tr>
		<td>Identifikasi</td>
		<td colspan="3">STD - 17</td>
	</tr>
	<tr>
		<td>Nama Butir Uji</td>
		<td colspan="3">Pengujian login dengan akun yang belum terdaftar didatabase</td>
	</tr>
	<tr>
		<td>Tujuan</td>
		<td colspan="3">Memeriksa apakah user bisa masuk ke sistem aplikasi</td>
	</tr>
	<tr>
		<td>Kondisi Awal</td>
		<td colspan="3">Membuka halaman login pada website</td>
	</tr>
	<tr>
		<td>Tanggal pengujian</td>
		<td colspan="3">19 - 05 - 2018</td>
	</tr>
	<tr>
		<td>Penguji</td>
		<td colspan="3">M. Fauji Al Faris</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Skenario</td>
	</tr>
	<tr>
		<td colspan="4">
		1. Masukan Username<br>
		2. Masukan Password<br>
		3. Klik Login
		</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Hasil</td>
	</tr>
	<tr>
		<td align="center" width="250px">Data yang diberikan</td>
		<td align="center" width="250px">Yang diharapkan</td>
		<td align="center" width="250px">Pengamatan</td>
		<td align="center" width="250px">Kesimpulan</td>
	</tr>
	<tr>
		<td>
		Username : farises <br>
		Password : 123
		</td>
		<td>Tidak dapat masuk ke halaman dashboard member</td>
		<td>Username dan password harus sesuai dengan akun yang telah terdaftar di database</td>
		<td>Gagal masuk ke halaman dashboard member</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Catatan</td>
	</tr>
	<tr>
		<td colspan="4"><br><br></td>
	</tr>
</table>

<br><br>

<!-- ===================================================================================================================================================== -->

<table border="1" align="center" width="1000px">
	<tr>
		<td>Identifikasi</td>
		<td colspan="3">STD - 18</td>
	</tr>
	<tr>
		<td>Nama Butir Uji</td>
		<td colspan="3">Pengujian login dengan mengosongkan username dan password</td>
	</tr>
	<tr>
		<td>Tujuan</td>
		<td colspan="3">Memeriksa apakah user bisa masuk ke sistem aplikasi</td>
	</tr>
	<tr>
		<td>Kondisi Awal</td>
		<td colspan="3">Membuka halaman login pada website</td>
	</tr>
	<tr>
		<td>Tanggal pengujian</td>
		<td colspan="3">19 - 05 - 2018</td>
	</tr>
	<tr>
		<td>Penguji</td>
		<td colspan="3">M. Fauji Al Faris</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Skenario</td>
	</tr>
	<tr>
		<td colspan="4">
		1. Masukan Username<br>
		2. Masukan Password<br>
		3. Klik Login
		</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Hasil</td>
	</tr>
	<tr>
		<td align="center" width="250px">Data yang diberikan</td>
		<td align="center" width="250px">Yang diharapkan</td>
		<td align="center" width="250px">Pengamatan</td>
		<td align="center" width="250px">Kesimpulan</td>
	</tr>
	<tr>
		<td>
		Username :  <br>
		Password : 
		</td>
		<td>Tidak dapat masuk ke halaman dashboard member</td>
		<td>Username dan password harus dilengkapi</td>
		<td>Gagal masuk ke halaman dashboard member</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Catatan</td>
	</tr>
	<tr>
		<td colspan="4"><br><br></td>
	</tr>
</table>

<br><br>

<!-- ===================================================================================================================================================== -->

<table border="1" align="center" width="1000px">
	<tr>
		<td>Identifikasi</td>
		<td colspan="3">STD - 19</td>
	</tr>
	<tr>
		<td>Nama Butir Uji</td>
		<td colspan="3">Pengujian mengisis form pembelian dengan data yang sesuai</td>
	</tr>
	<tr>
		<td>Tujuan</td>
		<td colspan="3">Memeriksa apakah transaksi terekam ke tabel penjualan</td>
	</tr>
	<tr>
		<td>Kondisi Awal</td>
		<td colspan="3">- Halaman Kategori Barang <br> - Masuk ke halaman Order</td>
	</tr>
	<tr>
		<td>Tanggal pengujian</td>
		<td colspan="3">19 - 05 - 2018</td>
	</tr>
	<tr>
		<td>Penguji</td>
		<td colspan="3">Sujiyanto</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Skenario</td>
	</tr>
	<tr>
		<td colspan="4">
		1. Isi semua data pada form order barang<br>
		3. Klik tombol simpan jika data sudah diinputkan
		</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Hasil</td>
	</tr>
	<tr>
		<td align="center" width="250px">Data yang diberikan</td>
		<td align="center" width="250px">Yang diharapkan</td>
		<td align="center" width="250px">Pengamatan</td>
		<td align="center" width="250px">Kesimpulan</td>
	</tr>
	<tr>
		<td>
		NIK 				: -- Pilih NIK -- <br>
		Nama Barang			: -- Pilih Barang -- <br>
		Harga 				: (akan muncul ketika Nama Barang sudah dipilih) <br>
		Uang Muka 			: (akan muncul ketika Nama Barang sudah dipilih) <br>
		Jangka Waktu/bln 	: 3 <br>
		Angsuran 			: (akan muncul ketika jangka waktu sudah diinputkan) <br>
		Total Harga 		: (akan muncul ketika harga, uang muka, jangka waktu, angsuran telah terisi) 
		</td>
		<td>Data yang telah diinputkan berhasil masuk ke tabel penjualan</td>
		<td>Semua data yang diinputkan harus sesuai dengan format yang ditentukan</td>
		<td>Berhasil melakukan Transaksi Order Barang</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Catatan</td>
	</tr>
	<tr>
		<td colspan="4"><br><br></td>
	</tr>
</table>

<br><br>

<!-- ===================================================================================================================================================== -->

<table border="1" align="center" width="1000px">
	<tr>
		<td>Identifikasi</td>
		<td colspan="3">STD - 20</td>
	</tr>
	<tr>
		<td>Nama Butir Uji</td>
		<td colspan="3">Pengujian mengisi form pembelian dengan data kosong</td>
	</tr>
	<tr>
		<td>Tujuan</td>
		<td colspan="3">Memeriksa apakah transaksi terekam ke tabel penjualan</td>
	</tr>
	<tr>
		<td>Kondisi Awal</td>
		<td colspan="3">- Halaman Kategori Barang <br> - Masuk ke halaman Order</td>
	</tr>
	<tr>
		<td>Tanggal pengujian</td>
		<td colspan="3">19 - 05 - 2018</td>
	</tr>
	<tr>
		<td>Penguji</td>
		<td colspan="3">Sujiyanto</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Skenario</td>
	</tr>
	<tr>
		<td colspan="4">
		1. Isi semua data pada form order barang<br>
		3. Klik tombol simpan jika data sudah diinputkan
		</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Hasil</td>
	</tr>
	<tr>
		<td align="center" width="250px">Data yang diberikan</td>
		<td align="center" width="250px">Yang diharapkan</td>
		<td align="center" width="250px">Pengamatan</td>
		<td align="center" width="250px">Kesimpulan</td>
	</tr>
	<tr>
		<td>
		NIK 				: <br>
		Nama Barang			: <br>
		Harga 				: <br>
		Uang Muka 			: <br>
		Jangka Waktu/bln 	: <br>
		Angsuran 			: <br>
		Total Harga 		:  
		</td>
		<td>Muncul pesan error dan memberikan keterangan bahwa data harus dilengkapi</td>
		<td>Semua data yang diinputkan harus diisi sesuai dengan format yang ditentukan</td>
		<td>Gagal melakukan Transaksi Order Barang</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Catatan</td>
	</tr>
	<tr>
		<td colspan="4"><br><br></td>
	</tr>
</table>

<br><br>

<!-- ===================================================================================================================================================== -->

<table border="1" align="center" width="1000px">
	<tr>
		<td>Identifikasi</td>
		<td colspan="3">STD - 21</td>
	</tr>
	<tr>
		<td>Nama Butir Uji</td>
		<td colspan="3">Pengujian mengisi form pembelian dengan data yang sama</td>
	</tr>
	<tr>
		<td>Tujuan</td>
		<td colspan="3">Memeriksa apakah transaksi terekam ke tabel penjualan</td>
	</tr>
	<tr>
		<td>Kondisi Awal</td>
		<td colspan="3">- Halaman Kategori Barang <br> - Masuk ke halaman Order</td>
	</tr>
	<tr>
		<td>Tanggal pengujian</td>
		<td colspan="3">19 - 05 - 2018</td>
	</tr>
	<tr>
		<td>Penguji</td>
		<td colspan="3">Sujiyanto</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Skenario</td>
	</tr>
	<tr>
		<td colspan="4">
		1. Isi semua data pada form order barang<br>
		3. Klik tombol simpan jika data sudah diinputkan
		</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Hasil</td>
	</tr>
	<tr>
		<td align="center" width="250px">Data yang diberikan</td>
		<td align="center" width="250px">Yang diharapkan</td>
		<td align="center" width="250px">Pengamatan</td>
		<td align="center" width="250px">Kesimpulan</td>
	</tr>
	<tr>
		<td>
		NIK 				: -- Pilih NIK -- <br>
		Nama Barang			: -- Pilih Barang -- <br>
		Harga 				: (akan muncul ketika Nama Barang sudah dipilih) <br>
		Uang Muka 			: (akan muncul ketika Nama Barang sudah dipilih) <br>
		Jangka Waktu/bln 	: 3 <br>
		Angsuran 			: (akan muncul ketika jangka waktu sudah diinputkan) <br>
		Total Harga 		: (akan muncul ketika harga, uang muka, jangka waktu, angsuran telah terisi) 
		</td>
		<td>Data yang telah diinputkan gagal masuk ke tabel penjualan</td>
		<td>Semua data yang diinputkan tidak boleh sama dengan data yang telah terdaftar sebelumnya</td>
		<td>Gagal melakukan Transaksi Order Barang</td>
	</tr>
	<tr>
		<td colspan="4" align="center">Catatan</td>
	</tr>
	<tr>
		<td colspan="4"><br><br></td>
	</tr>
</table>
</html>
