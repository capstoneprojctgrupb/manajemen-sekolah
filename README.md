## **README - Sistem Administrasi Sekolah Berbasis Web**  

### 📘 **Deskripsi Proyek**  
Proyek ini bertujuan untuk mengembangkan sistem administrasi berbasis web menggunakan **Laravel** guna meningkatkan efisiensi pengelolaan data siswa, mata pelajaran, dan nilai di sekolah dasar. Sistem ini mempermudah pengelolaan data secara terpusat, memungkinkan pengelolaan data siswa, pencatatan nilai, serta pembuatan Laporan Keterangan Hasil Belajar Siswa (LKAS) secara cepat, akurat, dan terstruktur.  

---

### 🎯 **Fitur Utama**  
- **Pengelolaan Data Siswa**: Tambah, edit, dan hapus data siswa.  
- **Pengelolaan Mata Pelajaran**: Tambah, edit, dan hapus data mata pelajaran.  
- **Pengelolaan Nilai Siswa**: Input dan pengelolaan nilai siswa per semester.  
- **Pencetakan Laporan**: Pembuatan dan pencetakan Laporan Keterangan Hasil Belajar Siswa (LKAS).  
- **Pengelolaan Pengguna**: Role pengguna sebagai Admin dan Guru dengan akses tertentu.  

---

### 💻 **Teknologi yang Digunakan**  
- **Framework**: Laravel  
- **Frontend**: Blade, HTML, CSS 
- **Backend**: PHP (Laravel)  
- **Database**: MySQL  

---

### 👥 **Tim Pengembang**  
- **Melin Yolantika** (043800452)  
- **Radian Yusuf Mahendra** (042676725)  
- **Muhammad Ilham Magreza** (044278335)  
- **Djohan Taruna Wibowo** (044335442)  
- **Akbar Solihin Zulkifli** (045062002)  

---

### 🎓 **Informasi Akademik**  
- **Program Studi**: Sistem Informasi  
- **Fakultas**: Sains dan Teknologi  
- **Universitas**: Universitas Terbuka  

---

### 📄 **Cara Menjalankan**  
1. **Clone Repositori**:  
   ```bash
   git clone https://github.com/username/nama-repositori.git
   cd nama-repositori
   ```

2. **Instalasi Dependensi**:  
   ```bash
   composer install
   ```

3. **Konfigurasikan File `.env`**:  
   Salin file `.env.example` menjadi `.env` dan sesuaikan pengaturan database.  
   ```bash
   cp .env.example .env
   ```

4. **Generate Key Aplikasi**:  
   ```bash
   php artisan key:generate
   ```

5. **Migrasi Database**:  
   ```bash
   php artisan migrate --seed
   ```

6. **Jalankan Server Lokal**:  
   ```bash
   php artisan serve
   ```

7. Akses aplikasi di **http://localhost:8000**.  

---
