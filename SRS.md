

## Software Requirements Specification
### Version 1.0
### 22 Februari 2018
![Logo Polindra](/image/polindra.png)

## AKBAR KOPKAR (Aplikasi Kredit Barang Koperasi Karyawan) POLINDRA

Anggota 
 1. Nur Inayatun Mahmuda (1603109)
 2. Muhammad Fauji Al Fariz (1603107)
 3. Sujiyanto (1603112)

### Jurusan Teknik Informatika 
### Polireknik Negeri Indramayu


### 1. Pendahuluan
**1.1 Tujuan**<br>
		Tujuan dari dokumen ini adalah untuk menyajikan deskripsi rinci tentang aplikasi yang akan dibuat serta dokumen ini akan menjelaskan tentang tujuan dan fitur dari sistem yang akan dibangun beserta interface dari sistem.<br>
**1.2 Lingkup Proyek**<br>
		Sistem Perangkat Lunak ini hanya akan menjadi aplikasi lokal, yang artinya aplikasi ini hanya akan dibuat untuk anggota yang terdaftar dalam koperasi karyawan Polindra. Sistem ini akan dirangcang untuk membantu admin koperasi dalam pemantauan penjualan serta angsuran pembayaran serta dapat membantu pihak anggota sebagai user yang menggunakan aplikasi ini untuk mempermudah melakukan transaksi pembelian barang dan peminjaman uang secara online. Dengan memaksimalkan sistem pada aplikasi ini maka akan memenuhi kebutuhan pihak koperasi dan tetap mudah dimengerti dalam hal penggunaan untuk semua user.<br>
**1.3 Definisi, Akronim, Singkatan**<br>

		| Istilah | Definisi                                       |
		|---------|------------------------------------------------|
		| Admin   | Orang yang mengelolah web server dari aplikasi |
		| User    | Pemakai atau pengguna aplikasi                 |
**1.4 Referensi** <br>
https://www.slideshare.net/rivaldysetiawan7/srs-example-webapp-33986122 <br>
**1.5 Overview**<br>
Bab 2, bagian Uraian Keseluruhan, dari dokumen ini memberikan sebuah gambaran fungsionalitas produk. Bab 3, Bagian Persyaratan Spesifikasi, dari dokumen ini ditulis terutama untuk menjelaskan secara teknis rinciannya fungsionalitas produk. Kedua bagian dokumen tersebut menggambarkan produk perangkat lunak yang sama secara keseluruhan, namun ditujukan untuk khalayak yang berbeda.

### 2. DESKRIPSI UMUM PERANGKAT LUNAK

**2.1 Perspektif Produk** <br>
	AKBAR Kopkar Polindra adalah aplikasi kredit barang di Koperasi Karyawan Politeknik Negeri Indramayu. Secara umum aplikasi ini berfungsi sebagai aplikasi penjualan yang berbasis android. Tujuannya untuk mempermudah  pihak koperasi dalam melakukan penjualan barang serta membantu pihak karyawan yang tergabung dalam anggota koperasi untuk melakukan pembelian barang karena pembayarannya dilakukan dengan sistem kredit tanpa menggunakan kartu kredit. Aplikasi ini berpacu pada aplikasi yang sudah ada sebelumnya yaitu aplikasi “Akulaku” namun aplikasi yang kita buat hanya ditujukan khusus untuk penjualan satu toko yaitu kopkar polindra dan hanya karyawan yang terdaftar yang bisa menggunakan aplikasi tersebut. Serta aplikasi ini memiliki fungsi tambahan untuk pengajuan peminjaman uang. <br>
	
**2.1.1 Antarmuka Sistem**<br>
![Use Case Diagram](/image/Use%20Case%20Diagram.png)<br>
**2.1.2 Mockup**<br>
![Dashboard](/image/Dashboard.png)
![Menu Elektronik](/image/Elektronik.png)<br>
![Angsuran](/image/Elektronik%20%28pilih%20angsuran%29.png)
![Login user](/image/Login%20User.png)<br>
![account](/image/Account.png)
![Bill](/image/Bill.png)<br>
![Login admin](/image/Login%20Admin.png)<br>
![Dashboard admin](/image/Dasboard%20Admin.png)<br>
**2.1.3 Antarmuka Hardware**<br>
 ![Antarmuka Hardware](/image/Antarmuka%20Hardware.png)<br>
 **2.2 Spesifikasi Kebutuhan Fungsional**<br>
Bagian ini menguraikan use case untuk masing-masing pengguna secara terpisah. Dimana aktor dalam aplikasi ini yaitu admin.<br>
**2.2.1 Admin Use Case**<br>
Admin dapat login pada website server dan menambahkan data anggota serta barang yang tersedia kemudian fungsi selanjutnya yaitu admin membuat laporan perkreditan.<br>
![Admin Use Case](/image/Use%20Case%20Admin.png)<br>
**2.2.2 User Use Case**<br>
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
1. Website Admin
- Admin dapat melakukan login
- Admin dapat menginputkan, mengedit dan menghapus data barang
- Admin dapat menginputkan, mengedit dan menghapus data anggota
- Admin dapat melihat ajuan kredit
- Admin dapat melihat laporan penjualan 
3.  Software User
- Pengguna dapat melakukan login
- Pengguna dapat melihat data barang yang tersedia
- Pengguna dapat melakukan pengajuan cicilan dalam pembelian barang
- Pengguna dapat melihat Bill pembayaran
- Pengguna dapat melakukan edit profile<br>
**3.2.1 Dashboard User**

| Nama Fungsi |Halaman awal user                           |
|---------|------------------------------------------------|
| **Ref** | **Bag 2.1.2** |
|**Trigger**|**Membuka dasboard user**|
|**Precondition**|**Tidak ada**|
|**Basic Path**|**User membuka aplikasi**|
|**Alternative**|**Tidak ada**|
|**Post Condition**|**Tanpa login user dapat melihat halaman dasboard**|
|**Exception Push**|**Tidak ada**|

**3.2.2 Menu Elektronik**

| Nama Fungsi |Elektronik                           |
|---------|------------------------------------------------|
|**Ref** | **Bag 2.1.2** |
|**Trigger**|**Membuka aplikasi menu elektronik**|
|**Precondition**|**Halaman Utama Aplikasi**|
|**Basic path**|**User membuka menu elektronik**|
|**Alternative**|**Tidak ada**|
|**Post Condition**|**Tanpa login user dapat melihat menu Elektronik**|
|**Exception Push**|**Tidak ada**|

**3.2.3 Pengajuan Cicilan**

| Nama Fungsi |Penjualan Cicilan                         |
|---------|------------------------------------------------|
| **Ref** | **Bag 2.1.2** |
|**Trigger**|**User memilih jangka waktu pembayaran**|
|**Precondition**|**Tampilan Detail barang**|
|**Basic Path**|**User memilih tombol bulan**|
|**Alternative**|**Tidak ada**|
|**Post Condition**|**Tanpa login user dapat melihat jumlah harga yang harus dibayar**|
|**Exception Push**|**Tidak ada**|

**3.2.4 Login User**

| Nama Fungsi |Login |
|---------|----------|
| **Ref** | **Bag 2.1.2** |
|**Trigger**|**User memasukan akun**|
|**Precondition**|**Tampilan pengajuan cicilan**|
|**Basic Path**|**User melakukan transaksi**|
|**Alternative**|**Tidak ada**|
|**Post Condition**|**User Mengisi akun login**|
|**Exception Push**|**Tidak ada**|

**3.2.5 Personal**

| Nama Fungsi |Perasonal |
|---------|--------------|
| **Ref** | **Bag 2.1.2** |
|**Trigger**|**User melihat data profile**|
|**Precondition**|**Tampilan halaman utama**|
|**Basic Path**|**Mengisi kelengkapan profile**|
|**Alternative**|**Tidak ada**|
|**Post Condition**|**User harus memiliki akun**|
|**Exception Push**|**Tidak ada**|

**3.2.6 Bill**

| Nama Fungsi |Bill |
|---------|--------------|
| **Ref** | **Bag 2.1.2** |
|**Trigger**|**User melihat tagihan pembayaran**|
|**Precondition**|**Tampilan halaman utama**|
|**Basic Path**|**User mengklik menu bill pembayaran**|
|**Alternative**|**Tidak ada**|
|**Post Condition**|**Hanya ada saat user melakukan transaksi**|
|**Exception Push**|**Tidak ada**|

**3.2.7 Login Admin**

| Nama Fungsi |Login |
|---------|----------|
| **Ref** | **Bag 2.1.2** |
|**Trigger**|**User memasukan akun**|
|**Precondition**|**Tampilan pengajuan cicilan**|
|**Basic Path**|**User melakukan transaksi**|
|**Alternative**|**Tidak ada**|
|**Post Condition**|**User mengisi akun login**|
|**Exception Push**|**Tidak ada**|

**3.2.8 Dashboard Admin**

| Nama Fungsi |Halaman awal admin |
|---------|----------|
| **Ref** | **Bag 2.1.2** |
|**Trigger**|**Membuka dasboard user**|
|**Precondition**|**Tidak ada**|
|**Basic Path**|**User membuka aplikasi**|
|**Alternative**|**Tidak ada**|
|**Post Condition**|**Tanpa login user dapat melihat halaman dashboard**|
|**Exception Push**|**Tidak ada**|

**3.3 Detail Persyaratan non-Fungsional**
			**3.3.1	Struktur data logis**
			**Struktur data yang ada pada aplikasi Akbar Kopkar**<br>
			![ERD](/image/ERD.png) 
			**Anggota**	
|Data item|Type|Description|Comment|
|---------|----|-----------|-------|
|Id_Anggota|integer|Identitas pengguna|Digunakan untuk Primary key       |
|No_hp|integer|Contact Person pengguna||
|NIK|integer|Nomor kependudukan pengguna||
|J_kelamin|char|Jenis Kelamin pengguna||
|tgl_lahir|date|Tanggal lahir pengguna||
|Alamat|string|Alamat pengguna||

**Admin**
|Data Item|Type|Description|Comment|
|---------|----|-----------|-------|
|Id_admin|Integer|Identitas admin|Primary key|
|Nama|String|Nama admin|       |
|Username|String|Username admin|       |
|Password|String|Autentikasi|       |

**Barang**
|Data Item|Type|Description|Comment|
|--|--|--|--|
|Id_barang|Integer|Identitas barang|  |
|nm_barang|String|nama barang|  |
|Kategori|String|kategori|  |
|Harga|Integer|harga|  |
|Stok|Integer|stok|  |

**Kategori**
|Data item|Type|Description|Comment|
|--|--|--|--|
|Id_kategori|Integer|Identitas kategori|Foregn key|
|nm_kategori|String|nama kategori||

**Transaksi**
|Data item|Type|Description|Comment|
|--|--|--|--|
|Kd_nota|Integer|Kode nota||
|nm_barang|String|Nama barang||
|nm_pembeli|String|Nama pembeli||
|cicilan|Integer|Ajuan cicilan||
|jumlah|Integer|Jumlah yang harus dibayar||
