# Whimpy & Xinxin — cara memakai hasil perubahan

Data pernikahan: Minggu, 20 Desember 2026, Rumah 30, Bogor.
Pemberkatan: 15:00 WIB–selesai. Resepsi: 17:00–20:00 WIB.
Countdown mengarah ke pemberkatan pukul 15:00 WIB (08:00 UTC).
Tidak ada jam selesai pemberkatan yang diasumsikan pada kalender; keterangannya menyebut waktu akhir belum ditentukan.

## Cara memakai

1. Ekstrak ZIP ini. Folder wedding-whimpy-xinxin berisi proyek lengkap.
2. Untuk mengganti seluruh proyek lokal, salin seluruh isinya ke folder proyek Anda.
3. Untuk copy–paste manual di GitHub, buka COPY-PASTE.md. Setiap judul menunjukkan path file. Buka file tersebut di GitHub, klik Edit, ganti seluruh isinya dengan blok kode yang sesuai, lalu Commit changes.
4. Gambar PNG baru tidak bisa di-copy sebagai teks: upload ke path yang sama seperti dalam folder public/assets.
5. Jalankan npm install, lalu npm run build. Build dan pemeriksaan proyek telah lolos di lingkungan pengerjaan.

## Yang sudah diubah

Nama dan keluarga kedua mempelai, urutan pria dahulu, tanggal, lokasi, Maps, dress code, countdown, kutipan umum Indonesia–Mandarin, label utama undangan, dan profil. Bio dan tautan Instagram kosong tidak ditampilkan. Kuis beserta tombol dan titik interaksinya dihapus. Ucapan tamu fiktif dikosongkan.
Ilustrasi generik baru: jas hitam dan gaun putih berenda dengan veil. Ini ilustrasi, bukan representasi wajah asli. Karakter game dan photobooth memakai sprite baru dengan empat pose; pembaca spritesheet menyesuaikan dimensi gambar.

## Masih perlu dilengkapi

- Audio Tong Hua belum disertakan karena tidak ada pada ZIP awal. Simpan rekaman piano instrumental pilihan Anda sebagai public/assets/audio/tong-hua-piano.m4a. Jalur, kredit, dan loop setelah membuka undangan sudah disiapkan. Saat file belum ada, musik undangan tidak akan tersedia; musik game tetap bawaan. Kredit pemain piano dapat diperbarui setelah file dipilih.
- Saat deploy, isi VITE_SITE_URL dengan domain final untuk preview link. Hubungkan DATABASE_URL dan SENDER_SALT sesuai README agar RSVP/ucapan tersimpan online. Tidak ada kredensial database yang dimasukkan ke paket ini.
- Preview browser belum dapat diverifikasi di lingkungan pengerjaan; lakukan pengecekan pada iPhone/Safari dan Android/Chrome sebelum menyebarkan undangan.

## Aset baru

public/assets/couple-whimpy-xinxin.png
public/assets/photobooth/couple-whimpy-xinxin.png

Ilustrasi dibuat dengan image generator bawaan: watercolor pasangan Indonesia–Tiongkok, pria berjas hitam dan dasi kupu-kupu, wanita bergaun putih renda dan veil, ivory/sage; sprite diadaptasi dari grid 2 kolom × 4 baris dengan empat pose, tanpa penutup kepala pria atau hijab.
