# 👥 Random User App

Aplikasi Flutter sederhana yang menampilkan daftar pengguna acak menggunakan [Random User API](https://randomuser.me/).

## 📱 Tampilan Aplikasi

Aplikasi menampilkan:
- Foto profil pengguna
- Nama lengkap
- Email
- Negara asal

## 🚀 Fitur

- Mengambil data dari API secara real-time
- Loading indicator saat data sedang diambil
- Error handling jika koneksi bermasalah
- Pull-to-refresh untuk memuat ulang data
- Tombol refresh di AppBar
- UI modern dengan Card dan ListTile

## 🛠️ Teknologi yang Digunakan

| Teknologi | Keterangan |
|---|---|
| Flutter | Framework UI |
| Dart | Bahasa pemrograman |
| HTTP Package | Mengambil data dari API |
| StatefulWidget | Manajemen state |
| Future & Async/Await | Pemrograman asynchronous |

## 📦 Dependencies

```yaml
dependencies:
  flutter:
    sdk: flutter
  http: ^1.2.1
```

## 🔗 API yang Digunakan
https://randomuser.me/api/?results=20

## ⚙️ Cara Menjalankan

1. Clone repository ini
```bash
   git clone https://github.com/AryaSaputra-Asra/random_user_app_Mobile_Programing.git
```

2. Masuk ke folder project
```bash
   cd random_user_app_Mobile_Programing
```

3. Install dependencies
```bash
   flutter pub get
```

4. Jalankan aplikasi
```bash
   flutter run
```

## 📁 Struktur Project
lib/
└── main.dart       # Semua kode utama aplikasi