# WinCBT Universal &mdash; Secure Exam Browser

Aplikasi Android Kiosk Client resmi dan universal untuk pelaksanaan Asesmen / Ujian Berbasis Komputer & Smartphone (**WinCBT Universal**). ujian yang aman, tertib, dan lancar.

---

## 🚀 Informasi Berkas Rilis Resmi

* **Berkas APK**: `WinCBT_Universal_v1.0.0.apk` *(Instalasi langsung di perangkat siswa/sekolah)*
* **Berkas AAB (Play Console)**: `WinCBT_Universal_v1.0.0.aab` *(Paket rilis Google Play Store)*
* **Ukuran Berkas APK**: `5.258.068 bytes` (~5.26 MB)
* **Ukuran Berkas AAB**: `4.642.287 bytes` (~4.64 MB)
* **Versi Rilis**: `v1.0.0 (Build 1)`
* **Application ID**: `com.sekolah.wincbtuniversal`
* **Target Kompatibilitas**: Android 8.0 (Oreo / API 26) hingga Android 15+ (Vanilla Ice Cream / API 35)

---

## 🔐 Integritas & Verifikasi Berkas (File Checksum)

Sebelum instalasi atau deployment, integritas berkas biner dapat diverifikasi menggunakan algoritma SHA-256:

```text
SHA-256 Checksum (APK):
90C6BC4AD31CCE3044856C735E3B09BD246E79C9F4C11DF1BEA7119B84A96611

SHA-256 Checksum (AAB Play Console):
B4327CB5F8AF3E3B41A79817C1E6524CC5C1E4D756639F71D1F8813B9FDA303F
```

Verifikasi di terminal/PowerShell:
```powershell
Get-FileHash -Path .\WinCBT_Universal_v1.0.0.apk -Algorithm SHA256
```

---

## 🔑 Sidik Jari Sertifikat Resmi (Google Play Console)

Sertifikat penandatanganan aplikasi (*App Signing Certificate*) yang terdaftar dan terverifikasi di Google Play:

```text
SHA-256 Certificate Fingerprint:
FF:8C:C9:CA:60:9E:0D:C9:08:64:E8:71:0C:73:75:52:FF:BF:60:4B:9E:AA:24:17:0A:B4:66:DB:FF:57:0B:A0

SHA-1 Certificate Fingerprint:
E3:73:D2:8E:6A:1E:BE:9B:77:2E:F5:08:A0:D2:84:90:42:EE:99:3B
```

---

## 🛡️ Fitur Keamanan & Keunggulan Utama

1. **Hardware Kiosk Mode & Semat Layar (Screen Pinning)**:
   - Mengunci layar secara ketat selama sesi ujian berlangsung.
   - Memblokir tombol navigasi (*Back, Home, Recent Apps*), gesture swipe, dan status bar notification shade.
2. **Universal Compatibility (Google Form & Web CBT)**:
   - Mendukung ujian menggunakan Google Forms, Google Workspace for Education, CBT Web Sekolah/Madrasah, Moodle, dan platform asesmen web lainnya.
3. **Pemindai QR Code Terintegrasi**:
   - Memudahkan siswa masuk ke ruang ujian dengan memindai kode QR soal tanpa perlu mengetik URL yang panjang dan rumit.
4. **Proteksi Anti-Curang (Anti-Cheat Engine)**:
   - Mencegah mode layar terbelah (*split-screen*), aplikasi mengambang (*floating apps / picture-in-picture*), dan upaya keluar aplikasi sebelum waktu ujian selesai.
5. **Ringan & Bebas Iklan**:
   - Didesain hemat memori (*zero-lag, anti-crash*) untuk berjalan mulus di berbagai perangkat Android bahkan dengan RAM terbatas (2GB/3GB).
   - 100% Bebas iklan komersial demi kenyamanan dan fokus belajar siswa.

---

## 📱 Petunjuk Instalasi untuk Siswa / Sekolah

1. Unduh berkas **`WinCBT_Universal_v1.0.0.apk`** pada gawai Android siswa.
2. Buka berkas unduhan tersebut.
3. Jika muncul notifikasi keamanan browser, pilih **"Izinkan Penginstalan dari Sumber Ini"** (*Allow from this source*).
4. Tekan tombol **Instal** dan tunggu proses selesai.
5. Buka aplikasi **WinCBT Universal**, izinkan akses kamera untuk pemindai QR Code, dan ikuti instruksi Pengawas / Proktor Ujian.

---

&copy; Tim Pengembang WinCBT Universal.
