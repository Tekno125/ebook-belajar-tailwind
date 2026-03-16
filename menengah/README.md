# 🟡 Tingkat 2: Menengah (Interactive & Customization)

> ⚠️ **Peringatan:** Ebook ini dihasilkan oleh AI. Mohon laporkan kesalahan yang ditemukan melalui _issues_.

**Fokus:** Interaktivitas state, kustomisasi tema, komponen reusable, dan optimasi aset.

Selamat datang di tingkat menengah! Pada tahap ini, Anda akan belajar membuat aplikasi lebih interaktif, menyesuaikan tema sesuai branding, dan mengoptimalkan hasil akhir untuk produksi. Materi ini dirancang untuk membawa kemampuan Anda dari sekadar "bisa membuat layout" menjadi "bisa membangun sistem desain".

## 📚 Kurikulum Pembelajaran

### 1. State & Interaktivitas
Membuat UI yang responsif terhadap interaksi pengguna.
- **Pseudo-classes:** `hover:`, `focus:`, `active:`, `visited:`, `first:`, `last:`.
- **Dark Mode:** Konfigurasi `darkMode: 'class'` dan penggunaan prefix `dark:`.
- **Group & Peer:** 
  - `group` & `group-hover`: Styling anak berdasarkan induk.
  - `peer` & `peer-checked`: Styling elemen berdasarkan saudara (sibling).
- **Focus Within:** `focus-within` untuk validasi form visual.

### 2. Kustomisasi Tema (Configuration)
Menyesuaikan Tailwind agar sesuai dengan identitas brand Anda.
- **Extending vs Overriding:** Menambah font baru, warna brand, atau breakpoint custom di `tailwind.config.js` tanpa menghapus default.
- **Custom Plugins:** Menggunakan plugin resmi (Typography, Forms, Aspect Ratio).
- **Arbitrary Values:** Menggunakan sintaks kotak siku `[]` untuk nilai spesifik tanpa config (contoh: `w-[350px]`, `bg-[#1da1f2]`).

### 3. Komponen & Reusability
Membangun sistem desain yang konsisten dan mudah dirawat.
- **@apply Directive:** Mengekstrak utility classes menjadi komponen CSS kustom (kapan harus dipakai dan kapan dihindari).
- **Component Libraries:** Membuat library tombol, card, input, dan modal yang konsisten.
- **Patterns:** Pola layout umum (Hero section, Feature grid, Footer, Navbar sticky).

### 4. Transformasi & Transisi
Menambahkan kehidupan pada elemen dengan animasi.
- **Transform:** `scale`, `rotate`, `translate`, `skew`.
- **Transition & Animation:** `transition-all`, `duration-300`, `ease-in-out`, `animate-spin`, `animate-pulse`.
- **Custom Keyframes:** Mendefinisikan animasi kustom di config.

### 5. Optimasi Build
Memastikan performa aplikasi tetap tinggi saat deployment.
- **Purge/Content Config:** Memastikan hanya class yang terpakai yang masuk ke production CSS.
- **Tree Shaking:** Memahami bagaimana Tailwind mengurangi ukuran file CSS secara drastis.

## 🛠️ Latihan Praktik

Tantangan di tingkat ini lebih berfokus pada integrasi beberapa konsep sekaligus:
1. **Dark Mode Toggle:** Buat halaman dengan tombol untuk beralih antara mode terang dan gelap, simpan preferensi pengguna.
2. **Komponen Interaktif:** Buat kartu produk yang memiliki efek hover, tombol "Tambah ke Keranjang" yang berubah状态 saat diklik, dan gambar yang zoom-in sedikit saat di-hover.
3. **Form Validasi Visual:** Gunakan `peer` dan `focus-within` untuk menampilkan pesan error atau sukses di sebelah input field secara otomatis.

## 🚀 Langkah Selanjutnya

Anda telah menyelesaikan seluruh materi dalam repositori ini! Untuk mengembangkan kemampuan lebih lanjut:
1. **Bangun Proyek Nyata:** Cobalah membuat portfolio pribadi, landing page produk, atau dashboard admin menggunakan semua ilmu yang telah dipelajari.
2. **Pelajari Framework JS:** Integrasikan pengetahuan Tailwind ini dengan React, Vue, atau Svelte untuk aplikasi yang lebih dinamis.
3. **Eksplorasi Ekosistem:** Lihat komponen siap pakai dari komunitas seperti Tailwind UI atau DaisyUI untuk referensi pola lanjutan.

---
*Selamat! Anda telah menyelesaikan jalur pembelajaran ini. Teruslah berkarya!*
