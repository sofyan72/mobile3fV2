Rangkuman Minggu ke 9

Menghubungkan Laravel dengan Flutter

Tujuuan: Membuat Aplikasi mobile flutter degan menggunakan Laravel

Setelah Pertemuan minggu lalu teman kami membahas tentang cara membuat projek Laravel dengan menggunakan API yang akan dihubungkan dengan Flutter. Untuk Minggu ke 9 teman kami melanjutkan pengerjaan projek minggu lalu.

 Pada perrcobaan kali ini masih tetap menggunakan aplikasi Postman, dan mempelajari yaitu. Mempelajari untuk menginputkan data melalui php artisan tinker, biasanya kita menggunakan phpMyAdmin untuk memasukkan data tetapi kali in kita mempeljari input data melalui php artisan tinker. 
php artisan tinker sendiri adalah semacam aplikasi REPL (read-eval-print-loop, atau aplikasi interaktif yang berjalan di aplikasi konsole seperti terminal dan command prompt) untuk PHP. Dengan Tinker kita bisa berinteraksi dengan aplikasi Laravel melalui perintah-perintah di terminal. Kita bisa berinteraksi dengan Eloquent ORM, dengan event, dan lain-lain.
 Setelah itu membuat controller yang diberi nama AuthController yang memiliki tiga fungsi yaitu, Registrasi, Login, dann Logout.
Selanjutnya mempelajari cara menggunakan dan membuat auth menggunakan auth sanctum. Laravel sanctum menyediakan featherweight authentication system untuk Single Page Application (SPA), mobile application dan API berbasis token yang sederhana. Sanctum memungkinkan setiap pengguna aplikasi menghasilkan beberapa token API untuk akun mereka. Token ini dapat diberikan kemampuan atau cangkupan yang menentukan tindakan mana yang diizinkan untuk dilakukan oleh token.
Selanjutnya pengujian penggunaan fungsi pada controller yang sua dibuat sebelumnya yaitu AuthController dengan mnggunakan Postman, kita akan mendapatkan token saat melakukan login dan token itu untuk mengakses data pada Postman. 
Setelah itu pada apliksi Postman akan melakkan pengujian Registrasi dan mendapatka token yang nanti akan digunakan untuk proses Login ataupun Logout.

Link Repo : https://github.com/SriKynanti/flutter-api

Link Dasboard Wakatime : https://github.com/SriKynanti/SriKynanti_Dasboard-img/blob/master/wakatime09.md
