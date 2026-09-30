# Panduan Pengguna AgenPro

**Versi: 1.4.0**
**Terakhir diperbarui: 30 September 2026**

---

## Daftar Isi

1. Pengenalan
2. Instalasi & Persiapan
3. Onboarding Pertama Kali
4. Manajemen Prospek
5. Manajemen Nasabah
6. Manajemen Polis
7. Pembayaran Premi
8. Interaksi Nasabah
9. Dashboard Premi
10. Agenda & Follow-up
11. Pipeline Penjualan
12. WhatsApp Integration
13. Pengaturan & Kustomisasi
14. Backup & Restore
15. Import & Export CSV
16. Verifikasi Keaslian APK
17. FAQ
18. Kontak & Dukungan

---

## 1. Pengenalan

**AgenPro** adalah aplikasi sales funnel untuk agen asuransi yang membantu Anda:

- Mengelola prospek dari awal sampai closing
- Menyimpan database nasabah dengan multiple polis
- Mencatat pembayaran premi & mengingatkan jatuh tempo
- Memantau APE (Annualized Premium Equivalent) & target
- Mengatur agenda follow-up otomatis
- Kirim WhatsApp dengan template
- Melihat statistik penjualan & grafik tren

### Fitur Utama v1.4.0

- Data tersimpan 100% lokal di HP Anda (privat & aman)
- Backup terenkripsi dengan PIN
- Dark mode & multi-tema (Hijau, Navy, Merah)
- PIN lock untuk keamanan
- Template WhatsApp yang bisa dikustomisasi
- Multiple polis per nasabah
- Dashboard Premi — APE, Target, Grafik Tren 6 Bulan
- Reminder Jatuh Tempo otomatis (H-30/H-7/H-1)
- Import CSV prospek & polis (bulk)
- Dukungan tablet (layout 2 kolom)

### 🆕 Fitur Baru di v1.4.0

- **🗂️ 11 Sumber Prospek** — Referral, Cold Market, Sosial Media, Event/Seminar, Walk-in, Website, Kampanye WhatsApp, Iklan Digital, Organik, Referensi, Lainnya.
- **✨ Transisi iOS-like** — Slide horizontal + fade saat berpindah antar tab, terasa lebih halus dan premium.

### 🎁 Fitur Bawaan v1.3.0

- **🔔 Notifikasi Kustom** — Suara, getaran, dan tombol aksi (Lihat, Tandai selesai, Tunda 1 jam) langsung dari notifikasi.
- **💰 Format Rupiah Otomatis** — Input Premi dan Estimasi Premi otomatis diformat (contoh: 8.000.000).
- **⏰ Reminder H-0 Jatuh Tempo** — Notifikasi jatuh tempo muncul tepat di hari-H, bukan cuma H-30/H-7/H-1.
- **🎂 Birthday Reminder Lebih Cepat** — Dipercepat dari 30 menit jadi 1 menit setelah aplikasi dibuka.
- **🔒 Obfuscation Lisensi** — Modul lisensi ter-obfuscate penuh (R8 inline) untuk keamanan.

---

## 2. Instalasi & Persiapan

### 2.1 Instalasi

1. Download file `app-release.apk` dari:
   https://github.com/denysuse/agenpro-releases/releases/latest
2. Buka File Manager, cari file APK
3. Tap file, lalu Install
4. Izinkan "Install from unknown sources" jika diminta
5. Buka aplikasi AgenPro

### 2.2 Syarat Minimal

- Android 8.0 (API 26) atau lebih baru
- Ruang penyimpanan: ~10 MB
- Internet: Tidak wajib (hanya untuk backup ke Drive)

### 2.3 Setup Profil Awal

1. Buka Pengaturan, lalu Profil Saya
2. Isi: Nama Agen (wajib), Nama Perusahaan, No WhatsApp
3. Tap "Tampilkan Data Lainnya" untuk isi: Alamat Email, Posisi/Jabatan, Kode Agen, Alamat Agency/Branch
4. Tap "Simpan Profil"

---

## 3. Onboarding Pertama Kali

Saat pertama kali buka, akan muncul 4 slide:

1. Slide 1: Selamat datang
2. Slide 2: Fitur pipeline
3. Slide 3: WhatsApp template
4. Slide 4: Pilih salah satu
   - "Isi Data Contoh" untuk coba dengan data dummy
   - "Mulai dari Kosong" untuk mulai dari nol

Setelah selesai, Anda masuk ke Beranda.

---

## 4. Manajemen Prospek

### 4.1 Menambah Prospek

1. Buka tab Prospek (ikon di bawah)
2. Tap tombol + (kanan bawah)
3. Isi data: Nama (wajib), No HP/WA, Kota Domisili, Sumber Prospek, Tahap Pipeline (Prospek/Kualifikasi/Presentasi/Proposal/Closing), Estimasi Premi, Suhu Prospek (Dingin/Hangat/Panas), Catatan
4. Tap "Simpan"

### 4.2 Melihat Detail Prospek

Tap kartu prospek untuk melihat: Info lengkap, Timeline Aktivitas, Riwayat Tahap Funnel, dan Riwayat Follow-up.

### 4.3 Edit & Hapus

- Edit: Buka detail, tap ikon pensil
- Hapus: Swipe kartu ke kiri ATAU tap ikon tong sampah
- Dialog konfirmasi akan muncul sebelum data dihapus

### 4.4 Filter & Cari

- Cari: Ketik di search bar
- Filter Lanjutan: Tap tombol "Filter lanjutan prospek"
- Filter berdasarkan tanggal, tahap, kota, sumber
- "Belum nasabah" untuk prospek yang belum dikonversi
- "Tanpa follow-up" untuk prospek tanpa agenda

### 4.5 Konversi ke Nasabah

Ketika prospek closing:

1. Buka detail prospek
2. Tap "Jadikan Nasabah"
3. Preview data: nama, HP/WA, domisili akan disalin ke nasabah
4. Tap "Konversi"

Catatan: Produk & polis tidak diinput di sini. Setelah jadi nasabah, tambahkan polis via Detail Nasabah, lalu tap tombol + Tambah Polis.

---

## 5. Manajemen Nasabah

### 5.1 Menambah Nasabah

1. Buka tab Nasabah
2. Tap tombol +
3. Isi data: Nama (wajib), No HP/WA, Kota Domisili, Tanggal Lahir
4. Tap "Simpan"

Catatan v1.4.0: Nasabah hanya menyimpan identitas. Produk, nomor polis, premi, dan tanggal jatuh tempo diinput di masing-masing polis.

### 5.2 Cari & Filter

- Cari: Nama, HP/WA, atau domisili
- Filter: Tap ikon di kanan search bar
- Pilihan: Nama (A-Z), Nama (Z-A), Domisili (A-Z), Terbaru

### 5.3 Badge Jatuh Tempo

Di card nasabah, ada badge yang muncul otomatis:

- Merah: Jatuh tempo 7 hari atau kurang / sudah lewat
- Oranye: Jatuh tempo 8-14 hari
- Kuning: Jatuh tempo 15-30 hari

### 5.4 Kontak Cepat

Tap ikon WhatsApp di kartu nasabah untuk buka chat.

### 5.5 Hapus Nasabah

Tap ikon tong sampah, konfirmasi, maka data nasabah dan semua polisnya akan terhapus.

---

## 6. Manajemen Polis

### 6.1 Menambah Polis

1. Buka Detail Nasabah
2. Tap + di section Polis
3. Isi: Produk, Nomor Polis, Premi per Periode, Periode Pembayaran (Bulanan/Kuartalan/Semesteran/Tahunan), Tanggal Mulai, Jatuh Tempo Berikutnya, Tanggal Polis Berakhir, Catatan (opsional)
4. Tap "Simpan"

### 6.2 Edit & Hapus Polis

- Edit: Tap ikon pensil di kartu polis
- Hapus: Tap ikon tong sampah, lalu konfirmasi

### 6.3 Status Polis

- Aktif: Polis berjalan normal
- Jatuh Tempo: Akan jatuh tempo 30 hari atau kurang
- Lapsed: Jatuh tempo sudah lewat
- Selesai: Polis berakhir

### 6.4 Multiple Polis

Satu nasabah bisa punya banyak polis. Contoh: Ahmad Dahlan punya Asuransi Kesehatan (Rp 12jt/bulan) dan Asuransi Jiwa (Rp 18jt/tahun). Setiap polis punya reminder jatuh tempo sendiri.

---

## 7. Pembayaran Premi

### 7.1 Mencatat Pembayaran

1. Buka Detail Nasabah, lalu Detail Polis
2. Tap ikon bayar (ikon uang)
3. Isi: Jumlah Dibayar (default: premi polis), Tanggal Pembayaran, Metode (Transfer/Autodebet/Tunai/Kartu Kredit/E-Wallet), Catatan (opsional)
4. Tap "Simpan"

### 7.2 Auto-Roll Jatuh Tempo

Setiap kali Anda mencatat pembayaran, jatuh tempo polis otomatis maju +1 periode:

- Bulanan: +30 hari
- Kuartalan: +90 hari
- Semesteran: +180 hari
- Tahunan: +365 hari

Contoh: Polis jatuh tempo 30 Nov 2026, Anda catat pembayaran, maka jatuh tempo berikutnya otomatis jadi 30 Des 2026.

### 7.3 Riwayat Pembayaran

Di Detail Nasabah ada section Riwayat Pembayaran:

- Total Dibayar: akumulasi semua pembayaran
- List pembayaran: tanggal, jumlah, metode, catatan

### 7.4 Hapus Pembayaran

Tap ikon tong sampah di item pembayaran, konfirmasi, data terhapus.

Catatan: Hapus pembayaran tidak mengembalikan jatuh tempo polis. Anda perlu edit polis manual jika perlu.

---

## 8. Interaksi Nasabah

### 8.1 Menambah Interaksi

1. Buka Detail Nasabah, section Interaksi Terakhir
2. Tap + di kanan header
3. Isi: Jenis (Telepon/WhatsApp/Kunjungan/Email/Lainnya), Judul (wajib), Catatan (opsional), Tanggal & Waktu
4. Tap "Simpan"

### 8.2 Hapus Interaksi

Tap ikon tong sampah di item interaksi, konfirmasi, terhapus.

### 8.3 Manfaat

Interaksi membantu Anda track riwayat komunikasi dengan nasabah. Contoh: telepon konfirmasi polis (25 Sep), WhatsApp reminder premi (20 Sep), kunjungan review portofolio (15 Sep).

---

## 9. Dashboard Premi

Di Beranda ada section Dashboard Premi dengan 5 komponen:

### 9.1 APE Bulan Ini

APE (Annualized Premium Equivalent) = premi disetahunkan.

Rumus:

- Bulanan x 12
- Kuartalan x 4
- Semesteran x 2
- Tahunan x 1

Contoh: Polis baru bulan ini Rp 15jt/bulan, maka APE = Rp 180jt.

### 9.2 APE Tahun Ini

Total APE dari semua polis yang dibuat tahun ini (Jan-Des). Berguna untuk pencapaian kontes dan target tahunan.

### 9.3 Target APE

Set target di Pengaturan, lalu Target Penjualan:

- Target APE per Bulan (Rp)
- Target APE per Tahun (Rp)

Progress bar akan muncul otomatis dengan warna: Merah (kurang dari 50%), Oranye (50-80%), Hijau (lebih dari 80%).

### 9.4 Grafik Tren 6 Bulan

Bar chart menunjukkan APE per bulan selama 6 bulan terakhir. Bulan ini di-highlight dengan warna lebih gelap.

### 9.5 Portofolio Aktif

Jumlah polis dengan status "Aktif" untuk dipantau agar tidak lapsed.

### 9.6 Jatuh Tempo 30 Hari

List polis yang akan jatuh tempo dalam 30 hari ke depan, dengan badge warna:

- Merah: Lewat / 7 hari atau kurang
- Oranye: 8-14 hari
- Kuning: 15-30 hari

---

## 10. Agenda & Follow-up

### 10.1 Menambah Agenda

1. Buka tab Agenda
2. Tap +
3. Isi: Judul (wajib), Prospek terkait, Jenis (Telepon/Pertemuan/Presentasi/Kirim Proposal/dll), Waktu Mulai, Pengingat (1 jam/3 jam/1 hari/3 hari sebelum), Keterangan
4. Tap "Simpan"

### 10.2 Kelompok Agenda

Agenda otomatis dikelompokkan: Terlambat (sudah lewat), Hari ini, Berikutnya (mendatang).

### 10.3 Snooze (Tunda)

Tap ikon jam di baris agenda untuk tunda 1 jam, 3 jam, 1 hari, 3 hari, atau pilih tanggal dan waktu spesifik.

### 10.4 Notifikasi Pengingat


Aplikasi mengirim notifikasi sesuai waktu pengingat yang diatur, dengan detail:

- **Suara & Getaran** — Notifikasi berbunyi & bergetar (bisa diatur di Pengaturan HP).
- **Tombol Aksi**:
  - **Lihat** — Buka detail agenda/polis langsung.
  - **Tandai selesai** — Selesaikan agenda tanpa buka aplikasi.
  - **Tunda 1 jam** — Tunda notifikasi 1 jam ke depan.
- **Jenis Notifikasi**:
  - Agenda follow-up (H-24 jam & H-4 jam)
  - Jatuh tempo premi (H-30, H-7, H-1, dan H-0/hari ini)
  - Ulang tahun nasabah (H-1 & hari-H)
- **Jika notifikasi tidak muncul**: Cek *Pengaturan HP → Aplikasi → AgenPro → Notifikasi* → pastikan diizinkan.
- **Matikan "Pause app activity if unused"** di pengaturan aplikasi agar notifikasi tidak dimatikan Android saat aplikasi lama tidak dibuka.

### 10.5 Tandai Selesai

Tap checkbox di kiri agenda untuk tandai selesai.

---

## 11. Pipeline Penjualan

### 11.1 Tampilan Mobile

Di HP, pipeline tampil sebagai tab per tahap yang bisa di-swipe.

### 11.2 Tampilan Tablet

Di tablet, pipeline tampil sebagai kolom Kanban berdampingan.

### 11.3 Tahap Pipeline

1. Prospek - Kontak awal
2. Kualifikasi - Menilai kebutuhan
3. Presentasi - Demo produk
4. Proposal - Kirim penawaran
5. Closing - Akad/penutupan

---

## 12. WhatsApp Integration

### 12.1 Kirim WhatsApp dari Prospek/Nasabah

1. Buka Prospek atau Detail Nasabah
2. Tap ikon WhatsApp (hijau)
3. Pilih Template atau tulis pesan manual
4. Tap "Kirim", WhatsApp terbuka

### 12.2 Template WhatsApp

Template default: Follow-up awal, Pengingat jatuh tempo, Ucapan ulang tahun, Konfirmasi pertemuan.

### 12.3 Edit Template

Template bisa dikustomisasi di dialog WhatsApp (tap "Edit Template").

---

## 13. Pengaturan & Kustomisasi

### 13.1 Tema Warna

Pengaturan, lalu Warna Tema. Pilih: Hijau, Navy Premium, atau Merah.

### 13.2 Mode Gelap

Pengaturan, lalu Tampilan. Pilih: Ikuti sistem, Terang, atau Gelap.

### 13.3 Target Penjualan

Pengaturan, lalu Target Penjualan:

- Target APE per Bulan (Rp)
- Target APE per Tahun (Rp)

Akan ditampilkan di Dashboard Premi dan Hero Card Beranda.

### 13.4 PIN Lock

Pengaturan, lalu Keamanan Aplikasi:

1. Input PIN (minimal 4 digit)
2. Tap "Aktifkan PIN"
3. Saat buka aplikasi, akan diminta PIN
4. Untuk menonaktifkan: tap "Nonaktifkan"

### 13.5 Business Card

Pengaturan, lalu Lihat Business Card. Menampilkan QR code berisi kontak Anda (vCard). Orang lain bisa scan untuk menyimpan kontak.

---

## 14. Backup & Restore

### 14.1 Backup ke Perangkat

1. Pengaturan, Laporan, lalu "Simpan di perangkat"
2. Pilih lokasi (Download, Drive, dll)
3. Input PIN backup
4. Tap "Lanjutkan"

Hasil: File .db terenkripsi (aman).

### 14.2 Restore dari Backup

1. Pengaturan, Laporan, lalu "Pulihkan file"
2. Pilih file backup
3. Input PIN backup
4. Tap "Lanjutkan"

Peringatan: Restore akan menimpa data saat ini.

### 14.3 Backup Otomatis

Aplikasi otomatis backup sekali sehari (kalau baterai cukup).

### 14.4 Backup ke Google Drive (Opsional)

Fitur ini memerlukan akun Google. Data tetap di Drive pribadi Anda.

---

## 15. Import & Export CSV

### 15.1 Export CSV

Pengaturan, Laporan, lalu "Ekspor laporan CSV". Format: Jenis, Nama, HP/Domisili, Produk, No. Polis, Tahap/Jenis, Tanggal, Status. File bisa dibuka di Excel atau Google Sheets.

### 15.2 Import Prospek CSV

Pengaturan, Laporan, lalu "Impor prospek dari template CSV".

Format kolom: nama, no hp, kota, sumber, tahap, suhu, estimasi premi.

### 15.3 Import Polis CSV

Pengaturan, Laporan, lalu "Impor polis dari CSV".

Format kolom: nama, nomorPolis, produk, premi, periode, tanggalMulai, tanggalJatuhTempo, status.

Aturan:

- nama harus match dengan nasabah yang sudah ada (case-insensitive)
- periode = Bulanan/Kuartalan/Semesteran/Tahunan
- tanggalMulai dan tanggalJatuhTempo = format yyyy-MM-dd
- Kalau nasabah tidak ketemu, baris di-skip (ada tanda X di preview)

---

## 16. Verifikasi Keaslian APK

Sebelum install, pastikan APK yang Anda download **asli dari sumber resmi**.

### 16.1 Sumber Resmi

Download hanya dari:

- **Landing page**: https://denysuse.github.io/agenpro-landing/
- **GitHub Releases**: https://github.com/denysuse/agenpro-releases/releases/latest
- **WhatsApp resmi**: https://wa.me/6281277077838

**Jangan install dari sumber lain** meskipun gratis.

### 16.2 SHA-256 Checksum

Checksum v1.4.0:

    2ec171941bbc8b749e36737a33bfd13689bf4f9cf7cc48990e52f9f194598d59

Jika hasil download Anda berbeda → **jangan install**, hubungi kami.

### 16.3 Cara Verifikasi

**Android:**
1. Install app **Hash Droid** dari Play Store
2. Buka file APK → pilih algoritma SHA-256
3. Cocokkan hasilnya dengan checksum di atas

**Windows (PowerShell):**

    Get-FileHash app-release.apk -Algorithm SHA256

**Mac / Linux:**

    shasum -a 256 app-release.apk

### 16.4 Scan VirusTotal

APK kami dipindai oleh 70+ antivirus di VirusTotal secara otomatis:

- Link scan: https://www.virustotal.com/gui/file/2ec171941bbc8b749e36737a33bfd13689bf4f9cf7cc48990e52f9f194598d59

Anda bisa cek hasilnya sendiri untuk memastikan tidak ada malware.

### 16.5 Keamanan Data

- ✅ **Semua data tersimpan LOKAL** di HP Anda (Room database)
- ✅ **Tidak ada koneksi ke server kami** — tidak ada data yang dikirim ke mana pun
- ✅ **Tidak ada tracking analytics**
- ✅ **Tidak ada iklan**
- ✅ **Tidak menjual data** ke pihak ketiga

Satu-satunya koneksi keluar adalah:
- Google Drive Backup (opsional — hanya jika Anda aktifkan)
- WhatsApp API (saat kirim pesan ke nasabah)

---

### 16.6 Penjelasan Tag VirusTotal

Saat Anda cek APK AgenPro di VirusTotal, mungkin muncul beberapa tag. Berikut penjelasannya:

| Tag | Penjelasan |
|---|---|
| `android` | File APK untuk Android — normal |
| `contains-elf` | Berisi library native (SQLite untuk database) — normal |
| `obfuscated` | Kode di-obfuscate untuk keamanan — bagus |
| `reflection` | Bagian dari obfuscation — normal |
| `checks-gps` | Dari library WorkManager, bukan untuk melacak Anda |
| `telephony` | Hanya untuk tombol "Telepon" di Detail Nasabah — bukan merekam |
| `apk` | Format file — normal |

**Yang perlu diyakinkan:**

- ✅ **0 dari 68 antivirus** mendeteksi malware
- ✅ **Tidak ada permission GPS** di aplikasi
- ✅ **Tidak ada permission mikrofon/kamera**
- ✅ **Semua data tersimpan lokal** di HP Anda

Kalau ada antivirus tertentu yang mendeteksi (false positive), biasanya karena
obfuscation R8 — laporkan ke kami dengan screenshot untuk kami tindak lanjut.

## 17. FAQ

Q: Apakah data saya aman?
A: Ya. Semua data tersimpan lokal di HP Anda (Room database). Kami tidak memiliki akses ke data Anda. Backup terenkripsi dengan PIN.

Q: Bagaimana kalau HP saya hilang?
A: Data akan hilang kecuali Anda punya backup. Rekomendasi: Backup rutin ke Google Drive atau flashdisk.

Q: Apakah bisa dipakai di beberapa HP?
A: Tidak secara langsung. Anda perlu backup di HP 1, lalu restore di HP 2.

Q: Apakah butuh internet?
A: Tidak untuk fungsi utama. Internet hanya untuk backup Google Drive (opsional) dan update aplikasi.

Q: Bagaimana cara export data?
A: Pengaturan, Laporan, lalu "Ekspor laporan CSV". File bisa dibuka di Excel.

Q: PIN saya lupa, bagaimana?
A: Sayangnya, PIN tidak bisa dipulihkan (demi keamanan). Anda perlu uninstall, lalu install ulang (data hilang).

Q: Apakah ada versi iOS?
A: Belum. Saat ini hanya Android.

Q: Bagaimana cara update aplikasi?
A: Download APK versi terbaru dari https://github.com/denysuse/agenpro-releases/releases/latest, install seperti biasa. Data lama tetap tersimpan.

Q: Apakah aplikasi gratis?
A: Trial gratis 5 hari. Hubungi WhatsApp +62 812-7707-7838 untuk info lisensi.

Q: Bagaimana cara hapus semua data?
A: Pengaturan HP, Apps, AgenPro, lalu Clear Storage. Atau uninstall aplikasi.

Q: Apa bedanya APE dengan premi biasa?
A: APE = premi disetahunkan (Bulanan x 12, Kuartalan x 4, dll). Premi biasa = jumlah yang dibayar per periode.

Q: Kenapa nasabah saya tidak punya produk?
A: Di v1.4.0, nasabah hanya menyimpan identitas. Produk dan polis ada di masing-masing polis. Tambah polis via Detail Nasabah, lalu + Tambah Polis.

---

## 18. Kontak & Dukungan

- Email: denysuse@gmail.com
- WhatsApp: +62 812-7707-7838 (https://wa.me/6281277077838)
- Privacy Policy: https://denysuse.github.io/privacy-policy/
- Download APK: https://github.com/denysuse/agenpro-releases/releases/latest

---

Copyright 2026 AgenPro. All rights reserved.
