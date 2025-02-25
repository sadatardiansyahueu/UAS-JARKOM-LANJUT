Nama : Sadat Ardiansyah

Nim : 20210801180

Prodi : Teknik Informatika

Penjelasan dari gambar ini merupakan representasi topologi jaringan untuk tiga kampus, yaitu:

Kampus Citra Raya
Kampus Kebon Jeruk
Kampus Harapan Indah
Berikut penjelasan setiap elemen di gambar:

1. Router dan IP Address
Setiap kampus memiliki tiga router utama yang menghubungkan jaringan antar perangkat.
Setiap router memiliki konfigurasi sebagai berikut:
AS (Autonomous System): Menunjukkan nomor identitas unik untuk pengelompokan jaringan.
Ether (Ethernet Interface): Interface yang digunakan pada setiap router memiliki IP Address spesifik. Misalnya, pada Kampus Citra Raya, ether1: 192.168.20.1/24.
IP Address tambahan juga digunakan untuk menghubungkan antar-router atau antar-perangkat dalam subnet yang sama.
2. Hubungan Antar Router
Router di setiap kampus terhubung dengan router lain melalui antarmuka Ethernet (eth).
Koneksi antar-router menunjukkan komunikasi antar-kampus melalui IP tertentu.
3. Switch dan Laptop
Setiap kampus dilengkapi dengan switch yang menghubungkan laptop-laptop klien.
Misalnya, di Kampus Citra Raya, switch (ETH 2) menghubungkan beberapa laptop seperti "Laptop Sadat" dan "Laptop Ardi."
Masing-masing laptop memiliki koneksi lokal ke router di kampus yang sama.
4. Koneksi Antar Kampus
Topologi menunjukkan bahwa masing-masing kampus memiliki jaringan yang terhubung antar-router menggunakan IP Address publik (misalnya, AS: 65001).

Jenis Topologi
Topologi Hybrid
Jaringan ini merupakan kombinasi dari beberapa jenis topologi:
Topologi Star (Bintang): Setiap kampus memiliki topologi bintang di mana router utama berfungsi sebagai pusat yang menghubungkan perangkat-perangkat lain (laptop dan switch).
Topologi Point-to-Point: Antar-router (dari kampus yang berbeda) saling terhubung menggunakan koneksi point-to-point untuk komunikasi antar-kampus.
Penjelasan Berdasarkan Elemen Topologi
Kampus Citra Raya

Topologi lokal berbentuk bintang, dengan Router 3 sebagai pusat jaringan lokal yang menghubungkan ke beberapa laptop melalui switch (ETH 2).
Router 3 juga terhubung ke router lain di kampus melalui koneksi point-to-point (eth1 dan eth3) untuk keperluan komunikasi antar-router.
Kampus Kebon Jeruk

Sama seperti Citra Raya, menggunakan topologi bintang untuk jaringan lokalnya.
Router 1 di Kampus Kebon Jeruk berfungsi sebagai pusat penghubung, mengelola koneksi antar perangkat lokal serta koneksi ke router kampus lain.
Kampus Harapan Indah

Topologi lokal berbentuk bintang, dengan Router 2 sebagai pusat yang menghubungkan perangkat lokal.
Koneksi point-to-point digunakan untuk berkomunikasi dengan router di kampus lain.
Koneksi Antar Kampus
Jaringan antar-kampus membentuk topologi mesh parsial, di mana:
Setiap router antar-kampus saling terhubung menggunakan antarmuka Ethernet tertentu.
Komunikasi antar-kampus mengandalkan koneksi point-to-point untuk berbagi data antar-AS (Autonomous System).
Contoh:
Router 3 dari Kampus Citra Raya terhubung dengan Router 1 di Kampus Kebon Jeruk melalui koneksi eth2.
Router 1 di Kampus Harapan Indah terhubung dengan router dari kedua kampus lainnya.
Kesimpulan
Topologi ini menggabungkan bintang untuk jaringan lokal di setiap kampus dan mesh parsial untuk koneksi antar-kampus. Pendekatan ini memberikan:

Efisiensi komunikasi di dalam masing-masing kampus.
Redundansi koneksi antar-router untuk memastikan ketersediaan jaringan antar-kampus.



