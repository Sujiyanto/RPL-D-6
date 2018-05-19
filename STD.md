
<html>
<h2 align="center">SOFTWARE TESTING DOCUMENT</h2>
<h3 align="center">APLIKASI KREDIT BARANG KOPERASI KARYAWAN POLITEKNIK NEGERI INDRAMAYU<br>
(AKBAR KOPKAR POLINDRA)</h3>

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
<h3 align="center">BAB 1<br> PENDAHULUAN</h3>

<h4> 1.1. Tujuan Pembuatan Dokumen</h4>
- Untuk mengidentifikasi dan mengungkapkan sebagai kesalahan sebanyak mungkin dalam perangkat lunak yang diuji.<br>
- Untuk membawa perangkat lunak diuji, setelah memperbaiki kesalahan yang diidentifikasi dan melakukan pengujian ulang, pada tingkat kualitas yang memadai.<br>
- Untuk melakukan tes yang diperlakukan secara efisien dan efektif, dalam keterbatasan penjadwalan. <br>


<h4>1.2. Deskripsi Umum SIstem</h4>
Perangkat lunak yang akan diuji adalah “Aplikasi Kredit Barang Koperasi Karyawan Polindra”. Perangkat lunak ini adalah perangkat lunak yang digunakan untuk melakukan transaksi kredit barang maupun uang di koperasi POLINDRA. Sistem ini diimplementasikan melalui komunikasi dan di media antara User dan admin dengan sistem.


<h4>1.3. Deskripsi Dokumen</h4>
Dalam dokumen ini berisi 3 bagian utama yaitu Pendahuluan, Identifikasi dan Rencana Pengujian, Deskripsi dan Uji Hasil.

<h4>1.4. Daftar Singkatan </h4>


<h4> 1.5. Dokumen Referensi </h4>

 - http://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0ahUKEwjd7pWs6LvaAhUFto8KHShUDGsQFggoMAA&url=http%3A%2F%2Fwww.san.uri.br%2F~pbetencourt%2FengsoftII%2FIEEE-P1016-d50.PDF&usg=AOvVaw0-Aa9INJSSPZeNBCHHyNms
 - http://www.slideshare.net/rivaldysetiawan7/srs-example-webapp-33986122
 - IEEE Software Engineering Standards Committee, “IEEE Std 830-1998, IEEE  Recommended Practice for Software Requirements Specifications”, October 20, 1998.<br>
 - https://www.google.co.id/url?sa=t&rct=j&q=&esrc=s&source=web&cd=4&ved=0ahUKEwitpsi807jaAhUHqo8KHS0SAMEQFghLMAM&url=http%3A%2F%2Fwww.cse.chalmers.se%2F~feldt%2Fcourses%2Freqeng%2Fexamples%2Fsrs_example_2010_group2.pdf&usg=AOvVaw1sbUrO_cREj3g8sqm8driM<br>
 - https://www.google.co.id/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&ved=0ahUKEwitpsi807jaAhUHqo8KHS0SAMEQFggoMAA&url=https%3A%2F%2Fwww.utdallas.edu%2F~chung%2FRE%2FPresentations07S%2FTeam_1_Doc%2FDocuments%2FSRS4.0.doc&usg=AOvVaw2zaGGnBB9yNttcKsuBifee<br>

<h3 align="center">BAB II <br> LINGKUNGAN PENGUJIAN PERANGKAT LUNAK</h3>

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
</html>
