<p align="center">
  <img src="docs/screenshots/banner.png" alt="TechDrop 2.0 Banner" width="100%">
</p>

<h1 align="center">💻 TechDrop 2.0</h1>

<p align="center">
  <strong>Game Edukasi Pengenalan dan Simulasi Merakit Perangkat Keras Komputer Berbasis Unity</strong>
</p>

<p align="center">
  <a href="https://khonif-zakaria.itch.io/techdropdev"><img src="https://img.shields.io/badge/itch.io-Play_Now-FA5C5C?style=for-the-badge&logo=itch.io&logoColor=white" alt="Play on itch.io"></a>
  <a href="https://github.com/Khoniv/techdrop-nivdev"><img src="https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Repo"></a>
  <img src="https://img.shields.io/badge/Unity-2021.3.45f2_LTS-black?style=for-the-badge&logo=unity&logoColor=white" alt="Unity">
  <img src="https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Platform Windows">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License MIT">
</p>

---

## 📌 Daftar Isi
* [Tentang Proyek (About Project)](#-tentang-proyek-about-project)
* [Fitur Utama](#-fitur-utama)
* [Galeri & Tangkapan Layar](#-galeri--tangkapan-layar)
* [Manual Book & Panduan Bermain](#-manual-book--panduan-bermain)
* [Daftar Perangkat Keras yang Dikenalkan](#-daftar-perangkat-keras-yang-dikenalkan)
* [Spesifikasi Sistem (System Requirements)](#-spesifikasi-sistem-system-requirements)
* [Cara Menjalankan & Instalasi](#-cara-menjalankan--instalasi)
* [Teknologi yang Digunakan (Tech Stack)](#-teknologi-yang-digunakan-tech-stack)
* [Struktur Direktori Repositori](#-struktur-direktori-repositori)
* [Pengembang & Kontak](#-pengembang--kontak)
* [Lisensi](#-lisensi)

---

## 📖 Tentang Proyek (About Project)

**TechDrop 2.0** adalah sebuah game edukasi interaktif 2D yang dikembangkan menggunakan mesin game **Unity**. Game ini dirancang secara khusus untuk menjadi media pembelajaran interaktif mengenai **Perangkat Keras Komputer (Computer Hardware)**.

Banyak pemula, pelajar, dan mahasiswa sering merasa kesulitan atau ragu saat pertama kali mempelajari komponen komputer secara langsung karena risiko kerusakan fisik atau sengatan listrik statis. Melalui **TechDrop**, pengguna dapat:
1. Mengenal bentuk fisik, fungsi, dan karakteristik setiap komponen PC.
2. Mempelajari urutan dan slot pemasangan hardware secara tepat ke motherboard dan casing.
3. Mengasah kecepatan serta ketepatan identifikasi perangkat keras melalui tantangan bertingkat yang seru dan menantang.

🎮 **Mainkan Sekarang di itch.io**: [https://khonif-zakaria.itch.io/techdropdev](https://khonif-zakaria.itch.io/techdropdev)

---

## ✨ Fitur Utama

- 📚 **Modul Materi Komprehensif**: Penjelasan rinci tentang Motherboard, CPU, RAM, Media Penyimpanan (HDD/SSD), VGA Card, Power Supply (PSU), dan Heatsink Cooler.
- 🛠️ **Modul Simulasi Merakit PC**: Alur langkah demi langkah merakit komponen ke soket motherboard dan casing dengan petunjuk visual yang jelas.
- 🎯 **Modul Bermain (27 Level Tantangan)**: Puzzle drag-and-drop dengan 27 level bertahap (Level 0 - 26) yang dilengkapi batasan waktu (countdown timer) dan sistem validasi penempatan otomatis.
- 🎵 **Tata Suara Dinamis & Pengaturan Audio**: Efek suara interaktif untuk feedback klik, drag, drop benar/salah, serta slider pengaturan volume SFX dan BGM.
- 🖥️ **Desain Responsif & Ringan**: Tampilan antarmuka yang ramah pengguna, modern, dan sangat ringan dijalankan di berbagai spesifikasi PC Windows.

---

## 🖼️ Galeri & Tangkapan Layar

| Menu Utama & Pilihan Modul | Simulasi Perakitan PC (Langkah 1) |
| :---: | :---: |
| <img src="docs/screenshots/preview-1.png" alt="Menu Utama" width="100%"> | <img src="docs/screenshots/preview-3.png" alt="Langkah 1 Merakit" width="100%"> |

| Tantangan Bermain (Level 2) | Modul Materi Edukasi (RAM) |
| :---: | :---: |
| <img src="docs/screenshots/preview-2.png" alt="Tantangan Bermain" width="100%"> | <img src="docs/screenshots/preview-4.png" alt="Modul Materi RAM" width="100%"> |

<p align="center">
  <img src="docs/screenshots/preview-5.png" alt="Tampilan Game Selesai" width="70%">
  <br><em>Tampilan Akhir: PC Berhasil Dirakit dan Sistem Siap Digunakan</em>
</p>

---

## 🎮 Manual Book & Panduan Bermain

> 📘 Untuk panduan teknis dan glosarium lengkap, silakan baca berkas [MANUAL_BOOK.md](MANUAL_BOOK.md).

### 1. Kontrol Dasar
* **Klik Kiri Mouse (LMB)**: Memilih menu, beralih materi, menekan tombol pause/pengaturan.
* **Klik Tahan & Seret (Drag & Drop)**: Mengambil komponen dari rak/baki dan mengarahkannya ke slot target.
* **Lepas Klik**: Menjatuhkan komponen pada slot yang dituju.

### 2. Aturan Permainan pada Mode Bermain
1. **Target**: Setiap level memiliki jumlah target komponen tertentu yang harus dipasangkan ke posisinya.
2. **Timer**: Terdapat waktu hitung mundur di pojok kiri atas. Pastikan seluruh komponen terpasang sebelum waktu habis.
3. **Validasi**:
   - Jika komponen dipasang pada slot yang **benar**, komponen akan mengunci otomatis dan memicu suara keberhasilan.
   - Jika dipasang pada slot yang **salah**, komponen akan memantul kembali ke tempat semula.
4. **Kemenangan**: Menyelesaikan seluruh komponen target tepat waktu untuk melaju ke level berikutnya.

---

## 🧩 Daftar Perangkat Keras yang Dikenalkan

1. **Motherboard / Mainboard**: Papan induk yang menghubungkan seluruh jalur komunikasi antarperangkat.
2. **Processor (CPU)**: Unit pemrosesan pusat yang bertindak sebagai otak utama komputer.
3. **RAM (Random Access Memory)**: Memori kerja cepat sementara untuk menjalankan program dan multitasking.
4. **Media Penyimpanan (Storage - HDD / SSD)**: Tempat menyimpan data dan sistem operasi secara permanen.
5. **VGA Card (GPU - Graphics Card)**: Kartu grafis pengolah gambar dan visual ke monitor.
6. **PSU (Power Supply Unit)**: Sumber penyuplai daya listrik searah (DC) untuk seluruh komponen PC.
7. **Heatsink Fan**: Perangkat pelepas panas untuk menjaga suhu processor tetap optimal.
8. **PC Case / Casing**: Rangka pelindung sirkuit dan dudukan seluruh perangkat keras PC.

---

## 💻 Spesifikasi Sistem (System Requirements)

| Kategori | Kebutuhan Minimum |
| :--- | :--- |
| **Sistem Operasi** | Windows 7 / 8 / 10 / 11 (64-bit) |
| **Prosesor** | Dual Core 2.0 GHz (Intel / AMD) |
| **RAM** | 2 GB |
| **Kartu Grafis** | Intel HD Graphics 4000 atau setara DirectX 10 |
| **Penyimpanan Kosong** | 300 MB ruang kosong |
| **Perangkat Masukan** | Mouse & Keyboard |

---

## 🚀 Cara Menjalankan & Instalasi

### Opsi 1: Menjalankan Langsung (Portable Executable)
1. Clone repositori ini ke komputer Anda:
   ```bash
   git clone https://github.com/Khoniv/techdrop-nivdev.git
   ```
2. Masuk ke folder proyek dan klik ganda pada berkas:
   ```text
   TechDrop 2.0.exe
   ```
3. Game langsung dapat dimainkan tanpa perlu instalasi tambahan.

### Opsi 2: Mengunduh Installer Resmi
1. Buka halaman rilis di [itch.io: TechDrop](https://khonif-zakaria.itch.io/techdropdev).
2. Unduh berkas `TechDrop Installer.exe`.
3. Buka installer dan ikuti langkah pemasangan hingga selesai.

---

## 🛠️ Teknologi yang Digunakan (Tech Stack)

- **Game Engine**: [Unity](https://unity.com/) (Version 2021.3.45f2 LTS)
- **Bahasa Pemrograman**: C# (.NET / Mono Framework)
- **UI Framework**: Unity UI & TextMeshPro
- **Platform Distribusi**: itch.io & GitHub

---

## 📂 Struktur Direktori Repositori

```text
techdrop-nivdev/
├── docs/
│   └── screenshots/          # Tangkapan layar dan banner game
│       ├── banner.png
│       ├── preview-1.png     # Menu Utama
│       ├── preview-2.png     # Level Bermain
│       ├── preview-3.png     # Mode Merakit
│       ├── preview-4.png     # Modul Materi
│       └── preview-5.png     # Game Selesai
├── MonoBleedingEdge/         # Runtime library Mono untuk Unity
├── TechDrop 2.0_Data/        # Aset game, audio, prefabs, dan scene compiled
├── TechDrop 2.0.exe          # Berkas eksekusi utama game Windows
├── UnityCrashHandler64.exe   # Crash handler terintegrasi Unity
├── UnityPlayer.dll           # Unity runtime player library
├── .gitignore                # Aturan pengecualian file git
├── CONTRIBUTING.md           # Panduan kontribusi proyek
├── LICENSE                   # Lisensi open-source (MIT)
├── MANUAL_BOOK.md            # Buku panduan & petunjuk penggunaan lengkap
└── README.md                 # Dokumentasi utama proyek
```

---

## 👤 Pengembang & Kontak

* **Pengembang**: **Khonif Zakaria** ([NivDev](https://github.com/Khoniv))
* **GitHub**: [@Khoniv](https://github.com/Khoniv)
* **itch.io**: [khonif-zakaria.itch.io](https://khonif-zakaria.itch.io/techdropdev)
* **Email**: [oniefzk11@gmail.com](mailto:oniefzk11@gmail.com)

---

## 📄 Lisensi

Proyek ini didistribusikan di bawah lisensi **MIT License**. Lihat berkas [LICENSE](LICENSE) untuk informasi lebih lanjut.
