# perbandingan-scanning-network
# Nmap

Nmap (Network Mapper) merupakan tools open-source yang digunakan untuk eksplorasi jaringan dan audit keamanan. Di Kali Linux, Nmap sangat populer di kalangan profesional keamanan untuk melakukan pemetaan jaringan, deteksi host, identifikasi layanan, dan pengujian kerentanan. Berikut adalah beberapa fungsi utama Nmap di Kali Linux:

berikut merupakan beberapa command yang dapat digunakan untuk melakukan scanning network

1. Nmap dapat memindai IP atau jaringan tertentu untuk menemukan host yang aktif dan port terbuka, berikut merupakan contoh command : nmap (nama website)

![nmap 1](https://github.com/user-attachments/assets/7ba4d761-2622-4763-acc6-ccb8af6220e3)

2. Nmap dapat mengenali versi layanan (seperti HTTP, FTP, atau SSH) yang berjalan di host tertentu, berikut merupakan contoh command : nmap -sV (nama website)

![nmap 2](https://github.com/user-attachments/assets/baf9b8a7-df72-40cd-84f1-2e85cb11c9e2)

3. Dengan menggunakan script Nmap (Nmap Scripting Engine - NSE), pengguna bisa memindai kerentanan di layanan yang ditemukan, berikut merupakan Contoh command: nmap --script=vuln 192.168.1.1
   akan menjalankan skrip deteksi kerentanan umum.

4. Nmap bisa digunakan untuk mendeteksi jenis sistem operasi yang digunakan oleh host, serta detail tentang versinya, berikut Contoh command: nmap -O 192.168.1.1
   akan mencoba mendeteksi sistem operasi host tersebut.
