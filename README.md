1. Instalasi Git
2. Download Git, buka website resminya Git (git-scm.com).
3. Kemudian unduh Git sesuai dengan arsitektur komputer kita. Kalau
4. menggunakan 64bit, unduh yang 64bit. Begitu juga kalau menggunakan 32bit.
download git
5.Selamat, Git sudah terinstal di Windows. Untuk mencobanya,silahkan buka CMD atau PowerShell, kemudian
git version

6. Menambahkan Global Config,Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi user.name dan user.email
7.konfigurasi ini bisa dilakukan untuk global repostiry atau individual repository. apabila belum dilakukan konfigurasi akan terjadi
8.kegagalan saat menjalankan perintah *git commit Config Global Repository
git config

9. Perintah Dasar Git,Buka direktory aktif, misal: d:\latihan1y(buka menggunakan Windows Explorer) klik kanan pada direktory
aktif tersebut, dan pilih menu Git Bash,
11.sehingga muncul git bash commad git bash2
12. Buat direktory project praktikum pertama dengan nama --latihan1--
13. Sehingga terbentuk satu direktori baru dibawahnya, selanjutnya masuk kedalam direktori tersebut dengan perintah cd direktory
aktif menjadi: d:\latihan1 git cd mkdir

14. Membuat Repository Local Jalankan perintah git init, untuk membuat repository local Repository baru berhasil di inisialisasi,
15.dengan terbentuknya satu direktori hidden dengan nama .git Screenshot git init

16. Pada direktori tersebut, semua perubahan pada working directoryakan disimpan. Menambahkan File baru pada repositor untuk membuat
17. file dapat menggunakan text editor, lalu menyimpan filenya pada direktori aktif (repository disini kita akan coba buat satu file
bernama README.md (text file)
GIT README

18. File README.md berhasil dibuat.Menambahkan File baru pada repository Untuk menambahkan file yang baru saja dibuat tersebut
gunakan perintah git add. File README.md berhasil ditambahkan. file add readme Commit (Menyimpan perubahan ke database)
20. Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah git commit -m “komentar commit”
21. Perubahan berhasil disimpan. $ git commit -m “File pertama"
git commit1

22. Membuat repository server, server reopsitory yang akan kita gunakan adalah http://github.com
23. Anda harus membuat akun terlebih dahulu.Pada laman github, klik tombol start a project, atau Dari menu (icon +) klik New
Repository
github resipotry Membuat repository server

24. Isi nama repositorynya, misal: labpy1. lalu klik tombol Create repository git labpy1
25. Menambahkan Remote Repository, Remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap
26.erubahan pada local repository, sehingga dapat diakses oleh banyak user.
27. Untuk menambahkan remote repository server, gunakan perintah git remote add origin URL
git origin

28. Push (Mengirim perubahan ke server) Untuk mengirim perubahan pada local repository ke server gunakan perintah git push.
29. Perintah ini akan meminta memasukkan username dan password pada akun github.com
git push origin

30. Melihat hasilnya pada server repository buka laman github.com,arahkan pada repositorinya.
31. Maka perubahan akan terlihat pada laman tersebut.beranda git
32. Clone repository, pada dasarnya adalah meng-copy repository server dan secara otomatis membuat satu direktory sesuai dengan nama
33. repositorynya (working directory).Untuk melakukan cloning, gunakan perintah git cloneh(url)
git clone

34. Kegunaan file README.md, Apabila kita menggunakan github, untuk memberikan penjelasan awal pada project yang kita buat, maka
35. dapat menggunakan sebuah file yang bernama README.md Pada file tersebut kita dapat membuat dokumentasi awal dari setiap projec

![](Screenshot/Screenshot (1).png)
