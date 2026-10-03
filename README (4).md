# Praktikum Web – Profil Organisasi Kampus (IMATIKA)

## Screenshoot Code

### 1. Kode HTML

Berikut adalah screenshoot kode HTML yang digunakan untuk membuat halaman profil Himpunan Mahasiswa Teknik Informatika (IMATIKA).

![Screenshoot Kode HTML](c:\Users\nurwa\Downloads\Untitled design (8).png)

## Screenshoot Output

Berikut adalah hasil tampilan halaman HTML setelah dijalankan melalui browser pada desktop.

![Screenshoot Output Desktop](c:\Users\nurwa\Downloads\Untitled design (7).png)


## Ringkasan

Pada praktikum ini dilakukan pembuatan halaman web statis sederhana yang menampilkan profil Himpunan Mahasiswa Teknik Informatika (IMATIKA) menggunakan HTML. Perubahan utama dilakukan pada struktur HTML dengan menampilkan judul organisasi, logo dan foto kegiatan, daftar bidang, alur pendaftaran, serta media sosial berupa Instagram, YouTube, dan email. Ketiga tipe list digunakan, yaitu unordered list untuk bidang organisasi, ordered list untuk alur pendaftaran, dan description list untuk istilah singkat, serta empat tautan yang terdiri dari anchor internal, tautan eksternal, dan mailto. Masalah yang ditemukan adalah link Instagram tidak dapat dibuka karena atribut ditulis `herf`, bukan `href`. Selain itu, gambar kegiatan tidak tampil karena masih memakai path lokal komputer dengan format HEIC yang tidak didukung browser, serta terdapat tag `</a>` penutup tanpa pembuka dan elemen `h3` di dalam `p` yang tidak sesuai aturan penulisan HTML. Solusinya adalah memperbaiki atribut menjadi `href`, mengonversi foto ke format JPG, menyimpannya di folder `images` dengan path relatif, menghapus tag yang berlebih, dan memindahkan heading keluar dari paragraf. Setelah file disimpan dan halaman di-refresh, seluruh gambar dan tautan dapat berfungsi dengan benar. Hasil akhirnya adalah halaman profil yang terstruktur dan siap dikembangkan dengan CSS pada tahap berikutnya.
