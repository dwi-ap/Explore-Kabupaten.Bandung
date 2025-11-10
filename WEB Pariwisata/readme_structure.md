# Landing Page Wisata Kabupaten Bandung

## 📁 Struktur Folder Project

```
landing-page-wisata/
│
├── index.html           # File HTML utama
├── style.css            # File CSS untuk styling
├── script.js            # File JavaScript untuk interaktivitas
│
└── images/              # Folder untuk menyimpan gambar
    ├── hero-bg.jpg              # Gambar background hero section
    ├── kawah-putih.jpg          # Gambar Kawah Putih
    ├── situ-patenggang.jpg      # Gambar Situ Patenggang
    ├── tangkuban-perahu.jpg     # Gambar Gunung Tangkuban Perahu
    ├── glamping-rancabali.jpg   # Gambar Glamping Lakeside
    ├── kebun-teh-rancabali.jpg  # Gambar Perkebunan Teh
    └── floating-market.jpg      # Gambar Floating Market Lembang
```

## 🖼️ Daftar Gambar yang Dibutuhkan

### 1. **hero-bg.jpg**
   - Deskripsi: Gambar pemandangan Kabupaten Bandung untuk background hero section
   - Resolusi minimal: 1920x1080px
   - Saran: Foto landscape/panorama pegunungan atau perkebunan teh

### 2. **kawah-putih.jpg**
   - Lokasi: Kawah Putih, Ciwidey
   - Resolusi minimal: 800x600px
   - Saran: Foto danau kawah dengan air putih kehijauan

### 3. **situ-patenggang.jpg**
   - Lokasi: Situ Patenggang, Ciwidey
   - Resolusi minimal: 800x600px
   - Saran: Foto danau dengan perkebunan teh di sekitarnya

### 4. **tangkuban-perahu.jpg**
   - Lokasi: Gunung Tangkuban Perahu, Lembang
   - Resolusi minimal: 800x600px
   - Saran: Foto kawah gunung berapi

### 5. **glamping-rancabali.jpg**
   - Lokasi: Rancabali
   - Resolusi minimal: 800x600px
   - Saran: Foto camping ground atau tenda dengan view danau/pegunungan

### 6. **kebun-teh-rancabali.jpg**
   - Lokasi: Perkebunan Teh Rancabali
   - Resolusi minimal: 800x600px
   - Saran: Foto hamparan kebun teh hijau

### 7. **floating-market.jpg**
   - Lokasi: Floating Market Lembang
   - Resolusi minimal: 800x600px
   - Saran: Foto pasar apung dengan perahu-perahu di danau

## 🚀 Cara Menjalankan Project

1. **Download/Clone Project**
   ```bash
   git clone [url-repository-anda]
   ```

2. **Siapkan Folder Images**
   - Buat folder bernama `images` di root project
   - Masukkan semua gambar sesuai nama di atas

3. **Buka File HTML**
   - Buka `index.html` menggunakan browser
   - Atau gunakan Live Server di VS Code

## 📝 Catatan Penting

### Format Gambar
- Format yang disarankan: **JPG** atau **PNG**
- Ukuran file: Maksimal 500KB per gambar (agar loading cepat)
- Aspect ratio untuk card destinasi: 4:3 atau 16:9

### Optimasi Gambar
Untuk performa website yang lebih baik, compress gambar menggunakan:
- [TinyPNG](https://tinypng.com/)
- [CompressJPEG](https://compressjpeg.com/)
- [Squoosh](https://squoosh.app/)

### Alternative Jika Tidak Ada Gambar
Jika belum memiliki gambar, Anda bisa:
1. Download dari situs free stock photos:
   - [Unsplash](https://unsplash.com/)
   - [Pexels](https://pexels.com/)
   - [Pixabay](https://pixabay.com/)

2. Atau gunakan placeholder sementara dengan mengganti di HTML:
   ```html
   <img src="https://via.placeholder.com/800x600?text=Kawah+Putih" alt="Kawah Putih">
   ```

## 🎨 Kustomisasi

### Mengubah Warna
Edit file `style.css` pada bagian:
```css
/* Warna utama: #2563eb (biru) */
/* Untuk mengubah, ganti semua #2563eb dengan warna pilihan Anda */
```

### Menambah Destinasi Baru
1. Copy-paste kode card di `index.html`
2. Ganti gambar, judul, lokasi, dan deskripsi
3. Tambahkan gambar baru ke folder `images/`

## 📱 Testing Responsivitas

Pastikan website terlihat baik di:
- ✅ Desktop (1920px ke atas)
- ✅ Laptop (1366px