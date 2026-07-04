<div align="center">

# 🚀 Innovation Lab 2025: WebGIS SDGs Tracker & Tech Stack Exploration

![Program](https://img.shields.io/badge/Program-Innovation_Lab_2025-blue?style=for-the-badge&logo=codeforces&logoColor=white)
![Organizer](https://img.shields.io/badge/Organizer-HMP_Manajemen_Informatika_UNESA-darkblue?style=for-the-badge)
![Tech](https://img.shields.io/badge/Tech_Focus-Web_Dev_%7C_C%2B%2B_%7C_UI--UX-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-In_Progress-yellow?style=for-the-badge)

<p align="center">
  <strong>Repositori dokumentasi instruksional, proyek implementasi, dan persiapan kompetisi teknologi nasional (OLIVIA & GEMASTIK).</strong>
</p>

[Tentang Program](#-tentang-program) • [Proyek Unggulan](#-proyek-unggulan-webgis-sdgs-tracker) • [Teknologi](#-spesifikasi-teknologi) • [Struktur Repositori](#-struktur-repositori) • [Instalasi](#-panduan-instalasi)

</div>

---

## 📖 Tentang Program

**Innovation Lab 2025** adalah program pelatihan intensif yang diselenggarakan oleh **Himpunan Mahasiswa D4 Manajemen Informatika, Universitas Negeri Surabaya (UNESA)**. Program ini dirancang khusus untuk memperkuat fundamental mahasiswanya dalam rekayasa perangkat lunak dan desain interaksi, sekaligus sebagai inkubator persiapan menuju ajang kompetisi bergengsi tingkat nasional seperti **OLIVIA** dan **GEMASTIK**.

### 🎯 Tujuan Instruksional
- 💻 **Web Engineering:** Membangun aplikasi berbasis web yang responsif, dinamis, dan terintegrasi data geospatial.
- ⚡ **Algoritma & Struktur Data:** Memperkokoh pemecahan masalah (problem-solving) menggunakan bahasa C++.
- 🎨 **UI/UX Design Thinking:** Menerapkan pendekatan *user-centered design* mulai dari *wireframing* hingga *high-fidelity prototyping* di Figma.

---

## 🌎 Proyek Unggulan: WebGIS SDGs Tracker

Sebagai bentuk implementasi nyata dari materi Web Development, repositori ini memuat prototipe **WebGIS SDGs Tracker**. Aplikasi ini berfungsi untuk memetakan, memvisualisasikan, serta melacak capaian *Sustainable Development Goals* (SDGs) di tingkat daerah secara interaktif.

### ✨ Fitur Utama Sistem
1. **Autentikasi Gerbang Masuk (`login.html`)**
   - Antarmuka minimalis berbasis Bootstrap dengan validasi input client-side untuk membatasi hak akses halaman kontrol panel.
2. **Dashboard Pemetaan Interaktif (`dashboard.html`)**
   - **Integrasi WebGIS:** Menyematkan peta spasial dinamis menggunakan teknologi *embedded maps*.
   - **Filter Multikategori:** Memungkinkan pengguna menyaring sebaran data berdasarkan pilar SDGs seperti *Pendidikan*, *Kesehatan*, dan *Lingkungan*.
   - **Panel Informasi Geografis:** Menampilkan *pop-up card* informatif mengenai detail lokasi, klasifikasi sektor, dan persentase progress capaian SDGs (Contoh studi kasus: Kampus Universitas Negeri Surabaya dengan Progress 90%).

---

## 🛠️ Spesifikasi Teknologi

Komposisi teknologi yang dipelajari dan diimplementasikan sepanjang program mencakup:

| Ranah Perkembangan | Teknologi / Framework / Tools |
| :--- | :--- |
| **Bahasa Pemrograman** | PHP, JavaScript, C++, HTML5, CSS3 |
| **Framework & Web Styling** | TailwindCSS, Bootstrap 5.3, Laravel, React.js |
| **Manajemen Data** | MySQL, Firebase |
| **Desain Antarmuka** | Figma (Wireframing, Prototyping, User Flow) |
| **Lingkungan Kerja** | VS Code, Git, GitHub, Laragon, XAMPP |

---

## 📂 Struktur Repositori

```text
innovationlab/
│
├── 📁 Web Development      # Implementasi proyek WebGIS SDGs Tracker (HTML, CSS, JS)
│   ├── login.html          # Gerbang autentikasi user
│   ├── landing.html        # Halaman selamat datang dan pengenalan platform
│   └── dashboard.html      # Panel utama visualisasi WebGIS berbasis TailwindCSS
│
├── 📁 C++ Programming      # Tugas, algoritma terstruktur, dan pemecahan masalah (OOP)
├── 📁 UI-UX Design         # Dokumentasi studi kasus, tautan Figma, dan aset desain
├── 📁 Assignments          # Evaluasi berkala dan logbook mingguan
├── 📁 Practice             # Latihan kode mandiri (Hands-on coding)
└── README.md               # Dokumentasi utama proyek
