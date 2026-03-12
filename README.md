Alumni Tracker System

# Deskripsi Sistem
Alumni Tracker System adalah aplikasi web yang digunakan untuk melacak informasi karir alumni berdasarkan data digital yang tersedia secara online.
Sistem ini dirancang untuk membantu institusi pendidikan dalam memantau perkembangan karir alumni setelah lulus. Aplikasi ini memungkinkan admin untuk menambahkan, mengedit, menghapus, serta melakukan tracking data alumni dari berbagai sumber.
Project ini dibuat sebagai tugas Daily Project 3 mata kuliah Rekayasa Kebutuhan.


# Fitur Utama
1. Menambahkan data alumni
2. Mengedit data alumni
3. Menghapus data alumni
4. Mencari alumni (search)
5. Dashboard statistik alumni
6. Auto refresh data alumni
7. Status badge alumni (Belum Dilacak / Sudah Dilacak)
8. Tracking alumni dari berbagai sumber


# Teknologi yang Digunakan

## Frontend
* HTML
* CSS
* JavaScript

## Backend
* Node.js
* Express.js

## Database
* SQLite


# Struktur Project
alumni-tracker
│
├── frontend
│   ├── index.html
│   ├── alumni.html
│   ├── result.html
│   └── script.js
│
├── backend
    ├── server.js
    ├── alumni.db
    └── package.json
│
└── README.md


# Cara Menjalankan Project
1. Clone Repository
git clone https://github.com/USERNAME/alumni-tracker.git

Masuk ke folder project:
cd alumni-tracker

2. Install Dependencies
npm install

3. Jalankan Server
node server.js

Server akan berjalan di:
http://localhost:3000

4. Jalankan Frontend
Buka file menggunakan browser:
frontend/index.html


# Demo Aplikasi
Web App (Frontend):
https://alumni-tracker-2023-206.netlify.app/ 

Repository GitHub:
https://github.com/Sabrinaananda/alumni-tracker.git


# Pengujian Sistem

| No | Fitur               | Langkah Pengujian                   | Hasil    |
| -- | ------------------- | ----------------------------------- | -------- |
| 1  | Tambah Alumni       | Menginput data alumni baru          | Berhasil |
| 2  | Edit Alumni         | Mengubah data alumni                | Berhasil |
| 3  | Delete Alumni       | Menghapus data alumni               | Berhasil |
| 4  | Tracking Alumni     | Menekan tombol track alumni         | Berhasil |
| 5  | Dashboard Statistik | Dashboard menampilkan jumlah alumni | Berhasil |
| 6  | Search Alumni       | Mencari alumni berdasarkan nama     | Berhasil |
| 7  | Auto Refresh Data   | Data diperbarui otomatis            | Berhasil |
| 8  | Status Badge        | Menampilkan status tracking alumni  | Berhasil |


# Aspek Kualitas Sistem

| Aspek           | Deskripsi                                    |
| --------------- | -------------------------------------------- |
| Functionality   | Semua fitur sistem berjalan sesuai kebutuhan |
| Usability       | Antarmuka sistem mudah digunakan             |
| Performance     | Sistem memberikan respon yang cepat          |
| Reliability     | Sistem stabil tanpa error selama pengujian   |
| Maintainability | Kode mudah dipelihara dan dikembangkan       |

---

# Author

**Sabrina Ananda R. F. P.**
Universitas Muhammadiyah Malang
Program Studi Informatika
202310370311206

