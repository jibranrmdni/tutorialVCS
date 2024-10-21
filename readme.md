# Cara Membuat Repository
<p>Dalam petunjuk ini, saya akan membahas bagaimana cara membuat repository baru di windows.</p>

## 1 persiapan
siapkan software bernama "git" bisa di download di website resmi https://git-scm.com/downloads

### installasi
jalankan setup git yang didownload dan akan muncul jendela seperti ini :
![jendela install](![home - Imgur](![git - Imgur](https://github.com/user-attachments/assets/cd8788bc-d93c-4aa8-bbdc-b45a4f77931e))
klik next saja sampai selesai dan install

## 2. Membuat akun Github
<p>Selanjutnya anda harus mempunyai akun github terlebih dahulu, jika anda belum pernah mendaftar, silahkan anda kunjungi website github.com lalu buat akun github</p>

### buat repository.
klik tombol "+" pada sudut kanan atas halaman web lalu klik "new repository"
![menambah repository](https://i.imgur.com/MqIEA8T.png)
maka akan mucul halaman di bawah ini :
![halaman penambahan repository](![home - Imgur](![repository - Imgur](https://github.com/user-attachments/assets/b08e30f0-5dd6-40b6-8773-53be4dda68d2)
)
)
isi nama repository sesuai keinginan anda lalu klik "create repository"

## 3 cara menggunakan git
buka software "git bash" yang sudah di install tadi, lalu ketikkan command line di bawah ini :

$ git config --global user.name "username yg anda buat di github"
$ git config --global user.email "email yg anda pakai untuk github"

contohnya seperti ini:
![contoh 1](![undefined - Imgur](![configgg - Imgur](https://github.com/user-attachments/assets/a5dacfeb-fac2-40c6-ac3e-72d6562b6a41))
lalu ketik command:

$ git config --list

maka akan muncul seperti ini:
![contoh 2](![git - Imgur (1)](![praktekkkkkk - Imgur](https://github.com/user-attachments/assets/2bb39c08-3f1a-41e3-8f90-91125ccd7402)
)


jika username dan email terisi sesuai yg anda ketik berarti berhasil
lalu buat folder untuk tempat menyimpan repository local di komputer anda dengan cara buat new folder di tempat yg anda suka contohnya:
![contoh 3](![gitt - Imgur](https://github.com/user-attachments/assets/f0958cc4-f3ce-46d0-9c25-1bd673c54ee8))

saya membuat folder "latihanvcs" di drive D
lalu klik kanan dan pilih "git bash here"
lalu ketik command:
```
$ git init
```
Lalu masukan perintah berikut untuk membuat file "readme.md"
```
$ echo "# Latihan1" >> readme.md
```
lalu ketik :
```
$ git add readme.md
```
setelah itu commit dengan cara :
```
$ git commit -m "komentar"
```
contohnya seperti ini:
![contoh 4](![git - Imgur (3)](![Cuplikan layar 2024-10-21 173022](https://github.com/user-attachments/assets/93daa808-0e8c-40af-a805-654dcec7a07f)
))

lalu ketik:
```
$ git remote add origin "link url repository di github"
```
contoh bisa dilihat di gambar sebelumnya
untuk mendapatkan link repository yg anda buat anda tinggal ke akun github anda
klik repository yg anda buat
![contoh 5](![posting - Imgur](![WhatsApp Image 2024-10-21 at 17 53 47_e4eb3c4c](https://github.com/user-attachments/assets/2e7d70dc-54a2-4a11-9f12-57d98e7bd59a)
))


lalu klik klik copy or download
![contoh 6](![copy or download - Imgur](https://github.com/user-attachments/assets/def8c62e-fa57-42ce-ba7c-3ec6087a0db3))


lalu ketik :
```
$ git push -u origin master
```
lalu anda akan diminta username dan password untuk login ke github anda dan selamat repository anda berhasil di isi (upload) dengan file readme.md silahkan cek repository anda di github dan anda akan melihat perubahan yg tadinya kosong menjadi berisi file readme.md

