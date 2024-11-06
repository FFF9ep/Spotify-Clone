# Spotify Clone 🎶

Spotify Clone adalah proyek kloning sederhana dari aplikasi Spotify menggunakan ReactJS, JavaScript, dan TailwindCSS. Aplikasi ini memungkinkan pengguna untuk mendengarkan lagu, mengelola daftar putar, dan menikmati pengalaman UI/UX yang mirip dengan Spotify.

## Fitur 🎶🎶🎶

- **Halaman Utama**: Tampilan yang menampilkan daftar album dan lagu yang tersedia.
- **Sidebar Navigasi**: Navigasi antar halaman (Home, Album, dan Playlist).
- **Kontrol Pemutar**: Fungsi play, pause, next, previous, dan volume control.
- **Mode Dark dan Light**: Tampilan dapat disesuaikan dengan mode gelap dan terang.
- **Penggunaan State Management**: Mengelola state aplikasi menggunakan React Context untuk menyimpan status pemutar, daftar lagu, dan kontrol volume.

## Teknologi yang Digunakan 👩‍💻

- **ReactJS**: Library utama untuk membangun antarmuka pengguna.
- **TailwindCSS**: Framework CSS yang digunakan untuk styling.
- **JavaScript (ES6)**: Bahasa pemrograman utama untuk logika aplikasi.
- **React Router**: Untuk navigasi antar halaman.
- **React Context API**: Untuk manajemen state global.

## Struktur Proyek 📂

```plaintext
.
├── public
│   ├── index.html
│   └── ...
├── src
│   ├── assets
│   │   └── songs/              # Folder lagu-lagu
│   ├── components
│   │   ├── Player.js           # Komponen untuk pemutar audio
│   │   ├── Sidebar.js          # Sidebar navigasi
│   │   └── ...
│   ├── context
│   │   └── PlayerContext.js    # State management untuk pemutar lagu
│   ├── pages
│   │   ├── Home.js             # Halaman utama dengan daftar lagu
│   │   ├── Album.js            # Halaman album
│   │   └── Playlist.js         # Halaman playlist
│   ├── App.js                  # Komponen utama aplikasi
│   ├── index.js                # Entry point aplikasi
│   └── ...
└── README.md
```

## Instalasi 🧑‍🏫

1. **Kloning Repository**

```bash
   git clone https://github.com/FFF9ep/Spotify-Clone.git
   cd spotify-clone
```

2. **Install Dependensi**

```bash
   npm install
```

4. **Jalankan Aplikasi**

```bash
   npm run dev
```

## 📘 Penggunaan

- **Jelajahi Halaman Utama**: Daftar album dan lagu ditampilkan di halaman utama.
- **Navigasikan Sidebar**: Gunakan sidebar untuk pindah ke halaman Album dan Playlist.
- **Kontrol Pemutar**: Kontrol musik tersedia di bagian bawah aplikasi. Anda dapat memainkan, menjeda, dan mengubah volume musik.

## Fitur Mendatang 😊

- **Pengelolaan Daftar Putar**: Fitur untuk menambahkan lagu ke dalam daftar putar.
- **Pencarian Lagu**: Memungkinkan pengguna mencari lagu di database.
- **Progress Bar**: Menampilkan durasi dan posisi lagu yang sedang diputar.
- **Pengaturan Volume**: Slider volume untuk mengatur tingkat suara.

## Kontribusi ⚡

Jika Anda ingin berkontribusi, silakan fork repository ini dan buat pull request. Saya sangat terbuka untuk masukan atau fitur baru.

## Lisensi ✌️

Proyek ini dilisensikan di bawah MIT License.

## 📞 Kontak

Jika Anda memiliki pertanyaan atau saran, jangan ragu untuk menghubungi saya melalui:

- Email: [fandardyy@gamil.com](mailto:fandardyy@gmail.com)
- LinkedIn: [Profil LinkedIn Saya](https://www.linkedin.com/in/fandiardyan111)

---

🌟 **Terima kasih telah menggunakan program ini!**
