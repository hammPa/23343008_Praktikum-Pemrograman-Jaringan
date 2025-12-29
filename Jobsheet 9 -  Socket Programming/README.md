# Jobsheet 9 - Socket Programming
# Latihan

Dari latihan pada jobsheet ini, saya memperoleh pengalaman langsung dalam membangun aplikasi komunikasi real-time menggunakan Socket Programming berbasis WebSocket dengan Socket.IO. Saya mempelajari bagaimana server dan client dapat saling terhubung, sehingga memungkinkan pertukaran data dua arah secara langsung tanpa harus melakukan request berulang seperti pada HTTP biasa.

Melalui implementasi aplikasi ruang obrolan (chat room), saya memahami penggunaan event socket.on dan socket.emit untuk menangani komunikasi berbasis peristiwa (event-based communication), pengelolaan pengguna dalam suatu room, serta mekanisme broadcast pesan ke seluruh client yang berada dalam room yang sama. Selain itu, saya juga mempelajari penggunaan namespace dan room pada Socket.IO untuk memisahkan komunikasi antar kelompok pengguna.

# Tugas

1. Jelaskan dengan disertai penjelasan baris kode terkait perbedaan fungsi socket.on yang ada pada file index.js di folder src dan file chat.js pada folder public/js!



2. Pada saat anda melakukan proses chat seperti pada langkah 12 dan 13. Bukalah inspect pada browser anda. Lalu bukalah menu console. Lakukanlah proses chat dan investigasi apa yang ditampilkan pada console tersebut. Uraikan penjelasan anda dengan mengaitkannya ke baris kode yang menurut anda berhubungan dengan hal tersebut! 

xxx

3. Pada file chat.html dibagian akhir pada baris kode <script> terdapat penggunaan library mustache, moment dan qs. Jelaskan bagaimana ketiga library ini berfungsi dalam aplikasi yang anda buat, kaitkanlah dengan baris kode yang menurut anda berhubungan! 

xxx

4. Bukalah chat.js, dan perhatikan bahwa ada beberapa baris kode yang telah ditandai dengan komentar elements, templates dan options. Jelaskan baris kode tersebut dan bagaimana kode tersebut berhubungan dengan file chat.html dan file index.html! 

xxx

5. Jelaskan fungsi file messages.js dan users.js dan bagaimana baris kode pada kedua file ini terhubung dengan index.js, chat.js dan kedua file html (chat.html dan index.html) 

xxx

6. Bagaimana aplikasi ini bisa mengirimkan lokasi? Jelaskan apa yang terjadi dengan disertai penjelasan baris kode! 

xxx

7. Kenapa aplikasi ini dijalankan menggunakan perintah npm run dev bukan menggunakan perintah node diikuti nama file seperti pada jobsheet-jobsheet sebelumnya? Coba juga jalankan aplikasi menggunakan perintah npm run start, investigasi apa yang terjadi dan apa yang membedakannya dengan npm run dev? 

xxx

8. Selain socket.on, fungsi socket apa lagi yang digunakan dalam aplikasi ini. Silakan telusuri dan jelaskan pendapat anda disertai dengan baris kode! 

xxx

9. Jelaskan terkait ini real-time bidirectional event-based communication disertai penjelasan baris kode sesuai aplikasi yang anda buat!

xxx
