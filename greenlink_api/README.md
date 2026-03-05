# GreenLink REST API
GreenLink REST API adalah backend API sederhana yang dibuat menggunakan PHP dan MySQL untuk mengelola data produk ramah lingkungan. 
API ini mendukung operasi CRUD (Create, Read, Update, Delete) pada data produk.

## Teknologi yang Digunakan
- PHP
- MySQL
- XAMPP
- REST API
- Postman

## Struktur Project
```
greenlink_api/
│
├── config/
│   └── database.php
│
├── produk/
│   ├── create.php
│   ├── read.php
│   ├── update.php
│   └── delete.php
│
└── README.md
```

## Setup Project

1. Install XAMPP
2. Jalankan Apache dan MySQL
3. Copy folder project ke:
```
htdocs/
```
hasil:
```
C:\xampp\htdocs\greenlink_api
```
4. Import database ke MySQL
5. Jalankan API melalui Postman

## Pengujian API

Pengujian endpoint dilakukan menggunakan Postman dengan mengirim request HTTP (GET, POST, PUT, DELETE) ke setiap endpoint.

## Hasil
API berhasil terhubung dengan database MySQL dan semua fungsi CRUD berjalan dengan baik.

## Author
Dwi Maulidan_187241006
Hassya Azzamakhsyari Oksigendaru_187241019
Muhammad Rizki Fahrezi_187241075
