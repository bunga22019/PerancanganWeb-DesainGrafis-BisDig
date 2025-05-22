# PerancanganWeb-DesainGrafis-BisDig

no 1 

## 📚 Studi Kasus
Situs portofolio mahasiswa tidak terlihat rapi saat dibuka di smartphone. Gambar terlalu besar dan teks meluber ke luar layar.

## 🎯 Solusi
Menggunakan konsep **Responsive Design** dengan bantuan **media queries** di CSS untuk memastikan tampilan situs menyesuaikan ukuran layar perangkat yang digunakan.

## 🧠 Penjelasan Responsive Design
**Responsive Design** adalah pendekatan dalam desain web yang membuat tampilan halaman web secara otomatis menyesuaikan diri dengan berbagai ukuran layar dan perangkat (desktop, tablet, smartphone). Tujuan utamanya adalah memberikan pengalaman pengguna (user experience) yang optimal di semua perangkat, tanpa perlu scroll horizontal atau zoom manual.

Fitur utama dari responsive design meliputi:
- **Layout fleksibel**: menggunakan persentase atau satuan fleksibel (seperti `vw`, `vh`, atau `em`) alih-alih piksel tetap.
- **Gambar responsif**: gambar disesuaikan agar tidak keluar dari batas layar.
- **Media queries**: aturan CSS khusus yang hanya berlaku untuk ukuran layar tertentu.

## 📐 Apa itu Media Queries?
**Media Queries** adalah fitur dalam CSS yang memungkinkan kita menerapkan style berbeda tergantung pada kondisi tertentu, seperti lebar layar, orientasi perangkat, atau resolusi layar.

Contoh umum penggunaan media queries:
```css
@media (max-width: 768px) {
  body {
    font-size: 16px;
  }
}


# 📘 Blog Interaktif - Komentar Tersembunyi

Ini adalah proyek blog sederhana berbasis HTML, CSS, dan JavaScript yang memungkinkan pengguna menampilkan atau menyembunyikan komentar pembaca melalui tombol interaktif. Desainnya responsif, ringan, dan cocok untuk pemula yang ingin memahami interaksi dasar pada halaman web.

## 🖼️ Tampilan
Blog memiliki tampilan modern dengan latar gradien, efek animasi saat komentar muncul, dan tombol interaktif untuk mengatur visibilitas komentar.

## 🚀 Fitur
- 🌐 Desain responsif dan bersih
- 💬 Tombol untuk menampilkan/sembunyikan komentar
- 🎨 Animasi `fadeIn` saat komentar ditampilkan
- 📱 Cocok untuk tampilan mobile dan desktop
- 🧠 Kode JavaScript ringan dan mudah dipahami

## 🛠️ Teknologi yang Digunakan
- **HTML5** untuk struktur halaman
- **CSS3** untuk styling dan animasi
- **JavaScript** untuk interaktivitas tombol komentar

## 📂 Struktur Proyek

blog-interaktif-komentar/
├── index.html ← File utama halaman blog
└── README.md ← Dokumentasi proyek ini
