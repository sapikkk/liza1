# liza1

Landing statis SawitPRO (affiliate/KOL dan Petani Juara). Tanpa build step.

## File

| Path | Dipakai untuk |
|------|----------------|
| `index.html` | Halaman utama (program affiliate & KOL) |
| `public/affiliate-embed.html` | URL yang sama untuk embed Wix |
| `public/petani-juara-embed.html` | Halaman Petani Juara (embed) |
| `public/favicon.svg` | Ikon tab |

Gambar sudah inline (data URI). CSS ada di `<style>` masing-masing file.

## Jalankan lokal

```bash
cd /Users/mpik/liza1
python3 -m http.server 8080
```

Buka `http://localhost:8080/` untuk affiliate. Petani Juara: `http://localhost:8080/public/petani-juara-embed.html`.

## Repo

Asal: [github.com/sapikkk/liza1](https://github.com/sapikkk/liza1). Dulu React + Vite hanya membungkus iframe ke `affiliate-embed.html`; stack itu sudah dihapus.
