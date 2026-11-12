# Panduan Pemindahan ke WordPress Elementor (Olamet Project)

Folder ini (`elementor-wordpress/`) berisi file-file yang sudah disiapkan dan dioptimalkan secara rapi agar siap pakai langsung di **WordPress Elementor**.

---

## 📁 Struktur File dalam Folder Ini

| Nama File | Fungsi | Lokasi Pasang di Elementor |
| :--- | :--- | :--- |
| **`00-SITE-GLOBAL-CSS.css`** | CSS Global Sitewide (styling seluruh komponen, font Google, warna neon, dark-mode, mobile responsive). | **Elementor Site Settings > Custom CSS** atau **Appearance > Customize > Additional CSS** |
| **`01-HEADER-TEMPLATE.html`** | Navbar Rounded dengan efek blur, sticky saat di-scroll, dropdown More, dan drawer mobile menu responsive. | **Elementor Theme Builder > Header** |
| **`02-FOOTER-TEMPLATE.html`** | Footer lengkap dengan 6 ikon SVG media sosial, Google Play / App Store badge, quick links, dan kontak support. | **Elementor Theme Builder > Footer** |
| **`03-PAGE-HOME.html`** | Konten Halaman Depan / Home (Hero, Trust Stats, Differences, How It Works, FAQ accordion, Lightbox modal). | Halaman Home / Front Page (Widget HTML) |
| **`04-PAGE-AGENCY-COOPERATION.html`** | Konten Halaman Agency Cooperation (Tutorial, 2 Model Agency, Tabel Komisi, Kalkulasi Penarikan Beans, CTA). | Halaman `/agency-cooperation` (Widget HTML) |
| **`05-PAGE-HOST-COOPERATION.html`** | Konten Halaman Host Cooperation (Tutorial & Visual Peran Host yang sudah dirapikan seimbang, Tabel Daily Task, Target Komisi, Benefit, CTA). | Halaman `/host-cooperation` (Widget HTML) |
| **`06-PAGE-ABOUT-US.html`** | Konten Halaman About Us (Terms of Service Olamet Live, legal clauses, info perusahaan). | Halaman `/about-us` (Widget HTML) |
| **`07-PAGE-CONTACT.html`** | Konten Halaman Contact Us (Kartu kontak support WhatsApp, Telegram, Email, Instagram, dan Carousel Galeri interaktif). | Halaman `/contact` (Widget HTML) |
| **`opsi-full-canvas-pages/`** | Berisi 5 file HTML standalone lengkap (jika Anda memilih membuat halaman menggunakan template **Elementor Canvas** tanpa Theme Builder). | Halaman Canvas Mandiri |

---

## 🚀 Panduan Langkah Demi Langkah (Metode Rekomendasi: Theme Builder)

Metode ini adalah standar terbaik Elementor karena Header dan Footer hanya dibuat satu kali dan otomatis terpasang rapi di seluruh halaman.

### Langkah 1: Pasang Global CSS (Hanya Perlu 1 Kali)
1. Buka Dashboard WordPress Anda.
2. Buka salah satu halaman di Elementor Editor.
3. Klik ikon hamburger di pojok kiri atas -> pilih **Site Settings** (Pengaturan Situs).
4. Gulir ke bawah dan pilih menu **Custom CSS**.
5. Buka file **`00-SITE-GLOBAL-CSS.css`**, copy seluruh isinya (`Ctrl + A` lalu `Ctrl + C`).
6. Paste ke dalam kolom Custom CSS Elementor.
7. Klik **Update / Simpan**.
> *Alternatif:* Anda juga bisa mem-paste kode CSS ini di menu WordPress: **Tampilan (Appearance) > Sesuaikan (Customize) > CSS Tambahan (Additional CSS)**.

---

### Langkah 2: Buat Template Header
1. Di Dashboard WordPress, buka **Templates > Theme Builder > Header** (atau gunakan plugin *Elementor Header & Footer Builder* jika memakai Elementor Free).
2. Klik **Add New Header**.
3. Buat Container / Section baru dengan 1 Kolom:
   - Atur **Content Width**: `Full Width` (Lebar Penuh).
   - Atur **Columns Gap**: `No Gap` (Tanpa Jarak).
4. Cari widget **HTML** dari panel elemen Elementor, lalu tarik (drag & drop) ke dalam section.
5. Buka file **`01-HEADER-TEMPLATE.html`**, copy seluruh isinya dan paste ke dalam widget HTML.
6. Klik **Publish**, lalu atur **Display Conditions**: pilih **Entire Site** (Seluruh Situs) -> Save & Close.

---

### Langkah 3: Buat Template Footer
1. Di Dashboard WordPress, buka **Templates > Theme Builder > Footer**.
2. Klik **Add New Footer**.
3. Buat Container / Section baru dengan 1 Kolom:
   - Atur **Content Width**: `Full Width`.
   - Atur **Columns Gap**: `No Gap`.
4. Drag & drop widget **HTML** ke dalam section.
5. Buka file **`02-FOOTER-TEMPLATE.html`**, copy seluruh isinya dan paste ke dalam widget HTML.
6. Klik **Publish**, lalu atur **Display Conditions**: pilih **Entire Site** (Seluruh Situs) -> Save & Close.

---

### Langkah 4: Buat Halaman (Pages)
Untuk setiap halaman (Home, Agency Cooperation, Host Cooperation, About Us, Contact):

1. Masuk ke **Pages (Laman) > Add New (Tambah Baru)**.
2. Berikan Judul dan pastikan **URL Slug / Permalink** sesuai dengan daftar berikut:
   - Halaman Home: Atur sebagai **Front Page** di *Settings > Reading*.
   - Halaman Agency Cooperation: Slug **`agency-cooperation`**
   - Halaman Host Cooperation: Slug **`host-cooperation`**
   - Halaman About Us: Slug **`about-us`**
   - Halaman Contact: Slug **`contact`**
3. Klik **Edit with Elementor**.
4. Di panel pengaturan halaman (ikon gerigi di kiri bawah):
   - Ubah **Page Layout** menjadi **Elementor Full Width** (sehingga Header dan Footer Theme Builder otomatis muncul di atas dan bawah).
5. Buat Section 1 Kolom:
   - Atur **Content Width**: `Full Width`.
   - Atur **Columns Gap**: `No Gap`.
6. Tarik (drag & drop) widget **HTML** ke dalam section.
7. Buka file page yang sesuai:
   - Untuk Home: buka **`03-PAGE-HOME.html`**
   - Untuk Agency Cooperation: buka **`04-PAGE-AGENCY-COOPERATION.html`**
   - Untuk Host Cooperation: buka **`05-PAGE-HOST-COOPERATION.html`**
   - Untuk About Us: buka **`06-PAGE-ABOUT-US.html`**
   - Untuk Contact: buka **`07-PAGE-CONTACT.html`**
8. Copy seluruh isi file dan paste ke dalam widget HTML tersebut.
9. Klik **Publish / Terbitkan**.

---

## 🎨 Opsi Alternatif: Metode Elementor Canvas (Single Page Full)
Jika Anda tidak menggunakan Theme Builder dan ingin mem-paste seluruh isi halaman termasuk Header dan Footer sekaligus dalam 1 widget:
1. Gunakan file yang ada di dalam sub-folder **`opsi-full-canvas-pages/`**.
2. Pada pengaturan halaman Elementor (ikon gerigi kiri bawah), ubah **Page Layout** menjadi **Elementor Canvas**.
3. Drag widget **HTML** ke halaman dan paste isi file dari folder `opsi-full-canvas-pages/`.

---

## ⚙️ Fitur Interaktif yang Sudah Bawaan di Dalam File:
- **Responsive Mobile Drawer**: Tombol hamburger di header otomatis membuka menu navigasi mobile yang smooth.
- **Lightbox Image Zoom**: Semua gambar peran/alur dapat di-klik untuk melihat preview ukuran penuh dengan modal overlay gelap.
- **FAQ Accordion**: Pertanyaan pada Home dan Agency otomatis membuka/menutup jawaban secara mulus.
- **Auto-Play Carousel**: Galeri foto pada halaman Contact otomatis slide setiap 3.5 detik dengan dukungan drag/swipe di layar sentuh HP dan tombol panah keyboard.
- **SEO & Accessibility**: Tag semantik HTML5, alt image lengkap, `width` & `height` untuk mencegah CLS, dan `loading="lazy"` untuk kecepatan loading.
