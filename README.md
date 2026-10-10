# Morfologi Bahasa Jawa — Aksara Jawa Converter

> Pembentukan kata turunan (berimbuhan) dengan Ater-ater dan Panambang. Konversi otomatis Latin ke Aksara Jawa dengan perbandingan dua paugeran: **KBJ (Kongres Bahasa Jawa)** dan **Sriwedari**.

![Aksara Jawa](https://img.shields.io/badge/Aksara-Jawa-brown?style=for-the-badge)
[Paugeran](https://img.shields.io/badge/Paugeran-KBJ%20%7C%20Sriwedari-green?style=flat-square)
[GitHub Pages](https://img.shields.io/badge/Deployed-GitHub%20Pages-blue?style=flat-square)
[License](https://img.shields.io/badge/License-MIT-lightgrey)

### Dari KANDANGJAGO untuk Nusantara

---

## ✨ Fitur Utama

**1. Morfologi Lengkap Bahasa Jawa**
- **Ater-ater (Awalan):** Mendukung 3 kelompok:
  - Anuswara (Sengau): `N- (Otomatis Sengau)`, `m-`, `n-`, `ny-`, `ng-`
  - Tripurusa & Tanggap: `dak-`, `tak-`, `kok-`, `ko-`, `di-`, `ka-`, `ke-`, `in- (seselan)`
  - Bawa & Sifat: `ma-`, `pa-`, `pi-`, `pra-`, `sa-`, `tar-`, `kami-`, `kapi-`, `kuma-`, `pating / paN-`
- **Kata Dasar:** Input bebas untuk kata dasar Jawa
- **Panambang (Akhiran):** `-a`, `-i`, `-é`, `-an`, `-an + é`, `-na`, `-ana`, `-en`, `-aké`, `-aken`, `-ipun`

**2. Dual Paugeran — Perbandingan Langsung**
- **Box Merah (KBJ):** `Paugeran KBJ` 
- **Box Hijau (Sriwedari):** `Paugeran Sriwedari`
- Penanganan khusus: untuk Sriwedari, `tak-` otomatis menjadi `dak-` dan `kok-` menjadi `ko-` (sesuai standar)

**3. Custom Aksara**
- Font `Ngayogyan` untuk rendering Aksara Jawa otentik
- Slider kontrol: Ukuran Font Aksara (1.5 - 4 rem) & Spasi Antar Baris (1 - 2.5)
- Tombol **Salin** untuk copy hasil Aksara Jawa
- Responsive 100% — optimal di desktop & mobile

## 📖 Panduan Penulisan Latin

Aturan penting yang diimplementasikan di aplikasi:

| Aturan | Cara Penulisan |
| :--- | :--- |
| **e pepet & e taling** | Gunakan `e` atau `ê` untuk e pepet (segar). Gunakan `é` atau `è` untuk e taling (bèbèk, saté) |
| **Aksara Swara** | Gunakan huruf kapital `A, I, U, E, O` |
| **Aksara Murda** | Ketik konsonan Kapital `N, K, T, S, P, G, B, J, NY` |
| **Aksara Rekan** | Gunakan huruf `f, v, z, kh, dz, gh` untuk kata serapan Arab/Belanda |

## 🚀 Cara Penggunaan

1. Pilih **Ater-ater** (awalan) dari dropdown — bisa dikosongkan
2. Ketik **Kata Dasar** di kolom tengah (contoh: `tulis`, `pangan`, `gawe`)
3. Pilih **Panambang** (akhiran) dari dropdown — bisa dikosongkan
4. Hasil Aksara Jawa otomatis muncul di dua box KBJ & Sriwedari
5. Atur ukuran font & spasi jika perlu, lalu klik **Salin**

Contoh:
- `N-` + `tulis` + `-an` → ꦤꦸꦭꦶꦱꦤ꧀ (tulisan)
- `di-` + `pangan` → ꦢꦶꦥꦔꦤ꧀
- `ka-` + `gawe` + `-an` → ꦏꦒꦮꦺꦪꦤ꧀

## 🔮 Roadmap

- [ ] Tambah mode transliterasi Aksara → Latin
- [ ] Export hasil sebagai PNG/SVG
- [ ] Kamus kata dasar Jawa built-in dengan autocomplete
- [ ] PWA support agar bisa offline
- [ ] Dark mode

## 🙏 Kredit & Lisensi

Dibuat oleh **KANDANGJAGO** untuk pelestarian Aksara Jawa.

Lisensi: **MIT** — bebas digunakan, dimodifikasi, dan disebarkan untuk pendidikan dan pelestarian budaya.
