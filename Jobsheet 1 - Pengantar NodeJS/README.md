# Jobsheet 1 - Pengantar Node.js

1. **Pemrograman Jaringan**  
   Pemrograman jaringan adalah bidang dalam ilmu komputer yang fokus pada pengembangan aplikasi yang memungkinkan komunikasi, pertukaran data, dan interaksi antar perangkat melalui jaringan, baik **LAN (Local Area Network)** maupun **WAN (Wide Area Network)**.

2. **Konsep Utama dalam Pemrograman Jaringan**  
   - **Client-Server Architecture** → Klien mengirim permintaan, server merespons.  
   - **Protokol Jaringan** → Aturan komunikasi (contoh: HTTP, SMTP).  
   - **Socket** → Titik akses aplikasi untuk berkomunikasi melalui jaringan (TCP/UDP).  
   - **Sinkron & Asinkron** → Sinkron menunggu respon, Asinkron tidak menunggu (lebih efisien).  
   - **Pemrograman Web** → Aplikasi berbasis server, diakses lewat browser.  
   - **Pemrograman Mobile** → Aplikasi mobile umumnya menggunakan REST API untuk komunikasi dengan server.

3. **Peran Node.js dalam Pemrograman Jaringan**  
   Node.js adalah **runtime JavaScript di sisi server** yang mendukung pemrograman **asinkron & event-driven**, sehingga:  
   - Responsif dan efisien dalam mengelola I/O.  
   - Cocok untuk aplikasi berskala besar dengan banyak koneksi.  
   - Memiliki **event loop** untuk mengelola proses asinkron tanpa blocking.  

4. **Keunggulan Node.js**  
   - **Efisiensi Skalabilitas** → Mampu menangani banyak koneksi dengan resource minimal.  
   - **Responsivitas Tinggi** → Tetap cepat meski operasi I/O lambat.  
   - **Cross-Platform** → Bisa dijalankan di Windows, Linux, dan macOS.  
   - **Integrasi JS Client-Server** → Satu bahasa untuk frontend & backend.  
   - **Ekosistem NPM** → Tersedia ribuan modul siap pakai.  

## Kesimpulan Latihan B
- Latihan ini menunjukkan cara membuat file JavaScript sederhana (`hello.js`) lalu menjalankannya menggunakan **Node.js**.  
- Node.js mampu mengeksekusi kode JavaScript langsung dari terminal tanpa memerlukan browser.  
- Hal ini membuktikan bahwa **Node.js adalah runtime environment** yang mengeksekusi JavaScript di sisi server.  

## Kesimpulan Latihan C
- Latihan ini menunjukkan untuk membuat file `hello-world.js` yang menjalankan **server HTTP sederhana** dengan Node.js.  
- Setelah dijalankan, server dapat diakses melalui browser pada alamat `http://127.0.0.1:3000/`.  
- Latihan ini menjadi dasar penting dalam **pemrograman jaringan**, karena Node.js menyediakan modul bawaan seperti `http` untuk membuat server dengan cepat dan efisien.  
