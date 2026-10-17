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
</p>

---

## 📌 Daftar Isi
* [Tentang Proyek](#-tentang-proyek)
* [Fitur Utama](#-fitur-utama)
* [Galeri & Tangkapan Layar](#-galeri--tangkapan-layar)
* [Panduan Permainan (Gameplay Guide)](#-panduan-permainan-gameplay-guide)
* [Daftar Perangkat Keras yang Dikenalkan](#-daftar-perangkat-keras-yang-dikenalkan)
* [Spesifikasi Sistem](#-spesifikasi-sistem)
* [Cara Menjalankan & Instalasi](#-cara-menjalankan--instalasi)
* [Teknologi yang Digunakan](#-teknologi-yang-digunakan)
* [Arsitektur & Struktur Direktori](#-arsitektur--struktur-direktori)
* [Pengembang & Kontak](#-pengembang--kontak)

---

## 📖 Tentang Proyek

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

## 🎮 Panduan Permainan (Gameplay Guide)

### 1. Kontrol Dasar
* **Klik Kiri Mouse (LMB)**: Memilih menu, membuka materi, dan menekan tombol navigasi.
* **Klik Tahan & Seret (Drag & Drop)**: Mengambil komponen hardware dan mengarahkannya ke soket tujuan.
* **Lepas Klik**: Menempatkan komponen pada slot yang dituju.

### 2. Aturan Permainan pada Mode Bermain
1. **Target**: Setiap level menentukan komponen tertentu yang harus dipasang dengan benar.
2. **Timer**: Terdapat waktu hitung mundur di bagian atas layar. Selesaikan pemasangan sebelum waktu habis.
3. **Validasi Slot**:
   - Jika komponen ditempatkan pada posisi yang **benar**, komponen akan terkunci otomatis dan memicu suara notifikasi berhasil.
   - Jika ditempatkan pada posisi yang **salah**, komponen akan otomatis memantul kembali ke baki inventaris.
4. **Kemenangan**: Level selesai dan level berikutnya terbuka setelah semua komponen terpasang tepat waktu.

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

## 💻 Spesifikasi Sistem

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
1. Clone repositori ini:
   ```bash
   git clone https://github.com/Khoniv/techdrop-nivdev.git
   ```
2. Buka folder proyek dan klik ganda pada:
   ```text
   TechDrop 2.0.exe
   ```
3. Game langsung dapat dimainkan tanpa perlu instalasi tambahan.

### Opsi 2: Mengunduh Installer Resmi
1. Kunjungi halaman resmi di [itch.io: TechDrop](https://khonif-zakaria.itch.io/techdropdev).
2. Unduh berkas **TechDrop Installer.exe**.
3. Jalankan file installer dan ikuti petunjuk pemasangan hingga selesai.

---

## 🛠️ Teknologi yang Digunakan

- **Game Engine**: [Unity](https://unity.com/) (Version 2021.3.45f2 LTS)
- **Bahasa Pemrograman**: C# (.NET / Mono Framework)
- **UI Framework**: Unity UI & TextMeshPro
- **Platform Distribusi**: itch.io & GitHub

---

## 📂 Arsitektur & Struktur Direktori

```text
techdrop-nivdev/
├── docs/
│   └── screenshots/          # Tangkapan layar dan banner game
│       ├── banner.png        # Banner header TechDrop
│       ├── preview-1.png     # Tampilan Menu Utama
│       ├── preview-2.png     # Tampilan Mode Bermain
│       ├── preview-3.png     # Tampilan Mode Merakit
│       ├── preview-4.png     # Tampilan Modul Materi
│       └── preview-5.png     # Tampilan Game Selesai
├── MonoBleedingEdge/         # Runtime library Mono Unity
├── TechDrop 2.0_Data/        # Aset game, audio, prefabs, dan scene data
├── TechDrop 2.0.exe          # Berkas eksekusi utama game (Windows)
├── UnityCrashHandler64.exe   # Crash handler bawaan Unity
├── UnityPlayer.dll           # Runtime player engine Unity
├── .gitignore                # Aturan pengecualian berkas git
└── README.md                 # Dokumentasi utama proyek
```

---

## 👤 Pengembang & Kontak

* **Pengembang**: **Khonif Zakaria** ([NivDev](https://github.com/Khoniv))
* **GitHub**: [@Khoniv](https://github.com/Khoniv)
* **itch.io**: [khonif-zakaria.itch.io](https://khonif-zakaria.itch.io/techdropdev)
* **Email**: [oniefzk11@gmail.com](mailto:oniefzk11@gmail.com)
