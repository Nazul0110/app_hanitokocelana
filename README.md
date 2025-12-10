#  Toko Celana 👖

Aplikasi **Hani Toko Celana** adalah aplikasi e-commerce sederhana berbasis Flutter yang berfokus pada penjualan berbagai jenis celana pria seperti jeans, chino, jogger, dan cargo. Aplikasi ini dibuat sebagai latihan pengembangan mobile dengan tampilan modern, dukungan dark mode, dan navigasi yang user-friendly.

---

## 📝 Informasi Mahasiswa

- **Nama**  : Hani Nuraini 
- **NIM**   : 14022300040
- **Kelas** : 5B-INF


---

## 📱 Deskripsi Singkat Aplikasi

Hani Toko Celana menampilkan katalog celana dengan desain UI yang modern dan bersih.  
Pengguna dapat melihat daftar produk, detail produk, menambahkan ke keranjang, dan melakukan simulasi checkout.  
Aplikasi juga sudah mendukung **dark mode** dengan tombol toggle langsung di dalam aplikasi.

---

## ✨ Fitur Utama

1. **Halaman Beranda (Home)**
   - Banner promo celana dengan desain gradasi.
   - Kolom pencarian (search bar) untuk mencari celana.
   - Daftar celana populer dengan kartu produk horizontal.

2. **Daftar Produk (Produk)**
   - Grid view berisi semua produk celana.
   - Filter kategori (Jeans, Chino, Jogger, Cargo).
   - Tap produk untuk membuka halaman detail.

3. **Detail Produk**
   - Menampilkan gambar celana (asset lokal).
   - Informasi nama, kategori, rating, harga, dan deskripsi produk.
   - Pilihan ukuran celana.
   - Tombol **“Tambah ke Keranjang”** di bagian bawah.

4. **Keranjang (Cart)**
   - Menampilkan produk yang ditambahkan ke keranjang.
   - Informasi harga total dan tombol **“Checkout Sekarang”**.
   - Informasi promo gratis ongkir.

5. **Halaman Favorit**
   - Menampilkan list produk favorit (dummy dari data yang sama).
   - Bisa masuk ke detail produk dari daftar favorit.

6. **Halaman Profile / Akun**
   - Menampilkan informasi akun pengguna (dummy).
   - Menu riwayat pesanan, alamat pengiriman, dan logout (non-fungsional/demo).

7. **Halaman Checkout**
   - Simulasi proses checkout.
   - Menampilkan konfirmasi pesanan berhasil.

8. **Dark Mode dengan Toggle**
   - Mendukung light mode & dark mode.
   - Tombol toggle tema (ikon 🌙/☀️) di pojok kanan atas halaman Home.
   - Seluruh tampilan (gradasi header, card, bottom bar) ikut menyesuaikan tema.

9. **Bottom Navigation Bar Modern**
   - 5 menu: Home, Produk, Favorit, Keranjang, Akun.
   - Desain kapsul dengan gradasi dan shadow halus.
   - Ikon berubah ketika aktif/non-aktif.

---

## 🗂 Struktur Penting Proyek

- `lib/main.dart` → Seluruh logic UI utama (screen + bottom nav + theme).
- `assets/images/` → Berisi gambar celana:
  - `celana_jeans.png`
  - `celana_chino.png`
  - `celana_jogger.png`
  - `celana_cargo.png`
- `pubspec.yaml` → Konfigurasi dependencies & pendaftaran assets.

Pastikan di `pubspec.yaml` bagian `flutter` sudah seperti ini:

```yaml
flutter:
  uses-material-design: true

  assets:
    - assets/images/celana_jeans.png
    - assets/images/celana_chino.png
    - assets/images/celana_jogger.png
    - assets/images/celana_cargo.png

▶️ Cara Menjalankan Aplikasi

Clone / buka project Flutter

git clone <url-repo-kamu>
cd app_hanitokocelana


Pastikan Flutter sudah terinstall

Cek dengan:

flutter --version


Install dependencies

flutter pub get


Pastikan folder assets & gambar sudah benar

Struktur minimal:

lib/
  main.dart
assets/
  images/
    celana_jeans.png
    celana_chino.png
    celana_jogger.png
    celana_cargo.png
pubspec.yaml


Clean project (opsional tapi disarankan setelah ubah assets)

flutter clean
flutter pub get


Jalankan di emulator / device

flutter run


Coba fitur dark mode

Buka aplikasi.

Di halaman Home, tap ikon 🌙 / ☀️ di kanan atas untuk mengubah tema.

💡 Catatan

Data produk yang digunakan masih dummy (hardcoded) di file main.dart.

Aplikasi ini bisa dikembangkan lagi:

Integrasi backend / API.

Sistem login & autentikasi.

Penyimpanan keranjang dan favorit dengan database lokal (misalnya sqflite atau hive).

Terima kasih sudah melihat proyek Hani Toko Celana 👖
Silakan modifikasi dan kembangkan sesuai kebutuhan tugas atau portofolio kamu!
<img width="473" height="991" alt="Screenshot 2025-12-10 200714" src="https://github.com/user-attachments/assets/8c8407a2-4d79-4ce7-9dfa-a178018df8ca" />
<img width="475" height="1005" alt="Screenshot 2025-12-10 200725" src="https://github.com/user-attachments/assets/db3b448a-b80d-454a-a759-6c85bf546c82" />
<img width="474" height="1010" alt="Screenshot 2025-12-10 200733" src="https://github.com/user-attachments/assets/407092b0-cdfc-4cfc-9fac-2bb2878eacd2" />
<img width="475" height="998" alt="Screenshot 2025-12-10 200743" src="https://github.com/user-attachments/assets/34dd5820-3a22-4450-ab0e-c46006ad3fc3" />
<img width="478" height="1006" alt="Screenshot 2025-12-10 200753" src="https://github.com/user-attachments/assets/715a2aec-63cc-4732-9dc4-0fe2d1e1641c" />
<img width="482" height="1008" alt="Screenshot 2025-12-10 200807" src="https://github.com/user-attachments/assets/e5f9e495-ac61-42de-add9-aa4281a96781" />



