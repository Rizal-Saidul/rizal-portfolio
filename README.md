# Portfolio - Saidul Rizal

Portfolio website sederhana yang menampilkan profil, skills, dan proyek-proyek yang telah dikerjakan.

## 🚀 Fitur

- **Desain Modern** - Menggunakan Tailwind CSS dengan efek glassmorphism
- **Responsive** - Tampil sempurna di berbagai ukuran layar
- **Dark Mode** - Tema gelap yang nyaman untuk mata
- **Animated** - Animasi halus dan transisi yang menarik
- **Tab Navigation** - Pemisahan proyek Backend dan Frontend

## 🛠️ Teknologi

- HTML5
- Tailwind CSS (via CDN)
- JavaScript (Vanilla)
- Google Fonts (Inter & Fira Code)

## 📂 Struktur File

```
portofofilo-basic/
├── index.html          # File utama portfolio
├── photo-profile.png   # Foto profil
└── README.md          # Dokumentasi ini
```

## 🌐 Cara Menggunakan

### Lokal

1. Clone repository ini
2. Buka file `index.html` di browser Anda
3. Portfolio siap digunakan!

### Deploy

Portfolio ini bisa di-deploy ke berbagai platform gratis:

#### GitHub Pages
1. Push repository ke GitHub
2. Buka Settings → Pages
3. Pilih branch `main` dan folder `/ (root)`
4. Klik Save
5. Portfolio akan tersedia di `https://username.github.io/repository-name`

#### Netlify
1. Drag & drop folder ke [Netlify Drop](https://app.netlify.com/drop)
2. Portfolio langsung online!

#### Vercel
1. Import repository ke [Vercel](https://vercel.com)
2. Deploy otomatis setiap kali push

## ✏️ Kustomisasi

### Mengubah Profil
Edit bagian profil di `index.html` (baris 92-93):
```html
<h1 class="text-2xl font-bold text-white">Saidul Rizal</h1>
<p class="text-sm text-accent mt-1">@rizalsaidul</p>
```

### Menambah/Edit Proyek
Edit data proyek di bagian JavaScript (baris 185-240):
```javascript
const projectsData = {
    backend: [
        {
            title: 'Nama Proyek',
            description: 'Deskripsi proyek',
            tech: { name: 'Rust', color: 'text-orange-400' },
            // ... data lainnya
        }
    ]
}
```

### Mengubah Warna
Edit konfigurasi Tailwind di `<script>` (baris 11-39):
```javascript
colors: {
    deep: '#0B1120',      // Background
    accent: '#38bdf8',    // Warna aksen (cyan)
    secondary: '#818cf8', // Warna sekunder (purple)
}
```

## 📝 Lisensi

Free to use - silakan digunakan dan dimodifikasi sesuai kebutuhan.

## 👤 Kontak

- GitHub: [@Rizal-Saidul](https://github.com/Rizal-Saidul)
- LinkedIn: [Muhamad Saidul Rizal](https://linkedin.com/in/muhamad-saidul-rizal)

---

✨ Built with passion and ☕ coffee
