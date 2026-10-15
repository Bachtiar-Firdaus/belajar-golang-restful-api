# Belajar Golang RESTful API

## Pendahuluan
RESTful API adalah standar komunikasi antar aplikasi menggunakan protokol HTTP dengan prinsip REST (Representational State Transfer).

## Setup Project
Langkah awal menyiapkan project Golang, struktur folder, dan dependency yang dibutuhkan.

## Membuat OpenAPI
OpenAPI digunakan untuk mendefinisikan spesifikasi API agar lebih mudah dipahami dan didokumentasikan.

## API Spec List Categories
Spesifikasi endpoint untuk menampilkan daftar kategori.

## API Spec Create Category
Spesifikasi endpoint untuk membuat kategori baru.

## API Spec Get Category
Spesifikasi endpoint untuk mengambil detail kategori berdasarkan ID.

## API Spec Update Category
Spesifikasi endpoint untuk memperbarui data kategori.

## API Spec Delete Category
Spesifikasi endpoint untuk menghapus kategori.

## API Spec Security
Menambahkan aspek keamanan pada API, seperti autentikasi dan otorisasi.

## Membuat Database
Menyiapkan database untuk menyimpan data kategori.

## Category Domain
Mendefinisikan domain model kategori.

## Category Repository
Membuat interface repository untuk kategori.

## Category Repository Implementation
Implementasi repository kategori dengan database.

## Category Service
Membuat service untuk mengatur logika bisnis kategori.

## Category Service Implementation
Implementasi service kategori sesuai kebutuhan aplikasi.

## Category Validation
Menambahkan validasi pada data kategori sebelum diproses.

## Category Controller
Membuat controller untuk menangani request terkait kategori.

## Category Controller Implementation
Implementasi controller kategori dengan memanggil service.

## HTTP Router
Mengatur routing HTTP agar request diarahkan ke controller yang sesuai.

## HTTP Server
Menjalankan server HTTP untuk melayani request API.

## Manual Test API
Melakukan pengujian manual API menggunakan tools seperti Postman atau curl.

## Error Handler
Menangani error agar response API lebih konsisten dan informatif.

## Authentication
Menambahkan autentikasi pada API untuk membatasi akses.

## Unit Test
Membuat unit test untuk memastikan setiap komponen API berjalan sesuai harapan.
