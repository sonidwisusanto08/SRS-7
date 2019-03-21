
<b>
<div class="container" style="font-family: times new roman">
	<div class="header" style="text-align: center">
		<font size="6">APLIKASI PEMESANAN GEPREK ALHAMDULILLAH <br> 
			BERBASIS MOBILE <br> </font>
		<font size="6">PROYEK 2 </font><br>
	</b>
	</div>
	<div class="content" style="text-align: center">
		 <img src="gambar/polindra.png" width="400" height="400">
		 <br>
		    <font size="4"> Disusun Oleh : <br></font>
		    <b>
		    <font size="5"> Kukuh Ajie Prayoga ( 1703066 ) <br></font>
			<font size="5">Muhammad Naufal Hariz (1703080 ) <br></font>
			<font size="5">Soni Dwi Susanto ( 1703083 ) <br></font></font>
	</div>
	<br>
	<div class="footer" style="text-align: center" >
		 <font size="6">D3 TEKNIK INFORMATIKA <br></font>
		 <font size="6">POLITEKNIK NEGERI INDRAMAYU<br></font>
		 <font size="6">2019 </font>
</b>
	</div>
</div>
<br>
<br>
<ol>
<b>1.1	Tujuan</b>
	<ol>
	Dokumen ini akan menyajikan deskripsi rinci tentang aplikasi Pemesanan Geprek Alhamdulillah yang akan dibuat. Dokumen akan menjelaskan mengenai spesifikasi pada aplikasi Pemesanan Geprek Alhamdulilah seperti fitur sistem, antarmuka sistem, sistem apa yang akan dilakukan, apa saja kendala pada saat aplikasi beroperasi, dana bagaiman system akan bereaksi pada saat sedang digunakan oleh pemakai atau user<br>
	Pengguna dari dokumen ini adalah perangkat lunak sistem Pemesanan geprek pengguna (user) dari perangkat lunak atau personil-personil yang terlibat dalam sistem.Dokumen ini akan digunakan sebagai bahan acuan dalam proses pengembangan dan sebagai bahan evaluasi pada saat proses pengembangan  perangkat lunak maupun di akhir pengembangannya. Dengan adanya dokumen SKPL ini diharapkan pengembangan perangkat lunak akan lebih terarah dan lebih terfokus serta tidak menimbulkan ambiguitas terutama bagi pengembang perangkat lunak Pemesanan geprek.
	</ol><br>
<b>1.2	Lingkup Masalah<br></b>
	<ol>Dokumen ini menyediakan acuan untuk pengendalian tentang aplikasi pemesanan Geprek Alhamdulillah. Adapun ruang lingkup pembuatan aplikasi ini adalah berbasis mobile yang memilih beberapa fasilitas yang ada yaitu : <br>
		<ol>
		1.2.1 Pembeli untuk mengelola data CRUD (Create, Read, Update, Delete) yang ada pada fitur- fitur aplikasi pemesanan Geprek Alhamdulillah seperti input pesanan makanan dan minuman, mendaftarkan akun pembeli.<br>
		</ol>
	</ol><br>
<b>1.3	Definisi, Akronim dan Singkatan</b>
   <ol>Istilah, Akronim dan Singkatan beserta Keterangannya : <br>
	 	<ol>
	 	<p>&nbsp;</p>
<table>
<tbody>
<tr>
<td width="37">
<p>No</p>
</td>
<td width="163">
<p>Akronim</p>
</td>
<td width="266">
<p>Singkatan</p>
</td>
</tr>
<tr>
<td width="37">
<p>1.</p>
</td>
<td width="163">
<p>SPMP</p>
</td>
<td width="266">
<p>Software Project Management Plan</p>
</td>
</tr>
<tr>
<td width="37">
<p>2.</p>
</td>
<td width="163">
<p>SRS</p>
</td>
<td width="266">
<p>Software Requirements Specifications</p>
</td>
</tr>
<tr>
<td width="37">
<p>3.</p>
</td>
<td width="163">
<p>SDD</p>
</td>
<td width="266">
<p>Software Design Document</p>
</td>
</tr>
<tr>
<td width="37">
<p>4.</p>
</td>
<td width="163">
<p>DFD</p>
</td>
<td width="266">
<p>Data Flow Diagram</p>
</td>
</tr>
<tr>
<td width="37">
<p>5.</p>
</td>
<td width="163">
<p>IEEE</p>
</td>
<td width="266">
<p>International Institute of Electronic and Electrical Engineers</p>
</td>
</tr>
<tr>
<td width="37">
<p>6.</p>
</td>
<td width="163">
<p>CRUD</p>
</td>
<td width="266">
<p>Create, Read, Update, dan Delete</p>
</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
		 <br>
	 	<br>
	 </div>
	 	</ol>
 </ol></br>
<b>1.4	Referensi</b><br>
	<ol>Dokumen-dokumen yang digunakan sebagai referensi dalam pembuatan SKPL ini adalah sebagai berikut: <br>
		<ol>
	    1.4.1 IEEE. IEEE Std 830-1998 IEEE Recommended Practice for Software Requirements Specifications.<br> 
		</ol>
    </ol><br>
<b>1.5	Deskripsi Umum Dokumen</b><br>
	<ol>Dokumen ini secara garis besar terdiri dari tiga bab dengan perincian sebagai berikut: <br>
		<ol>
		1.5.1 Bab 1 berisi pendahuluan, menjelaskan mengenai tujuan pembuatan dokumenSRS, lingkup, definisi (akronim, atau singkatan), referensi, dan Overview.<br>
		1.5.2 Bab 2 menjelaskan keseluruhan deskripsi dari Aplikasi Pemesanan Geprek Alhamdulillah Berbasis Mobile. Deskripsi umum tersebut memberikan gambaran lengkap mengenai semua fungsi yang akan dilakukan oleh sistem..<br>
		1.5.3 Bab 3 berisi penjelasan detail dari  masing-masing kebutuhan lain yang spesifik.<br>
		1.5.4 Bab 4 berisikan tentang uraian mengenai informasi pendukung dalam pembuatan proyek Aplikasi Pemesanan Geprek Alhamdulillah. <br>
		</ol>
	</ol>
</ol><br>
 <b><li>Gambaran Umum</li><br></b>
 <ol>Aplikasi Pemesanan Geprek Alhamdulillah merupakan aplikasi untuk mempermudah transaksi geprek dalam pembelian makanan dan minuman yang dilakukan di geprek tersebut . dimana pembeli dapat memesan makanan  dan minuman dengan aplikasi mobile yang disediakan oleh geprek sebagai pengganti daftar menu makanan dan menu minuman manual yang ada di geprek tersebut, aplikasi pelanggan tersebut juga dapat berguna sebagai admin yang dimana admin tersebut dapat melakuakan proses CRUD menu makanan yang juga dapat merubah status  jadi atau tidaknya memesan makanan dan minuman yang ada dalam menu</ol>
<ol>
	<b>2.1 Perspektif produk</b> 
	<ol>Aplikasi Pemesanan Geprek Alhamdulillah adalah aplikasi yang digunakan untuk memesan menu melalui mobile yang sebelumnya menggunaka metode manual dengan menulis menu. Kemudian aplikasi Pemesanan Geprek Alhamdulillah juga dapat melakukan pencatatan transaksi.<br> 
		<ol>
		2.1.1 Antarmuka sistem  
			  <ol><div class="content" style="text-align: center">
		 <img src="gambar/pembeli.png" width="300" height="300">
		</div>
		 <br></ol>
		2.1.2 Antarmuka pengguna 
			  <ol>Perangkat lunak untuk aplikasi ini dibuat dengan menggunkan aplikasi flash.Dimana tampilan didesain dengan menggunakan template yang ada. Perangkat lunak untuk layanan dalam Aplikasi ini dilengkapi dengan menu untuk pengaksesan berbagai fungsi yang disediakan.</ol>
		2.1.3 Antarmuka perangkat keras
			  <ol>
			  Perangkat keras yang dapat digunakan dalam perangkat lunak yang dibuat:<br>
				1.	Laptop<br>
				2.	Processor Core iColeron or higher.<br>
				3.	Penyimpanan(Hardisk) Minimal 2 GB free space.<br>
				4.	Smartphone minimal android Jelly Bean or higher.<br>
				5.  Monitor resolusi 1240 x 768 colors 5. <br>
				6.  Keyboard dan mouse compatible with windows.
			</ol>
		2.1.4 Antarmuka perangkat lunak
			  <ol>Perangkat lunak yang dibutuhkan untuk perpustakaan antara lain:<br>
				1. Sistem Operasi Windows (XP,Vista,7,Server 2008) dll<br>
				2. Android Studio<br>
				3. Balsamiq Mockup 3<br>
			</ol>
		2.1.5 Antarmuka komunikasi
			  <ol>
			  1. Paket Data<br>
			  2. Wifi<br>
			  3. Smartphone
			  </ol>
		2.1.6 Batasan-batasan memori
			  <ol>1. RAM yang kami gunakan adalah minimal 4 gb.
				  2. Memori yang dibutuhkan aplikasi minimal 50 mb. 
				</ol>
		2.1.7 Operasi-operasi
			  <ol>Perangkat lunak dapat dijalankan di Handpone.</ol>
		2.1.8 Kebutuhan-kebutuhan dalam tahapan adaptasi
			<ol>Kebutuhan adaptasi yang diperlukan pada saat pengembangan aplikasi dengan menggunakan fungsi update data agar memudahkan admin dalam mengkoreksi pengetikan yang salah.
			</ol>
		</ol>
	</ol><br>
	<b>2.2 Fungsi-fungsi produk<br></b>
	<ol>Perangkat Lunak Sistem Pemesanan Geprek Alhamdulillah ini mempunyai beberapa fungsi utama, 
	antara lain: <br>
	<ol>
		1. Memudahkan pemesanan geprek.<br>
		2. Memudahkan dalam melihat menu-menu yang dijual.<br>
		3. Menyediakan informasi mengenai data produk yang akurat<br>
		</ol>
	</ol><br>
	<b>2.3 Karakteristik pengguna<br></b>
	<ol>
	Dalam sistem informasi ini, users yang terlibat adalah sebagai berikut:
		<ol>
		2.3.2 Pembeli
			  <ol>
			  1. pembeli mampu membaca dan menulis.<br>
			  2. pembeli mengerti cara menggunakan smartphone dengan sistem operasi android
			  </ol>
		</ol>
	</ol><br>
	<b>2.4 Batasan-batasan<br></b>
		<ol>
		1. Berjalan pada platform android<br>
		2. Sementara ini aplikasi ini hanya untuk Geprek Alhamdulillah Indramayu<br>
		3. Aplikasi ini untuk layanan pesan antar<br>
		</ol>
	<b>2.5 Asumsi-asumsi dan ketergantungan/keterkaitan<br></b>
		<ol>
		Aplikasi Pemesanan Geprek Alhamdulillah ini dapat dikembangkan lagi dengan menambah banyak café pengguna, dan penambahan super admin untuk konfirmasi café mana saja yang boleh menggunakan aplikasi ini. Sehingga aplikasi ini dapat digunakan oleh banyak café yang ingin menggunakan aplikasi ini.<br>
		</ol><br>
	<b>2.6 Kebutuhan – kebutuhan penyeimbang
		<ol>
			1.Customer Requirements<br>
		Customer Requirements adalah analisis yang dilakukan terhadap pelanggan agar dapat mengetahui apa saja kebutuhan pelanggan sehingga pengembang dapat membuat sistem yang sesuai dengan kebutuhan pelanggan.<br>
			2. Detil Requirements<br>
		Detil Requirements adalah suatu analisis yang terdiri dari properti dan fungsionalitas spesifik yang diekspresikan dalam bentuk yang detail.<br>
	</ol>
	</ol>

<b>
<li>Kebutuhan lain yang spesifik</li><br>
</b>
	<ol>
		<b>3.1. Perfoma</b><br>
		<ol>
			1. Berjalan pada system operasi minimal android lollipop. <br>
			2. Respon program kurang 30 detik.<br>
			3. Berjalan pada browser apapun<br>
		</ol>
		<b>3.2. Keamanan Aplikasi</b><br>
		<ol>
			•	Validasi username dan password harus sesuai dengan yang didaftarkan sehingga tidak terjadi kesalahan login pada aplikasi Geprek Alhamdulillah.<br>
		</ol>
		</ol>
		<b>3.3. Kebutuhan Antar Muka</b><br>
		<ol>
			Kebutuhan antarmuka dalam program ini antara lain adalah kebutuhan perangkat keras berupa <i>Personal Computer</i> berupa <i>Central Processing Unit(CPU)</i>,<i>mouse, keyboard, monitor,</i> dimana perangkat PC harus terhubung dengan jaringan internet. Sedangkan untuk kebutuhan perangkat lunak yang harus disediakan adalah berupa sebuah web <i>browser</i> seperti Internet Explorer, Mozilla Firefox, dan sebagainya untuk menjalankan aplikasi berbasis web.<br>
		</ol>
	</ol>

<b>
<li>Informasi Pendukung</li><br>
</b>
	<ol>
Informasi yang kami dapatkan, yaitu dari beberapa situs website, jurnal tugas akhir, dan mitra Geprek Alhamdulillah.
</ol>