Sistem Jaringan Bisnis Perusahaan

Desain Jaringan Enterprise/Proyek Cisco Packet Tracer

Dalam studi kasus dan persyaratan, jaringan dasar menggunakan 172.16.1.0, tetapi saya menggunakan 192.168.0.0.
Alamat IP publik yang diberikan adalah 195.136.17.0/30, 195.136.17.4/30, 195.136.17.8/30, dan 195.136.17.12/30, tetapi saya menggunakan 103.133.254.0/30, 103.133.254.4/30, 103.133.254.8/30, dan 103.133.254.12/30.
Untuk bagian ICT, ruang server, dan setiap departemen, saya menetapkan 256 host sehingga perangkat dapat ditambah di masa depan jika diperlukan.
Untuk informasi lebih lanjut, silakan cek laporan.
SSH diaktifkan hanya untuk Departemen Keuangan dan Admin.

-Studi Kasus dan Persyaratan-
Sebuah pusat dukungan di lantai perdagangan memiliki 600 staf. Mereka baru saja melakukan ekspansi dan membutuhkan pindah ke gedung baru. Gedung tersebut belum memiliki jaringan, sehingga sebelum mereka pindah, layanan jaringan baru harus dirancang dan diimplementasikan.

Jaringan saat ini meliputi elemen-elemen berikut:
Gedung baru diharapkan memiliki tiga lantai dengan dua departemen di masing-masing lantai, misalnya:

1. Lantai 1
Departemen Penjualan dan Pemasaran (120 pengguna)
Departemen Sumber Daya Manusia dan Logistik (120 pengguna)
2. Lantai 2
Departemen Keuangan dan Akuntansi (120 pengguna)
Departemen Administrasi dan Hubungan Masyarakat (120 pengguna)
3. Lantai 3
ICT (120 pengguna)
Ruang Server (12 perangkat)
Sebagai anggota tim jaringan, Anda ditugaskan untuk merancang jaringan untuk gedung baru ini. Pada tahap ini, desain logis diperlukan untuk memastikan bahwa jaringan baru memenuhi kebutuhan bisnis saat ini dan mampu mendukung perkembangan di masa depan:

Persyaratan Jaringan
1. Gunakan Cisco Packet Tracer untuk merancang dan mengimplementasikan solusi jaringan.
2. Gunakan model hierarki dengan redundansi di setiap lapisan (dua router dan dua multilayer switch).
3. Hubungkan jaringan ke dua ISP untuk menyediakan redundansi, dan setiap router harus terhubung ke kedua ISP.
4. Setiap departemen harus memiliki jaringan nirkabel.
5. Setiap departemen harus berada di VLAN dan subnet yang berbeda.
6. Subnet jaringan dasar 172.16.1.0 untuk menyediakan jumlah IP yang sesuai.
7. Hubungkan jaringan ke alamat IP publik statis yang diberikan untuk koneksi ke ISP.
8. Konfigurasikan pengaturan perangkat dasar (hostname, password konsol, banner, dan lainnya).
9. Konfigurasikan inter-VLAN routing pada multilayer switch.
10. Semua perangkat di jaringan harus memperoleh alamat IP secara dinamis dari DHCP server.
11. Perangkat di ruang server harus memiliki IP statis.
12. Gunakan OSPF sebagai protokol routing untuk mengiklankan rute.
13. Konfigurasikan SSH pada router dan switch layer tiga untuk akses jarak jauh yang aman.
14. Konfigurasikan port-security untuk Departemen Keuangan dengan metode sticky dan mode pelanggaran shutdown.
15. Konfigurasikan PAT menggunakan ACL untuk menerapkan keamanan pada NAT.
16. Uji dan verifikasi komunikasi untuk memastikan semuanya berjalan dengan baik.

Teknologi yang Diimplementasikan
1. Membuat topologi jaringan menggunakan Cisco Packet Tracer.
2. Desain jaringan hierarki.
3. Menghubungkan perangkat jaringan dengan kabel yang benar.
4. Konfigurasi pengaturan dasar perangkat.
5. Membuat VLAN dan menetapkan port.
6. Subnetting dan pemberian IP Address.
7. Inter-VLAN routing pada multilayer switch.
8. Konfigurasi DHCP Server untuk alokasi IP dinamis.
9. Konfigurasi SSH untuk akses aman jarak jauh.
10. OSPF sebagai protokol routing.
11. NAT Overload (PAT).
12. Konfigurasi ACL standar dan extended.
13. Port-security pada switch.
14. WLAN menggunakan Cisco Access Point.
15. Konfigurasi perangkat host.
16. Konfigurasi router ISP.
17. Pengujian dan verifikasi komunikasi jaringan.
