# 📹 LIVE CCTV Yogyakarta

Platform sederhana untuk memantau kamera CCTV publik di seluruh wilayah **Daerah Istimewa Yogyakarta** secara real-time.

🌐 **Live site:** [xxgbrl.github.io/cctv-yogyakarta](https://xxgbrl.github.io/cctv-yogyakarta)

---

## Wilayah yang Tersedia

| Wilayah | Server 1 | Server 2 |
|---|---|---|
| Kota Yogyakarta | ✅ cctv.jogjakota.go.id | ✅ cctv.jogjaprov.go.id |
| Kabupaten Bantul | ✅ bantulkab.go.id | ✅ cctv.jogjaprov.go.id |
| Kabupaten Sleman | ✅ 24jam.slemankab.go.id | ✅ cctv.jogjaprov.go.id |
| Kabupaten Kulon Progo | ❌ Belum tersedia | ✅ cctv.jogjaprov.go.id |
| Kabupaten Gunungkidul | ✅ app-smartcity.gunungkidulkab.go.id | ✅ cctv.jogjaprov.go.id |

---

## Struktur Folder

```
cctv-yogyakarta/
├── index.html              # Halaman utama (pemilihan wilayah)
├── jogjakota/              # CCTV Kota Yogyakarta - Server 1
├── jogjakota2/             # CCTV Kota Yogyakarta - Server 2
├── bantul/                 # CCTV Kabupaten Bantul - Server 1
├── bantul2/                # CCTV Kabupaten Bantul - Server 2
├── sleman/                 # CCTV Kabupaten Sleman - Server 1
├── sleman2/                # CCTV Kabupaten Sleman - Server 2
├── kulonprogo2/            # CCTV Kabupaten Kulon Progo - Server 2
├── gunungkidul/            # CCTV Kabupaten Gunungkidul - Server 1
├── gunungkidul2/           # CCTV Kabupaten Gunungkidul - Server 2
├── about.html
├── contact.html
├── privacy-policy.html
├── terms-of-service.html
├── robots.txt
└── sitemap.xml
```

---

## Fitur

- 🎥 Streaming CCTV publik real-time via HLS (m3u8)
- 🔍 Pencarian kamera per wilayah
- 📱 Responsif — mobile & desktop friendly
- ⚡ Ringan, tanpa framework, pure HTML/CSS/JS
- 🌙 Dark mode by default

---

## Sumber Data

Seluruh stream CCTV berasal dari sumber **publik resmi**:

- [cctv.jogjakota.go.id](https://cctv.jogjakota.go.id)
- [cctv.jogjaprov.go.id](https://cctv.jogjaprov.go.id)
- [bantulkab.go.id](https://bantulkab.go.id/cctv)
- [24jam.slemankab.go.id](https://24jam.slemankab.go.id)
- [app-smartcity.gunungkidulkab.go.id](https://app-smartcity.gunungkidulkab.go.id/cctv)

Website ini **tidak menyimpan, merekam, atau memodifikasi** data video apapun. Seluruh stream tetap berada di server masing-masing instansi penyedia.

---

## Lisensi

Kode sumber website ini dilisensikan di bawah [MIT License](LICENSE).

Konten video CCTV adalah milik masing-masing instansi pemerintah penyedia dan tidak termasuk dalam lisensi ini.

---

*Platform ini dibuat untuk memudahkan masyarakat dalam memantau kondisi Daerah Istimewa Yogyakarta secara real-time.*
