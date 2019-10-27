A. Membuat reposiory lokal
  
	1. langkah pertama buat folder baru dan beri nama latihangit
	2. buka folder baru lalu kelik kanan lalu pilih GIT BASH HERE
	3. setelah tampilan GIT BASH keluar lalu ketik $ mkdir latihan1 lalu enter
	4. setelah jadi folder latihan1 lalu masuk kedalam folder dengan perintah $ cd latiahan1
	5. setelah muncul tulisan : d:/latiahangit\latiahan1 berati direktory sudah aktif
	6. jalankan perintah $ git init untuk membuat reposiory local
	7. reposiory baru berhasil di inisialisasi, dengan terbentuknya satu direktori hidden dengan .git
	8. pada derektori tersebut, semua perubahan pada working directory akan disimpan

B. Menambahkan file baru pada repository

	1. Untuk membuat file dapat menggunakan text editor, lalu menyimpan filenya pada direktori aktif (repository)
	2. disini kita akan coba buat satu file bernama README.md (text file)
	3. File README.md berhasil dibuat.
	4. Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add.

C.Commit (Menyimpan perubahan ke database)

	1. Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah git commit -m “komentar commit”

D. Membuat repository server

	1. Server reopsitory yang akan kita gunakan adalah http://github.com
	2. Anda harus membuat akun terlebih dahulu.
	3. Pada laman github, klik tombol start a project, atau
	4. Dari menu (icon +) klik New Repository

E. Membuat repository server

	1. Isi nama repositorynya, misal: labpy1.
	2.lalu klik tombol Create repository

F. Menambahkan Remote Repository

	1. Remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository, sehingga dapat diakses oleh banyak user.
	2. Untuk menambahkan remote repository server, gunakan perintah git remote add origin [url]

G. Push (Mengirim perubahan ke server)

	1. Untuk mengirim perubahan pada local repository ke server gunakanperintah git push,$ git push -u origin master
	2. Perintah ini akan meminta memasukkan username dan passwordpada akun github.com 

H. Melihat hasilnya pada server repository

	1. Buka laman github.com,arahkan pada repositorinya.
	2. Maka perubahan akan terlihat pada laman tersebut.

I. Clone Repository

	1. Clone repository, pada dasarnya adalah meng-copy repository server dan secara otomatis membuat satu direktory sesuai dengan nama repositorynya (working directory).
	2. Untuk melakukan cloning, gunakan perintah git clone [url]