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

![dasboard 1](https://user-images.githubusercontent.com/123666514/215257558-99514e0c-29c1-4e3c-ac4a-75eb766d3cda.PNG)


<h3>3. Buat Repository</h3>
<p>Setelah berhasil login ke GitHub, Anda bisa mulai membuat repository. Klik tombol New pada menu Repositories untuk membuat repository baru.</p>

![dasboard](https://user-images.githubusercontent.com/123666514/215257511-cf0de684-ca15-4ed6-8ff8-36bf5ed88f8e.PNG)

<p>Kemudian Anda akan diarahkan pada halaman untuk membuat repository baru seperti gambar di bawah ini.</p>

![create](https://user-images.githubusercontent.com/123666514/215257569-0b6b57fd-e891-4b33-b563-cbcb4498f847.PNG)

<p>Anda perlu mengisi detail informasi berikut:</p>

  <b>Nama Repository</b> : digunakan untuk identitas repository yang dibuat.<br>
  <b>Deskripsi Repository</b> : berfungsi untuk deskripsi dari repository yang dibuat.<br>
  <b>Jenis Repository</b> : jenis repository  dibagi menjadi Public dan Private. Ketika Anda mengatur repository menjadi Public, orang lain dapat melihat repository yang Anda buat. Sebaliknya, jika Anda mengaturnya sebagai Private, repository tersebut hanya bisa diakses oleh Anda.

<p>Setelah mengisi detail informasi di atas, klik Create Repository.</p>

<h3>4. Buat Folder pada Local Disk Computer</h3>
<p>Selanjutnya, Anda perlu membuat folder pada local disk komputer Anda. Fungsinya adalah untuk menyimpan update file dari repository GitHub yang telah Anda buat.</p>

![new folder](https://user-images.githubusercontent.com/123666514/215281654-16940211-3e34-4463-b551-562ba4182a64.PNG)

<p>Untuk pengguna linux kalian dapat menjalanakan perintah:</p>
<p>$ mkdir "nama_folder"</p>

![New folder linux](https://user-images.githubusercontent.com/123666514/215281896-4145f8dd-3148-478a-855e-117b85118105.PNG)

<h3>5. Buka Folder Menggunakan Git Bash</h3>
<p>Selanjutnya kalian harus membuka folder pada local disk komputer Anda,  buka folder tersebut dengan cara klik kanan lalu pilih Git Bash Here. Setelah itu akan muncul seperti di bawah ini.</p>

![git bash](https://user-images.githubusercontent.com/123666514/215282103-1cde7285-678e-4cd3-b5c2-92581f278b07.PNG)

<p> Setelah itu akan muncul seperti di bawah ini.</p>

![cmd](https://user-images.githubusercontent.com/123666514/215282197-dc57872d-b6dd-4ec3-8a58-d7869e79f5d3.PNG)

<p>Untuk pengguna linux kalian cukup membuka folder dengan perintah.</p>
<p>$ cd "nama_folder"</p>

![Terminal](https://user-images.githubusercontent.com/123666514/215282410-87209e37-ae96-4f16-aac3-c52b9154f711.PNG)

<h3>6. Ubah Folder Menjadi Repository</h3>
<p>Setelah itu, ubah folder tersebut menjadi repository menggunakan perintah berikut:</p>
<p>$ git init</p>

![git init](https://user-images.githubusercontent.com/123666514/215282505-0d4382b0-9139-4e58-abeb-70817eb20821.PNG)

<h3>7. Tambah File ke Repository</h3>
<p>Untuk bisa menambahkan file ke repository GitHub, kita buat file di folder yang sudah dibuat (LatihanVCS). Contohnya, di sini saya membuat file README.md</p>
<p>$ echo "text_yang_diinput_pada_file" >> nama_file</p>

![new file](https://user-images.githubusercontent.com/123666514/215283286-0f70affc-b72c-4219-b48a-349ce0b458ae.PNG)

<p>$ git add nama_file</p>

![new file 2](https://user-images.githubusercontent.com/123666514/215283289-6767fd52-6efc-484f-ae37-8a020aebea4e.PNG)

<h3>8. Buat Commit</h3>
<p>Selanjutnya, Anda perlu membuat Commit. Commit berfungsi untuk menambahkan update file serta komentar. Jadi setiap kontributor bisa memberikan konfirmasi update file di proyek yang sedang dikerjakan. Masukkan perintah berikut untuk membuat Commit:</p>
<p>$ git commit -m "komentar_commit"</p>

![commit](https://user-images.githubusercontent.com/123666514/215283538-1a28a343-533f-43c1-8642-70924ed9b64c.PNG)

<h3>9. Remote repository Github</h3>
<p>Remote repository berfungsi untuk mengupload file yang telah Anda buat sebelumnya di local disk. Masukkan perintah berikut ini untuk melakukan remote repository:</p>
<p>$ git remote add origin [url_repository]</p>

![remote](https://user-images.githubusercontent.com/123666514/215284025-9cc502d8-b3cd-4f96-99d3-2af78a496fb8.PNG)

<h3>10. Push ke Github</h3>
<p>Langkah terakhir adalah push ke GitHub Push ini berfungsi untuk mengupload hasil akhir dari langkah-langkah di atas. Masukkan perintah berikut untuk melakukan push ke GitHub:</p>
<p>$ git push -u origin master</p>
