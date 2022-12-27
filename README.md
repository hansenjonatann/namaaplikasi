# namaaplikasi
Project yang sedang dikembangkan bersama tim

Aturan - aturan yang harus dipatuhi di dalam proyek namaaplikasi 

- Branch <b>main</b> adalah branch yang digunakan ketika proses staging selesai dan product akan dirilis 
- Branch <b>staging</b> adalah branch yang digunakan ketika proses dari branch dev selesai dan akan dimasukkan sebagai rilis beta 
- Branch <b>dev</b> adalah branch yang digunakan oleh developer tim yaitu tempat developer meletakkan kodingan dan source code sehingga tidak mengganggu branch utama atau Main 

Alur kerja :

Dev ---> Staging ---> Main

Main akan dilakukan jika semua anggota tim sudah menyetujui tentang perubahan yang dilakukan 

Alur pengerjaan ketika di dalam code editor dan menggunakan terminal git bash 

1. <b>Git pull</b> digunakan untuk mengambil source code dari repository github dengan nama "namaaplikasi"
2. <b> Git add . </b> digunakan untuk menambahkan file dari komputer local ke dalam repostitory 
3. <b> Git commit -m "namaperubahan" </b> digunakan untuk mengkonfirmasi perubahan yang terjadi di dalam repository github .
4. <b> git branch -M dev </b> digunakan untuk memindahkan branch main ke branch dev agar kodingan dapat dipush ke dalam repository branch dev 
5. <b> git push origin dev </b> digunakan untuk melakukan pemindahan file ke dalam repository github branch dev .



<b>Copyright 2022 Hansen Jonatan & Tim </b>


