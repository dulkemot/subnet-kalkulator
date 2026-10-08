# 🧮 Kalkulator Subnet IPv4

Hitung network, broadcast, range host, netmask, wildcard, dan representasi biner dari IP + prefix. Mobile-first, 100% offline — untuk teknisi di lapangan.

![Status](https://img.shields.io/badge/mobile_first-blue?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)

## Fitur

- Input IP + slider prefix /1–/32, hasil instan
- Network, broadcast, netmask, wildcard, total & usable host
- Biner IP & mask (membantu belajar subnetting)
- Tombol **Salin** per baris + shortcut prefix populer (/30…/8)
- Penanganan khusus /31 & /32 (point-to-point)

## Teknologi

Astro static + vanilla JS bitwise. Satu file `src/pages/index.astro`.

## Run

```bash
npm install
npm run dev
```

Live: https://dulkemot.github.io/subnet-kalkulator/

MIT — dulkemot 2026
