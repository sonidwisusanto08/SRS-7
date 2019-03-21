<h1>
	<i>Software Rewuired Specification (SRS)</i>
</h1>
<ol>
	<p>BAB I </p>
	<li>Pendahuluan</li>
</ol>
<ul>
	<li>1.1 Tujuan</li>
	<p>Dokumen ini akan menyajikan deskripsi rinci tentang aplikasi pemesanan Geprek Alhamdulillah yang akan dibuat. Dokumen akan menjelaskan mengenai spesifikasi pada aplikasi Pemesanan Geprek Alhamdulillah seperti fitur sistem antarmuka sistem, sistem apa yang akan dilakukan,apa saja kendala pada saat aplikasi beroperasi, dana bagaimana system akan beraksi pada saat sedang digunakan oleh pemakai atau user</p>
</ul>
<ul>
	<li>1.2 Lingkup</li>
	<p>Dokumen ini menyediakan acuan untuk pengendalian tentang aplikasi pemesanan Geprek Alhamdulillah. Adapun ruang lingkup pembuatan aplikasi ini adalah berbasis mobile yang memilih beberapa fasilitas yang ada yaitu : </p>
	<p>1.Pembeli untuk mengelola data CRUD (Create,Read,Update,Delete ) yang ada pada fitur-fitur aplikasi pemesanan Geprek Alhamdulillah seperti input pesanan makanan dan minuman, mendaftarkan akun pembli</p>
</ul>
<ul>
	<li>1.3 Definisi, akronim, singkatan</li>
	<p>1.SPMP = Software Project Management Plan</p>
	<p>2.SRS = Software Requirement Specifications</p>
	<p>3.SDD = Software Design Document</p>
	<p>4.DFD = Data Flow Diagram</p>
	<p>5.IEEE = International Instittue of Electronic and Electrical Engineers</p>
	<p>6.CRUD = Create, Read, Update, dan Delete</p>

</ul>
<ul>
	<li>1.4 Referensi</li>
	<p>1.1.	IEEE. IEEE Std 830-1998 IEEE Recommended Practice for Software Requirements Specifications</p>
</ul>
<ul>
	<li>1.5 Overview</li>
	<p>
		Penulisan dokumen SRS ini dibagi menjadi beberapa bab sebagai berikut :
	</p>
	<p>
		BAB I berisi pendahuluan, menjelaskan mengenai tujuan pembuatan dokumen SRS, lingkup, definisi (akronim atau singkata), referensi dan Overview
	</p>
	<p>
		BAB II menjelaskan keseluruhan deskripsi dari Aplikasi Pemesanan Geprek Alhamdulillah Berbasis Mobile. Deskripsi umum tersebut memberikan gambaran lengkap mengenai semua fungsi yang akan dilakukan oleh sistem.
	</p>
	<p>
		BAB III berisi penjelasan detail dari masing-masing kebuthan lain yang spesifik
	</p>
	<p>
		BAB IV berisikan tentang uraian mengenai informasi pendukung dalam pembuatan proyek Aplikasi Pemesanan Geprek Alhamdulillah
	</p>
</ul>

<ol>
	<p>BAB II</p>
	<li>GAMBARAN UMUM</li>
	<p>
		Aplikasi Pemesanan Geprek Alhamdulillah merupakan aplikasi untuk mempermudah transaksi geprek dalam pembelian makanan dan minuman yang dilakukan di geprek tersebut. dimana pembeli dapat memesanan makanan dan minuman dengan aplikasi mobile yang disediakan oleh geprek sebagai pengganti daftar menu makanan dan menu minuman manual yang ada di geprek tersebut, aplikasi pelanggan tersebut juga dapat berguna sebagai admin yang dimana admin tersebut dapat melakukan proses CRUD menu makanan yang juga dapat merubah status jadi atau tidaknya memesan maakanan dan minuman yang ada dalam menu.
	</p>
</ol>
<ul>
	<li>2.1 Perpektif produk</li>
	<p>
		Aplikasi Pemesanan Geprek Alhamdulillah adalah aplikasi yang digunakanan untuk memesan menu mobile yang sebelumnya menggunakan metode manual dengan menulis menu. Kemudian aplikasi Pemesanan Geprek Alhamdulillah juga dapat melakukan pencatatan transaksi.
	</p>
</ul>
<ul>
	<li>2.1.1 Antarmuka sistem</li>
</ul>
<ul>
	<li>2.1.2 Antarmuka pengguna</li>
	<p>
		Aplikasi Pemesanan Geprek Alhamdulillah menggunakan antarmuak berbasis mobile.Dimana antarmuka mobile digunakan untuk pelayan dan pelanggan.
	</p>
</ul>
<ul>
	<li>2.1.3 Antarmuka perangkat keras</li>
	<li>Laptop</li>
	<li>Processor Core iColeron or Higher</li>
	<li>Penyimpanan (hardisk) Minimal 4 GB free space</li>
	<li>Smartphone minumal android Jelly Bean or Higher</li>
	<li>Monitor resolusi 1240 x 768 colors 5</li>
	<li>Keyboard dan mouse compatible with windows</li>
</ul>
<ul>
	<li>2.1.4 Antarmuka perangkat lunak</li>
	<li>Windows 7 or higher</li>
	<li>Android Studio</li>
	<li>Corel Draw X7</li>
	<li>Database Mysql</li>
	<li>Balsamiq Mockups 3</li>
	<li>Sublime Text 3 atau Dreamweaver
	</li>
</ul>
<ul>
	<li>2.1.5. Antarmuka komunikasi</li>
	<li>Paket Data</li>
	<li>Wifi</li>
	<li>Smartphone</li>
</ul>
<ul>
	<b>2.1.6 Batasan Memori</b>
	<li>RAM yang kami gunakan adalah minimal 4 gb</li>
	<li>Memori yang dibutuhkan aplikasi minimal 50mb</li>
</ul>
<ul>
	<b>2.1.7 Operasi-operasi</b>
	<li>Input pesanan</li>
</ul>
<ul>
	<b>2.1.8 Kebutuhan Adaptasi</b>
	<p>
		Kebutuhan adaptasi yang diperlukan pada saat pengembanggan aplikasi denggan menggunakan fungsi update data aagar memudahkan admin dalam mengkoreksi pengetikan yang salah.
	</p>
</ul>
<ul>
	<b>2.2 Fungsi-fungsi produk</b>
	<li>Memudahkan pemesanan geprek dan melihat menu-menu yang dijual</li>
</ul>
<ul>
	<b>2.3 Karakteristik Pengguna</b>
	<li>Pengguna mampu membaca dan menulis</li>
	<li>Pengguna mengerti cara menggunakan smartphone dengan sistem operasi android</li>
</ul>
<ul>
	<b>2.4 Batasan-batasan</b>
	<li>Berjalan pada platfrom android</li>
	<li>Sementara ini aplikasi hanya untuk Geprek Alhamdulillah Indramayu</li>
	<li>Aplikasi ini untuk layanan pesan antar</li>
</ul>
<ul>
	<b>2.5 Asumsi-asumsi dan keterkaitan</b>
	<p>
		Aplikasi Pemesanan Geprek Alhamdulillah ini dapat dikembangkan lagi dengan menambah banyak cafe pengguna, dan penambahan super admin untuk konfirmasi cafe mana saja yang boleh menggunakan aplikasi ini. Sehingga aplikasi ini dapat digunakan oleh banyak cafe yag ingin menggunakan aplikasi ini.
	</p>
</ul>
<ul>
	<b>2.6 Kebutuhan-kebutuhan penyeimbang</b>
	<li>Costumer Requirements</li>
	<p>
		Costumer Requirements adalah analisis yang dilakukan terhadap pelanggan agar dapat mengetahui apa saja kebutuhan pelanggan sehingga penggembang dapat membuat sistem yang sesuai dengan kebutuhan pelanggan.
	</p>
	<li>Detil Requirements</li>
	<p>
		Detil Requirements adalah suatu analisis yang terdiri dari properti dan fungsionalitas spesifik yang diekspresikan dalam bentuk yang detail.
	</p>
</ul>