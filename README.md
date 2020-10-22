# LatihanVCS9 

 ### Nama : Muhammad Rifai Aditia
 ### Kelas : TI.20.A.1
 ### NIM : 312010065

 ### LANGKAH AWAL MENGGUNAKAN GIT

* ### CARA MENDOWNLOAD GIT
   
   Download git terlebih dahulu,dengan link berikut :click Here

   ![gitscm](foto/gitscm.png) <br>

   setelah file terdownload silahkan lakukan instalasi dengan referensi berikut ini : Git installation guide

   ![owen](foto/owen.png) <br>

   setelah installasi selesai,buka GitBash pada menu di windows, dan lakukan pengecekan versi,dengan mengetik syntax berikut :
git --version

![gitversion](foto/gitversion.png) <br>

jika muncul tampilan git version, berarti Git sudah berhasil di install dan bisa di gunakan Langkah pertama kita mengkonfirmasikan user email dan user name kalian

![useremail](foto/useremail.png) <br>

buat akun di GitHub,seperti contoh dibawah ini. Dan lakukan verifikasi akun melalui email yang sudah terdaftar.

jika akun GitHub sudah selesai dibuat dan di verifikasi, proses selanjutnya silahkan buat Repository seperti gambar dibawah ini :
penjelasan

Repository Name : (Silahkan isi nama repository yan diinginkan seperti contoh saya ingin membuat repository Latihanvcs3)
Description : (Isi dengan deskripsi atau penjelasan tentang repository Anda)
Public / Private : (Pilih salah satu jenis repository akan bisa dilihan sama semua orang atau tidak)
Add a README.md file : Centang pada bagian ini jika Anda menginginkan file README.md ada di repository Anda
Add .gitignore : Merupakan sebuah file yang berisi daftar nama-nama file dan direktori yang akan diabaikan oleh Git.
Choose a license : Silahkan centang jika Anda memiliki lisensi pada repository yang akan dibuat Kemudian tekan tombol Create Repository untuk menyimpan

![lanjutan](foto/lanjutan.png) <br>

ika repository sudah dibuat maka akan muncul tampilan seperti dibawah ini :

![maemunah](foto/maemunah.png)  <br>

Pembuatan akun dan repository pada Github telah selesai, saat ini akan kita lakukan untuk me-remote repository Github pada GitBash Lokal. Bagaimana caranya? Langkah pertama kita harus menyalin link URL git kita di Github, dengan cara tekan tombol Code lalu klik Copy.

![arum](foto/arum.png) <br>

Setelah Link URL git kita tercopy, Silahkan buka File Explorer pada Windows, kemudian pilih folder dimana kita akan mendownload Repository dari Github ke lokal. Kemudian Klik Kanan, Pilih Git Bash Here.

![berlin](foto/berlin.png) <br>

Pop Up Command Prompt (CMD) akan terbuka. Pada proses ini kita akan melakukan download file repository yang tadi dibuat, dengan mengetikkan syntax berikut :

git clone [URL] pada contohnya, saya akan memasukan git clone:https://github.com/adit567/LatihanVCS9.git

![sobha](foto/sobha.png) <br>

Setelah proses cloning selesai, pada saat ini kita masih pada folder awal, kita harus masuk kedalam folder yang telah dicloning tadi yaitu LatihanVCS dengan mengetikkan syntax berikut : cd Latihan18/

![zulfi](foto/zulfi.png) <br>

Saat ini kita sudah masuk kedalam folder LatihanVCS, Silahkan edit file README.md yang ada di File Explorer. Bisa menggunakan Text Editor *(Sublime Text, Notepad, Notepad++, Visual Studio Code). Edit sesuai dengan keinginan. Aturan file .md (Markdown) bisa dilihat di Link berikut ini : click here

![ikky](foto/ikky.png)

Setelah file README.md diedit, silahkan Simpan file tersebut dengan cara CTRL+S atau File -> Save

Langkah selanjutnya setelah file disimpan, kita kembali pada App Git Bash (CMD). Ketik pada Git Bash seperti berikut ini :
git add.

![ziddan](foto/ziddan.png) <br>

Setelah selesai melakukan git add . langkah berikutnya kita akan melakukan *commit. Fungsi commit adalah untuk menyimpan perubahan yang dilakukan, tetapi tidak ada perubahan pada remote repository. Ketik pada App Git Bash seperti berikut ini : git commit
"Update README.md"

![gilang](foto/gilang.png) <br>

Git commit telah selesai di lakukan. Untuk saat ini akan melakuka Git Push, Git Push berfungsi untuk mengirimkan perubahan file setelah di commit ke remote repository. Silahkan ketik pada App Git Bash seperti berikut : git push

![riris](foto/riris.png) <br>