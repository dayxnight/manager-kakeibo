# Aplikasi Manajer Keuangan Kakeibo

Aplikasi Kakeibo sederhana berbasis web untuk membantu Anda melacak pemasukan dan pengeluaran. Aplikasi ini sepenuhnya berjalan di sisi klien (browser) dan tidak memerlukan backend.

## Struktur Folder

```
├── index.html                # Halaman HTML utama aplikasi
├── css/
│   └── style.css             # Semua gaya CSS kustom
└── js/
    ├── app.js                # Logika aplikasi utama dan event listener
    ├── utils.js              # Fungsi utilitas (enkripsi, dekripsi, pesan)
    ├── ui.js              # Logika pengelolaan ui
    ├── storage.js               # Logika pengelolaan data (transaksi, saldo, localStorage)
```

## Cara Menjalankan Aplikasi

1. **Klon repositori**
   ```bash
   git clone https://github.com/dayxnight/manager-kakeibo.git
   cd manager-kakeibo
   ```

2. **Buka aplikasi**
   - Cukup buka file `index.html` di browser web pilihan Anda (Chrome, Firefox, Edge, dll).
   - atau bisa juga akses melalui github page saya di https://dayxnight.github.io/manager-kakeibo/

---
