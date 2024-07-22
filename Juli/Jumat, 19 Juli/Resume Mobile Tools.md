# PostgreSQL
PostgreSQL adalah Relational Data Base Management System (RDBMS) open-source sehingga bebas digunakan dan dimodifikasi oleh komunitas besar yang aktif. PostgreSQL terkenal dengan kinerjanya yang tinggi dan kepatuhan terhadap standar SQL dengan sangat baik, sehingga cocok untuk menangani beban kerja yang berat. PostgreSQL mendukung fitur-fitur canggih seperti transaksi ACID, foreign keys, joins, views, triggers, dan stored procedures.
### Perbandingan
MySQL/MariaDB: PostgreSQL lebih baik dalam menangani operasi kompleks dan memiliki dukungan fitur yang lebih luas.  
SQLite: PostgreSQL lebih cocok untuk aplikasi skala besar dan multi-pengguna karena mendukung transaksi dan kinerja yang lebih baik.   
MongoDB: PostgreSQL menawarkan data yang lebih konsisten dan kemampuan SQL yang kuat, sementara MongoDB lebih baik untuk skenario yang memerlukan skala horizontal dan data semi-terstruktur.  
# Express
Express.js adalah framework web aplikasi untuk Node.js, yang menyediakan serangkaian fitur untuk membangun aplikasi web dan API. Express memiliki arsitektur minimalis dan fleksibel sehingga sering digunakan dikalangan pengembang Node.js. Express dapat menggunakan sistem middleware dan routing untuk menambah fitur autentikasi dan membuat pembuatan restful API dengan mudah. 
### Perbandingan
Django (Python): Express cocok untuk proyek yang memerlukan waktu pengembangan cepat dan kinerja tinggi. Django menawarkan fitur lebih lengkap tetapi lebih berat dan kompleks.   
Ruby on Rails: Express lebih minimalis dan fleksibel, memungkinkan pengembang untuk memilih modul dan middleware yang sesuai. Rails memiliki konvensi lebih banyak dan cenderung lebih opiniatif.
Spring Boot (Java): Express lebih mudah dipelajari dan digunakan, sementara Spring Boot lebih cocok untuk aplikasi skala enterprise dengan kebutuhan kompleksitas tinggi.
# Flutter
Flutter adalah framework open-source yang kuat dan fleksibel yang dikembangkan oleh Google untuk membangun aplikasi mobile, web, dan desktop dari satu basis kode tunggal. Flutter menggunakan bahasa pemrograman Dart dan menawarkan berbagai alat dan widget untuk membangun antarmuka pengguna yang menarik dan interaktif.  
Dengan menggunakan flutter, pengembang dapat menggunakan satu basis kode untuk membangun aplikasi di iOS, Android, Web, dan Desktop. Sehingga ini akan menghemat waktu dan usaha pengembangan karena tidak perlu menulis kode terpisah untuk setiap platform.   
Flutter memiliki fitur hot reload yang memungkinkan pengembang untuk melihat perubahan kode secara langsung yang mempermudah debuggin tanpa harus me-restart aplikasi. Flutter menyediakan berbagai widget siap pakai dan dapat dimodifikasi dan dikombinasikan untuk membangun antarmuka pengguna. Sama seperti bahasa pemrograman lainnya, flutter dapat digunakan dengan berbagai IDE seperti Android Studio, Visual Studio Code, dan lainnya.  
### Arsitektur
#### 1. Dart Platform   
Flutter menggunakan bahasa pemrograman Dart yang juga dikembangkan oleh Google. Dart memiliki kelebihan untuk pengembangan berperforma tinggi dan mudah dipelajari, dengan sintaks yang digunakan mirip JavaScript atau Java. 
#### 2. Flutter Engine  
Mesin rendering Flutter ditulis dalam C++ dan menggunakan Skia untuk rendering 2D. Oleh karena itu, flutter menyediakan layanan low-level dan dapat menampilkan animasi, grafik, dan plugin lainnya.  
#### 3. Foundation Library  
Foundation library berisi kelas-kelas dasar dan utilitas yang digunakan oleh widget Flutter. Arsitektur ini juga menyediakan berbagai API untuk operasi dasar seperti koleksi, IO, dan manipulasi data.  
#### 4. Widgets  
Widget adalah elemen dasar dari antarmuka pengguna di Flutter.Setiap elemen UI, seperti tombol, teks, dan gambar, adalah widget yang dapat disusun dan diubah.

### Pub.dev
Pub.dev adalah repositori paket resmi untuk Dart dan Flutter. Berikut adalah beberapa paket yang sering digunakan oleh pengembang Flutter:
#### 1. provide
> Paket ini digunakan untuk state management, yaitu untuk mengelola state aplikasi dan membuat state yang reaktif.
#### 2. http
> Paket ini digunakan untuk HTTP request, yaitu mengirim dan menerima data dari API
#### 3. flutter_bloc
> Paket ini digunakan untuk state management menggunakan Bloc pattern. Bloc digunaka untuk mengelola state yang kompleks.
#### 4. shared_preferences
> Paket ini digunakan untuk penyimpanan data sederhana dalam bentuk key-value, seperti pengaturan aplikasi atau token autentikasi.
#### 5. flutter_local_notifications
> Paket ini digunakan untuk menampilkan notifikasi di perangkat pengguna.

#### 6. dio
> Paket ini digunakan untuk melakukan HTTP request dengan fitur tambahan seperti interceptor, retry, dan cancel.
#### 7. image_picker
> Paket ini digunakan untuk memilih gambar dari galeri atau kamera untuk digunakan dalam aplikasi.

### Perbandingan
|Aspek|kotlin|Flutter|
|------|-----|-----|
|Bahasa pemrograman| Kotlin | Dart|
|Penggunaan utama| Pengembangan Android Native, Backend, Multiplatform |Pengembangan aplikasi cross-platform (iOS, Android)|
|Kerangka kerja|	Android SDK|Flutter SDK|
|Kinerja| Native| Near-native|
|UI components|Native Android UI components|Customizable widgets yang konsisten di seluruh platform|
|Hot reload| Tidak ada | Ada |
| Ukuran aplikasi | Lebih kecil untuk aplikasi native Android | Cenderung lebih besar karena bundling Flutter engine|
|Arsitektur aplikasi| Mendukung berbagai pola arsitektur (MVVM, MVP, MVI) | Biasanya menggunakan pattern BLoC, Provider, GetX|
