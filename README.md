# 💄 Beauty Studio Website

## 👩‍💻 Kelompok / Developer
- **Cindy Artika** (241402012) – Frontend
- **Salwa Halila** (241402027) – Frontend
- **Rohaya Hasibuan** (241402030) – Backend 
- **Enjely Margaret Sianturi** (241402046) – Backend    
- **Willy Armando Sianipar** (241402135) – Backend & Frontend Developer


---

## 📝 Description
Beauty Studio merupakan usaha di bidang kecantikan yang berfokus pada layanan perawatan rambut, wajah, dan tubuh. Selama ini, kegiatan administrasi di salon masih dilakukan secara konvensional, seperti mencatat data pelanggan, jadwal layanan, stok produk, serta transaksi keuangan secara manual di buku catatan atau nota kertas. Seiring bertambahnya pelanggan dan variasi layanan yang ditawarkan, cara kerja ini menjadi kurang efisien dan rawan terjadi kesalahan, seperti pencatatan ganda, data hilang, maupun keterlambatan dalam proses pembuatan laporan.

Website Beauty Studio dikembangkan untuk menjawab kendala tersebut dengan menghadirkan sistem informasi berbasis web yang terintegrasi dan mudah digunakan. Platform ini dirancang agar dapat diakses oleh pelanggan, pegawai, maupun pemilik salon, sehingga proses operasional menjadi lebih teratur dan transparan.

**Fitur Pelanggan**

Reservasi Online: Pelanggan dapat memesan layanan seperti potong rambut, creambath, facial, atau perawatan kuku secara daring dengan memilih tanggal dan waktu yang diinginkan.

Pelacakan Status Reservasi: Melalui kode booking, pelanggan bisa melihat status reservasi mereka secara real-time.

Riwayat Layanan: Sistem menampilkan catatan layanan dan transaksi sebelumnya untuk memudahkan pelanggan memilih layanan pada kunjungan berikutnya.

**Fitur Pegawai**

Penjadwalan Kerja: Pegawai dapat mengakses jadwal kerja dan daftar pelanggan yang sudah melakukan reservasi sesuai dengan shift atau waktu yang telah ditentukan.

Pembaruan Status Layanan: Setiap pegawai bisa memperbarui status layanan menjadi sedang dikerjakan atau selesai langsung melalui sistem.

Laporan Harian: Sistem secara otomatis membuat laporan aktivitas harian pegawai untuk membantu proses evaluasi kinerja dan perhitungan gaji.

**Fitur Pemilik Salon**

Manajemen Data Terpadu: Pemilik dapat mengelola data pelanggan, layanan, produk, pegawai, serta transaksi keuangan dari satu sistem terpusat.

Pemantauan Aktivitas Pegawai: Melalui dashboard, pemilik bisa memonitor aktivitas pegawai dan progres layanan secara langsung.

Laporan Keuangan Otomatis: Sistem menghasilkan laporan pendapatan dan pengeluaran harian, mingguan, hingga bulanan secara otomatis tanpa perlu pencatatan manual.

Cetak Invoice dan Laporan: Pemilik dapat mencetak invoice transaksi serta laporan keuangan langsung dari website dengan format yang rapi dan profesional.

Dengan penerapan website ini, seluruh kegiatan operasional di Beauty Studio menjadi lebih terorganisir, cepat, dan akurat. Data pelanggan, layanan, dan transaksi tersimpan dengan aman dalam sistem digital, sementara pelanggan mendapatkan kemudahan dalam melakukan reservasi dan memperoleh pelayanan yang lebih modern. Selain itu, pemilik salon juga dapat mengambil keputusan bisnis dengan lebih tepat berdasarkan data yang disajikan secara real-time dan terstruktur.


---

## ⚙ Tech Stack
- *PHP v8.x* → Bahasa pemrograman utama  
- *Laravel v12* → Framework PHP modern  
- *MySQL* → Database manajemen data  
- *Composer v2.8.6* → Dependency Manager untuk PHP  
- *XAMPP / Laragon* → Web server lokal  
- *HTML, CSS, JavaScript* → Untuk tampilan frontend interaktif  

---

## 🚀 Langkah Setup dan Run

Ikuti langkah-langkah berikut untuk menjalankan proyek di komputer lokal:

### 1️⃣ Clone Repository
```bash
git clone https://github.com/Enjely-Sianturi03/Beauty_Studio.git
```
### 2️⃣ Masuk ke Folder Proyek
```bash
cd BeautyStudio
```
### 3️⃣ Install Dependency Composer
Pastikan Composer sudah terinstal.
```bash
composer install
```
4️⃣ Salin File .env dari Contoh
```bash
cp .env.example .env
```
5️⃣ Generate App Key
```bash
php artisan key:generate
```
6️⃣ Atur Konfigurasi Database di .env
Contoh pengaturan:
```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=beauty_studio
DB_USERNAME=root
DB_PASSWORD=
```
7️⃣ Jalankan Migrasi Database
```bash
php artisan migrate
```
8️⃣ Jalankan Seeder
```bash
php artisan db:seed
```
9️⃣ Jalankan Server Laravel
```bash
php artisan serve
```