Hallo, nama saya Dhea Dwi Adelia. Saya akan menjelaskan cara menggunakan Git, yang kita perlukan adalah aplikasi Git, dan akun Git. Sebelum itu kita harus menginstall aplikasi Git. Berikut tutorial penginstallan aplikasi Git.
###Tutorial penginstallan aplikasi Git
- Pertama, anda buka situs resminya di git-scm.com .
![Screenshot (17)](https://user-images.githubusercontent.com/115794875/196307674-ffdad09c-0d19-402d-9fa6-273234d85d80.png)
Download sesuai dengan bit (32 bit atau 64 bit) agar laptop anda support. Selesai download klik install.
- Lalu klik next simpan lokasi di C:\ProgramFiles\Git(disesuaikan), lalu di next sampai ke step install, tunggu sampai selesai.
![image](https://user-images.githubusercontent.com/115794875/196308523-5e75a8a3-3eee-4a70-8833-b0e109d6ae8f.png)
- Setelah melakukan penginstalan, buka git cmd untuk mengetahui apakah sudah bisa melakukan proses atau belum jika muncul git version berarti sudah siap melakukan proses. Untuk mengetahui versinya ketikan perintah git --version. Saya memakai versi 2.38.0.windows.1
![Screenshot (18)](https://user-images.githubusercontent.com/115794875/196309682-34ba4745-f521-4192-81ef-633bacd85922.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Cara membuat akun git
- Disini anda harus membuat akun git terlebih dahulu  untuk membuat repository server bukalah link tersebut http://github.com

![Screenshot (19)](https://user-images.githubusercontent.com/115794875/196310564-a1305abf-bf10-4357-9416-b5bee7777a98.png)

- Pada langka selanjutnya anda boleh langsung diskip saja.
   
  ### Membuat repositori baru

- Ini adalah tampilan pertama setelah kalian selesai membuat akun git

![Screenshot (22)](https://user-images.githubusercontent.com/115794875/196403714-7e6d2c0b-477f-43b2-a5e9-ce0fd1da6705.png)

- Langkah selanjutnya nanti anda akan dialihkan ke tab baru untuk membuat repositori baru, isi susuai inspirasi anda setelah selesai klik buat repositori. 

 ![Screenshot (23)](https://user-images.githubusercontent.com/115794875/196402959-28f8a634-2ccd-4388-b476-b86711af9d37.png)

-  Lalu nanti di tab baru ada url, url ini akan digunakan untuk remote GitHub.

  ![Screenshot (18)](https://user-images.githubusercontent.com/115677959/195978391-435ade62-7139-47d7-b50b-073c6c000bdb.png)

### Membuat Repository Local

- Lalu kita buka file explorer pilih dilocal disk (c) (atau dmana saja sesuai keinginan anda), lalu klik kanan pilih *Git Bash here* .
![Screenshot (20)](https://user-images.githubusercontent.com/115677959/195978607-35aa8e50-d7fd-4451-b5a6-754d887eb31f.png)


- Lalu kita akan menambahkan Config Global Repository  pakai user name dan user email yang tadi sudah dibuat, dengan perintah : 	
      *$ git config --global user.email “email_user”*
      *$ git config --global user.name “nama_user”*

  ![image](https://user-images.githubusercontent.com/115794875/196407829-698a1f14-cf09-4892-a7c9-f2f85fe3708e.png)

- Buatlah direktori baru dengan menggunakan perintah " mkdir lab_pemrograman "  LALU *" cd lab_pemrograman![image](https://user-images.githubusercontent.com/115794875/196408140-be11f231-fd5d-4e92-bb75-19cdc0200807.png)
 ##### Cara penggunaan git dengan perintah daasar git init fungsi  perintahnya  untuk membuat repository local 

- Lalu jalankan perintah git init untuk membuat membuat file kosong berformat GIT. File ini fungsinya untuk menyimpan semua perubahan pada working directory dan file ini terbentuknya hidden.
 
 ![image](https://user-images.githubusercontent.com/115794875/196408313-945fe242-473b-4bd4-9d8e-86fde194bb36.png)


-  Lalu buat 1 file baru bernama README.md, dengan memasukan perintah echo “#latihan1” >> README.md. Lalu untuk melihat file ketik perintah “ls 

![image](https://user-images.githubusercontent.com/115794875/196408604-56ff4a95-1d6b-4c70-94bf-487a15eb245c.png)
 ##### Cara penggunaan git dengan perintah dasar git add  fungsi perintahnya untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit
- Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add. Dengan perintah $ git add README.md. Kalau ingin melihat infonya ketik perintah git status.
 ![image](https://user-images.githubusercontent.com/115794875/196408811-212ab03e-fe7c-426b-b65b-40e51e850381.png)

- Untuk menyimpan perubahan yang ada kedalam database gunakan perintah git commit -m “komentar commit"
  ![67557721-cadd1e80-f73f-11e9-8f44-dc52f8676eb3](https://user-images.githubusercontent.com/115677959/195979372-25d6dfbd-f125-4b89-9d0a-d4d48f5efc75.png)

##### *File berhasil tersimpan*

-  Langkah berikutnya kita kembali ke website GitHub untuk melihat repositori yang sudah dibuat.
Nah di Quick Setup nanti ada url github kita, url tersebut untuk perintah_ “git remote add origin [url] “ DAN PERINTAH GIT CLONE “ git clone [ url ] “_

 ##### Cara penggunaan git dengan perintah dasar  git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)

- Sudah mengetahui url githubnya lalu ketik perintah git remote add origin [url],urlnya diganti dengan url github anda https://github.com/adeliadhea06/latihan1.git
   ![image](https://user-images.githubusercontent.com/115794875/196409020-1f3390a2-bd5f-4064-84d1-cd74bd5973be.png)


 ##### Cara penggunaan git dengan perintah dasar git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository

- Untuk  mengirim perubahan pada local repository ke server gunakan perintah “git push -u origin master”. Ingat pada langkah ini kita harus memasukan username dan password gethub.
![image](https://user-images.githubusercontent.com/115794875/196409152-efda3b26-3819-455f-9f2c-79f3ecd4dfd4.png)

 ##### Cara penggunaan git dengan perintah dasar  git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.

- Kalau ingin melakukan cloning, gunakan perintah git clone [url], urlnya diganti dengan url github anda https://github.com/adeliadhea06/latihan1.git . Jika ingin masuk kedirektorti gunakan perintah “cd [nama direktori anda]”, dan jika ingin melihat semua isi direektori gunakan perintah “ls -1"
 ![image](https://user-images.githubusercontent.com/115794875/196409284-86a3de99-bdf6-4df6-b9df-bbd183f54d4e.png)


-  Selesai Jika ingin melihat hasilnya cek di laman gethub arahkan ke repositorinya
  
#### *FILE README.md tersebut masih kosong jikalau anda ingin mengisi kekosongan file tersebut silahkan klik saja icon pensil yang berada di kanan atas*.
### *Terimakasih*
