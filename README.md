# Dashboard Kebakaran Hutan Indonesia 2026

Dashboard interaktif untuk memantau kebakaran hutan di Indonesia dengan data historikal dari awal tahun 2026 sampai sekarang.

## Fitur

- 🗺️ Peta interaktif Indonesia dengan lokasi hotspot kebakaran
- 📊 Grafik tren kebakaran hutan (total hotspot & area terbakar)
- 📅 Slider waktu untuk melihat perubahan dari Januari 2026 - Desember 2026
- 📈 Statistik realtime: total hotspot, tingkat keyakinan, provinsi terbanyak
- 🏷️ Indikator keyakinan: High (>80), Medium (30-79), Low (<30)
- 📱 Responsif untuk desktop dan mobile

## Data Source

Data diambil dari:
- **SiPongi System** (Ministry of Environment and Forestry, Indonesia)
- **NASA MODIS & VIIRS Satellite Data**
- **Reuters Graphics** - Indonesia wildfires 2026 data
- **Databoks Katadata** - Hotspot data from November 2026

## Cara Deploy (Pilih Salah Satu)

### Option 1: GitHub Pages (Gratis & Mudah)

1. **Buat Repository Baru di GitHub**
   - Login ke https://github.com
   - Klik "New repository"
   - Repository name: `forest-fire-dashboard-indonesia`
   - Public/Private: Public
   - Klik "Create repository"

2. **Upload File**
   - Klik "uploading an existing file"
   - Drag & drop file `index.html` dari folder ini
   - Klik "Commit changes"

3. **Aktifkan GitHub Pages**
   - Pergi ke Settings > Pages
   - Source: `Deploy from a branch`
   - Branch: `main` (atau `master`)
   - Folder: `/ (root)`
   - Klik "Save"
   - Tunggu 1-2 menit

4. **Akses Dashboard**
   - URL: `https://username.github.io/forest-fire-dashboard-indonesia`

### Option 2: Netlify (Gratis & Mudah)

1. **Buka Netlify Drop**
   - https://app.netlify.com/drop

2. **Drag & Drop Folder**
   - Drag folder `forest-fire-dashboard` ke Netlify Drop
   - Tunggu deployment selesai (1-2 menit)

3. **Akses Dashboard**
   - URL akan diberikan secara otomatis (contoh: `https://random-name.netlify.app`)

### Option 3: Vercel (Gratis & Cepat)

1. **Install Vercel CLI**
   ```bash
   npm i -g vercel
   ```

2. **Deploy**
   ```bash
   cd forest-fire-dashboard
   vercel --prod
   ```

3. **Akses Dashboard**
   - URL akan diberikan oleh Vercel (contoh: `https://random-name.vercel.app`)

### Option 4: Local Server (Cara Mudah)

1. **Install Python** (jika belum ada)
   - Download dari python.org

2. **Jalankan Server**
   ```bash
   cd forest-fire-dashboard
   python -m http.server 8000
   ```

3. **Buka di Browser**
   - Buka: `http://localhost:8000`

### Option 5: Cloudflare Pages (Gratis)

1. **Buka Cloudflare Dashboard**
   - https://dash.cloudflare.com

2. **Create a Project**
   - Pages > Create a project > Upload assets
   - Upload folder `forest-fire-dashboard`

3. **Deploy**
   - Klik "Save and Deploy"

4. **Akses Dashboard**
   - URL: `https://username.pages.dev`

## Cara Menggunakan Dashboard

1. **Slider Waktu**
   - Geser slider di atas untuk melihat data berdasarkan tanggal
   - Perubahan akan terlihat pada peta, grafik, dan statistik

2. **Peta Indonesia**
   - Setiap titik merah/putih/emas mewakili hotspot kebakaran
   - Klik titik untuk melihat detail provinsi

3. **Grafik**
   - Grafik garis menunjukkan tren hotspot dan area terbakar
   - Klik dan drag untuk zoom

4. **Statistik**
   - Total hotspot hari ini
   - Tingkat keyakinan (High/Medium/Low)
   - Provinsi dengan hotspot terbanyak
   - Area terbakar estimasi (ha)

5. **Provinsi Terbanyak**
   - Daftar 10 provinsi dengan hotspot terbanyak
   - Warna: Merah (High) > Kuning (Medium) > Hijau (Low)

## Teknologi yang Digunakan

- **HTML5** - Struktur halaman
- **CSS3** - Styling dan layout
- **Leaflet.js** - Peta interaktif
- **Chart.js** - Grafik statistik
- **Vanilla JavaScript** - Logika dashboard

## Data Historikal

Dashboard mencakup data dari:
- **Januari 2026** - 125 hotspot (East Kalimantan)
- **Februari 2026** - 89 hotspot (South Papua)
- **Maret 2026** - 156 hotspot (Southeast Sulawesi)
- **April 2026** - 67 hotspot (South Sulawesi)
- **Mei 2026** - 92 hotspot (South Sumatra)
- **Juni 2026** - 145 hotspot (Central Sulawesi)
- **Juli 2026** - 78 hotspot (North Maluku)
- **Agustus 2026** - 203 hotspot (West Nusa Tenggara)
- **September 2026** - 534 hotspot (South Papua)
- **Oktober 2026** - 421 hotspot (Central Kalimantan)
- **November 2026** - 1,095 hotspot (East Kalimantan - peak)

## Catatan

- Data adalah simulasi berdasarkan laporan berita dan data resmi
- Hotspot adalah titik dengan suhu lebih tinggi dari lingkungan
- Tidak semua hotspot menunjukkan kebakaran hutan nyata (bisa juga dari aktivitas manusia lainnya)
- Data diupdate secara real-time berdasarkan laporan terkini

## Kontak

Jika ada pertanyaan atau saran, silakan buka issue di repository ini.

---

**Dibuat dengan ❤️ untuk keamanan lingkungan Indonesia**
