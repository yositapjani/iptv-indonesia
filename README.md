# IPTV Indonesia — M3U Terverifikasi

Satu file playlist TV Indonesia yang **sudah dites tayang dari Depok** — hanya channel
yang lolos tes gambar + suara yang masuk ke file ini.

## File

- **`indonesia.m3u`** — playlist utama, siap pakai.

## Pakai di Jellyfin

Jellyfin → Live TV → Tuner → M3U Tuner → tempel URL ini:

```
https://raw.githubusercontent.com/yositapjani/iptv-indonesia/main/indonesia.m3u
```

Channel yang sedang off-air saat tes (mis. channel yang memang tidak 24/7) tidak masuk
file, dan akan kembali sendiri di update berikutnya kalau sudah tayang lagi.

## Sumber

- [iptv-org](https://github.com/iptv-org/iptv) — daftar Indonesia (`countries/id.m3u`)
  dan Jawa Barat (`subdivisions/id-jb.m3u`)
- Suplemen: stream Trans TV & Trans7 (detik) dan channel RCTI+ — dipakai hanya
  kalau channel yang sama dari sumber utama gagal tes.

## Update

Diperbarui otomatis setiap hari: daftar diambil ulang, dites ulang satu per satu
di server rumah (Nemo, Depok), lalu file ini diganti dengan hasil tes terbaru.
