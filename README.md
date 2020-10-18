Nama    : Rurelawati

NIM     : 312010377

Kelas   : TI.20.A.2


Latihan 1
1. Langkah pertama membuat folder "program 1", saya membuat folder di dekstop komputer.
2. Klik kanan pada folder yang sudah dibuat tadi lalu klik terminal "git bush here" lalu akan muncul gambar seperti berikut:
![1 1](https://user-images.githubusercontent.com/72727632/96370055-ceef2100-1186-11eb-9026-c4fab7952a28.png)

3. Kemudian membuat folder dengan mengetik pada terminal "mkdir latihan1"
![1 2](https://user-images.githubusercontent.com/72727632/96370206-41f89780-1187-11eb-8067-ec5a7a7b281a.png)
setelah itu, program 1 akan ada folder baru di dalamnya yaitu "latihan1"

4. Langkah selanjutnya masuk ke dalam folder "latihan1" dengan mengetik "cd latihan1", seperti berikut:
![1 3](https://user-images.githubusercontent.com/72727632/96370424-eda1e780-1187-11eb-86ab-b828c21b4123.png)

5. Buatlah folder tersebut menjadi repo (repository) dengan cara "git init". jika benar ada gambar akan seperti dibawah ini:
![1 4](https://user-images.githubusercontent.com/72727632/96370570-85073a80-1188-11eb-84d9-474c5a57ce46.png)
jika sudah seperti ini artinya folder sudah menjadi repo

6. Setelah itu buat file README.md dengan mengetik "echo latihan1 >>README.md" 
![1 5](https://user-images.githubusercontent.com/72727632/96370600-9a7c6480-1188-11eb-8e1e-31ee8feef3bf.png)

7. Check file, apakah sudah terdaftar atau belum, dengan mengetik "git status", seperti ini:
![1 6](https://user-images.githubusercontent.com/72727632/96370609-9f411880-1188-11eb-8629-1af7615fd15d.png)
warna merah tersebut menandakan file belum di add.

8. Selanjutnya ketik "git add <file>" atau jika file yang berwarna merah lebih dari satu ketik (git add.)
![1 7](https://user-images.githubusercontent.com/72727632/96371087-45415280-118a-11eb-9bd5-1894a0112ec1.png)
untuk kembali mengecek apalkah sudah terdaftar, klik kembali "git status" 
![1 8](https://user-images.githubusercontent.com/72727632/96371172-9f421800-118a-11eb-80e0-f0977d27efeb.png)
maka warna file akan berubah menjadi warna hijau. tanda nya sudah di add
  
9. Langkah selanjutnya commit file tersebut dengan mengetik (git commit -m "pesan") 
![1 9](https://user-images.githubusercontent.com/72727632/96371390-bcc3b180-118b-11eb-8b8d-d220020d6571.png)
 jika tidak ada masalah, maka menambah file baru selesai dan terlihat seperti gambar diatas.

10. Langkah selanjutnya membuat akun github http:github.com
11. Jika sudah membuat akun github, buatlah repositori yang bar dengan klik "new repository"
![2 0](https://user-images.githubusercontent.com/72727632/96371571-7ae73b00-118c-11eb-83e3-fb691cb4f7f6.png)

11. Selanjutnya mengisi nama repositorinya "Repository name"
![2 1](https://user-images.githubusercontent.com/72727632/96371718-5c357400-118d-11eb-9eee-0a3dfda7873b.png)
- isi nama repositorry nya dengan nama "latihan_VCS" , untuk nama repository bisa menyesuaikan sesuai keperluan.
- selanjutnya isi description. diusahakan sejelas mungkin agar memudahkan pencarian.
- pilih public
- lalu create repositorinya.

12. Setelah create repositorinya, maka akan muncul gambar sebagi berikut:
![2 2](https://user-images.githubusercontent.com/72727632/96371914-69069780-118e-11eb-922b-30bccd5e42de.png)
copy link tersebut untuk menghubungkan antara akun github dengan akun git yang ada di laptop/pc.

13. Cara menghubungkannya, ketiklah "git remote add origin <link>"
![2 3](https://user-images.githubusercontent.com/72727632/96372052-41fc9580-118f-11eb-99b4-ccd0f5647769.png)

14. Langkah selanjutnya ketik "git push -u origin master"
![2 4](https://user-images.githubusercontent.com/72727632/96372194-01e9e280-1190-11eb-94f8-c14084cbbc13.png)
dan file sudah terhubung dengan git anda.



Pesan:
- mkdir <file name> (untuk membuat file baru)
- git init (untuk membuat depository local)
- git status (untuk mengecek apakah ada perubahan di dalam file)
- git add (untuk menambahkan file baru)
- git commit (untuk menyimpan perubahan ke dalam database git)
- git remote (untuk menghubungkan file ke github)
- git push (untuk mengupload file ke github)
