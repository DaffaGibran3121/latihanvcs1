# latihanvcs1
## TUTORIAL MENGGUNAKAN GIT
<p align="center">

 ![137566814-9c8c078c-1c3e-475c-b23d-7f4922f74beb](https://user-images.githubusercontent.com/92356397/137698494-f02cc591-2d95-4bcc-9db0-1258d6dd567f.gif)


 
 <a href="https://api.whatsapp.com/send?phone=6287888660568"><img alt="WhatsApp" src="https://img.shields.io/badge/My-Whatsapp-%23017e40?style=for-the-badge&logo=whatsapp&logoColor=white"/></a>

## Requirements
* Git
## Informasi
Apa itu Git?

Git merupakan software berbasis Version Control System (VCS) yang bertugas untuk mencatat perubahan seluruh file atau repository suatu project. Developer software biasa menggunakan Git untuk distributed revision (VCS terdistribusi), hal ini bertujuan untuk menyimpan database tidak hanya ke satu tempat. Namun semua orang yang terlibat dalam penyusunan kode dapat menyimpan database ini.

## Tutorial
Pada saat pertama kali menggunakan Git, perlu dilakukan konfigurasi Username dan Email. Jalankan perintah berikut:
>git config --global user.name "username"

>git config --global user.name "email"
 
 ![Gambar (1)](https://user-images.githubusercontent.com/92356397/137681860-4cc56892-8a73-4343-a1f0-2ffd13624c71.png)
 Jalankan perintah git init. untuk membuat repository local
> git init

![Gambar (2)](https://user-images.githubusercontent.com/92356397/137681766-a954b9b3-a437-4608-a21a-163c82d3d946.png)
Untuk membuat file dapat menggunakan Text Editor, Lalu menyimpan filenya pada repository. Sebagai contoh disini saya akan membuat file README.md dengan perintah berikut
> * echo "# Latihan1" >> README.md

![Gambar(3)](https://user-images.githubusercontent.com/92356397/137681674-3e420cd9-1ab9-4588-a07e-e87a3ca2c896.png)
* Untuk menambahkan file yang sudah kita buat, gunakan perintah git add (Nama File) atau bisa menggunakan git add . (Jika file nya ada banyak)
> git add README.md
> git add .

![Gambar (4)](https://user-images.githubusercontent.com/92356397/137681518-7645f7e8-f720-4249-8ee6-c637f43fb41e.png)
Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah git commit -m "nama project"
Dan yang ada di dalam tanda kutip " " itu nama project kita dan jangan sama setiap kali kita upload project
> git commit -m "First Project"
![Screenshot (18)](https://user-images.githubusercontent.com/92356397/137696063-4d0ccfbf-0195-462d-b532-c7dc9b7e0e62.png)
Untuk menyimpan setiap perubahan pada repository local, gunakan perintah git remote add origin (url)
> git remote add origin https://github.com/DAFFAGIBRAN3121/latihanvcs1.git

![Screenshot (19)](https://user-images.githubusercontent.com/92356397/137696962-b4e9faab-3570-49a6-8db0-9ee213ab9936.png)
Untuk mengirim perubahan pada repository local ke server, gunakan perintah git push
Perintah ini akan meminta Username dan Password pada akun github mu
> git push -u origin master

![Screenshot (17)](https://user-images.githubusercontent.com/92356397/137690311-1349ceda-b87b-4e20-8e62-14ae5848914a.png)
Selesai
## TERIMAKASIH
