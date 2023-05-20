## Latihan Menggunakan Git
## TUTORIAL MENGGUNAKAN GIT

<p align="center">
 <img src="https://user-images.githubusercontent.com/91085882/137566814-9c8c078c-1c3e-475c-b23d-7f4922f74beb.gif"/>
</p>
<p align="center">
<a href="https://github.com/akmalabdilah"><img title="Author" src="https://img.shields.io/discord/102860784329052160?color=BLUE&label=M.%20AKMAL%20AL%20ABDILAH1&logo=GITHUB&logoColor=BLACK&style=plastic"></a>
<p align="center">

<p align="center">
<a href="https://github.com/akmalabdilah/tugas-permogra#Requirements">Requirements</a> •
<a href="https://github.com/akmalabdilah/tugas-permogra#informasi-git">Informasi</a> •
<a href="https://github.com/akmalabdilah/tugas-permogra#Tutorial">Tutorial</a>
</p>
</div>

# Requirements
- [Git](https://git-scm.com/download)

# Informasi Git
Apa itu Git?
<p>
Git merupakan software berbasis Version Control System (VCS) yang bertugas untuk mencatat perubahan seluruh file atau repository suatu project. Developer software biasa menggunakan Git untuk distributed revision (VCS terdistribusi), hal ini bertujuan untuk menyimpan database tidak hanya ke satu tempat. Namun semua orang yang terlibat dalam penyusunan kode dapat menyimpan database ini.
</p>

# Tutorial
- Pada saat pertama kali menggunakan Git, perlu dilakukan konfigurasi
Username dan Email. Jalankan perintah berikut:
```bash
> git config --global user.name "username"
> git config --global user.email "email"
```
![Gambar 1](Screenshots/ss1.JPG)

- Jalankan perintah git init. untuk membuat repository local
```bash
> git init
```
![Gambar 2](Screenshots/ss2.JPG)

- Untuk membuat file dapat menggunakan Text Editor, Lalu menyimpan
filenya pada repository. Sebagai contoh disini saya akan membuat file README.md dengan perintah berikut
```bash
> echo "# Latihan1" >> README.md
```
![Gambar 3](Screenshots/ss3.JPG)

- Untuk menambahkan file yang sudah kita buat, gunakan perintah git add (Nama File) atau bisa menggunakan git add . (Jika file nya ada banyak)
```bash
> git add README.md
> git add .
```
![Gambar 4](Screenshots/ss4.JPG)

- Untuk menyimpan perubahan yang ada kedalam database repository
local, gunakan perintah git commit -m "nama project"
- Dan yang ada di dalam tanda kutip " " itu nama project kita dan jangan sama setiap kali kita upload project
```bash
> git commit -m "First Project"
```
![Gambar 5](Screenshots/ss5.png)

- Untuk menyimpan setiap perubahan pada repository local, gunakan perintah git remote add origin (url)
```bash
> git remote add origin https://github.com/kyuurazz/LatihanVCS.git
```
![Gambar 6](Screenshots/ss6.png)

- Untuk mengirim perubahan pada repository local ke server, gunakan perintah git push
- Perintah ini akan meminta Username dan Password pada akun github mu atau klik Sign in with your browser
```bash
> git push -u origin master
```
![Gambar 7](Screenshots/ss7.png)

- Jika sudah berhasil, maka tampilan nya akan seperti dibawah ini
![Gambar 8](Screenshots/ss8.png)

- Dan file sudah berhasil di upload ke Github anda
![Gambar 9](Screenshots/ss9.png)

- Selesai


<div>
<h2 align="center">Thanks For Reading!!!</h2>
<div align="center">
<img src="https://user-images.githubusercontent.com/91085882/222731693-24383140-7623-4e7a-a528-6621380b7be8.gif">
