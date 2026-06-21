# Kasir Elba Prime

Aplikasi kasir pribadi gratis berbasis HTML/CSS/JavaScript.

## Fitur

- Setup toko dan PIN
- Dashboard omzet harian
- Kasir dan keranjang
- Produk dan stok
- Pembukuan kas masuk/keluar
- Laporan transaksi
- Export CSV
- Backup dan import JSON

## Cara bikin link gratis GitHub Pages

1. Buka repository ini di GitHub.
2. Masuk ke **Settings**.
3. Cari menu **Pages**.
4. Pada **Build and deployment**, pilih:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/root**
5. Klik **Save**.
6. Tunggu sampai muncul link website.

Link biasanya menjadi:

`https://anggarjiwa-max.github.io/kasir-elba/`

## Catatan penting

Versi ini menyimpan data di browser/perangkat yang dipakai.

Artinya:

- Kalau kasir dipakai di HP toko, data tersimpan di HP toko.
- Kalau owner buka dari laptop lain, data belum otomatis ikut.
- Pakai fitur **Download Backup** dan **Import Backup** untuk pindah data.

Untuk data yang otomatis sinkron antar perangkat, perlu database online seperti Supabase, Firebase, atau Google Sheets.
