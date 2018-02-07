{\rtf1\ansi\ansicpg1252\cocoartf1138\cocoasubrtf510
{\fonttbl\f0\fswiss\fcharset0 Helvetica;\f1\fnil\fcharset0 LucidaGrande;}
{\colortbl;\red255\green255\blue255;\red36\green41\blue46;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc0\levelnfcn0\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{decimal\}.}{\leveltext\leveltemplateid1\'02\'00.;}{\levelnumbers\'01;}\fi-360\li720\lin720 }{\listlevel\levelnfc2\levelnfcn2\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{lower-roman\}.}{\leveltext\leveltemplateid2\'02\'01.;}{\levelnumbers\'01;}\fi-360\li1440\lin1440 }{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{square\}}{\leveltext\leveltemplateid3\'01\uc0\u9642 ;}{\levelnumbers;}\fi-360\li2160\lin2160 }{\listname ;}\listid1}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}}
\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural

\f0\fs24 \cf0  
\b\fs48 \cf2 Use Case Diagram\
\pard\pardeftab720\sa320

\b0\fs32 \cf2 Berdasarkan 
\i features
\i0  yang telah di-design, dibuatkan diagram 
\i use case
\i0 .\
Simbol lingkaran elips menunjukkan 
\i use case
\i0  untuk proses tertentu dan simbol orang pada diagram tersebut menunjukkan aktor yang terlibat dalam 
\i use case
\i0  tersebut.\
Simbol panah menunjukkan generalisasi (super class/extends), pada diagram contoh di atas 
\i staff kasir
\i0  dan 
\i staff manajemen
\i0  merupakan sub dari aktor 
\i staff
\i0 .\
Masing-masing use case perlu dibuatkan narasi.\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa320
\ls1\ilvl0\cf2 {\listtext	1.	}Login\uc0\u8232 
\b Description
\b0 \uc0\u8232 User masuk ke sistem untuk tujuan meng-
\i establish
\i0  identitas user di dalam sistem (untuk keperluan pencatatan dan akuntibilitas).\uc0\u8232 Seluruh fungsi sistem hanya dapat digunakan apabila user sudah login ke dalam sistem.\u8232 
\b Normal Flow
\b0 \
\pard\tx940\tx1440\pardeftab720\li1440\fi-1440
\ls1\ilvl1\cf2 {\listtext	i.	}User menyalakan aplikasi POS\
{\listtext	ii.	}Aplikasi POS menampilkan halaman login\
{\listtext	iii.	}User memasukkan user dan password untuk login ke sistem\
{\listtext	iv.	}Sistem memeriksa user dan password, apabila valid dan masih aktif, user akan di-login-kan ke sistem\
{\listtext	v.	}User sudah dapat menggunakan aplikasi POS\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa320
\ls1\ilvl0
\b \cf2 {\listtext	2.	}Alternative Flow
\b0 \uc0\u8232 User salah memasukkan user/password\
\pard\tx940\tx1440\pardeftab720\li1440\fi-1440
\ls1\ilvl1\cf2 {\listtext	i.	}User memasukkan user/password yang salah\
{\listtext	ii.	}Sistem menampilkan pesan kesalahan dan menunggu user untuk memasukkan user dan password lagi\
{\listtext	iii.	}Ulangi proses normal flow langkah ke ii.\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa320
\ls1\ilvl0\cf2 {\listtext	3.	}Logout\uc0\u8232 
\b Description
\b0 \uc0\u8232 User keluar dari sistem. Setiap user berkewajiban untuk logout dari sistem apabila sudah selesai menggunakan sistem.\u8232 
\b Preconditions
\b0 \uc0\u8232 User dalam keadaan login di sistem.\u8232 
\b Normal Flow
\b0 \
\pard\tx940\tx1440\pardeftab720\li1440\fi-1440
\ls1\ilvl1\cf2 {\listtext	i.	}User mengakses menu logout atau menekan tombol close pada aplikasi POS\
{\listtext	ii.	}Sistem meng-logout user\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa320
\ls1\ilvl0\cf2 {\listtext	4.	}Add User (user management)\uc0\u8232 
\b Description
\b0 \uc0\u8232 Menambahkan user baru ke dalam sistem.\u8232 
\b Precondition
\b0 \uc0\u8232 User sudah login sebagai user manajemen.\u8232 
\b Normal Flow
\b0 \
\pard\tx940\tx1440\pardeftab720\li1440\fi-1440\sa320
\ls1\ilvl1\cf2 {\listtext	i.	}User membuka menu user management dan menekan tombol add untuk menambahkan user baru.\
{\listtext	ii.	}Sistem menampilkan form pendaftaran user baru\
{\listtext	iii.	}User menginput data user baru:\
\pard\tx1660\tx2160\pardeftab720\li2160\fi-2160
\ls1\ilvl2\cf2 {\listtext	
\f1 \uc0\u9642 
\f0 	}nama lengkap\
{\listtext	
\f1 \uc0\u9642 
\f0 	}nama user\
{\listtext	
\f1 \uc0\u9642 
\f0 	}password & password verification\
{\listtext	
\f1 \uc0\u9642 
\f0 	}jenis user (kasir/manajemen)\
{\listtext	
\f1 \uc0\u9642 
\f0 	}optional mengupload foto\
\pard\tx940\tx1440\pardeftab720\li1440\fi-1440\sa320
\ls1\ilvl1\cf2 {\listtext	iv.	}dan menekan tombol save untuk menyimpan data user\
{\listtext	v.	}Sistem memeriksa validitas data user baru, menyimpan informasi user ke databse dan menampilkan pesan notifikasi ke user bahwa user sudah tersimpan.\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa320
\ls1\ilvl0\cf2 {\listtext	5.	}Remove User (user management)\uc0\u8232 
\b Description
\b0 \uc0\u8232 Meng-nonaktifkan user. User yang sudah di-nonaktifkan tidak dapat login ke dalam sistem.\u8232 
\b Precondition
\b0 \uc0\u8232 User sudah login sebagai user manajemen.\u8232 
\b Normal Flow
\b0 \
\pard\tx940\tx1440\pardeftab720\li1440\fi-1440
\ls1\ilvl1\cf2 {\listtext	i.	}User membuka menu user management dan memilih account user yang akan dinonaktifkan.\
{\listtext	ii.	}Sistem menampilkan form tampilan informasi account user.\
{\listtext	iii.	}User menekan tombol non-aktif untuk meng-nonaktifkan user.\
{\listtext	iv.	}Sistem mengupdate status keaktifan user ke database.\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa320
\ls1\ilvl0\cf2 {\listtext	6.	}Untuk mengaktifkan kembali user, lakukan flow yang sama.\
{\listtext	7.	}Update user account (user management)\uc0\u8232 
\b Description
\b0 \uc0\u8232 Mengubah informasi mengenai user, misalnya nama lengkap atau password.\u8232 
\b Precondition
\b0 \uc0\u8232 User sudah login sebagai user manajemen.\u8232 
\b Normal Flow
\b0 \
\pard\tx940\tx1440\pardeftab720\li1440\fi-1440
\ls1\ilvl1\cf2 {\listtext	i.	}User membuka menu user management dan memilih account user yang akan di-update.\
{\listtext	ii.	}Sistem menampilkan form tampilan informasi account user.\
{\listtext	iii.	}User mengupdate informasi user dan menekan tombol save.\
{\listtext	iv.	}Sistem menyimpan perubahan account user ke database.\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa320
\ls1\ilvl0\cf2 {\listtext	8.	}Add Product (product management)\uc0\u8232 
\b Description
\b0 \uc0\u8232 Menambahkan product baru ke dalam sistem.\u8232 
\b Precondition
\b0 \uc0\u8232 User sudah login sebagai user manajemen.\u8232 
\b Normal Flow
\b0 \
\pard\tx940\tx1440\pardeftab720\li1440\fi-1440\sa320
\ls1\ilvl1\cf2 {\listtext	i.	}User membuka menu product management dan menekan tombol add untuk menambahkan product baru.\
{\listtext	ii.	}Sistem menampilkan form pendaftaran product baru\
{\listtext	iii.	}User menginput data product baru:\
\pard\tx1660\tx2160\pardeftab720\li2160\fi-2160
\ls1\ilvl2\cf2 {\listtext	
\f1 \uc0\u9642 
\f0 	}kode product\
{\listtext	
\f1 \uc0\u9642 
\f0 	}nama product\
{\listtext	
\f1 \uc0\u9642 
\f0 	}harga product\
{\listtext	
\f1 \uc0\u9642 
\f0 	}jenis product\
{\listtext	
\f1 \uc0\u9642 
\f0 	}optional mengupload foto\
\pard\tx940\tx1440\pardeftab720\li1440\fi-1440\sa320
\ls1\ilvl1\cf2 {\listtext	iv.	}dan menekan tombol save untuk menyimpan data product\
{\listtext	v.	}Sistem memeriksa validitas data product baru, menyimpan informasi product ke databse dan menampilkan pesan notifikasi ke user bahwa data sudah tersimpan.\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa320
\ls1\ilvl0\cf2 {\listtext	9.	}Remove Product (product management)\uc0\u8232 
\b Description
\b0 \uc0\u8232 Meng-nonaktifkan product. Product yang sudah di-nonaktifkan tidak akan dimunculkan pada saat pelanggan melakukan order.\u8232 
\b Precondition
\b0 \uc0\u8232 User sudah login sebagai user manajemen.\u8232 
\b Normal Flow
\b0 \
\pard\tx940\tx1440\pardeftab720\li1440\fi-1440
\ls1\ilvl1\cf2 {\listtext	i.	}User membuka menu product management dan memilih product yang akan dinonaktifkan.\
{\listtext	ii.	}Sistem menampilkan form tampilan informasi product.\
{\listtext	iii.	}User menekan tombol non-aktif untuk meng-nonaktifkan product.\
{\listtext	iv.	}Sistem mengupdate status keaktifan product ke database.\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa320
\ls1\ilvl0\cf2 {\listtext	10.	}Untuk mengaktifkan kembali product, lakukan flow yang sama.\
{\listtext	11.	}Update Product (product management)\uc0\u8232 
\b Description
\b0 \uc0\u8232 Mengubah informasi mengenai product, misalnya harga atau foto product.\u8232 
\b Precondition
\b0 \uc0\u8232 User sudah login sebagai user manajemen.\u8232 
\b Normal Flow
\b0 \
\pard\tx940\tx1440\pardeftab720\li1440\fi-1440
\ls1\ilvl1\cf2 {\listtext	i.	}User membuka menu product management dan memilih product yang akan di-update.\
{\listtext	ii.	}Sistem menampilkan form tampilan informasi product.\
{\listtext	iii.	}User mengupdate informasi product dan menekan tombol save.\
{\listtext	iv.	}Sistem menyimpan perubahan account product ke database.\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa320
\ls1\ilvl0\cf2 {\listtext	12.	}Order\uc0\u8232 
\b Description
\b0 \uc0\u8232 Pelanggan melakukan order makanan/minuman.\u8232 
\b Precondition
\b0 \uc0\u8232 User sudah masuk ke dalam sistem sebagai user kasir.\u8232 
\b Normal Flow
\b0 \
\pard\tx940\tx1440\pardeftab720\li1440\fi-1440\sa320
\ls1\ilvl1\cf2 {\listtext	i.	}Pelanggan melakukan order kepada kasir sesuai dengan menu product yang tersedia.\
{\listtext	ii.	}Staff menginput orderan pelanggan ke dalam sistem:\
\pard\tx1660\tx2160\pardeftab720\li2160\fi-2160
\ls1\ilvl2\cf2 {\listtext	
\f1 \uc0\u9642 
\f0 	}Product yang diorder\
{\listtext	
\f1 \uc0\u9642 
\f0 	}Jumlah (qty) product\
\pard\tx940\tx1440\pardeftab720\li1440\fi-1440\sa320
\ls1\ilvl1\cf2 {\listtext	iii.	}Sistem memeriksa validitas order dan kemudian menyimpan informasi order ke database.\
{\listtext	iv.	}Sistem menampilkan total tagihan.\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa320
\ls1\ilvl0
\b \cf2 {\listtext	13.	}Alternative Flow
\b0 \uc0\u8232 Pelanggan memesan product yang tidak aktif.\
\pard\tx940\tx1440\pardeftab720\li1440\fi-1440
\ls1\ilvl1\cf2 {\listtext	i.	}Pada proses validasi order, sistem menampilkan notifikasi ke user bahwa product yang di-order tidak tersedia.\
{\listtext	ii.	}User mengubah order atau membatalkan order sesuai dengan keputusan dari pelanggan.\
{\listtext	iii.	}Sistem memvalidasi order. Jika sudah valid simpan data order ke database. Jika belum ulangi proses ini.\
{\listtext	iv.	}Sistem menampilkan total tagihan (jika order tidak dibatalkan).\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa320
\ls1\ilvl0\cf2 {\listtext	14.	}Payment\uc0\u8232 
\b Description
\b0 \uc0\u8232 Pelanggan membayar pesanan.\u8232 
\b Precodition
\b0 \uc0\u8232 User sudah masuk ke dalam sistem sebagai user kasir. Orderan pelanggan sudah disimpan oleh sistem (order valid).\u8232 
\b Normal Flow
\b0 \
\pard\tx940\tx1440\pardeftab720\li1440\fi-1440
\ls1\ilvl1\cf2 {\listtext	i.	}Staff kasir meminta pembayaran kepada pelanggan sesuai dengan total tagihan. Kemudian staff kasir menginput informasi pembayaran.\
{\listtext	ii.	}Sistem merekam informasi pembayaran dan kemudian mencetak faktur order dan pembayaran.\
{\listtext	iii.	}Staff kasir menginformasikan ke staff barista untuk membuat pesanan sesuai dengan faktur order dan pembayaran.\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa320
\ls1\ilvl0\cf2 {\listtext	15.	}Report POS\uc0\u8232 
\b Description
\b0 \uc0\u8232 Menampilkan summary transaksi POS berdasarkan kriteria tertentu.\u8232 
\b Precondition
\b0 \uc0\u8232 User sudah login sebagai user manajemen.\u8232 
\b Normal Flow
\b0 \
\pard\tx940\tx1440\pardeftab720\li1440\fi-1440
\ls1\ilvl1\cf2 {\listtext	i.	}User mengakses menu laporan dan memilih laporan POS.\
{\listtext	ii.	}Sistem menampilkan form untuk menerima input kriteria laporan.\
{\listtext	iii.	}User menginput kriteria laporan dan mengklik tombol report.\
{\listtext	iv.	}Sistem mengolah data report dan kemudian menampilkan laporan kepada user.\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa320
\ls1\ilvl0\cf2 {\listtext	16.	}Report Cash Register\uc0\u8232 
\b Description
\b0 \uc0\u8232 Menampilkan summary transaksi cash register berdasarkan kriteria tertentu.\u8232 
\b Precondition
\b0 \uc0\u8232 User sudah login sebagai user manajemen.\u8232 
\b Normal Flow
\b0 \
\pard\tx940\tx1440\pardeftab720\li1440\fi-1440
\ls1\ilvl1\cf2 {\listtext	i.	}User mengakses menu laporan dan memilih laporan Cash Register.\
{\listtext	ii.	}Sistem menampilkan form untuk menerima input kriteria laporan.\
{\listtext	iii.	}User menginput kriteria laporan dan mengklik tombol report.\
{\listtext	iv.	}Sistem mengolah data report dan kemudian menampilkan laporan kepada user.\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa320
\ls1\ilvl0\cf2 {\listtext	17.	}Cash In/Out\uc0\u8232 
\b Description
\b0 \uc0\u8232 Proses memasukkan uang atau menarik uang dari cash register tanpa melalui proses penjualan.\u8232 
\b Precondition
\b0 \uc0\u8232 User sudah login sebagai user kasir.\u8232 
\b Normal Flow
\b0 \
\pard\tx940\tx1440\pardeftab720\li1440\fi-1440\sa320
\ls1\ilvl1\cf2 {\listtext	i.	}User mengakses menu cash register dan kemudian memilih menu cash in atau cash out.\
{\listtext	ii.	}Sistem menampilkan form input data cash in/out.\
{\listtext	iii.	}User menginput data cash in/out:\
\pard\tx1660\tx2160\pardeftab720\li2160\fi-2160
\ls1\ilvl2\cf2 {\listtext	
\f1 \uc0\u9642 
\f0 	}Jumlah\
{\listtext	
\f1 \uc0\u9642 
\f0 	}Keterangan\
\pard\tx940\tx1440\pardeftab720\li1440\fi-1440\sa320
\ls1\ilvl1\cf2 {\listtext	iv.	}dan kemudian menekan tombol save.\
{\listtext	v.	}Sistem menyimpan data cash in/out ke database dan mencetak faktur cash in/out.\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa320
\ls1\ilvl0\cf2 {\listtext	18.	}Ganti Shift\uc0\u8232 
\b Description
\b0 \uc0\u8232 Proses pergantian shift user kasir. Pada proses ini, kedua kasir akan memeriksa jumlah uang di cash register dan melakukan serah terima cash register.\u8232 
\b Precondition
\b0 \uc0\u8232 User sudah login sebagai user kasir.\u8232 
\b Normal Flow
\b0 \
\pard\tx940\tx1440\pardeftab720\li1440\fi-1440
\ls1\ilvl1\cf2 {\listtext	i.	}User mengakses menu cash register, ganti shift.\
{\listtext	ii.	}Sistem menampilkan form meminta informasi login kasir pengganti.\
{\listtext	iii.	}Kasir pengganti memasukkan informasi login.\
{\listtext	iv.	}Sistem memeriksa login kasir pengganti dan apabila valid tampilkan laporan cash register.\
{\listtext	v.	}Kasir pertama dan kasir pengganti sama-sama memeriksa dan laporan cash register. Jika sudah benar. Kasir pertama akan menekan tombol SERAH dan menginput password usernya. Sedangkan kasir pengganti akan menekan TERIMA dan menginput password usernya.\
{\listtext	vi.	}Sistem mencetak faktur serah terima dan meng-logout kasir pertama dan berikutnya meng-login kasir pengganti.}