# Sholat Reminder

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0-brightgreen.svg)

**Sholat Reminder** adalah ekstensi Visual Studio Code yang menampilkan pengingat waktu sholat berdasarkan **City ID** yang ditentukan. Ekstensi ini akan menampilkan countdown menuju waktu sholat berikutnya langsung di dalam VSCode.

## Fitur

- **Set City ID**: Atur City ID untuk jadwal sholat di lokasi Anda.
- **Status Bar Reminder**: Menampilkan countdown menuju waktu sholat berikutnya di status bar.
- **Full-Screen Notification**: Memberikan notifikasi layar penuh saat waktu sholat tiba.
- **Automatic Reload**: Mereload ekstensi secara otomatis setelah City ID diperbarui.

## Sumber API

Ekstensi ini menggunakan [API myQuran](https://api.myquran.com/) untuk mendapatkan jadwal sholat. Jadwal diperbarui setiap kali Anda mengatur atau mengubah City ID, sehingga memastikan waktu sholat yang akurat sesuai lokasi Anda.

## Cara Mendapatkan City ID

Untuk menggunakan ekstensi ini, Anda memerlukan City ID yang sesuai dengan lokasi Anda. Berikut cara mendapatkannya:

1. Buka [Dokumentasi API myQuran](https://api.myquran.com/).
2. Navigasi ke bagian yang menyediakan daftar **City ID** untuk berbagai kota. Anda dapat melihat endpoint seperti `https://api.myquran.com/v2/sholat/kota/semua` untuk mendapatkan semua City ID yang tersedia.
3. Cari City ID untuk kota Anda dan catat ID-nya. Contoh: `1301` untuk Jakarta.

## Instalasi

1. **Unduh dan Instal**: Anda bisa mengunduh ekstensi ini melalui Visual Studio Code Marketplace.
2. Setelah diinstal, ekstensi akan aktif secara otomatis.

## Cara Menggunakan

1. **Mengatur City ID**:

   - Buka Command Palette (tekan `Ctrl+Shift+P` atau `Cmd+Shift+P` di Mac).
   - Ketik `Set City ID for Sholat Reminder` dan pilih perintah tersebut.
   - Masukkan City ID sesuai lokasi Anda untuk menampilkan jadwal sholat yang sesuai.

2. **Menampilkan Pengingat Waktu Sholat**:

   - Ekstensi akan menampilkan waktu sholat berikutnya dalam bentuk countdown di status bar.
   - Ketika waktu sholat tiba, akan muncul notifikasi layar penuh di VSCode.

3. **Merubah City ID**:
   - Jika Anda berpindah lokasi, Anda dapat mengubah City ID dengan perintah yang sama di Command Palette.
   - Setelah City ID berhasil diperbarui, VSCode akan otomatis reload untuk menerapkan perubahan.

## Contoh Tampilan

<!-- ![Sholat Reminder Status Bar](media/screenshot.png) -->

## Lisensi

Ekstensi ini dilisensikan di bawah [MIT License](LICENSE.md).

## Kontribusi

Kami menyambut kontribusi dari komunitas! Silakan fork repositori ini dan buat pull request untuk perbaikan atau fitur baru.

## Catatan

Pastikan koneksi internet aktif agar dapat mengambil jadwal sholat terbaru dari server.