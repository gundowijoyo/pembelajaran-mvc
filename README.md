# Pembelajaran Model-View-Controller (MVC)

## Pendahuluan
Model-View-Controller (MVC) adalah pola arsitektur perangkat lunak yang memisahkan aplikasi menjadi tiga komponen utama: Model, View, dan Controller. Tujuannya adalah untuk memisahkan logika bisnis dari tampilan antarmuka pengguna, sehingga membuat aplikasi lebih mudah dikelola dan dikembangkan.

## Komponen MVC

### Model
Model bertanggung jawab untuk mengelola data dan logika bisnis. Model menerima input dari Controller dan memperbarui datanya sesuai dengan logika aplikasi.

### View
View bertugas menampilkan data kepada pengguna. View mengambil data dari Model dan menampilkannya dalam format yang mudah dipahami. View tidak memiliki logika bisnis, hanya bertugas untuk presentasi data.

### Controller
Controller bertindak sebagai perantara antara Model dan View. Controller menerima input dari pengguna melalui View, memprosesnya, dan kemudian mengirimkan perintah ke Model untuk memperbarui data. Setelah Model diperbarui, Controller mengarahkan View untuk memperbarui tampilan berdasarkan data terbaru.

## Diagram MVC

```plaintext
[View] <--> [Controller] <--> [Model]
