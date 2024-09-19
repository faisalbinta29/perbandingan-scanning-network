# perbandingan-scanning-network
# Nmap

Nmap (Network Mapper) merupakan tools open-source yang digunakan untuk eksplorasi jaringan dan audit keamanan. Di Kali Linux, Nmap sangat populer di kalangan profesional keamanan untuk melakukan pemetaan jaringan, deteksi host, identifikasi layanan, dan pengujian kerentanan. Berikut adalah beberapa fungsi utama Nmap di Kali Linux:

berikut merupakan beberapa command yang dapat digunakan untuk melakukan scanning network

1.Nmap dapat memindai IP atau jaringan tertentu untuk menemukan host yang aktif dan port terbuka, berikut merupakan contoh command : nmap (nama website)

![nmap 1](https://github.com/user-attachments/assets/7ba4d761-2622-4763-acc6-ccb8af6220e3)

2.Nmap dapat mengenali versi layanan (seperti HTTP, FTP, atau SSH) yang berjalan di host tertentu, berikut merupakan contoh command : nmap -sV (nama website)

![nmap 2](https://github.com/user-attachments/assets/baf9b8a7-df72-40cd-84f1-2e85cb11c9e2)

3.Dengan menggunakan script Nmap (Nmap Scripting Engine - NSE), pengguna bisa memindai kerentanan di layanan yang ditemukan, berikut merupakan Contoh command: nmap --script=vuln 192.168.1.1
akan menjalankan skrip deteksi kerentanan umum.

4.Nmap bisa digunakan untuk mendeteksi jenis sistem operasi yang digunakan oleh host, serta detail tentang versinya, berikut Contoh command: nmap -O 192.168.1.1 
akan mencoba mendeteksi sistem operasi host tersebut.

# Zenmap

Zenmap adalah antarmuka grafis resmi untuk Nmap. Zenmap dirancang untuk membuat penggunaan Nmap lebih mudah, terutama bagi pengguna yang kurang familiar dengan perintah baris (command line interface). Dengan Zenmap, pengguna dapat melakukan pemindaian jaringan, melihat hasil secara visual, dan menyimpan profil pemindaian untuk digunakan kembali di masa depan.

Fitur Utama Zenmap:
Antarmuka Visual: Zenmap menyediakan antarmuka yang mudah digunakan dengan opsi-opsi yang intuitif, yang memungkinkan pengguna untuk mengonfigurasi pemindaian tanpa harus menulis perintah Nmap secara manual.

Profil Pemindaian: Zenmap memiliki fitur untuk menyimpan dan mengelola profil pemindaian. Pengguna bisa membuat profil dengan konfigurasi tertentu dan menggunakannya kembali di lain waktu, sehingga memudahkan pengulangan pemindaian jaringan.

Visualisasi Topologi Jaringan: Zenmap dapat menampilkan topologi jaringan secara visual setelah pemindaian selesai. Pengguna dapat melihat perangkat apa saja yang terhubung dalam jaringan, rute yang digunakan, dan status perangkat tersebut.

Penyimpanan Hasil Pemindaian: Zenmap memungkinkan pengguna untuk menyimpan hasil pemindaian dalam berbagai format, seperti XML, untuk analisis atau dibagikan dengan tim lain.

Support Multi-Platform: Zenmap tersedia untuk berbagai sistem operasi seperti Linux, Windows, dan macOS.

Menyederhanakan Perintah Nmap: Zenmap menampilkan perintah Nmap yang sesuai dengan konfigurasi pemindaian yang dipilih pengguna, sehingga membantu mempelajari perintah-perintah Nmap sambil menggunakan GUI.

Cara Menggunakan Zenmap:
1.Masukkan Alamat Target: Pengguna hanya perlu memasukkan alamat IP atau domain target.

2.Pilih Profil Pemindaian: Zenmap memiliki beberapa profil pemindaian yang bisa dipilih, seperti pemindaian cepat/quick scan, pemindaian intensif, atau deteksi OS.

3.Lihat Hasil: Setelah pemindaian selesai, hasil akan ditampilkan dalam bentuk tabel, grafik, dan topologi jaringan.

berikut merupakan contoh hasil tampilan
![zenmap 1](https://github.com/user-attachments/assets/0a63ccbc-9f74-4eef-ad03-4db6ebf0be10)

# Anggry IP Scan

Angry IP Scanner adalah alat pemindai jaringan sumber terbuka yang ringan dan mudah digunakan, yang dirancang untuk memindai alamat IP dan port dalam suatu jaringan. Alat ini sering digunakan oleh administrator jaringan dan profesional keamanan untuk memantau jaringan, mencari perangkat aktif, serta memeriksa port yang terbuka.

Fitur Utama Angry IP Scanner:

Pemindaian Cepat dan Ringan: Angry IP Scanner terkenal karena kecepatannya dalam memindai jaringan, karena menggunakan teknik pemindaian multi-threading, yang memproses banyak alamat IP secara paralel.

Antarmuka yang Sederhana: Angry IP Scanner memiliki antarmuka grafis yang sederhana dan mudah digunakan, bahkan oleh pengguna yang tidak berpengalaman dalam administrasi jaringan.
Pengguna hanya perlu memasukkan rentang IP atau alamat IP spesifik, dan pemindaian bisa langsung dimulai.

Fleksibilitas dalam Pemindaian: Pengguna dapat memilih untuk memindai alamat IP dalam rentang tertentu dan juga menentukan port mana saja yang ingin dipindai.
Selain itu, alat ini bisa memindai perangkat di jaringan lokal (LAN) atau jaringan yang lebih besar.

Informasi yang Ditampilkan: Setelah pemindaian selesai, Angry IP Scanner menampilkan daftar perangkat yang aktif, bersama dengan informasi seperti alamat IP, hostname, status port, dan MAC address (jika tersedia).
Hasil pemindaian bisa diekspor dalam format berbeda seperti CSV, TXT, XML, atau bahkan diekspor ke basis data SQL.

Plugin yang Dapat Diperluas: Angry IP Scanner mendukung plugin, sehingga pengguna dapat menambahkan fungsionalitas tambahan sesuai dengan kebutuhan mereka.
Multi-Platform:

Alat ini tersedia untuk berbagai sistem operasi seperti Windows, Linux, dan macOS.

Penggunaan Angry IP Scanner

Pemindaian IP: Pengguna bisa memasukkan rentang alamat IP atau alamat tunggal yang ingin dipindai. Misalnya, memasukkan 192.168.1.1-254 akan memindai seluruh alamat di jaringan lokal tersebut.

Pemindaian Port: Pengguna bisa menentukan port tertentu yang ingin dipindai. Jika tidak ada port yang ditentukan, Angry IP Scanner akan memindai port standar seperti HTTP (port 80), SSH (port 22), dan lainnya.

Ekspor Hasil: Setelah pemindaian selesai, hasil bisa disimpan dan diolah lebih lanjut untuk analisis jaringan atau audit keamanan.

Deteksi Perangkat Aktif: Angry IP Scanner menandai perangkat mana saja yang aktif (online) berdasarkan respons dari ping atau koneksi ke port terbuka.

contoh hasil tampilan :

![anggry ip scan 1](https://github.com/user-attachments/assets/ed17e2ce-a7a3-41f4-b61e-b46e855f7abd)

# hasil akhir

Nmap merupakan tools yang  kuat dan serbaguna untuk pemindaian jaringan dan audit keamanan.tools ini cocok untuk pengguna tingkat lanjut karena mendukung berbagai fungsi seperti deteksi sistem operasi, layanan, dan kerentanan. Namun, Nmap memiliki kurva belajar yang lebih tinggi, karena sebagian besar dioperasikan melalui antarmuka baris perintah. 

di sisi lain, Zenmap merupakan antarmuka grafis untuk Nmap yang dirancang untuk mempermudah penggunaannya, terutama bagi mereka yang kurang nyaman dengan command line. Zenmap menawarkan kemudahan dalam pemindaian dan analisis jaringan melalui visualisasi topologi, serta memungkinkan pengguna menyimpan profil pemindaian untuk penggunaan ulang, meskipun tetap memiliki kompleksitas dari Nmap di baliknya. 

sedangkan Angry IP Scanner, sebagai alternatif yang lebih ringan, menawarkan pemindaian jaringan yang sangat cepat dan sederhana, ideal untuk pengguna yang hanya perlu memindai jaringan dasar atau memonitor perangkat aktif dengan cepat. Meskipun Angry IP Scanner tidak memiliki kemampuan mendalam seperti Nmap, alat ini sangat mudah digunakan bahkan oleh pengguna non-teknis, berkat antarmuka grafis yang sederhana. 

Secara keseluruhan, Nmap cocok untuk pemindaian mendalam oleh profesional keamanan, Zenmap adalah pilihan tepat untuk pengguna yang ingin kekuatan Nmap dengan kemudahan antarmuka grafis, dan Angry IP Scanner sempurna untuk pengguna yang memerlukan alat cepat dan ringan tanpa kompleksitas berlebih.

