# Tugas Praktikum Aplikasi Berbasis Platform

**Nama:** Muhammad Rafiful Hana  
**NIM:** 2311102227  
**Fakultas:** Teknik Informatika - Telkom University  

---

## Daftar Isi

1. [Deskripsi Proyek](#deskripsi-proyek)
2. [Struktur Direktori](#struktur-direktori)
3. [Modul 4 - Form Neurobrutalist](#modul-4---form-neurobrutalist)
   - [Tampilan](#tampilan-modul-4)
   - [Fitur](#fitur-modul-4)
   - [Teknologi](#teknologi-modul-4)
4. [Modul 5 - Web Profile Kudus](#modul-5---web-profile-kudus)
   - [Tampilan](#tampilan-modul-5)
   - [Fitur](#fitur-modul-5)
   - [Teknologi](#teknologi-modul-5)
5. [Cara Menjalankan](#cara-menjalankan)
6. [Referensi](#referensi)

---

## Deskripsi Proyek

Proyek ini merupakan kumpulan tugas praktikum mata kuliah Aplikasi Berbasis Platform yang berfokus pada pengembangan web menggunakan pendekatan desain **Neurobrutalism** — gaya desain yang menggabungkan elemen brutalisme dengan sentuhan modern, seperti warna kontras, tipografi monospace, garis tegas, dan shadow yang ekspresif.

Terdapat dua modul utama dalam proyek ini:

- **Modul 4:** Formulir input data mahasiswa dengan gaya neurobrutalist murni (tanpa framework CSS).
- **Modul 5:** Halaman profil pribadi yang menampilkan identitas dan informasi tentang Kota Kudus, menggunakan Bootstrap 5 dengan sentuhan neurobrutalist.

---

## Struktur Direktori

```
.
├── README.md
├── Modul 4/
│   ├── form.html          # Halaman form neurobrutalist
│   ├── output.png         # Screenshot hasil tampilan form
│   └── telkom.jpg         # Gambar latar Telkom University
└── Modul 5/
    ├── webprofile.html    # Halaman profil neurobrutalist
    ├── output.png         # Screenshot hasil tampilan profil
    └── kudus.jpg          # Gambar latar Kota Kudus
```

---

## Modul 4 - Form Neurobrutalist

Modul ini berisi halaman **formulir input data** dengan tema neurobrutalist yang menampilkan berbagai elemen form HTML seperti input teks, password, email, radio button, checkbox, dropdown select, dan textarea.

### Tampilan Modul 4

![Tampilan Form Neurobrutalist](Modul%204/output.png)

Formulir ini menggunakan background image Telkom University yang difilter dengan efek grayscale dan noise overlay, serta dilengkapi dengan shadow merah khas neurobrutalist.

### Fitur Modul 4

- Input teks untuk nama lengkap (readonly) dan username
- Input password dengan placeholder petunjuk
- Input email khusus domain Telkom University
- Radio button untuk jenis kelamin
- Checkbox untuk pilihan ketertarikan (Cyber Security, Web Brutalist, AI Engineering, GameDev, UI/UX Radical)
- Dropdown select untuk jenjang pendidikan (D3, S1, S2, S3)
- Textarea untuk kritik dan saran
- Tombol aksi Batal dan Submit dengan efek hover
- Desain responsif untuk berbagai ukuran layar
- Efek hover pada card utama yang memberikan interaksi translasi dan shadow

### Teknologi Modul 4

- HTML5
- CSS3 murni (tanpa framework)
- Desain Neurobrutalist dengan palet warna hitam, putih, dan merah (#dc2626)
- Efek noise berbasis SVG inline

---

## Modul 5 - Web Profile Kudus

Modul ini berisi halaman **profil pribadi** yang menampilkan biodata mahasiswa serta informasi tentang **Kota Kudus**, Jawa Tengah. Halaman ini menggunakan Bootstrap 5 sebagai basis layout dengan tetap mempertahankan estetika neurobrutalist.

### Tampilan Modul 5

![Tampilan Web Profile Kudus](Modul%205/output.png)

Halaman profil menampilkan background Kota Kudus dengan filter gelap dan efek noise, dipadukan dengan elemen bootstrap yang dimodifikasi secara brutal.

### Fitur Modul 5

- Header hero dengan nama dan tagline Kota Kudus
- Badge cluster menampilkan identitas, NIM, fakultas, dan asal
- Layout dua kolom: biodata (kiri) dan profil singkat (kanan)
- Biodata lengkap meliputi nama, NIM, fakultas, universitas, tempat lahir, jenis kelamin, email, dan kontak
- Daftar ketertarikan/hobi dengan ikon Bootstrap Icons
- Quote inspiratif tentang Kota Kudus
- Tombol interaktif "Eksplor Biodata Kudus" dengan feedback dinamis menggunakan JavaScript
- Footer dengan informasi lokasi
- Desain responsif untuk perangkat mobile menggunakan Bootstrap grid system

### Teknologi Modul 5

- HTML5
- CSS3 dengan desain neurobrutalist
- **Bootstrap 5.3** (CDN) untuk layout responsif
- **Bootstrap Icons 1.11** (CDN) untuk ikon
- JavaScript vanilla untuk interaktivitas tombol
- Efek noise dan overlay diagonal berbasis CSS

---

## Cara Menjalankan

Kedua halaman web ini berbasis HTML statis dan tidak memerlukan server backend. Untuk menjalankannya:

### Opsi 1 - Buka Langsung di Browser

1. Buka folder proyek di file manager.
2. Klik dua kali file `Modul 4/form.html` atau `Modul 5/webprofile.html`.
3. Halaman akan terbuka di browser default Anda.

### Opsi 2 - Menggunakan Live Server (VS Code)

1. Buka proyek di Visual Studio Code.
2. Install ekstensi **Live Server** jika belum ada.
3. Klik kanan pada file `Modul 4/form.html` atau `Modul 5/webprofile.html`.
4. Pilih **Open with Live Server**.
5. Halaman akan terbuka di browser dengan fitur auto-reload.

### Catatan

- Pastikan koneksi internet aktif saat membuka `Modul 5/webprofile.html` karena file tersebut menggunakan CDN Bootstrap dan Bootstrap Icons.
- File gambar (`telkom.jpg` dan `kudus.jpg`) harus berada di direktori yang sama dengan file HTML masing-masing agar background dapat tampil.

---

## Referensi

- [Bootstrap 5 Documentation](https://getbootstrap.com/docs/5.3/)
- [Bootstrap Icons](https://icons.getbootstrap.com/)
- [MDN Web Docs - HTML Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms)
- [Neurobrutalism Design Movement](https://www.awwwards.com/neuro-brutalism/)
- Telkom University - Program Studi S1 Informatika