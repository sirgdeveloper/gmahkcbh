# Website GMAHK Batu Hijau

Website gereja GMAHK Batu Hijau (Gereja Masehi Advent Hari Ketujuh, Maluk, Sumbawa Barat, Nusa Tenggara Barat).

Pendeta Jemaat: Pdtm. Grifin Sakul

## Isi ZIP ini

- `index.html` — seluruh website dalam satu file. Logo, foto pendeta, dan gambar sudah disisipkan di dalam file ini, jadi cukup file ini saja yang dibutuhkan untuk tampil.
- `README.md` — panduan ini.

## Cara publish lewat GitHub Pages

1. Buka github.com dan buat repository baru, misalnya `gmahk-batu-hijau`.
   - Pilih Public.
   - Centang "Add a README file" boleh dikosongkan, karena file di ZIP ini sudah ada README-nya.
2. Di halaman repository, klik **Add file > Upload files**.
3. Seret `index.html` dan `README.md` dari ZIP ini ke halaman upload, lalu klik **Commit changes**.
4. Masuk ke **Settings > Pages**.
5. Di bagian **Build and deployment**, pilih:
   - Source: **Deploy from a branch**
   - Branch: **main** (atau master), folder: **/(root)**
   - Klik **Save**.
6. Tunggu 1-2 menit, lalu buka alamat yang muncul di bagian atas halaman Pages, bentuknya:
   `https://<nama-pengguna-github>.github.io/gmahk-batu-hijau/`

Setiap kali ada perubahan, upload ulang `index.html` yang baru dan commit lagi.

## Catatan penting

- "Kelola Website" dan "Edit Langsung di Halaman" terkunci password. Aksesnya hanya berupa tautan kecil di footnote, di samping tulisan copyright. Klik tautan itu, masukkan password pembuat website, dan panel kelola baru terbuka. Password aslinya tidak ditampilkan di halaman atau kode website; yang tersimpan hanya hash SHA-256-nya. Status terbuka hanya berlaku selama sesi browser itu, dan bisa dikunci ulang dengan tombol Kunci / Keluar.
- Panel Kelola Website sudah lengkap untuk semua komponen, termasuk Misi dan Visi, Bidang Pelayanan, Berita, Khotbah, Wawasan, Jadwal Ibadah, dan Kesaksian, plus bagian Teks Lainnya.
- Media Sosial — Tautan Langsung: kolom link Facebook, Instagram, YouTube, TikTok, Saluran WhatsApp, dan Spotify di Kelola Website; tombolnya tampil di Kontak dan footer dan membuka akun resmi di tab baru.
- Materi via Tautan Langsung: pengelola menempelkan link file di lokasi aslinya (Google Drive, YouTube, OneDrive, dll) dengan judul, jenis, dan keterangan; pengunjung diarahkan langsung ke link tersebut.
- Dokumentasi Kegiatan: setiap item (Pelayanan, Berita, Khotbah, Wawasan, Jadwal, Kesaksian, Materi) bisa dilengkapi foto atau video dokumentasi, lewat unggahan (sekitar 2 MB per file, tersimpan di perangkat pengelola) atau tautan langsung Google Drive/YouTube; dokumentasi tampil di kartu itemnya dan terkumpul di galeri Dokumentasi Kegiatan. Foto yang diunggah pengelola otomatis dikompres ke WebP di browser supaya file tetap ringan.
- Semua gambar website sudah dikompres (gambar latar ayat harian, foto pendeta, logo, dan foto kegiatan), sehingga `index.html` sekitar 7 MB dan ZIP ini sekitar 5 MB, jauh di bawah batas 25 MB.
- Tampilan pembuka adalah Ayat Hari Ini: 14 ayat Alkitab yang berganti otomatis setiap hari berdasarkan tanggal WITA, masing-masing dengan gambar latar yang sesuai.
- Donasi: Bank Mandiri a/n GMAHK Batu Hijau, No. Rek. 1610004484742. Nomor ini sudah tercantum di seksi Donasi di website.
- Formulir doa: tombol Kirim via Email hanya tampil bila pengelola sudah mengisi alamat email resmi di Kelola Website. Bila kolom email masih kosong, tombol itu disembunyikan dan pengunjung diarahkan memakai WhatsApp.
- Lokasi di footer hanya "Maluk, Kabupaten Sumbawa Barat, Nusa Tenggara Barat", tanpa alamat jalan, nomor telepon, atau email palsu. Isi nomor WhatsApp dan alamat email resmi melalui Kelola Website bila sudah ada.
- Fitur "Kelola Website" dan upload foto/PDF/PPT di website ini menyimpan perubahan di browser perangkat yang mengedit (localStorage). Artinya:
  - Perubahan yang dibuat lewat "Kelola Website" di satu HP/laptop tidak otomatis terlihat oleh pengunjung lain.
  - Versi yang dilihat semua orang di GitHub Pages adalah versi `index.html` yang diupload.
  - Kalau One mengubah data lewat "Kelola Website" dan ingin perubahan itu terlihat semua orang, ekspor ulang website dari Muse dan upload ulang `index.html` ke GitHub.
