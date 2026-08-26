# API Todo List Management Backend

REST API untuk pengelolaan daftar tugas (Todo List) menggunakan Node.js, Express.js, dan MongoDB.

## Fitur Utama
* Autentikasi User (Register & Login dengan JWT & Password Hashing).
* Manajemen Kategori Todo (CRUD).
* Manajemen Todo List (CRUD) terhubung ke User & Kategori.
* Fitur Filtering, Sorting, Searching, dan Pagination pada Todo.
* Proteksi API Key untuk endpoint eksternal.
* Pencatatan Activity Log otomatis.

## Teknologi yang Digunakan
* Node.js & Express.js
* MongoDB & Mongoose
* JSON Web Token (JWT) & Bcryptjs
* Dotenv

## Cara Menginstall dan Menjalankan Project

1. Clone repository ini:
   ```bash
   git clone <URL_REPOSITORY_GITHUB_KAMU>
   cd api-todo-list