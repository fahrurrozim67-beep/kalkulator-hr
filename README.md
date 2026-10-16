# Kalkulator HR

Kumpulan tools hitung HR gratis untuk HR, admin, payroll, dan karyawan Indonesia. Semua perhitungan berjalan di browser tanpa server.

## Tools

| Tool | Folder | Status |
|---|---|---|
| Kalkulator Lembur (PP 35/2021) | [`kalkulator-lembur/`](kalkulator-lembur/) | ✅ Live |
| Kalkulator BPJS (tarif & batas upah 2026) | [`kalkulator-bpjs/`](kalkulator-bpjs/) | ✅ Live |
| Kalkulator PPh 21 (TER PP 58/2023) | [`kalkulator-pph21/`](kalkulator-pph21/) | ✅ Live |
| Masa Kerja & Pesangon (PP 35/2021) | [`kalkulator-pesangon/`](kalkulator-pesangon/) | ✅ Live |
| Penggabung File Excel | [`penggabung-excel/`](penggabung-excel/) | ✅ Live |
| Penghapus Data Duplikat | [`penghapus-duplikat/`](penghapus-duplikat/) | ✅ Live |

## Struktur

```
/
├── index.html                  # Beranda, daftar semua tools
├── sitemap.xml                 # Daftar halaman untuk Google
├── kalkulator-lembur/
│   └── index.html              # Kalkulator lembur
├── kalkulator-bpjs/
│   └── index.html              # Kalkulator BPJS
├── kalkulator-pph21/
│   └── index.html              # Kalkulator PPh 21
├── kalkulator-pesangon/
│   └── index.html              # Kalkulator masa kerja & pesangon
├── penggabung-excel/
│   └── index.html              # Gabung banyak file Excel/CSV
├── penghapus-duplikat/
│   └── index.html              # Hapus baris duplikat
├── assets/theme.css            # Tema bersama halaman tool (motif slip gaji)
└── assets/vendor/xlsx-js-style/
    └── xlsx.bundle.js          # Library baca/tulis Excel (Apache 2.0)
```

Setiap tool berada di foldernya sendiri dengan file `index.html`, sehingga URL-nya rapi (misalnya `/kalkulator-lembur/`).

## Yang perlu diganti sebelum online

Cari kata `GANTI` di setiap file:

1. Alamat `fahrurrozim67-beep.github.io/kalkulator-hr` (canonical, og:url, `sitemap.xml`) → domain sendiri, jika nanti pindah domain.
2. Link "traktir kopi" → link Saweria/Trakteer.
3. Slot `SLOT IKLAN` / `TEMPAT KODE GOOGLE ADSENSE` → kode AdSense setelah disetujui.

## Hosting gratis

- **Cloudflare Pages:** Workers & Pages → Create → Pages → Connect to Git → pilih repo ini. Build command dikosongkan, output directory `/`.
- **GitHub Pages:** Settings → Pages → Source: *Deploy from a branch* → `main` / `root`.

## Dasar hukum

Kalkulator lembur mengacu pada PP No. 35 Tahun 2021 Pasal 26–33. UU Pelindungan Ketenagakerjaan disahkan DPR pada 6 Oktober 2026 dengan masa transisi satu tahun. Rumus perlu ditinjau ulang jika terbit aturan pelaksana baru.
