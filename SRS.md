


## SOFTWARE REQUIREMENT SPESIFICATION
## APLIKASI KREDIT BARANG KOPERASI KARYAWAN (AKBAR KOPKAR) POLINDRA
### Version 1.0
### 24 Maret 2018
![Logo Polindra](/image/polindra.png)

Anggota 
 1. Nur Inayatun Mahmuda (1603109)
 2. Muhammad Fauji Al Fariz (1603107)
 3. Sujiyanto (1603112)
 4. Astri Alisah (1603091)
 Kelompok 5
 D3TI2D

###  TEKNIK INFORMATIKA
### POLITEKNIK NEGERI INDRAMAYU


### 1. Pendahuluan
**1.1 Tujuan**<br>
		Tujuan dari dokumen ini adalah untuk menyajikan deskripsi rinci tentang aplikasi yang akan dibuat serta dokumen ini akan menjelaskan tentang tujuan, istilah-istilah yang digunakan pada dokumen  dan fitur dari sistem yang akan dibangun beserta interface dari sistem.<br>
**1.2 Lingkup Proyek**<br>
		Sistem Perangkat Lunak ini hanya akan menjadi aplikasi lokal, yang artinya aplikasi ini hanya akan dibuat untuk anggota yang terdaftar dalam koperasi karyawan Polindra. Sistem ini akan dirangcang untuk membantu admin koperasi dalam pemantauan penjualan serta angsuran pembayaran serta dapat membantu anggota sebagai user yang menggunakan aplikasi ini untuk mempermudah melakukan transaksi pembelian barang dan peminjaman uang secara online. Dengan memaksimalkan sistem pada aplikasi ini maka akan memenuhi kebutuhan pihak koperasi dan tetap mudah dimengerti dalam hal penggunaan untuk semua user.<br>
**1.3 Definisi, Akronim, Singkatan**<br>

		| Istilah | Definisi                                                                                      |
		|---------|-----------------------------------------------------------------------------------------------|
		| Kredit  | Melakukan pembayaran dengan cara mengangsur                                                   |
		| Koperasi| Organisasi ekonomi yang dimiliki dan dioperasikan oleh beberapa orag demi kepentingan bersama |
		| User    | Pemakai atau pengguna aplikasi                                                                | 
		| Admin   | Orang yang mengelolah web server dari aplikasi                                                |

**1.4 Referensi** <br>
https://www.slideshare.net/rivaldysetiawan7/srs-example-webapp-33986122 <br>
**1.5 Overview**<br>
Dokumen ini dibagi menjadi tiga bagian utama. Bagian pertama. Bagian utama berisi penjelasan dokumen SRS yang mencangkup tujuan pembuatan dokumen ini, lingkup masalah yang diselesaikan yang dikembangkan oleh kami yaitu definisi, referensi dan deskripsi umum. Bagian kedua berisi penjelasan secara umum mengenai aplikasi yang akan dikembangkan meliputi fungsi, karakteristik pengguna, batasan dan asumsi yang diambil dalam pengembang aplikasi. Bagian ke tiga berisi uraian aplikasi secara lebih rinci. 

### 2. GAMBARAN UMUM

**2.1 Perspektif Produk** <br>
	AKBAR Kopkar Polindra adalah aplikasi kredit barang di Koperasi Karyawan Politeknik Negeri Indramayu. Secara umum aplikasi ini berfungsi sebagai aplikasi penjualan yang berbasis android. Tujuannya untuk mempermudah  pihak koperasi dalam melakukan penjualan barang serta membantu pihak karyawan yang tergabung dalam anggota koperasi untuk melakukan pembelian barang karena pembayarannya dilakukan dengan sistem kredit tanpa menggunakan kartu kredit. Aplikasi ini berpacu pada aplikasi yang sudah ada sebelumnya yaitu aplikasi “Akulaku” namun aplikasi yang kita buat hanya ditujukan khusus untuk penjualan satu toko yaitu kopkar polindra dan hanya karyawan yang terdaftar yang bisa menggunakan aplikasi tersebut, kelebihan dari aplikasi ini mudah dioperasikan dan dipahami Serta aplikasi ini memiliki fungsi tambahan untuk pengajuan peminjaman uang. <br>
	
**2.1.1 Antarmuka Sistem**<br>
![Use Case Diagram](/image/Use%20Case%20Diagram.png)<br>
**2.1.2 Mockup**<br>
![Home](/image/Home.png)
![Detail Elektronik](/image/Detail%20Elektronik.png) <br>
![Pilihan Angsuran](/image/Pilihan%20Angsuran.png)
![Login](/image/Login.png) <br>
![Personal](/image/Personal.png)
![Laporan Pembayaran](/image/Laporan%20Pembayaran.png) <br>
![Login Admin](/image/Login%20Admin.png)
![Dashboard](/image/Dashboard.png) <br>
**2.1.3 Antarmuka Hardware**<br>
 ![Antarmuka Hardware](/image/Antarmuka%20Hardware.png)<br>
  **2.2 Spesifikasi Kebutuhan Fungsional**<br>
Bagian ini menguraikan use case untuk masing-masing pengguna secara terpisah. Dimana aktor dalam aplikasi ini yaitu admin.
![Use case keseluruhan](/image/Use%20case.png)<br>
**2.2.1 Use Case Admin**<br>
Admin dapat login pada website server dan menambahkan data anggota serta barang yang tersedia kemudian fungsi selanjutnya yaitu admin membuat laporan perkreditan.<br>
![Admin Use Case](/image/Use%20Case%20Admin.png)<br>
**2.2.2 Use Case Member**<br>
User dapat menggunakan fungsi login pada aplikasi adnroid kemudian melihat barang dan melakukan transaksi.<br>
![User Use Case](/image/Use%20Case%20User.png)<br>
**2.3 Spesifikasi Kebutuhan non-Fungsional**<br>
 1. Sistem dapat dijalankan diperangkat smartphone dan oleh beberapa software web browser
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
**3.2.1. Home**

|Nama Fungsi  |Halaman Awal User  |
|--|--|
| Ref |Bag 2.1.2  |
| Triger | Membuka Home |
| Precondition | Tidak ada |
| Basic Path | User membuka aplikasi |
| Alternative | Tidak ada |
| Post Condition | Tanpa login dapat melihat halaman Home |
| Exception Push | Tidak ada |
Tabel 3.1
**3.2.2. Detail Elektronik**
| Nama Fungsi |Elektronik  |
|--|--|
| Ref |Bag 2.1.2  |
| Trigger | Membuka aplikasi detail elektronik |
|Precondition | Halaman utama aplikasi |
|Basic Path | User membuka detail elektronik |
| Alternative | Tidak ada |
| Post condition | Tanpa login dapat melihat detail elektronik |
| Exception Push | Tidak ada |
Tabel 3.2 Elektronik

**3.2.3. Pilih Angsuran**
| Nama Fungsi | Pilih Angsuran |
|--|--|
| Ref  |Bag 2.1.2  |
| Trigger | User memilih jangka waktu pembayaran |
| Precondition | Tampilan detail barang|
| Basic Path | User memilih tombol waktu/bulan |
| Post Condition | Tanpa login dapat melihat jumlah harga yang harus dibayar |
| Exception Push | Tidak ada |
Tabel 3.3 Pilih Angsuran Pembayaran

3.2.4. Login
| Nama Fungsi | Login |
|--|--|
| Ref | Bag 2.1.2 |
| Trigger | User memasukkan akun |
| Precondition | Tampilan pilihan angsuran |
| Basic Path | User melakukan transaksi |
|Alternative | Tidak ada |
|Post Condition | User mengisi akun login |
|Exception Push | Tidak ada |
Tabel 3.4 Login User Android

**3.2.5. Personal**
|Nama Fungsi  |Personal  |
|--|--|
| Ref  |Bag 2.1.2  |
| Trigger | User melihat data profile |
| Precondition | Tampilan Halaman utama |
| Basic Path | Mengisi kelengkapan profile |
| Alternative | Tidak ada |
| Post Condition | User harus memiliki akun |
| Exception Push | Tidak ada |
Tabel 3.5 Account User Android

**3.2.6. laporan Pembayaran**
|Nama Fungsi  |Laporan Pembayaran  |
|--|--|
| Ref  | Bag 2.1.2 |
| Trigger | User melihat tagihan pembayaran |
|Precondition | Tampilan halaman utama |
| Basic Path | User mengklik menu laporan pembayaran |
| Alternative | Tidak ada |
| Post Condition | Hanya ada saat user melakukan transaksi |
|Exception Push | Tidak ada |
Tabel 3.6 Laporan Pembayaran

**3.2.7. Login Admin**
| Nama Fungsi | Login |
|--|--|
|Ref | Bag 2.1.2 |
|Trigger | Admin memasukkan akun |
|Precondition | Tidak ada |
|Basic Path | Admin mengakses website |
|Alternative | Tidak ada |
|Post Condition | Masuk ke halaman dashbord admin |
|Exception Push | Tidak ada |
Tabel 3.7 Login Admin 

**3.2.8. Dashboard Admin**

| Nama Fungsi | Halaman awal admin |
|--|--|
|Ref | Bag 2.1.2 |
|Trigger | Membuka halaman dashbord |
|Precondition | Tidak ada |
|Basic Path | Membuka aplikasi |
|Alternative | Tidak ada |
|Post Condition |Masuk halaman dashbord |
|Exception Push | Tidak ada |
Tabel 3.8 Dashbord Admin

**3.3 Detail Persyaratan non-Fungsional** <br>
			**3.3.1	Logika Struktur data **
			![ERD](https://raw.githubusercontent.com/Sujiyanto/RPL-D-6/master/image/ERD.png)

**Tabel Admin**

| Data Item | Type | Description | Comment |
|-----------|------|-------------|---------|
|Id_admin|Varchar|Identitas admin|Primary key|
|Nama_admin|Varchar|Nama admin|       |
|Username|Varchar|Username admin|       |
|Password|Varchar|Password admin|       |
Tabel 3.9 Tabel Admin

** Tabel Member **
| Data Item | Type | Description | Comment |
|--|--|--|--|
|id_member | Varchar | Identitas admin | Primary key |
|nik | Varchar | Nomor induk kepegawaian | |
|nama_member | Varchar | Nama member | |
|ttl | Varchar | Tempat tanggal lahir | |
|jk| Varchar | jenis kelamin | |
|alamat | Varchar | Alamat member | |
|no_hp | Varchar | No hp member | |
|email | Varchar | No hp member | |
|username | Varchar | Username member | |
|Password | Varchar | Password akun member | |
Tabel 3.10 Tabel Member

**Tabel Barang**

| Data Item | Type | Description | Comment |
|-----------|------|-------------|---------|
|Id_barang|Varchar|Identitas barang| Primary key |
|nm_barang|Varchar|nama barang|  |
|Kategori|Varchar|kategori|  |
|Harga|Varchar|harga|  |
|Stok|Varchar|stok|  |
Tabel 3.11 Tabel Barang

** Tabel Order **
| Data Item | Type | Description | Comment |
|--|--|--|--|
|id_nota | Varchar | No nota | Primary key |
|id_barang | Varchar | Identitas barang | Foreign key |
|id_member | Varchar | identitas member | Foreign key|
| Jangka_waktu | Varchar | Jangka waktu angsuran | |
|jumlah | Varchar | Jumlah uang yang harus dibayar | |
Tabel 3.12 Tabel Order