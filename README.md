# Remote Branch Management Demo

Proyek ini bertujuan untuk mendemonstrasikan pengelolaan cabang remote (remote branch) menggunakan Git. Melalui contoh ini, Anda akan mempelajari cara membuat, mengelola, dan menggabungkan cabang remote dalam alur kerja pengembangan.

## 📖 Daftar Isi

- [Pendahuluan](#pendahuluan)
- [Fitur](#fitur)
- [Prasyarat](#prasyarat)
- [Instalasi](#instalasi)
- [Penggunaan](#penggunaan)
  - [Mengkloning Repository](#mengkloning-repository)
  - [Membuat Cabang Baru](#membuat-cabang-baru)
  - [Mendorong Cabang ke Remote](#mendorong-cabang-ke-remote)
  - [Menarik Perubahan dari Remote](#menarik-perubahan-dari-remote)
  - [Menggabungkan Cabang](#menggabungkan-cabang)
  - [Menghapus Cabang Remote](#menghapus-cabang-remote)
- [Kontribusi](#kontribusi)
- [Lisensi](#lisensi)

## Pendahuluan

Dalam pengembangan perangkat lunak, penggunaan cabang (branch) memungkinkan tim untuk bekerja secara paralel tanpa mengganggu kode utama. Cabang remote adalah cabang yang disimpan di repository server, seperti GitHub, yang memungkinkan kolaborasi tim yang lebih efisien.

## Fitur

- **Membuat Cabang Baru:** Memulai fitur atau perbaikan baru tanpa mengganggu kode utama.
- **Mendorong ke Remote:** Mengirim cabang lokal ke repository remote untuk kolaborasi.
- **Menarik Perubahan:** Memperbarui cabang lokal dengan perubahan terbaru dari remote.
- **Menggabungkan Cabang:** Mengintegrasikan perubahan dari cabang lain ke cabang utama.
- **Menghapus Cabang Remote:** Membersihkan cabang yang sudah tidak diperlukan lagi.

## Prasyarat

- Git terinstal di sistem Anda. [Download Git](https://git-scm.com/downloads)
- Akses ke repository remote (misalnya, GitHub).

## Instalasi

1. **Clone Repository Ini**

   ```bash
   git clone https://github.com/username/remote-branch-demo.git
   cd remote-branch-demo
