# FYP-02-2022
Project repository for group 02

**A.  Topik Proyek**
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

Tools Editor : Sublime HQ Pty Ltd Version 3.2.1



**==>  Daftar User Type** 


Ada **3 user** pada website LMS SMA N 1 Simanindo

**1.	Administrator**

Administrator merupakan pihak yang mengelola seluruh kegiatan yang terdapat pada sistem LMS SMAN 1 Simanindo.

Task Description: Administrator dapat mengelola akun pengguna, mengelola mata pelajaran, mengelola kategori kelas, melihat aktivitas dari admin, menambahkan tahun ajaran, serta menambahkan event yang ada di SMAN 1 Simanindo. 

Berikut akun role administrator untuk dapat mengakses website LMS SMAN 1 Simanindo.

```sh
username	: admin
password	: admin
```

Berikut Dashboard dari admin


![1](https://user-images.githubusercontent.com/71743279/184470161-48a41f65-b9b6-44c6-a7e9-c94b89d14728.png)


**2.	Guru**

Guru merupakan pihak yang akan menggunakan sistem LMS SMAN 1 Simanindo.

Task Description: Guru dapat meng-enroll mata pelajaran yang diampu, mengupload materi, mengelola kuis, mengelola upload tugas dan nilai tugas, mengirim pesan kepada guru maupun siswa (chatbox), menambahkan event, menambahkan pengumuman, melihat aktivitas masuk dan keluar dari siswa, serta menginput siswa kedalam kelas yang diampu.

Berikut akun role guru untuk dapat mengakses website LMS SMAN 1 Simanindo.

```sh
username	: intan123
password	: intan123
```
Berikut Dashboard dari guru

![2](https://user-images.githubusercontent.com/71743279/184470169-0bb81778-b71b-4a3d-91b6-40f9247bf6ce.png)


**3.	Siswa**

Siswa merupakan pihak yang akan menggunakan sistem LMS SMAN 1 Simanindo.

Task description : Siswa dapat mendownload materi yang diupload oleh guru, mendownload tugas dan mengirim tugas, mengikuti quiz, melihat progres tugas dan quiz, melihat teman sekelas, melihat notifikasi, melihat pengumuman dan event, serta mengirim pesan kepada guru maupun siswa (chatbox). 

Berikut akun role siswa untuk dapat mengakses website LMS SMAN 1 Simanindo.
```sh
username	: 11418001
password	: jeyshen123
```

Berikut Dashboard dari siswa

![3](https://user-images.githubusercontent.com/71743279/184470178-4230271d-1c3d-4e0d-a0e3-80585b23bac3.png)

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

![15](https://user-images.githubusercontent.com/71743279/184470302-adaad389-3ba3-4e5b-9f93-6064fca22daa.png)





2.	Buka lokasi directory XAMPP dimana sudah terdapat folder yang akan menjadi destinasi dari repository yang ingin diclone, kemudian jalankan CMD/git bash pada folder tersebut, dengan cara klik kanan 🡪 pilih Git Bash Here. 

![4](https://user-images.githubusercontent.com/71743279/184470313-40c11d9e-6bec-4268-aba6-11c7da45f64e.png)


3.	Langkah selanjutnya, lakukan clone project dengan mengetik git clone link repositories yang sudah disalin bertujuan meminta server dari github untuk mengirimkan informasi dari link repositories. 

![5](https://user-images.githubusercontent.com/71743279/184470341-a423df0a-0330-417a-a867-c9c18d268596.png)




Gambar dibawah merupakan tampilan informasi dapat dibaca dan terdownload di repository penyimpanan yang sudah ditetapkan sebelumnya. 

![16](https://user-images.githubusercontent.com/71743279/184470356-e2823d53-1c6b-444b-a0bb-36684ae76405.png)


Anda dapat melihat proses download selesai dengan membuka direktori, jika sudah ada, nama folder tersebut sama dengan nama repository yang diclone. 


4.  Selain cara clone project, anda dapat mengakses repository dengan cara mendownlod nya, buka link github ini https://github.com/repoTAD4TRPL/FYP-02-2022 kemudian klik download zip.

![19](https://user-images.githubusercontent.com/71743279/184470927-325dab54-071e-48cb-8e5a-df662b839f69.png)
Kemudian, anda save zip dari repository github nya. 

![20](https://user-images.githubusercontent.com/71743279/184470948-15b28995-feae-4d8c-943c-465a6dd4c618.png)

Langkah selanjutnya ekstrak folder tersebut dengan cara klik kanan Extract Here. 

![21](https://user-images.githubusercontent.com/71743279/184470965-591b1ec1-abbb-4309-a103-8b8ee8eb27c5.png)

Berikut proses extract folder dari github

![22](https://user-images.githubusercontent.com/71743279/184470987-10b7c626-d415-4f31-b3fe-5c476e9be500.png)


Jika Folder tersebut berhasil di extract maka tampilannya sebagai berikut. 

![23](https://user-images.githubusercontent.com/71743279/184471003-e0da1764-650a-4812-9938-9768884b1d6d.png)


5.	Kemudian, mengaktifkan Apache dan MySQL pada XAMPP anda dengan menekan action button start. 

![17](https://user-images.githubusercontent.com/71743279/184470364-428dbac1-208e-49ca-978f-bc3106c259d2.png)



6.	Langkah selanjutnya bukalah php admin di browser dengan mengetik  http://localhost/phpmyadmin/ 

![8](https://user-images.githubusercontent.com/71743279/184470392-9839e491-89fd-4942-bf87-dbe3e293c9b0.png)

atau anda dapat mengklik admin pada MySQL, sistem akan membuka otomatis sql pada browser anda. 

![9](https://user-images.githubusercontent.com/71743279/184470376-93228547-04cc-42af-9376-23d08c8c4874.png)


 

7.	Langkah selanjutnya, membuat nama database bebas, namun disini kami menyarankan anda yaitu tugasakhir02, silahkan klik new dan isi db kemudian klik create.

![10](https://user-images.githubusercontent.com/71743279/184470515-40c883d6-d887-4952-9ebb-f87a4334dfc4.png)


Lalu, import database yang berada dalam directory FYP-02-2022

![11](https://user-images.githubusercontent.com/71743279/184470522-cbbbfae6-c0ec-4fbb-958c-481a0d48a33c.png)


Kemudian menyesuaikan nama database yang telah dibuat kedalam db connector, pada file ini nama database tugasakhir02 

![10](https://user-images.githubusercontent.com/71743279/184470407-8530958f-26e4-4c20-a57f-d2c89c45e87a.png)



8.	Setelah itu silahkan buka web browser anda dengan mengetik directory xampp anda, http://localhost/directoryanda/

Disini terdapat perbedaan halaman untuk mengakses dari admin dengan guru dan siswa, berikut uraiannya



⮚	Admin

Untuk mengakses LMS dari sisi admin dapat membukanya dengan http://localhost/directoryanda/admin, sebagai contoh pada directory saya, saya membukanya dengan http://localhost/Final Artefak/dicoba/FYP-02-2022/admin

Silahkan login menggunakan default account guru yang telah dijelaskan sebelumnya pada Daftar User Type. 

Tampilan Login Admin

![13](https://user-images.githubusercontent.com/71743279/184470430-9368590c-8e6b-4ec1-a51a-1c8681722c62.png)


 ⮚	Guru dan Siswa
 
Untuk mengakses LMS dari sisi guru maupun sisi siswa dapat membukanya dengan http://localhost/directoryanda/, sebagai contoh pada directory saya, saya membukanya dengan http://localhost/Final Artefak/dicoba/FYP-02-2022/ 

Tampilan Login Guru maupun Siswa

![14](https://user-images.githubusercontent.com/71743279/184470437-7ee66ac1-bc56-4380-bf08-fe3e8904f6e0.png)



