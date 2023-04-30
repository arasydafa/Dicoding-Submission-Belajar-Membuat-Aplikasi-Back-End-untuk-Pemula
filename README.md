# Bookshelf API

## Deskripsi
Repositori ini berisi kode sumber untuk submission dari kursus "Belajar Membuat Aplikasi Back-End untuk Pemula" di [Dicoding](https://www.dicoding.com/academies/261).

## Gambaran Proyek
Proyek ini adalah API sederhana untuk manajemen koleksi buku. API ini dibangun menggunakan Node.js dan framework Hapi.

## Cara Menjalankan
Untuk menjalankan proyek secara lokal, ikuti langkah-langkah berikut:

1. Clone repositori ini
2. Install dependencies dengan menjalankan `npm instal`
3. Jalankan server dengan menjalankan `npm run start` atau `npm run start-dev` jika ingin menggunakan `Nodemon` untuk melihat perubahan secara real-time.
4. Akses API melalui http://localhost:9000

## Endpoint API
API ini memiliki beberapa endpoint sebagai berikut:

- `GET /books` - Mengambil semua buku
- `GET /books/{bookId}` - Mengambil buku berdasarkan id
- `POST /books` - Menambahkan buku baru
- `PUT /books/{bookId}` - Mengubah buku berdasarkan id
- `DELETE /books/{bookId}` - Menghapus buku berdasarkan id

Anda dapat menguji endpoint-endpoint API ini menggunakan [Postman](https://www.postman.com/downloads/).
