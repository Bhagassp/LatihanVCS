## Latihan 1
## TUTORIAL MENGGUNAKAN GIT

# Requirements
- [Git](https://git-scm.com/download)

# Informasi
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
<<<<<<< HEAD
![gambar1](Screenshoot/1.png)
=======
<img src="https://user-images.githubusercontent.com/92350818/137706412-ed0da6a8-f4f9-4589-8c6e-068c62497d77.png">
>>>>>>> d21a7f995d39ebe66c7609e67ba7fcf5079b30d1

- Jalankan perintah git init. untuk membuat repository local
```bash
> git init
```
<<<<<<< HEAD
![gambar2](Screenshoot/2.png)
=======
<img src="https://user-images.githubusercontent.com/92350818/137707325-eebaf827-1f36-4b4a-be59-916c2bd2d3b8.png">
>>>>>>> d21a7f995d39ebe66c7609e67ba7fcf5079b30d1

- Untuk membuat file dapat menggunakan Text Editor, Lalu menyimpan
filenya pada repository. Sebagai contoh disini saya akan membuat file README.md dengan perintah berikut
```bash
> echo "# Latihan1" >> README.md
```
<<<<<<< HEAD
![gambar3](Screenshoot/3.png)
=======
<img src="https://user-images.githubusercontent.com/92350818/137707461-5f807515-73ba-40d6-b985-0ef67819eb54.png">
>>>>>>> d21a7f995d39ebe66c7609e67ba7fcf5079b30d1

- Untuk menambahkan file yang sudah kita buat, gunakan perintah git add (Nama File) atau bisa menggunakan git add . (Jika file nya ada banyak)
```bash
> git add README.md
> git add .
```
<<<<<<< HEAD
![gambar4](Screenshoot/4.png)
=======
<img src="https://user-images.githubusercontent.com/92350818/137708550-695a32b7-b6f4-46d9-bc25-51f6f8c1a5d1.png">
>>>>>>> d21a7f995d39ebe66c7609e67ba7fcf5079b30d1

- Untuk menyimpan perubahan yang ada kedalam database repository
local, gunakan perintah git commit -m "nama project"
- Dan yang ada di dalam tanda kutip " " itu nama project kita dan jangan sama setiap kali kita upload project
```bash
> git commit -m "First Project"
```
<<<<<<< HEAD
![gambar5](Screenshoot/5.png)
=======
<img src="https://user-images.githubusercontent.com/92350818/137708995-bae1b261-6e55-4599-be38-5c2de7c987cb.png">
>>>>>>> d21a7f995d39ebe66c7609e67ba7fcf5079b30d1

- Untuk menyimpan setiap perubahan pada repository local, gunakan perintah git remote add origin (url)
```bash
> git remote add origin https://github.com/kyuurazz/LatihanVCS.git
```
<<<<<<< HEAD
![gambar6](Screenshoot/6.png)
=======
<img src="https://user-images.githubusercontent.com/92350818/137709107-0db3858d-fc30-419e-b157-3aee60ff1fe9.png">
>>>>>>> d21a7f995d39ebe66c7609e67ba7fcf5079b30d1

- Untuk mengirim perubahan pada repository local ke server, gunakan perintah git push
- Perintah ini akan meminta Username dan Password pada akun github mu
```bash
> git push -u origin master
```
<<<<<<< HEAD
![gambar7](Screenshoot/7.png)

- Selesai

# TERIMAKASIH
=======
<img src="https://user-images.githubusercontent.com/92350818/137709168-6d3179ea-dea5-469b-8832-de67263a9320.png">

- Selesai

# TERIMAKASIH
>>>>>>> d21a7f995d39ebe66c7609e67ba7fcf5079b30d1
