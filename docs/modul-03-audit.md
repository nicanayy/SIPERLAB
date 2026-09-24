# Audit Modul 03 – CSS dan Box Model

## 1. Halaman yang diuji

Pada Modul 03 saya melakukan pengujian pada tiga halaman SIPERALAB, yaitu halaman Beranda, Katalog Peralatan, dan Formulir Peminjaman.

Ketiga halaman tersebut sudah menggunakan external stylesheet `styles.css` sehingga tampilan CSS dapat digunakan secara konsisten.

## 2. Audit Equipment Card

Pada halaman Katalog Peralatan, saya melakukan pengecekan pada bagian kartu peralatan dengan elemen:
<article class="equipment-card">

Berdasarkan pemeriksaan menggunakan DevTools pada tab Computed, hasil pengukuran pada equipment-card adalah:
Content: 216.806 × 376.181 px
Padding: 16 px
Border: 1.2 px
Margin: 16 px


3. Hasil Pengujian 
Setelah CSS diterapkan, hasil pengujian yang saya lakukan adalah:
    1.Tampilan halaman sudah lebih rapi.
    2.Kartu peralatan memiliki border, padding, dan jarak yang jelas.
    3.Tidak terdapat scroll horizontal pada halaman.
    4.Formulir dapat digunakan dengan keyboard.
    5.Focus outline dapat terlihat ketika berpindah menggunakan keyboard.
    6.Penggunaan box-sizing: border-box sudah diterapkan pada elemen halaman.
