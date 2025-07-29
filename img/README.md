# Struktur Folder Gambar Website Dusun Gagan

Folder ini berisi semua aset gambar yang digunakan dalam website profil Dusun Gagan. Struktur folder diorganisir berdasarkan kategori untuk memudahkan manajemen dan pencarian file.

## Struktur Folder

```
img/
├── README.md                 # Dokumentasi ini
├── hero/                     # Gambar untuk hero section
│   ├── hero-bg.jpg          # Background hero utama
│   ├── hero-bg-profil.jpg   # Background hero halaman profil
│   └── hero-bg-overlay.png  # Overlay pattern untuk hero
├── profil/                   # Gambar untuk halaman profil
│   ├── sejarah-dusun.jpg    # Foto sejarah dusun
│   ├── peta-dusun.png       # Peta lokasi dusun
│   └── geografis/           # Sub-folder untuk data geografis
│       ├── koordinat.jpg
│       └── batas-wilayah.png
├── perangkat/               # Foto perangkat dusun
│   ├── kepala-dusun.jpg     # Foto kepala dusun
│   ├── sekretaris.jpg       # Foto sekretaris
│   ├── ketua-rt1.jpg        # Foto ketua RT 01
│   └── ketua-rt2.jpg        # Foto ketua RT 02
├── fasilitas/               # Gambar fasilitas umum
│   ├── balai-dusun.jpg      # Foto balai dusun
│   ├── masjid.jpg           # Foto masjid
│   ├── sekolah/             # Sub-folder untuk fasilitas pendidikan
│   │   ├── paud.jpg
│   │   └── sd.jpg
│   └── kesehatan/           # Sub-folder untuk fasilitas kesehatan
│       └── posyandu.jpg
├── potensi/                 # Gambar potensi dusun
│   ├── pertanian/           # Sub-folder untuk potensi pertanian
│   │   ├── sawah.jpg
│   │   ├── panen-padi.jpg
│   │   └── irigasi.jpg
│   ├── peternakan/          # Sub-folder untuk potensi peternakan
│   │   ├── kandang-sapi.jpg
│   │   └── peternakan-ayam.jpg
│   └── umkm/                # Sub-folder untuk UMKM
│       ├── kerajinan.jpg
│       └── makanan-lokal.jpg
├── kegiatan/                # Gambar kegiatan masyarakat
│   ├── gotong-royong/       # Sub-folder untuk kegiatan gotong royong
│   │   ├── kerja-bakti.jpg
│   │   └── bersih-desa.jpg
│   ├── keagamaan/           # Sub-folder untuk kegiatan keagamaan
│   │   ├── pengajian.jpg
│   │   └── syawalan.jpg
│   └── sosial/              # Sub-folder untuk kegiatan sosial
│       ├── pkk.jpg
│       └── karang-taruna.jpg
├── news/                    # Gambar untuk berita/artikel
│   ├── gotong-royong.jpg    # Berita gotong royong
│   ├── pengajian.jpg        # Berita pengajian
│   ├── panen.jpg            # Berita musim panen
│   └── pembangunan.jpg      # Berita pembangunan
├── galeri/                  # Koleksi foto untuk halaman galeri
│   ├── lingkungan/          # Sub-folder untuk foto lingkungan
│   │   ├── pemandangan-1.jpg
│   │   ├── jalan-desa.jpg
│   │   └── sunset.jpg
│   ├── budaya/              # Sub-folder untuk foto budaya
│   │   ├── tradisi-1.jpg
│   │   └── upacara-adat.jpg
│   └── pembangunan/         # Sub-folder untuk dokumentasi pembangunan
│       ├── jalan-baru.jpg
│       └── jembatan.jpg
├── icons/                   # Icon dan logo
│   ├── logo-dusun.png       # Logo resmi dusun
│   ├── favicon.ico          # Favicon website
│   └── social-media/        # Icon media sosial
│       ├── facebook.png
│       ├── instagram.png
│       └── youtube.png
└── placeholders/            # Gambar placeholder sementara
    ├── placeholder-person.jpg    # Placeholder foto orang
    ├── placeholder-landscape.jpg # Placeholder foto pemandangan
    └── placeholder-news.jpg      # Placeholder foto berita
```

## Konvensi Penamaan File

### Format Penamaan
- Gunakan huruf kecil semua
- Pisahkan kata dengan tanda hubung (-)
- Gunakan format: `kategori-deskripsi-nomor.ekstensi`
- Contoh: `sawah-padi-01.jpg`, `kepala-dusun-sutrisno.jpg`

### Ukuran Gambar yang Direkomendasikan
- **Hero Background**: 1920x1080px (landscape)
- **Foto Perangkat**: 400x400px (square)
- **Foto Berita**: 800x600px (4:3 ratio)
- **Foto Galeri**: 1200x800px (3:2 ratio)
- **Icon**: 64x64px atau 128x128px (square)

### Format File
- **Foto**: JPG/JPEG (untuk foto dengan banyak warna)
- **Grafik/Logo**: PNG (untuk gambar dengan transparansi)
- **Icon**: SVG (untuk scalability) atau PNG

## Optimisasi Gambar

### Ukuran File
- **Hero images**: maksimal 500KB
- **Foto content**: maksimal 200KB
- **Thumbnail**: maksimal 50KB

### Tools yang Direkomendasikan
- [TinyPNG](https://tinypng.com/) - untuk kompresi
- [Squoosh](https://squoosh.app/) - untuk optimisasi
- [GIMP](https://www.gimp.org/) - untuk editing

## Cara Penggunaan

1. **Upload foto ke folder yang sesuai**
2. **Gunakan nama file yang deskriptif**
3. **Optimalkan ukuran file sebelum upload**
4. **Update file HTML jika mengganti path gambar**

## Contoh Penggunaan dalam HTML

```html
<!-- Hero background -->
<section style="background-image: url('img/hero/hero-bg.jpg')">

<!-- Foto perangkat -->
<img src="img/perangkat/kepala-dusun.jpg" alt="Kepala Dusun">

<!-- Foto berita -->
<img src="img/news/gotong-royong.jpg" alt="Kegiatan Gotong Royong">

<!-- Foto galeri -->
<img src="img/galeri/lingkungan/pemandangan-1.jpg" alt="Pemandangan Dusun">
```

## Maintenance

- Review dan bersihkan file yang tidak terpakai setiap bulan
- Backup folder img/ secara berkala
- Update dokumentasi ini jika ada perubahan struktur

---

**Catatan**: Pastikan semua gambar memiliki hak cipta yang sesuai dan izin untuk digunakan dalam website ini.
