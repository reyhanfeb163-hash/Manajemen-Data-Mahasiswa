# Sistem Manajemen Data Mahasiswa 🎓

Sebuah aplikasi web interaktif untuk mengelola data akademik mahasiswa. Proyek ini dibangun sebagai bagian dari Ujian Tengah Semester (UTS) mata kuliah Pemrograman Web. Aplikasi ini sepenuhnya berjalan di sisi klien (*client-side*) dan memanfaatkan fitur **Local Storage** pada *browser* sebagai basis data, sehingga tidak memerlukan instalasi *server* atau basis data tambahan.

---

## ✨ Fitur Utama

* **Sistem CRUD Lengkap:** Mendukung operasi Tambah (Create), Tampil (Read), Ubah (Update), dan Hapus (Delete) data mahasiswa.
* **Tema Gelap dan Terang:** Dilengkapi tombol *toggle* Dark/Light Mode. Preferensi tema pengguna disimpan otomatis di *browser*.
* **Pencarian Real-Time:** Menemukan data dengan cepat berdasarkan NIM atau Nama langsung saat pengguna mengetik.
* **Pengurutan Data (Sorting):** *Header* tabel (NIM dan Nama) dapat diklik untuk mengurutkan data secara *Ascending* (A-Z) maupun *Descending* (Z-A).
* **Pagination Dinamis:** Membagi data ke dalam beberapa halaman (maksimal 5 baris per halaman) agar antarmuka tabel tetap rapi.
* **Validasi Input:** Mencegah pendaftaran atau pembaruan data dengan NIM yang sama (NIM berfungsi sebagai *Primary Key*).
* **Desain Responsif:** Tata letak fleksibel yang secara otomatis beradaptasi dengan ukuran layar PC, *Tablet*, maupun *Smartphone*.

---

## 🛠️ Teknologi yang Digunakan

* **HTML5:** Sebagai kerangka dan struktur semantik halaman web.
* **CSS3 (Vanilla):** Penataan gaya dan tata letak menggunakan Flexbox secara murni (tanpa Bootstrap/Tailwind).
* **JavaScript (Vanilla):** Menangani logika manipulasi DOM, validasi *form*, dan algoritma fitur.
* **Web Storage API:** Menggunakan `localStorage` untuk menyimpan data *state* secara persisten di perangkat pengguna.

---

## 🚀 Cara Menjalankan Aplikasi

1. Unduh (Download ZIP) atau *clone* repositori ini ke komputer Anda.
2. Buka *folder* hasil unduhan.
3. Klik dua kali pada file `UTS_Pemrograman Web.html` (atau klik kanan dan pilih "Buka dengan Chrome/Firefox/Edge").
4. Aplikasi akan langsung berjalan di *browser*. Tidak membutuhkan instalasi *software* tambahan apa pun.

---

## 📁 Struktur File

Proyek ini dibangun menggunakan pendekatan *Single-File*, sehingga sangat mudah untuk dipelajari dan didistribusikan.

* `UTS_Pemrograman Web.html`: Satu-satunya file yang memuat keseluruhan elemen (HTML, CSS, dan logika JavaScript).

---

## 💡 Catatan Pengembang

Data yang Anda inputkan akan tersimpan di dalam memori *browser* Anda sendiri. Jika Anda membersihkan data *cache/history* browser, maka data mahasiswa yang telah diinputkan akan ikut terhapus.
