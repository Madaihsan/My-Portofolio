<div align="center">

# 🌐 Mada Ihsan Wicaksono — Portfolio Website

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-Visit_Site-06b6d4?style=for-the-badge&logoColor=white)](https://madaihsan.github.io)
[![GitHub](https://img.shields.io/badge/GitHub-Madaihsan-181717?style=for-the-badge&logo=github)](https://github.com/Madaihsan)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-mada--ihsan-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/mada-ihsan)

<br/>

> *Personal portfolio website — built with pure HTML, Tailwind CSS, and vanilla JavaScript.*

<br/>

![Portfolio Preview](./images/preview.png)

</div>

---

## ✨ Fitur

- 🎨 **Dark theme** dengan aksen biru/cyan dan efek glassmorphism
- 🌊 **Particle canvas** animasi interaktif di Hero section
- ✍️ **Typewriter effect** pada subtitle
- 🃏 **3D tilt cards** pada section Proyek
- 🎠 **Carousel sertifikat** dengan navigasi panah & dots
- 📱 **Fully responsive** — mobile, tablet, dan desktop
- 📧 **Contact form** terintegrasi EmailJS (tanpa backend)
- ⚡ **Smooth scroll reveal** animasi pada setiap section
- 🔠 **Scrolling marquee** skills bar

---

## 🛠️ Teknologi

| Teknologi | Kegunaan |
|-----------|----------|
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) | Struktur halaman |
| ![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white) | Styling & layout |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) | Animasi & interaksi |
| ![EmailJS](https://img.shields.io/badge/EmailJS-FF5722?style=flat&logoColor=white) | Contact form |
| ![Lucide](https://img.shields.io/badge/Lucide_Icons-F56565?style=flat&logoColor=white) | Icon library |

---

## 📁 Struktur Proyek

```
portfolio/
├── index.html          # File utama
├── images/             # Foto profil & sertifikat
│   ├── foto-profile.png
│   └── ...
└── README.md
```

---

## 🚀 Cara Menjalankan

**1. Clone repository ini:**
```bash
git clone https://github.com/Madaihsan/My-Portofolio.git
cd portfolio
```

**2. Buka langsung di browser:**
```bash
# Cukup buka file index.html di browser
open index.html
```

**Atau gunakan Live Server** (VSCode extension) untuk development.

---

## ⚙️ Konfigurasi EmailJS

Agar form kontak berfungsi, daftar di [emailjs.com](https://emailjs.com) lalu isi 3 nilai ini di bagian `EMAILJS CONFIG` dalam `index.html`:

```js
const EMAILJS_SERVICE_ID  = 'YOUR_SERVICE_ID';
const EMAILJS_TEMPLATE_ID = 'YOUR_TEMPLATE_ID';
const EMAILJS_PUBLIC_KEY  = 'YOUR_PUBLIC_KEY';
```

---

## 📸 Mengganti Foto Profil

Ganti bagian avatar di Hero section:
```html
<img src="./images/foto-profile.png" alt="Mada Ihsan Wicaksono"
     class="w-full h-full object-cover object-top" />
```

---

## 📜 Sections

| # | Section | Deskripsi |
|---|---------|-----------|
| 01 | **Hero** | Nama, role, CTA buttons, foto profil |
| 02 | **About** | Profil singkat & statistik |
| 03 | **Skills** | Skill bars & badge teknologi |
| 04 | **Projects** | 4 proyek utama dengan 3D card |
| 05 | **Certifications** | Carousel 17 sertifikat & prestasi |
| 06 | **Organisasi** | Timeline Robotic Development Community |
| 07 | **Contact** | Info kontak & form kirim pesan |

---

## 📬 Kontak

<div align="center">

📧 **madaihsan123@gmail.com**  
📍 Yogyakarta, Indonesia  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/mada-ihsan)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github)](https://github.com/Madaihsan)

</div>

---

<div align="center">

Dibuat dengan ❤️ oleh **Mada Ihsan Wicaksono** · 2025

</div>
