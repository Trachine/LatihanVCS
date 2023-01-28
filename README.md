<h2>Git</h2>
Git adalah perangkat lunak pengendali versi atau proyek manajemen kode perangkat lunak yang diciptakan oleh Linus Torvalds, yang pada awalnya ditujukan untuk pengembangan kernel Linux. Desain Git terinspirasi oleh BitKeeper dan Monotone. Git pada awalnya hanya dirancang sebagai mesin tingkat rendah yang dapat digunakan oleh tampilan muka (front end) lain seperti Cogito atau StGIT. Namun selanjutnya proyek inti Git telah berkembang menjadi pengendali revisi lengkap yang dapat digunakan langsung. Saat ini, beberapa perangkat lunak terkenal menggunakan Git sebagai pengendali revisinya, antara lain kernel Linux, Server X.org, pengembangan inti OLPC (One Laptop per Child), serta kerangka kerja web Ruby on Rails. Pemeliharaan perangkat lunak Git saat ini diawasi oleh Junio Hamano. Dirilis di bawah Lisensi Publik Umum GNU versi 2, Git adalah suatu perangkat lunak bebas. 

<h2>Cara menggunakan git</h2>
<p>Untuk menggunakan git pastikan kalian sudah menginstall git terlebih dahulu.</p>

<h3>1. Login Git</h3>
<p>Untuk login ke Git, Anda bisa menggunakan akun GitHub, Gitlab, atau Bitbucket. Jika belum memiliki akun dari ketiga platform tersebut, Anda bisa mendaftarkan diri terlebih dahulu. Selanjutnya Anda bisa melakukan login awal pada Git  menggunakan Command Prompt  (Windows) atau Command Line (Linux).</p>

<p>masukkan username GitHub Anda menggunakan perintah di bawah ini. Lalu tekan ENTER jika sudah benar.</p>
<p>$ git config --global user.name "UsernameAnda"</p>
<p>Kemudian masukkan email yang terdaftar di GitHub Anda menggunakan perintah di bawah  ini. Lalu tekan ENTER jika sudah benar.</p>
<p>$ git config --global user.email IsiDenganEmailAnda@gmail.com</p>
<p>Selanjutnya untuk memastikan proses login Anda berhasil, masukkan perintah berikut.</p>
<p>$ git config --list</p>

![1 login git](https://user-images.githubusercontent.com/123666514/215147495-68789af4-bc45-4aa6-adb9-0b1535868eae.png)

<h3>2. Login Github</h3>
<p>Langkah kedua dalam menggunakan Git adalah Anda harus login ke dalam website <a href="https://github.com">GitHub</a>. Github dan Git memiliki hubungan khusus, yaitu Git yang berperan sebagai version control system dan Github menjadi hosting atau sebagai penyimpan kode pemrograman.</p>

<p>Setelah Anda login, akan muncul tampilan dashboard dari GitHub seperti  gambar di bawah ini.</p>

![dasboard](https://user-images.githubusercontent.com/123666514/215240716-37d5c5cf-23bf-4930-9844-677617201262.PNG)

<h3>3. Buat Repository</h3>
<p>Setelah berhasil login ke GitHub, Anda bisa mulai membuat repository. Klik tombol New pada menu Repositories untuk membuat repository baru.</p>



<p>Kemudian Anda akan diarahkan pada halaman untuk membuat repository baru seperti gambar di bawah ini.</p>

<p>Anda perlu mengisi detail informasi berikut:</p>

  <b>Nama Repository</b> : digunakan untuk identitas repository yang dibuat.<br>
  <b>Deskripsi Repository</b> : berfungsi untuk deskripsi dari repository yang dibuat.<br>
  <b>Jenis Repository</b> : jenis repository  dibagi menjadi Public dan Private. Ketika Anda mengatur repository menjadi Public, orang lain dapat melihat repository yang Anda buat. Sebaliknya, jika Anda mengaturnya sebagai Private, repository tersebut hanya bisa diakses oleh Anda.

<p>Setelah mengisi detail informasi di atas, klik Create Repository.</p>

<h3>4. Buat Folder pada Local Disk Computer</h3>
<p>Selanjutnya, Anda perlu membuat folder pada local disk komputer Anda. Fungsinya adalah untuk menyimpan update file dari repository GitHub yang telah Anda buat.</p>

<h3>5. Buka Folder Menggunakan Git Bash</h3>
<p>Setelah berhasil membuat folder pada local disk komputer Anda,  buka folder tersebut dengan cara klik kanan lalu pilih Git Bash Here. Setelah itu akan muncul seperti di bawah ini.</p>

<h3>6. Ubah Folder Menjadi Repository</h3>
<p>Setelah itu, ubah folder tersebut menjadi repository menggunakan perintah berikut:</p>
<p>$ git init</p>

<h3>7. Tambah File ke Repository</h3>
