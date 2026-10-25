TradeLog PWA — paket awal

Isi:
- index.html: aplikasi TradeLog dari file asli, dengan metadata PWA dan registrasi service worker
- manifest.webmanifest: nama, ikon, dan pengaturan instalasi
- sw.js: cache dasar untuk penggunaan offline
- icon.svg: ikon aplikasi

Agar bisa diinstal lewat Chrome Android, unggah seluruh isi folder ini ke hosting HTTPS (misalnya GitHub Pages). Membuka index.html langsung dari Download tidak cukup untuk mengaktifkan instalasi PWA.

PENTING:
1. Data lama di browser lokal tidak otomatis pindah ke alamat hosting baru karena penyimpanan browser terpisah per alamat/origin.
2. Di situs yang sudah online, buka TradeLog lalu tekan Restore dan pilih file tradelog-backup-YYYY-MM-DD.json.
3. Pastikan data sudah kembali sebelum mengandalkan versi online. Simpan file backup JSON sebagai cadangan.
