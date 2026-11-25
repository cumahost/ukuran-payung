# Panduan Visual Ukuran Payung Promosi (`ukuran.payunghujan.com`)

Halaman edukasi dan katalog visual interaktif milik **Alat Promosi Bali** (`payunghujan.com`) untuk membantu calon pelanggan memahami perbedaan ukuran jari-jari (*rib length* dalam inci/cm) dengan bentangan diameter asli payung saat dibuka.

## Fitur Utama
- **Visualisasi Skala Proporsional:** Perbandingan ukuran payung terhadap siluet manusia dewasa (±170 cm) secara *real-time*.
- **5 Kategori Ukuran Standar:**
  1. Payung Lipat (Lipat 2 & Lipat 3 — Manual / Duomatic)
  2. Payung Standar 24 Inci (Diameter ± 105 cm)
  3. Payung 26 Inci — Ruji Single Chrome (Diameter ± 115 cm)
  4. Payung Semi Golf 28 Inci — Otomatis (Diameter ± 120–125 cm)
  5. Payung Golf 30 Inci — Custom Ruji & Handel (Diameter ± 130–135 cm)
- **Konfigurator Custom Golf 30":** Pilihan varian ruji (*Single, Double, Fiber Manual, Fiber Otomatis*) serta handel (*Kayu Standar, Kayu J, Plastik Pedal, Spon EVA*).
- **Generator Pesan Konsultasi:** Otomatis menyusun teks permintaan penawaran & mockup gratis yang siap disalin ke WhatsApp.

## Struktur File
- `index.html` — Halaman utama aplikasi statis (HTML + Tailwind CSS + Vanilla JS).
- `README.md` — Dokumentasi repositori dan panduan deployment.

## Cara Deploy ke Cloudflare Pages
1. Simpan `index.html` dan `README.md` ke dalam repositori GitHub.
2. Buka **Cloudflare Dashboard** → **Workers & Pages** → **Create** → **Pages** → **Connect to Git**.
3. Pilih repositori GitHub tersebut dengan pengaturan build berikut:
   - **Framework preset:** `None`
   - **Build command:** *(kosongkan)*
   - **Build output directory:** `/`
4. Setelah proses deploy selesai, masuk ke tab **Custom domains** pada proyek Pages tersebut.
5. Tambahkan custom domain: `ukuran.payunghujan.com` (Cloudflare akan otomatis membuatkan DNS CNAME record karena domain `payunghujan.com` sudah dikelola di Cloudflare).

---
Semua pertanyaan bisa langsung ke nomor 081337070502

© **Alat Promosi Bali** — Jl. Pulau Batanta No. 6, Denpasar, Bali.
