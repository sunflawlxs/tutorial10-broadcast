# Tutorial10 BROADCAST
Nama: Sheryl Ivana Widjaja<br>
NPM: 2206824943<br>
Kelas: Pemrograman Lanjut - A<br>


## REFLEKSI 2

###### 2.1. Original code of broadcast chat.
![](images/1.png)  
![](images/2.png)

* Server dapat dijalankan menggunakan perintah `cargo run --bin server`, sementara setiap klien dapat dijalankan menggunakan perintah `cargo run --bin client`.
* Setiap klien dan server menerima *broadcast* dari semua klien lainnya. Ketika seorang klien memasukkan pesan melalui baris perintah, pesan tersebut akan dikirimkan ke server.
* Server kemudian akan meneruskan pesan tersebut ke semua klien yang terhubung. Dengan demikian, setiap klien akan menerima pesan dari klien lainnya melalui server. Semua pesan yang dimasukkan oleh klien akan didistribusikan kepada semua klien yang terhubung ke server.