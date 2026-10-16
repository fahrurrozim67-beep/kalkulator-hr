# Kalkulator HR

Kumpulan tools hitung HR gratis untuk HR, admin, payroll, dan karyawan Indonesia. Semua perhitungan berjalan di browser tanpa server.

## Tools

| Tool | Folder | Status |
|---|---|---|
| Kalkulator Lembur (PP 35/2021) | [`kalkulator-lembur/`](kalkulator-lembur/) | ✅ Live |
| Kalkulator BPJS | – | Segera |
| Kalkulator PPh 21 | – | Segera |
| Masa Kerja & Pesangon | – | Segera |
| Penggabung File Excel | – | Segera |
| Penghapus Data Duplikat | – | Segera |

## Struktur

```
/
├── index.html                  # Beranda, daftar semua tools
└── kalkulator-lembur/
    └── index.html              # Kalkulator lembur
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
