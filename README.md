# MoveeApp
## API
> API adalah singkatan dari Application Programming Interface yaitu sebuah software
yang memungkinkan para developer untuk mengintegrasikan dan mengizinkan dua aplikasi yang
berbeda secara bersamaan untuk saling terhubung satu sama lain.
Tujuan penggunaan dari API adalah untuk saling berbagi data antar aplikasi yang berbeda
tersebut, dan juga untuk mempercepat proses pengembangan aplikasi dengan cara menyediakan
sebuah function yang terpisah sehingga para developer tidak perlu lagi membuat fitur yang
serupa.
### Jenis Api
1.	Public API
2.	Private API
3.	Partner API
4.	Composite API

### Manfaat API
1.	Memudahkan membangun aplikasi yang fungsional
2.	Pengembangan aplikasi menjadi lebih efisien
3.	Meringankan beban server

### Cara kerja API

Aplikasi mengakses API -> API melakukan request ke server -> Server memberi respon ke API -> API menyampaikan respon ke aplikasi

## REST API

> REST API merupakan salah satu dari desain arsitektur yang terdapat di dalam API itu
sendiri. Dan cara kerja dari RESTful API yaitu REST client akan Melakukan akses pada
data/resource pada REST server dimana masing-masing resource. Atau data/resource tersebut
akan dibedakan oleh sebuah global ID atau URIs (Universal Resource Identifiers).
Jadi, Nantinya data yang diberikan oleh REST server itu bisa berupa format text, JSON atau
XML. Dan saat ini format yang paling populer dan paling banyak digunakan adalah format
JSON.

Adapun metode HTTP yang secara umum dipakai dalam REST api adalah:
* GET, berfungsi untuk membaca data/resource dari REST server
* POST, berfungsi untuk membuat sebuah data/resource baru di REST server
* PUT, berfungsi untuk memperbaharui data/resource di REST server
* DELETE, berfungsi untuk menghapus data/resource dari REST serve
* OPTIONS, berfungsi untuk mendapatkan operasi yang disupport pada resource dari
REST server.

Cara kerja RESTful API adalah REST client akan mengakses data/resource ke REST server dimana masing-masing resource atau data tersebut dibedakan oleh sebuah global ID atau URIs (Universal Resource Identifiers).
REST ialah salah satu implementasi dari web service sebagai sebuah standar yang digunakan untuk pertukaran data antar aplikasi atau sistem.
Biasanya aplikasi atau sistem ini menggunakan bahasa pemrogramman yang berbeda sehingga untuk bisa berkomunikasi satu sama lainnya bisa menggunakan web service ini.

### Kelebihan 
*	Bisa digunakan oleh banyak bahasa pemroggraman dan banyak platform
*	Lebih simple dibandingkan dengan SOAP
*	Mudah dipelajari
*	Seperti web, menggunakan protokol HTTP, dan HTTP ada dimana-mana

### Kekurangan
*	Waktu akses yang biasanya lebih lama dibandingkan dengan native library
*	Lebih rentan dengan serangan keamanan karena harus melewati protocol HTTP

## RETROFIT
> Retrofit adalah sebuah library android yang membantu pengembang untuk melakukan
request ke sebuah endpoint REST API. Library inimenyederhanakan kode program yang digunakan untuk mengakses REST API. Tidak hanya untuk
mengakses REST API dengan proses sederhana (GET, POST, PUT, DELETE) retrofit juga
mendukung berbagai macam format authentikasi via http, menambahkan header pada request,
menambahkan parameter serta mengirim data berupa image ke server.

Retrofit memudahkan untuk terhubung ke layanan web REST dengan menerjemahkan API ke dalam antarmuka Java. 
Kita akan melihat salah satu library HTTP yang paling populer dan sering direkomendasikan untuk Android. 
Library yang kuat ini mempermudah penggunaan data JSON atau XML, yang kemudian diurai menjadi Plain Old Java Objects (POJOs). 
Permintaan GET, POST, PUT, PATCH, dan DELETE semua bisa dieksekusi. Seperti kebanyakan perangkat lunak open-source, 
Retrofit dibangun di atas beberapa library dan alat bantu lainnya. Di balik layar, Retrofit memanfaatkan OkHttp (dari pengembang yang sama) untuk menangani permintaan jaringan. 
Selain itu, Retrofit tidak memiliki konverter JSON built-in untuk mengurai dari objek JSON ke Java.


