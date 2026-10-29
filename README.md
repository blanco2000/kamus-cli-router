# Kamus CLI Router

Library command CLI router/switch per merek dan OS (Cisco, Juniper, Huawei, MikroTik, Arista, Fortinet, Nokia, F5).

## Isi folder
| File | Fungsi |
|---|---|
| index.html | Aplikasinya |
| manifest.webmanifest | Nama app, ikon, warna (agar bisa di-install di Android) |
| sw.js | Service worker, agar app bisa dibuka offline |
| icon-*.png | Ikon app |

## Cara update command
1. Edit `index.html`, upload ulang ke repository (timpa file lama).
2. Buka `sw.js`, naikkan versi `kamus-cli-v1` menjadi `kamus-cli-v2`, upload ulang.
3. Di HP, tutup lalu buka lagi app-nya (dua kali bila perlu) agar versi baru masuk.
