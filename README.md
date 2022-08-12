# FYP-02-2022
Project repository for group 02

A.  Topik Proyek
: “Pengembangan Learning Management System (LMS) Menggunakan Metode Prototyping Dan Evaluasi Aspek Usability (studi Kasus Sman 1 Simanindo)”

**B. Nama Aplikasi**                : LMS SMAN 1 Simanindo
**C. Jenis Sistem atau Aplikasi**   :  Sistem berbasis Website
**D. Persiapan** *meliputi:*
**==>  Spesifikasi device laptop**
    RAM : 4 GB 
    Operating System: Windows 10 Home
    Penyimpanan: 512 GB 
    Processor 	: Intel® Core™ i5 8250U Processor (6M Cache, up to 3.40 GHz)RA 
**==>  Spesifikasi Tools** 
    PhpMyAdmin: minimal Version 5.1.1
    Database Mysql: Versi 8.0.28
    Apache : 2.4.48
    Tools Editor : Sublime Text
**==>  Daftar User Type** 
Link hostinger: https://lmssman1simanindo.online/

Ada **3 user** pada website LMS SMA N 1 Simanindo
**1.	Administrator**
Administrator merupakan pihak yang mengelola seluruh kegiatan yang terdapat pada sistem LMS SMAN 1 Simanindo.
Task Description: Administrator dapat mengelola akun pengguna, mengelola mata pelajaran, mengelola kategori kelas, melihat aktivitas dari admin, menambahkan tahun ajaran, serta menambahkan event yang ada di SMAN 1 Simanindo. Berikut akun role administrator untuk dapat mengakses website LMS SMAN 1 Simanindo.
```sh
username	: admin
password	: admin
```

Berikut Dashboard dari admin
[!Img 1] (/1.png)

**2.	Guru**
Guru merupakan pihak yang akan menggunakan sistem LMS SMAN 1 Simanindo.
Task Description: Guru dapat meng-enroll mata pelajaran yang diampu, mengupload materi, mengelola kuis, mengelola upload tugas dan nilai tugas, mengirim pesan kepada guru maupun siswa (chatbox), menambahkan event, menambahkan pengumuman, melihat aktivitas masuk dan keluar dari siswa, serta menginput siswa kedalam kelas yang diampu.
Berikut akun role guru untuk dapat mengakses website LMS SMAN 1 Simanindo.

```sh
username	: intan123
password	: intan123
```
Berikut Dashboard dari guru
[!Img 1] (/2.png)

**3.	Siswa**
Siswa merupakan pihak yang akan menggunakan sistem LMS SMAN 1 Simanindo.
Task description : Siswa dapat mendownload materi yang diupload oleh guru, mendownload tugas dan mengirim tugas, mengikuti quiz, melihat progres tugas dan quiz, melihat teman sekelas, melihat notifikasi, melihat pengumuman dan event, serta mengirim pesan kepada guru maupun siswa (chatbox). 
Berikut akun role siswa untuk dapat mengakses website LMS SMAN 1 Simanindo.
```sh
username	: 11418001
password	: jeyshen123
```

Berikut Dashboard dari siswa
[!Img 1] (/3.png)

**Langkah-langkah menjalankan website LMS SMAN 1 Simanindo.** 
▪	General Requirement (Persyaratan Umum)
-	Sistem memiliki php versi 5 ke atas (anda dapat mencek dengan link https://bit.ly/3PhZE4i )
-	Memiliki browser yang mendukung developer mode (Chrome, Mozilla, Microsoft Edge dll.)
-	Memiliki web server untuk dapat mengakses database local yaitu XAMPP (sudah mencakup server Apache dan MySQL) Jika belum memiliki dapat mengikuti langkah dari link ini https://bit.ly/3JLPGak 
-	Memiliki folder hasil clone FYP-02-2022 (Berisikan folder aplikasi dan file query database)
-	Memiliki git pada sistem operasi, jika belum tersedia dapat di download dari link https://git-scm.com/downloads

▪	 Preparation (Persiapan)
1.	Mengakses link repository https://github.com/repoTAD4TRPL/FYP-02-2022  

kemudian salin URL HTTPS di github dari project tersebut.
[!Img 1] (/15.png)


2.	Buka lokasi directory XAMPP dimana sudah terdapat folder yang akan menjadi destinasi dari repository yang ingin diclone, kemudian jalankan CMD/git bash pada folder tersebut, dengan cara klik kanan 🡪 pilih Git Bash Here. 
[!Img 1] (/4.png)


3.	Langkah selanjutnya, lakukan clone project dengan mengetik git clone link repositories yang sudah disalin bertujuan meminta server dari github untuk mengirimkan informasi dari link repositories. 
git clone https://github.com/repoTAD4TRPL/FYP-02-2022.git
[!Img 1] (/5.png)


Gambar dibawah merupakan tampilan informasi dapat dibaca dan terdownload dapat repository penyimpanan yang sudah ditetapkan sebelumnya. 

[!Img 1] (/6.png)


Anda dapat melihat proses download selesai dengan membuka direktori, jika sudah ada, nama folder tersebut sama dengan nama repository yang diclone. 


4.	Kemudian, mengaktifkan Apache dan MySQL pada XAMPP anda dengan menekan action button start. 
[!Img 1] (/7.png)

5.	Langkah selanjutnya bukalah php admin di browser dengan mengetik  http://localhost/phpmyadmin/ 
[!Img 1] (/8.png)


	atau anda dapat mengklik admin pada MySQL, sistem akan membuka otomatis sql pada browser anda. 
	[!Img 1] (/9.png)

 

6.	Langkah selanjutnya, membuat nama database bebas, namun disini kami menyarankan anda yaitu tugasakhir02, silahkan klik new dan isi db kemudian klik create. 
[!Img 1] (/10.png)


    Lalu, import database yang berada dalam directory FYP-02-2022
    [!Img 1] (/11.png)

    
    Kemudian menyesuaikan nama database yang telah dibuat kedalam db connector, pada file ini nama database tugasakhir02 
     [!Img 1] (/12.png)

7.	Setelah itu silahkan buka web browser anda dengan mengetik directory xampp anda, http://localhost/directoryanda/
Disini terdapat perbedaan halaman untuk mengakses dari admin dengan guru dan siswa, berikut uraiannya
⮚	Admin
Untuk mengakses LMS dari sisi admin dapat membukanya dengan http://localhost/directoryanda/admin, sebagai contoh pada directory saya, saya membukanya dengan http://localhost/Final Artefak/dicoba/FYP-02-2022/admin
Silahkan login menggunakan default account guru yang telah dijelaskan sebelumnya pada Daftar User Type. 
Tampilan Login Admin
[!Img 1] (/13.png)


    ⮚	Guru dan Siswa
    Untuk mengakses LMS dari sisi guru maupun sisi siswa dapat membukanya dengan http://localhost/directoryanda/, sebagai contoh pada directory saya, saya membukanya dengan http://localhost/Final Artefak/dicoba/FYP-02-2022/ 
    Tampilan Login Guru maupun Siswa

    [!Img 1] (/14.png)


