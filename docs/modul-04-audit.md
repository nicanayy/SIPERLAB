# Audit Modul 04 — SIPERALAB

## 1. Responsive Layout

Pengujian dilakukan pada tiga ukuran viewport:

- **360 px**: layout form menjadi satu kolom dan tidak terdapat horizontal scroll.
- **768 px**: layout hero berubah menjadi dua kolom antara konten dan gambar.
- **1280 px**: katalog peralatan menjadi tiga kolom dan form menjadi dua kolom.

## 2. Flexbox dan Grid

Flexbox digunakan pada bagian header, navigasi, hero, dan form-actions karena bagian tersebut membutuhkan pengaturan elemen dalam satu arah serta pengaturan jarak dan posisi.

Grid digunakan pada katalog peralatan dan form karena elemen-elemen tersebut lebih sesuai ditampilkan dalam beberapa kolom yang terstruktur.

## 3. Overflow

Pada pengujian ukuran 360 px, 768 px, dan 1280 px tidak ditemukan horizontal scroll. Gambar juga menyesuaikan lebar container sehingga tidak menyebabkan overflow.

## 4. Validasi Form

Validasi form berhasil diuji menggunakan browser:

- Form tidak dapat dikirim ketika field wajib masih kosong.
- NIM kurang dari 10 digit ditolak.
- Durasi peminjaman lebih dari 7 hari ditolak.

## 5. Accessibility

Pengujian menggunakan keyboard dan zoom 200% perlu dilakukan untuk memastikan seluruh elemen tetap dapat digunakan dan layout tidak mengalami masalah.

## 6. Console dan Terminal

Console browser dan terminal perlu diperiksa kembali untuk memastikan tidak terdapat error yang belum dijelaskan.

## 7. Kesimpulan

Implementasi Modul 04 telah menerapkan responsive layout menggunakan Flexbox dan Grid. Layout dapat menyesuaikan ukuran viewport 360 px, 768 px, dan 1280 px tanpa horizontal overflow. Validasi dasar pada form peminjaman juga telah berhasil diuji.