# Lumbung - Dashboard Retail Management System

## Deskripsi Proyek
**Lumbung** adalah aplikasi dashboard berbasis **Django** (backend) dan **React.js** (frontend) yang dirancang untuk membantu manajemen toko retail. Aplikasi ini dirancang untuk digunakan secara lokal pada server internal, dengan fitur utama yang berfokus pada efisiensi pengelolaan penjualan, inventaris, dan laporan operasional.

---

## Fitur Utama
### 1. Manajemen Penjualan
- Melacak data penjualan harian, mingguan, dan bulanan.
- Statistik dan grafik interaktif tentang performa penjualan.
- Ekspor data penjualan ke format **PDF** dan **Excel**.

### 2. Manajemen Stok
- Pencatatan stok barang masuk dan keluar.
- Notifikasi stok rendah atau habis.
- Filter dan pencarian dinamis untuk memudahkan pencarian data barang.

### 3. Laporan & Analisis
- Ringkasan laporan penjualan dan inventaris dalam bentuk tabel dan grafik.
- Statistik performa berdasarkan kategori barang.
- Visualisasi menggunakan **Chart.js** untuk membantu pengambilan keputusan.

### 4. Pengaturan Toko
- Manajemen data toko, seperti jam operasional, kontak, dan lokasi.
- User management: Role-based access control (admin, staff, manager).
- Sistem autentikasi menggunakan **JWT** untuk keamanan.

---

## Fitur Pendukung
- **Notifikasi Dinamis**: Memberikan peringatan otomatis terkait stok habis atau perubahan status barang.
- **Responsif**: Desain dashboard optimal untuk desktop dan tablet.
- **Ekspor Data**: Mendukung ekspor laporan dalam format **PDF** dan **Excel**.
- **Sistem Modular**: Memungkinkan pengembangan fitur tambahan dengan arsitektur modular.

---

## Teknologi yang Digunakan
- **Backend**: Django, Django REST Framework
- **Frontend**: React.js, Axios
- **Database**: PostgreSQL
- **Grafik**: Chart.js atau alternatif
- **Autentikasi**: JSON Web Token (JWT)
- **CSS Framework**: TailwindCSS atau Bootstrap (dapat disesuaikan)
- **Versi Kontrol**: GitHub

---

## Keunggulan Sistem
### Pro:
1. **Performa Cepat**: Optimasi untuk penggunaan lokal dengan server internal.
2. **Desain Modern**: Antarmuka berbasis React.js yang responsif dan interaktif.
3. **Fleksibel**: Mudah diintegrasikan dan dikembangkan lebih lanjut.
4. **Modular**: Struktur aplikasi mendukung penambahan fitur baru.

### Cons:
1. **Kurva Belajar**: Memerlukan waktu untuk memahami integrasi antara Django dan React.js.
2. **Setup Awal Kompleks**: Dibutuhkan instalasi dan konfigurasi awal yang lebih teknis.
3. **Dependensi Tambahan**: Membutuhkan library eksternal seperti Axios dan JWT.

---

## Struktur Menu Dashboard
1. **Ringkasan**
   - Statistik penjualan dan stok dalam bentuk grafik.
2. **Penjualan**
   - Daftar transaksi penjualan.
   - Fitur filter, pencarian, dan ekspor.
3. **Stok**
   - Manajemen barang masuk dan keluar.
   - Notifikasi stok rendah.
4. **Laporan**
   - Grafik dan tabel analisis performa toko.
5. **Pengaturan Toko**
   - Profil toko, user management, dan pengaturan akses.

---

## Tujuan Proyek
Proyek ini bertujuan untuk memberikan solusi pengelolaan toko yang **efisien**, **modern**, dan **mudah digunakan**, khususnya untuk kebutuhan **server lokal**.

---

