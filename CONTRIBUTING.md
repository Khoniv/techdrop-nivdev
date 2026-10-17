# Panduan Kontribusi (Contributing Guide)

Terima kasih atas ketertarikan Anda untuk berkontribusi pada pengembangan **TechDrop 2.0**! Proyek ini bertujuan untuk menyediakan media pembelajaran pengenalan perangkat keras komputer yang interaktif dan menyenangkan bagi siswa, mahasiswa, dan pemula.

---

## 📌 Cara Berkontribusi

### 1. Melaporkan Masalah (Bug Reports)
Jika Anda menemukan kendala saat memainkan game (glitch visual, audio tidak sinkron, error drag-and-drop, crash), silakan buka [GitHub Issue](https://github.com/Khoniv/techdrop-nivdev/issues) dengan format:
- **Deskripsi Bug**: Jelaskan apa yang terjadi.
- **Langkah untuk Mereproduksi**: Urutan tindakan sebelum bug terjadi.
- **Tangkapan Layar (Screenshot)**: Sertakan gambar jika memungkinkan.
- **Spesifikasi Perangkat**: Sistem Operasi Windows dan resolusi layar yang digunakan.

### 2. Mengajukan Ide & Fitur Baru (Feature Requests)
Punya ide untuk menambahkan level baru, perangkat keras modern (seperti PCIe Gen 5 SSD, Water Cooling, GPU terbaru), atau mode kuis interaktif? Buat issue baru berlabel `enhancement`.

### 3. Kontribusi Kode & Aset (Pull Requests)
1. Lakukan **Fork** pada repositori ini.
2. Buat branch baru untuk fitur atau perbaikan bug Anda:
   ```bash
   git checkout -b feature/fitur-baru
   ```
3. Lakukan commit perubahan Anda dengan pesan yang jelas dan deskriptif:
   ```bash
   git commit -m "Add: Penjelasan komponen NVMe SSD pada modul materi"
   ```
4. Push branch ke repository fork Anda:
   ```bash
   git push origin feature/fitur-baru
   ```
5. Buka **Pull Request** ke branch `main` repositori utama ini.

---

## 🎨 Standar Desain & Aset
- Pastikan sprite 2D menggunakan format resolusi proporsional dan tidak pecah.
- Setiap teks edukatif menggunakan bahasa Indonesia yang baik, komunikatif, dan akurat secara terminologi teknis komputer.
- Gunakan audio/efek suara yang bebas royalti (Royalty-Free).

---

## 📬 Kontak
Untuk pertanyaan atau kolaborasi lebih lanjut:
- **Developer**: Khonif Zakaria (NivDev)
- **Email**: [oniefzk11@gmail.com](mailto:oniefzk11@gmail.com)
- **itch.io**: [https://khonif-zakaria.itch.io/techdropdev](https://khonif-zakaria.itch.io/techdropdev)
