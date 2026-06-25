<p align="center">
  <img src="assets/images/logo.png" alt="DompetGweh Logo" width="150" />
</p>

<h1 align="center">DompetGweh</h1>

<p align="center">
  <i>"Catat masuknya dikit, keluarnya banyak."</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/versi-1.1.0-10B981?style=flat-square" alt="Versi 1.1.0" />
  <img src="https://img.shields.io/badge/platform-Android-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Android" />
  <img src="https://img.shields.io/badge/Flutter-3.19-54C5F8?style=flat-square&logo=flutter&logoColor=white" alt="Flutter" />
  <img src="https://img.shields.io/badge/offline--first-✓-10B981?style=flat-square" alt="Offline First" />
</p>

**DompetGweh** adalah aplikasi pencatatan keuangan pribadi modern berbasis **Flutter** yang didesain khusus untuk pengguna **Android** dan **iOS**, dengan dukungan platform **Web** & **Windows** untuk pengujian dan pengembangan secara lokal.

DompetGweh membantu Anda melacak keuangan harian secara mandiri, aman (offline-first), dan dengan antarmuka yang sangat nyaman di mata.

---

## ✨ Fitur Unggulan

* **💰 Set Saldo Awal Sesuka Anda**
  Mulailah pencatatan dari nol (`Rp 0`) atau sesuaikan saldo awal Anda kapan saja langsung dari dashboard utama sesuai dengan kondisi riil dompet Anda.

* **👁️ Mode Samaran (Hide/Show Nominal)**
  Privasi Anda terjaga sepenuhnya. Sembunyikan nominal Saldo Utama, Pemasukan, Pengeluaran, dan Anggaran Anda menjadi `Rp ••••••` hanya dengan satu ketukan ikon mata toggle.

* **🎯 Anggaran Global & Per Kategori**
  Tetapkan anggaran bulanan secara global maupun per kategori pengeluaran. Sinyal warna visual (**Hijau / Jingga / Merah**) membantu Anda tetap terkontrol dan terhindar dari kebobolan.

* **📊 Visualisasi Keuangan Interaktif**
  Dapatkan insight keuangan instan melalui diagram donat distribusi kategori pengeluaran dan grafik tren bulanan yang premium.

* **🖨️ Cetak & Bagikan Riwayat Instan**
  Cetak laporan PDF langsung dari perangkat mobile atau salin ringkasan rapi ke clipboard dalam satu ketukan.

* **🎨 Tampilan Warm Mint Light**
  Nikmati kenyamanan visual dengan latar belakang putih-lembut (`#F5F8F6`) dipadukan aksen warna mint yang segar, tanpa membuat mata lelah.

* **ℹ️ Halaman Tentang Aplikasi**
  Informasi versi, pembuat, sekilas aplikasi, dan panduan penggunaan tersedia langsung di dalam aplikasi.

---

## 🚀 Panduan Instalasi & Pengujian

### 📥 Unduh Langsung (Android)

Bagi Anda yang ingin langsung mencoba aplikasi di HP Android tanpa perlu melakukan build manual:

* **Link Download**: **[Unduh DompetGweh v1.1.0 APK (via Diawi)](https://i.diawi.com/r9D7iv)**
* *Buka tautan di atas melalui browser HP Anda atau pindai (scan) QR Code yang tersedia di halaman tersebut untuk menginstal aplikasi secara instan.*

---

### 📱 Build Mandiri (Android & iOS)

* **Android (Build APK)**:
  ```bash
  flutter build apk --release
  ```
  File instalasi tersedia di:
  `build/app/outputs/flutter-apk/app-release.apk`

* **iOS**:
  ```bash
  flutter build ipa
  ```

---

### 💻 Pengujian & Pengembangan Lokal (Web & Windows)

Untuk menjalankan dan mengedit aplikasi di laptop:

* **Web (Chrome)**:
  ```bash
  flutter run -d chrome
  ```

* **Windows Desktop**:
  ```bash
  flutter run -d windows
  ```

---

## 📋 Changelog

### v1.1.0 (2026-06-25)
- ✨ Fitur anggaran per kategori (category budget)
- ✨ Halaman Tentang Aplikasi (versi, pembuat, tutorial)
- ✨ Konfirmasi kembali saat formulir ada data yang belum disimpan
- ✨ Pemisah ribuan otomatis di dialog edit transaksi
- 🐛 Fix overflow di halaman Riwayat (bottom & right)
- 🐛 Fix warna teks deprecated (onBackground → onSurface)
- 🐛 Fix PDF font fallback untuk kondisi offline

### v1.0.0 (2026-06-24)
- 🎉 Rilis pertama
