# 🖥️ Smart Door Lock - Web Dashboard

Ini adalah antarmuka berbasis web untuk sistem kunci pintu pintar. Dashboard ini menampilkan status pintu secara real-time dan memungkinkan kontrol jarak jauh melalui Firebase Realtime Database. Dibangun menggunakan HTML dan JavaScript.

## 📁 Repository Contents

- `index.html` - Halaman utama dashboard yang menampilkan status dan tombol kontrol.
- `config.js` - File konfigurasi Firebase untuk menghubungkan dashboard ke database.

## ⚙️ Setup Instructions

1. ☁️ Gunakan Firebase yang sama dengan proyek ESP32.
2. ✏️ Edit `config.js` dan isi dengan informasi dari Firebase Console:
   - 🔑 API key
   - 🌐 Auth domain
   - 🔗 Database URL
   - 🆔 Project ID
   - 📲 Messaging sender ID
   - 📦 App ID
3. 🌍 Buka `index.html` di browser. Dashboard akan menampilkan status pintu dan tombol kontrol Lock/Unlock.

## 🌟 Features

- 🪟 Menampilkan status pintu secara real-time.
- 🔓 Kontrol kunci dari browser menggunakan tombol Lock dan Unlock.
- ⚡ Integrasi langsung ke Firebase dengan JavaScript sederhana.
- 🧩 Konfigurasi cepat hanya dengan edit `config.js`.

## 📝 Catatan

- Gunakan koneksi internet yang aman saat mengakses dashboard.
- Pastikan Firebase Database Rules sudah mengizinkan read/write yang diperlukan.
- Jangan share file `config.js` di publik jika berisi kredensial sensitif.

**📅 Tanggal mulai proyek:** 25 November 2024  
**🛠️ Teknologi yang digunakan:** HTML, JavaScript, Firebase
