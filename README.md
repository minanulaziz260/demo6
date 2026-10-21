# Source Code - Undangan Digital "Majestic Citadel"
**URL Asli:** https://our-wedding.link/preset&design?preset_id=65ce2fa24ca4c2d6fbb6fbec  
**Diambil pada:** 2026-10-21  
**Preset ID:** `65ce2fa24ca4c2d6fbb6fbec`  
**Nama Design:** Majestic Citadel  
**Platform:** Our Wedding Link (Nuxt.js 2 SSR)

---

## Struktur Direktori

```
wedding_src/
├── index.html                        # Halaman utama (SSR HTML lengkap)
├── _nuxt/
│   ├── *.js                          # Bundle JavaScript Nuxt (11 file)
│   ├── manifest.2360f4b3.json        # PWA manifest
│   └── icons/                        # Icon PWA berbagai ukuran (64–512px)
├── ikon/
│   ├── favicon-32.png
│   └── favicon-192.png
├── css/
│   └── css-tema_custom-XTtS6qTDDCsdW4IX5BqL   # Custom theme CSS dari server
├── cdn-uploads/
│   ├── css/
│   │   ├── XTtS6qTDDCsdW4IX5BqL.css            # CSS tema utama
│   │   └── custom-XTtS6qTDDCsdW4IX5BqL.css     # CSS tema custom
│   ├── preset-images/                            # Gambar preset Majestic Citadel
│   │   ├── majestic-citadel-sampul.webp
│   │   ├── majestic-citadel-pembuka.webp
│   │   ├── majestic-citadel-pria.webp
│   │   ├── majestic-citadel-wanita.webp
│   │   └── majestic-citadel-galeri-[1-4].webp
│   ├── 45cf4150-d96c-11ee-87b2-dd402f354725.png  # OG image / preview
│   └── 8cde97a0-cc1d-11ee-8a12-1d71291003ab.jpg  # Gambar pendukung
└── cdn-external/
    ├── animate.min.css                # Animate.css 4.1.1
    ├── owl.carousel.min.css           # OwlCarousel2 2.3.4
    ├── owl.theme.default.min.css      # OwlCarousel2 theme
    └── fancybox.css                   # FancyApps UI 4.0
```

---

## Tech Stack

| Komponen | Teknologi |
|----------|-----------|
| Framework | **Nuxt.js 2** (Vue.js SSR) |
| Bahasa | JavaScript (bundle minified) |
| CSS | Custom theme + Animate.css + OwlCarousel2 + FancyBox |
| CDN | cdn-uploads.owlink.id |
| Hosting | Cloudflare (Rocket Loader) |
| Font | Google Fonts: Space Grotesk, Space Mono |
| PWA | Ya (manifest + icons) |

---

## Catatan Penting

> **⚠️ Ini adalah client-side bundle (compiled/minified).**  
> Source code asli (Vue SFC `.vue`, halaman Nuxt, store Vuex) **tidak tersedia publik** karena merupakan milik Our Wedding Link.

### Yang tersedia:
- ✅ HTML hasil SSR (lengkap dengan data preset)
- ✅ JavaScript bundle tercompile (minified, obfuscated)
- ✅ CSS tema custom (bisa dibaca langsung)
- ✅ Semua gambar preset Majestic Citadel
- ✅ PWA manifest & icons

### Yang tidak tersedia:
- ❌ Source `.vue` components (server-side, proprietary)
- ❌ Nuxt config, server API, database
- ❌ Font files (Google Fonts CDN)
- ❌ Beberapa asset internal yang butuh autentikasi

---

## Cara Membuka Lokal

Buka `index.html` di browser. Beberapa fitur interaktif memerlukan server karena menggunakan API calls ke `our-wedding.link`.

Untuk JS bundle berfungsi penuh, perlu Nuxt dev server asli.

---

## JS Bundle Files

| File | Ukuran | Keterangan |
|------|--------|-----------|
| `5b1af1d.js` | ~1.3 MB | Bundle utama (vendor + framework) |
| `e99f1fa.js` | ~496 KB | Komponen & halaman |
| `a581122.js` | ~367 KB | Library tambahan |
| `4c1c9a9.js` | ~284 KB | Komponen lainnya |
| `3e1932b.js` | ~87 KB  | Komponen halaman |
| `6877ee7.js` | ~47 KB  | Utilities |
| `6f9e794.js` | ~25 KB  | Router/store |
| `c63b0ed.js` | ~22 KB  | Helpers |
| `aa8f11c.js` | ~14 KB  | Misc |
| `3716d60.js` | ~12 KB  | Config |
| `e85fdd7.js` | ~8.7 KB | Entry point |
