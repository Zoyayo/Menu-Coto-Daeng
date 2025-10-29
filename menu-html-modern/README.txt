Menu HTML – Modern Minimal (Tanpa Tombol WhatsApp)
==================================================

File:
- index.html   -> Menu publik (hanya gambar, harga, deskripsi, & status ketersediaan)
- menu.json    -> Data menu (sudah diisi kategori & item sesuai permintaan Anda)
- editor.html  -> Editor offline untuk tambah/ubah kategori & item, lalu Export menu.json
- qr.html      -> Buat & unduh QR ke URL situs Anda

Cara pakai:
1) Upload semua file ke hosting statis (Netlify, Vercel, GitHub Pages, atau cPanel/FTP).
2) Buka index.html (menu siap dipakai). Scan QR dari qr.html untuk memudahkan pelanggan.
3) Untuk update: buka editor.html -> Load menu.json -> edit -> Export -> ganti file menu.json di server.

Catatan:
- Jika suatu item tidak memiliki "image" (URL), di menu akan tampil placeholder minimal.
