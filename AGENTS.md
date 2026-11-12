# CODING AGENT RULES

Projek ini akan dipakai untuk Wordpress Elementor HTML Element dan Site Custom CSS. Oleh karena itu, projek ini WAJIB mengikuti konfigurasi ini:

- Setiap page adalah HTML.
- Setiap HTML page punya Javascripnya sendiri dan WAJIB INTERNAL JAVASCRIPT.
- Untuk design WAJIB pakai CSS EXTERNAL, TIDAK BOLEH CSS INTERNAL dan INLINE.
- Saat membuat Header (Nav) dan Footer, WAJIB DIBUAT HTML TERPISAH. Jangan satukan dengan HTML PAGE.
- Custom Font wajib dari Google Font.
- Menikuti Aturan Detail dibawah ini.

## Aturan Penulisan Konten

- Jangan pernah mengubah copywriting yang diberikan user.
- Jangan menambahkan atau mengurangi apapun yang diberikan user.
- Copywriting harus 100% karena itu sudah disesuaikan untuk SEO.

## Aturan Projek

- Pastikan struktur projeknya rapih, assets tempatkan di tempatnya.
- Semua page HTML dan CSS ada di root, jangan masukkan kedalam sub-folder.

## Aturan HTML

- Setiap Page = 1 Full HTML Standalone
- Wajib mengikuti bestpractice SEMANTIC HTML agar SEOnya bagus.
- Wajib mengisi semua ALT IMAGE dengan isi sesuai dengan konteksnya.
- Tidak boleh mengimport Custom Font di HTML karena Custom Font Wajib di CSS.
- Tiap Link Internal untuk pindah antar page wajib "/<slug-page>" dengan mengikuti prinsip href Wordpress Elementor Page dan slugnya harus sesuai dengan nama page .html yang dibuat.
- Untuk External Link tidak ada aturan khusus kecuali harus open in blank page.
- Header dan Footer dipisah, dengan membuat header.html dan footer.html.
- Header.html berisi Navbar dengan UI Rounded dan stay ketika di scroll

## Aturan CSS

- CSS masuk ke Global CSS Elementor yang berlaku sitewide.
- CSS hanya ada 1 dan UNTUK SEMUA PAGE termasuk Header dan Footer.
- Pastikan mengikuti bestpractice CSS dengan mengdefine hal berulang dengan ":root {--<property-css>}"
- Saat menggunakan Custom Font wajib mengimport dari CSS menggunakan CSS "@import".
- Pastikan Mobile First Responsive Breakpoin.

## Aturan JS

- Semua TAG script JS harus inline di dalam body TAG HTML.
- Menerapkan Internal JS.
- Tidak ada file .js terpisah.
- Dilarang menaruh script di dalam head.

# Aturan Accessibility dan Performa

- Semua img wajib ada alt dan ada isinya sesuai konteksnya.
- loading="lazy" untuk semua gambar kecuali LCP image (hero above the fold).
- Semua img wajib ada attribute width dan height untuk mencegah layout shift (CLS).
- Gunakan rel="preload" untuk aset kritis.

## List Link/Informasi External

Berikut adalah Link yang berguna dan akan di pakai mengisi link dari copywriting. Kalau linknya Kosong berarti memang tidak ada dan kalau ada isinya pastikan dipakai!

# CTA & APPLICATION BUTTONS
- Btn CTA Become A agent : https://olamet-client.olamet.net/build2/index.html#/subagentRegister?key=6c46753b47532ae24bd082a7c2810610&guildName=We&nick=We&lang=en
- Btn CTA Become A host : https://olamet-client.olamet.net/build2/index.html#/memberInvitation?key=6c46753b47532ae24bd082a7c2810610&guildName=We&nick=We&lang=en
- Btn Sign in : https://h5.olamet.net
- Btn PlayStore : https://olamet-client.olamet.net/build2/index.html#/share?inviteCode=79DTZ5
- Btn AppStore : https://olamet-client.olamet.net/build2/index.html#/share?inviteCode=79DTZ5
- Btn Join us Agent : https://olamet-client.olamet.net/build2/index.html#/subagentRegister?key=6c46753b47532ae24bd082a7c2810610&guildName=We&nick=We&lang=en
- Btn Join us Host : https://olamet-client.olamet.net/build2/index.html#/memberInvitation?key=6c46753b47532ae24bd082a7c2810610&guildName=We&nick=We&lang=en

# FOOTER
- icon wajib menggunakan svg untuk media sosial dibawah ini
- Email : olamet994@gmail.com
- Telegram : telegram.me/olametappservice
- Instagram : olametagency
- tiktok : olametapp
- Whatsapp  : +62 853-5334-4593
- Whatsapp 2 : +62 821-181-2261
- Website : olametapp.com

