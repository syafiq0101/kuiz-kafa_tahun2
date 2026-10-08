# kuiz-kafa_tahun2

Website kuiz KAFA untuk pembelajaran anak Tahun 2, menggunakan React dan Vite.

## Keperluan

- Node.js 18 atau lebih baharu yang serasi dengan Vite 5.
- npm dan Git.

## Install

```bash
git clone https://github.com/syafiq0101/kuiz-kafa_tahun2.git
cd kuiz-kafa_tahun2
npm install
```

## Run untuk pembangunan

```bash
npm run dev
```

Buka URL yang dipaparkan dalam terminal. Port pembangunan dikonfigurasi kepada `5173` (biasanya `http://localhost:5173`); Vite boleh menggunakan port lain jika port tersebut sedang digunakan.

## Build dan preview

```bash
npm run build
npm run preview
```

`build` menghasilkan fail dalam folder `dist/`. Selepas build berjaya, `preview` membolehkan hasilnya disemak secara tempatan melalui URL dalam terminal.

## Struktur ringkas projek

| Fail / folder | Kegunaan |
| --- | --- |
| `index.html` | Halaman HTML utama dan titik masuk aplikasi. |
| `src/main.jsx` | Memuatkan React dan gaya aplikasi. |
| `src/App.jsx` | Komponen utama aplikasi. |
| `src/index.css` | Gaya paparan aplikasi. |
| `vite.config.js` | Konfigurasi Vite dan pelayan pembangunan. |
| `package.json` | Dependencies serta skrip `dev`, `build` dan `preview`. |
| `.gitignore` | Mengabaikan dependencies, hasil build dan fail tempatan. |

## Status semasa

Setakat 8 Oktober 2026, projek masih pada peringkat rangka awal. Paparan utama mengandungi tajuk dan penerangan ringkas. Soalan kuiz, modul mengikut subjek, shuffle soalan dan pengiraan markah belum dilaksanakan dalam kod semasa.
