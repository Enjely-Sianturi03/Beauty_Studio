# 💄 Beauty Studio Website

## 👩‍💻 Kelompok / Developer
- *Cindy Artika* (241402012) – Frontend
- *Salwa Halila* (241402027) – Frontend
- *Rohaya Hasibuan* (241402030) – Backend 
- *Enjely Margaret Sianturi* (241402046) – Backend    
- *Willy Armando Sianipar* (241402135) – Backend & Frontend Developer


---

## 📝 Description
*Beauty Studio* adalah website layanan salon modern yang dibuat untuk memudahkan pelanggan melakukan *reservasi online, melihat **layanan salon, dan membantu pemilik dalam **mengelola data pelanggan, layanan, serta booking* secara efisien.

Website ini dibangun menggunakan *Laravel* dan *MySQL, dengan tampilan elegan berbasis **HTML, CSS, dan JavaScript*.

### 🎯 Tujuan Website
- Memudahkan pelanggan dalam melakukan pemesanan layanan salon tanpa perlu datang langsung.  
- Membantu pemilik salon mengelola data transaksi, pelanggan, dan laporan keuangan secara digital.  
- Menyediakan dashboard admin yang menampilkan data secara *real-time* dan mudah dipantau.

---

## ⚙ Tech Stack
- *PHP v8.x* → Bahasa pemrograman utama  
- *Laravel v12* → Framework PHP modern  
- *MySQL* → Database manajemen data  
- *Composer v2.8.6* → Dependency Manager untuk PHP  
- *XAMPP / Laragon* → Web server lokal  
- *HTML, CSS, JavaScript* → Untuk tampilan frontend interaktif  

---

## 🚀 Installation Guide

Ikuti langkah-langkah berikut untuk menjalankan proyek di komputer lokal:

### 1️⃣ Clone Repository
```bash
git clone https://github.com/Enjely-Sianturi03/Beauty_Studio.git

### 2️⃣ Masuk ke Folder Proyek
```bash
cd BeautyStudio

### 3️⃣ Install Dependency Composer
Pastikan Composer sudah terinstal.
```bash
composer install

4️⃣ Salin File .env dari Contoh
```bash
cp .env.example .env

5️⃣ Generate App Key
```bash
php artisan key:generate

6️⃣ Atur Konfigurasi Database di .env
Contoh pengaturan:
```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=beauty_studio
DB_USERNAME=root
DB_PASSWORD=

7️⃣ Jalankan Migrasi Database
```bash
php artisan migrate

8️⃣ Jalankan Seeder
```bash
php artisan db:seed

9️⃣ Jalankan Server Laravel
```bash
php artisan serve
