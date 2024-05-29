# APBO-SI-Daycare

# Use case Diagram
![Use case diagram(5)](https://github.com/DeniSaputra1/APBO-SI-Daycare/assets/145963420/d42fbb3e-5701-4dbe-bfb6-cf1726546ab4)


Aktor yang terlibat 
•	Anak-anak : Penerima layanan
•	Orang tua / wali : Penanggung Jawab
•	Staff Daycare : Pemberi Layanan dan pengawasan
•	Admin : Pengelola sistem Daycare 

Penjelasan Use Case : 
1.	Login : Aktor (Orang Tua/Wali, Staf Daycare, Administrator) yang melakukan login ke sistem dengan menggunakan akun yang vaild.
2.	Pendaftran anak : Orang tua/wali mendaftarkan anak ke daycare, termasuk mengisi data pribadi dan riwayat kesehatan anak.
3.	Melihat Jadwal anak : Orang tua/wali melihat jadwal harian dan mingguan anak di daycare.
4.	Melihat laporan kehadiaran : Orang tua/wali melihat laporan kehadiran anak selama berada di daycare.
5.	Menghubungi staff : Orang tua/wali menghubungi staf daycare untuk berbagai keperluan seperti menanyakan kondisi anak.
6.	Mengelola Jadwal : Staf daycare membuat dan mengelola jadwal aktivitas anak-anak.
7.	Mengelola kehadiran : Staf daycare mencatat dan mengelola kehadiran anak setiap hari.
8.	Membuat laporan pengembangan : Staf daycare membuat laporan perkembangan anak, mencakup aspek kognitif, fisik, sosial, dan emosional.
9.	Menghubungi orang tua/ wali: Staf daycare menghubungi orang tua/wali untuk memberikan informasi atau menanyakan hal terkait anak.
10.	 Mengelola data anak : Admin mengelola data anak yang terdaftar di daycare.
11.	Mengelola data staff : Admin mengelola data staf yang bekerja di daycare.
12.	Menglola data orang tua/wali : Admin mengelola data orang tua/wali yang terdaftar di sistem.
13.	Mengelola sistem : Admin mengelola keseluruhan sistem, termasuk pengaturan, keamanan, dan pemeliharaan.
14.	Penerima layanan : anak anak menerima layanan yang diberikan oleh daycare.


# Class Diagram 
![UML class(3)](https://github.com/DeniSaputra1/APBO-SI-Daycare/assets/145963420/40a7afba-4328-419b-9440-34709ee4e350)

# ERD (Entity Relationship Diagram)
![ERD](https://github.com/DeniSaputra1/APBO-SI-Daycare/assets/145963420/c04e186d-0d4b-4a10-8557-bf47520e9490)

Penjelasan :
1.	OrangTua -> anak (one to many) : satu orang tua/wali bisa memiliki banyak anak
2.	Anak -> Kehadiran (one to many ) : satu anak bisa memiliki banyak catatan kehadiran
3.	Jadwal -> kehadiran (one to many) : satu jadwal bisamemiliki catatan kehadiran 
4.	Staff -> jadwal (one to many ) : satu staf bisa memiliki banyak jadwal
5.	Admin -> jadwal (one to many ) : satu admin bisa mengelola banyak jadwal
6.	Admin -> LaporanPerkembangan (one to many) : satu admin bisa mengelola banyak laporan perkembangan.



