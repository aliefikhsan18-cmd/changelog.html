# Komponen Changelog

Komponen timeline changelog yang bersih dan responsif, dibuat dengan HTML dan CSS murni — tanpa framework, tanpa JavaScript.

# Tampilan

Layout kartu terpusat yang menampilkan:
- Timeline dengan garis vertikal di tengah
- Tanggal di kiri, deskripsi di kanan
- Penanda titik untuk setiap entri
- Tombol "Visit Complete Changelog" di bagian bawah

# Dibuat Dengan

- HTML5
- CSS3 (Flexbox, Grid, Media Queries)

# Struktur Proyek


# Cara Menjalankan

1. Clone atau unduh repositori ini
2. Buka `index.html` di browser
```bash
git clone https://github.com/username/changelog-component.git
cd changelog-component
open index.html
```

# Fitur

- ✅ HTML & CSS murni — tanpa dependensi
- ✅ Desain responsif (mobile & desktop)
- ✅ Layout timeline yang bersih
- ✅ Entri mudah dikustomisasi

#  Tampilan Responsif

| Layar | Layout |
|-------|--------|
| Desktop (> 560px) | Tanggal kiri · Titik tengah · Deskripsi kanan |
| Mobile (≤ 560px) | Satu kolom · Titik & garis di kiri |


https://roadmap.sh/projects/changelog-component

# Kustomisasi

Untuk menambahkan entri changelog baru, salin cuplikan ini di dalam `.timeline`:
```html
<div class="timeline-item">
  <div class="timeline-date">Bulan DD, YYYY</div>
  <div class="timeline-dot"></div>
  <div class="timeline-content">Deskripsi pembaruan kamu di sini</div>
</div>
```

# Lisensi

Proyek ini bersifat open source dan tersedia di bawah [Lisensi MIT](LICENSE).

---

Dibuat sebagai bagian dari tantangan Frontend Projects di [roadmap.sh](https://roadmap.sh).
