# Panduan Lengkap Deploy SaaS Undangan Digital (GitHub + Cloudflare 100% Gratis)

## 1. Susunan File dalam Paket ZIP Ini
- `index.html` : Halaman Utama / Landing Page Penjualan & Katalog Tema.
- `portal.html` : Portal Login Terpadu untuk Pelanggan (Edit Data & Kirim WA) dan Super Admin (Buat Akun & Kelola Klien).
- `invitation.html` : Mesin Undangan Digital VIP Multi-Klien (Segel Lilin 3D, Tirai Beludru, Musik Otomatis, Efek Foto Scroll).
- `_redirects` : Konfigurasi Cloudflare Pages agar URL undangan singkat & elegan (`domain.com/raka-kinanti?to=Bapak+Budi`).

## 2. Langkah Upload ke GitHub (Gratis)
1. Buka https://github.com dan buat repository baru bernama `aurelia-royal-invite`.
2. Klik **Add file** -> **Upload files**.
3. Tarik semua file hasil ekstrak ZIP ini ke dalam halaman GitHub tersebut, lalu klik **Commit changes**.

## 3. Langkah Tayangkan Online di Cloudflare Pages (Gratis Tanpa Kartu Kredit)
1. Masuk ke https://dash.cloudflare.com -> menu **Workers & Pages** -> **Create** -> tab **Pages** -> **Connect to Git**.
2. Pilih repository `aurelia-royal-invite`.
3. Pada **Build settings**:
   - Framework preset: `None`
   - Build command: *(kosongkan)*
   - Build output directory: `/`
4. Klik **Save and Deploy**. Website Anda langsung online!

## 4. Akun Login Default (Portal)
- **Login Pelanggan:** Slug = `raka-kinanti` | PIN = `123456`
- **Login Super Admin:** Email = `admin@aurelia.id` | Password = `admin123`
