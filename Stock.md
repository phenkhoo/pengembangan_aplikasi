# Company Inventory 

## Identifikasi stakeholder
1.	Staff administrator
2.	Client
3.  Vendor Formulator 
4.  Manager

## Identifikasi tujuan proyek
Tujuan utamanya dari Inventory Company application ini adalah untuk menyederhanakan pengelolaan stok barang di gudang agar pekerjaan perusahaan dapat berlangsung dengan baik. 
## Functional Requirement
Fitur-fitur yang harus diimplementasikan pada aplikasi ini adalah:
1. Sistem ini bertujuan menyediakan antarmuka yang efisien bagi pengguna untuk mengelola inventaris, namun juga menyediakan beragam pilihan bagi pengelola inventori melalui berbagai fungsi yang ada.
2. Desainnya sedemikian rupa sehingga pengguna tidak perlu memperbarui inventaris secara manual setiap saat, Sistem dilakukan untuk pengguna
3. Memilii fungsi seperti menambakan item, menghapus atau memperbarui item.
4. Mencakup penambahan vendor/client untuk bahan. menghapus vendor, memeriksa tingkat ambang, memproses pesanan, mengubah pesanan yang di proses.

### Flow proses bisnis
1.  Client melakukan pemesanan via email terhadap staff administrator
2.	Staff menginput pemesanan ke sistem dan kemudian mencetak faktur order dan pembayaran.
3.	Client memberi bukti pembayaran pesanan dan staff memberikan tanda terima pembayaran.
4.	Staff administrator check ulang ketersediaan barang dan menginformasikan kepada client.
5.  Barang di masukkan ke ekspedisi pengiriman. 

## Non-Functional Requirements
1. Aplikasi harus mudah digunakan oleh manajer dan staff administrator sehingga mereka tidak perlu membaca buku panduan manual.
2. Data bisa diekspor ke pengelola sehingga membuat sistem lebih portable.

## Design Solusi

1. Aplikasi Inventory

*	User management
Untuk login/logout dan identifikasi staff yang melakukan transaksi.
Fungsi untuk manajemen:
1	Menambahkan user baru
2	Menghapus/disable user (user tidak dapat login)
3	Mengganti password user (reset password)
*	Product management
Untuk daftar produk yang dijual dan bisa diorder.
1	Menambahkan product baru
2	Mengupdate informasi product
3	Menghapus/mengnontaktifkan product
*	Order and Payment
Menerima orderan dan menerima pembayaran.
1	Menerima pemesanan dari client
1	Menerima bukti pembayaran dari pelanggan
*	Report
1.	Menampilkan daftar transaksi yang terjadi.
*	User management
Untuk login/logout dan identifikasi staff yang melakukan transaksi.
* Report
Menampilkan jumlah uang, barang yang tersedia dan seluruh transaksi.
