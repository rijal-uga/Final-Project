# Pelacak Tindak Lanjut Arahan

Aplikasi web satu halaman (tanpa server) untuk mencatat arahan rapat, memantau yang terlambat, dan menyalin ringkasan pengingat per PIC ke WhatsApp.

- `index.html` aplikasi
- `sop.html` panduan SOP dan Instruksi Kerja (gaya pusat bantuan)
- `manifest.webmanifest`, `sw.js`, `icon.svg` agar bisa dipasang di layar HP dan tetap terbuka saat offline

Fitur: tambah dan ubah arahan, status belum/proses/selesai, penanda terlambat dan segera, cari, urungkan hapus, ringkasan WhatsApp, cadangan dan pemulihan (.json), ekspor Excel (.csv), pengingat kalender (.ics).

Data tersimpan di browser (localStorage). Jangan mengisi data rahasia.
