# LAMPCARA - Proyek UAS Introduction to Internet Technology

Selamat datang di **LAMPCARA**, sebuah aplikasi web pariwisata interaktif yang didedikasikan untuk provinsi Lampung.

Proyek ini dibuat untuk memenuhi tugas **Ujian Akhir Semester (UAS) mata kuliah Introduction to Internet Technology**. Aplikasi ini dibangun sebagai *Single Page Application* (SPA) menggunakan **React.js** dan mengintegrasikan berbagai API modern untuk menyajikan data yang dinamis dan pengalaman pengguna yang kaya.

## 🌟 Fitur Utama

* **Halaman Utama (Home):**
    * Video *hero section* yang sinematik.
    * Galeri foto destinasi dan penjelasan motto Lampung ("Sang Bumi Ruwai Jurai").
    * *Slider* interaktif untuk 10 destinasi unggulan.
    * Grid kartu untuk semua 16 destinasi.
* **Halaman Wisata (Wisata):**
    * Peta interaktif dari **MapTiler** untuk setiap destinasi.
    * Deskripsi lengkap dan gambar untuk 16 lokasi wisata.
    * Integrasi video YouTube (diambil via **YouTube Data API**).
* **Halaman About Us:**
    * Profil tim pengembang (Kelompok 8) dengan tautan media sosial.
* **Halaman Contact Us:**
    * Formulir kontak fungsional yang terhubung ke **Google Sheets** via **SheetDB**.
    * Notifikasi *popup* menggunakan **SweetAlert2** saat formulir terkirim.
* **Komponen Global:**
    * *Navbar* dinamis yang berubah tampilan saat *scroll* (Bootstrap Offcanvas).
    * *Widget* cuaca *real-time* di *footer* menggunakan **OpenWeatherMap API**.
    * Animasi *scroll* yang halus di seluruh halaman menggunakan **AOS**.

## 🛠️ Teknologi & API

* **Framework:** React.js
* **Routing:** React Router DOM
* **Styling:** CSS Murni & Bootstrap 5
* **Animasi:** AOS (Animate On Scroll)
* **Notifikasi:** SweetAlert2
* **Request API:** Axios
* **Peta:** MapTiler SDK
* **Cuaca:** OpenWeatherMap API
* **Video:** YouTube Data API v3
* **Formulir:** SheetDB (Google Sheets)

## 👨‍💻 Tim Pengembang (Kelompok 8)

* **Kelvin Jonathan Setiawan**
* **Gregorius Frederico** 
* **Gadiel Narain**
* **Kent Seanly Teguh**
