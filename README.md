# Generator Surat Peminjaman & Reservasi STITEK Bontang

Aplikasi web sederhana untuk menghasilkan surat peminjaman alat dan reservasi ruangan di STITEK Bontang. Aplikasi ini memungkinkan mahasiswa, dosen, staff, dan organisasi kemahasiswaan untuk membuat surat peminjaman secara otomatis dengan format yang standar.

## Fitur

### 1. Dua Jenis Formulir
- **Peminjaman Alat & Ruangan**: Untuk peminjaman ruangan beserta peralatan pendukung
- **Reservasi Ruangan**: Khusus untuk peminjaman ruangan saja

### 2. Dukungan Multi-user
Mendukung berbagai jenis peminjam:
- Organisasi Mahasiswa (Ormawa/Himpunan)
- Mahasiswa
- Dosen
- Staff

### 3. Data yang Dapat Diisi
#### Data Surat
- Kota Surat (default: Bontang)
- Tanggal Surat (otomatis tanggal hari ini)
- Nomor Surat
- Jabatan Penerima (default: Ketua STITEK Bontang)
- Nama Penerima

#### Data Peminjam
**Untuk Ormawa/Himpunan:**
- Tujuan/Dalam Rangka Acara
- Nama Organisasi
- Nama Kegiatan
- Data Penanggung Jawab (Ketua & Sekretaris)

**Untuk Mahasiswa:**
- Nama Mahasiswa
- NIM
- Keperluan Peminjaman

**Untuk Dosen/Staff:**
- Nama Dosen/Staff
- NIP/NIK
- Keperluan Peminjaman

#### Waktu & Tempat
- Tanggal Kegiatan
- Waktu Pelaksanaan
- Ruangan yang Dipinjam

#### Daftar Alat (khusus form Peminjaman Alat & Ruangan)
- Nama Alat
- Jumlah
- Unit

### 4. Fitur Tambahan
- Preview surat real-time
- Pengecekan ketersediaan ruangan
- Notifikasi jika ruangan sudah di-booking
- Format surat otomatis sesuai peminjam
- Cetak surat langsung ke PDF

## Cara Penggunaan

1. **Memilih Jenis Surat**
   - Klik tab "Peminjaman Alat & Ruangan" untuk meminjam ruangan dan alat
   - Klik tab "Reservasi Ruangan" untuk meminjam ruangan saja

2. **Mengisi Formulir**
   - Isi semua data yang diperlukan sesuai dengan status peminjam
   - Data akan otomatis ter-preview di panel sebelah kanan
   - Untuk peminjaman alat, klik tombol "+ Tambah Alat" untuk menambahkan peralatan

3. **Mencetak Surat**
   - Klik tombol "Cetak Surat" untuk menghasilkan dokumen siap cetak
   - Surat akan dicetak sesuai format yang ditampilkan di preview

## Daftar Ruangan Tersedia
- Lab Pemrograman
- Lab Arsitektur
- Lab Multimedia
- Ruang 3C
- Ruang 3B
- Ruang 4A
- Ruang 4B
- Ruang 2C (Djuanda)
- Lab Elektro (Djuanda)

## Teknologi yang Digunakan
- HTML5
- CSS (Tailwind CSS)
- JavaScript (Vanilla)
- Font: Inter (UI) dan Times New Roman (Preview Surat)

## Instalasi

1. Clone repository ini atau download file HTML
2. Buka file `formpinjam.html` di browser modern
3. Aplikasi siap digunakan

## Persyaratan Sistem
- Browser modern yang mendukung HTML5
- Koneksi internet (untuk loading Tailwind CSS dan font)
- JavaScript harus diaktifkan

## Pengembangan
Untuk pengembangan lebih lanjut, beberapa fitur yang bisa ditambahkan:
- Integrasi dengan database untuk menyimpan history peminjaman
- Sistem approval online
- Ekspor ke format docx
- Sistem notifikasi email
- Kalendar peminjaman ruangan

## Struktur File
```
formpinjam.html     # File utama aplikasi
README.md           # Dokumentasi proyek
```

## Kontribusi
Jika Anda ingin berkontribusi pada proyek ini, silakan:
1. Fork repository
2. Buat branch baru
3. Commit perubahan Anda
4. Push ke branch
5. Buat Pull Request

## Lisensi
Proyek ini bersifat open source dan dapat digunakan secara bebas dengan mencantumkan sumber.

---
Dibuat dengan ❤️ untuk STITEK Bontang