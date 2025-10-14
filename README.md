# 📄 Template Microsoft Word – Normal.dotm (Format Akademik)

## 🧩 Tentang File Ini
File **`normal.dotm`** ini merupakan template dasar **Microsoft Word** yang telah saya modifikasi untuk mempermudah penulisan dokumen akademik seperti **makalah, proposal, sempro, tugas akhir, dan skripsi**.  

Dengan template ini, kamu tidak perlu lagi repot mengatur format setiap kali membuat dokumen baru. Semua pengaturan layout, gaya tulisan, hingga penomoran halaman sudah disiapkan agar sesuai dengan kebutuhan umum karya tulis akademik.

---

## ⚙️ Cara Instalasi Template

### 🪟 Windows

1. **Tutup semua dokumen Microsoft Word.** Pastikan tidak ada proses Word yang berjalan di background.  
2. **Buka folder penyimpanan template Word:**
   - Cara cepat: tekan `Win + R`, lalu ketik:
     ```bash
     %appdata%\Microsoft\Templates
     ```
   - Atau manual:
     ```bash
     C:\Users\<nama_pengguna>\AppData\Roaming\Microsoft\Templates
     ```
3. **Backup file lama (opsional):**
   - Salin `normal.dotm` bawaan dan ubah namanya jadi `normal_backup.dotm`.
4. **Salin file `normal.dotm` dari paket ini** ke folder tersebut.  
5. **Buka kembali Microsoft Word.**  
   Template akan otomatis aktif setiap kali kamu membuat dokumen baru (`Ctrl + N`).

---

### 🍎 macOS

1. Tutup Microsoft Word sepenuhnya.  
2. Buka Finder, lalu arahkan ke:
   ```bash
   /Users/<nama_pengguna>/Library/Application Support/Microsoft/Office/User Templates/
3. Ganti file Normal.dotm dengan file yang baru.
4. Buka kembali Word untuk mulai menggunakan template.

## ✨ Fitur Utama Template

### 📐 Format Dasar
- **Margin:** 4 cm kiri, 4 cm atas, 3 cm kanan, 3 cm bawah (format 4-4-3-3)  
- **Font:** Times New Roman 12 pt  
- **Paragraf:** Rata kanan–kiri *(Justify)*  

---

### 🧭 Heading & Struktur Dokumen
Telah disiapkan **Heading 1–5** sesuai kebutuhan penulisan:

| Level | Contoh | Shortcut |
|:------|:--------|:----------|
| Heading 1 | BAB | `Alt + 1` |
| Heading 2 | Subbab 1.1 | `Alt + 2` |
| Heading 3 | Subbab 1.1.1 | `Alt + 3` |
| Heading 4 | Sub-subbagian | `Alt + 4` |
| Heading 5 | Detail lebih dalam | `Alt + 5` |

---

### 📚 Daftar Isi, Gambar, dan Tabel Otomatis
Gunakan shortcut berikut untuk menampilkan daftar otomatis:

| Fungsi | Shortcut | Keterangan |
|:--------|:-----------|:------------|
| Tampilkan **Daftar Isi** | `Alt + D` | Membuat daftar isi otomatis |
| Tampilkan **Daftar Gambar** | `Alt + G` | Membuat daftar gambar otomatis |
| Tampilkan **Daftar Tabel** | `Alt + T` | Membuat daftar tabel otomatis |
| Tambahkan **Caption Gambar** | `Alt + Shift + G` | Menambahkan label dan nomor gambar |
| Tambahkan **Caption Tabel** | `Alt + Shift + T` | Menambahkan label dan nomor tabel |
| **Update Daftar Isi** | `Alt + U` | *Hanya memperbarui daftar isi, bukan gambar/tabel!* |

> 🟡 **Catatan:** Jika ingin memperbarui *daftar gambar* atau *daftar tabel*, hapus daftar lama lalu tampilkan ulang dengan shortcut `Alt + G` atau `Alt + T`.

---

### 🧩 Section Break & Penomoran Halaman
Gunakan:
- `Alt + N` → Menambahkan *Section Break*  
- `Alt + P` → Mengatur **Page Numbering Otomatis**

Tersedia **2 mode**:
1. **Mode 1** – Cover & halaman setelahnya dalam satu section (Section 1).  
   Bab 1 dan seterusnya mulai dari Section 2++.  
2. **Mode 2** – Cover dan halaman setelahnya section berbeda.  
   Cover = Section 1, Halaman setelahnya = Section 2, Bab 1 dan seterusnya Section 3++.

**Pilihan tambahan:**
- Nomor halaman setelah cover bisa menggunakan **i** atau **ii**.  
- Penempatan nomor halaman:
  - All Footer = **Footer tengah penuh**  
  - Kombinasi = Halaman bab: **Footer tengah**, halaman setelah bab: **Header kanan**

---

## 📘 Panduan Penomoran Halaman Otomatis

Fitur **penomoran halaman otomatis** pada template ini bergantung pada **section break** di Microsoft Word.  
Artinya, pengguna perlu **menambahkan section break secara manual** sebelum menjalankan penomoran.

### 🧩 Cara Penggunaan:
1. Tempatkan kursor di **akhir bagian sebelumnya** (misalnya di akhir halaman cover).  
2. Tekan **`Alt + N`** → untuk menambahkan **Section Break (Next Page)**.  
3. Lalu tekan **`Alt + P`** untuk membuka dialog **Penomoran Halaman Otomatis**.  
4. Pilih mode yang diinginkan:  
   - **Mode 1:** Halaman cover dan halaman setelahnya berada dalam satu section (Section 1). Bab 1 dan seterusnya dimulai dari Section 2++.  
   - **Mode 2:** Halaman cover dan halaman setelahnya berada di section yang berbeda (Cover = Section 1, setelahnya = Section 2, Bab 1 dan seterusnya = Section 3++).  
5. Halaman setelah cover **hanya menggunakan angka romawi kecil** *(i, ii, iii, ...)*.  
   - Kamu bisa memilih apakah ingin dimulai dari **i** atau **ii**.  
6. Penempatan nomor halaman:  
  - All Footer = **Footer tengah penuh**  
  - Kombinasi = Halaman bab: **Footer tengah**, halaman setelah bab: **Header kanan**

---

### ⚠️ Jika Terjadi Masalah “Double Break”

Kadang tanpa sengaja pengguna menambahkan **lebih dari satu pemisah halaman**, misalnya:  
- Dua **Section Break (Next Page)** berturut-turut, **atau**  
- Satu **Section Break** dan satu **Page Break (Ctrl + Enter)** di tempat yang sama.  

Kondisi ini bisa menyebabkan:
- Munculnya halaman kosong di antara bagian,  
- Nomor halaman tidak berurutan, atau  
- Format halaman jadi tidak sesuai.

#### 🛠 Cara Mengatasinya:
1. Aktifkan tampilan tanda format:  
   - Tekan **`Ctrl + Shift + 8`** atau klik ikon **¶ (Show/Hide ¶)** di tab *Home*.  
2. Periksa area antarbagian (misalnya antara cover dan halaman berikutnya).  
3. Jika terlihat **lebih dari satu pemisah** (baik *Page Break* maupun *Section Break*), hapus yang berlebih.  
4. Pastikan **hanya ada satu Section Break** antara dua bagian utama.  
5. Setelah itu, jalankan kembali penomoran otomatis dengan **`Alt + P`**.

> 💡 **Tips:** Gunakan tampilan *Draft View* di Word agar lebih mudah mendeteksi posisi *Page Break* dan *Section Break*.

---

## 🧠 Tujuan Pembuatan

Template ini dibuat untuk membantu mahasiswa dalam menulis dokumen akademik dengan format yang konsisten, profesional, dan efisien, tanpa perlu mengatur layout dari awal.

---

## 📦 Download Template

Kamu bisa mengunduh file template melalui link berikut:  
➡️ [Download Normal.dotm Template (RAR)](https://github.com/Aandikei/tools-ms-word/releases/tag/word)

---

## ✉️ Kontak

Jika kamu memiliki pertanyaan, menemukan masalah, atau ingin memberikan saran terkait template ini, silakan hubungi:  
📧 **andiahmad9288@gmail.com**

---

## 🧪 Testing Information

Template ini telah diuji menggunakan **Microsoft Word 2013 (versi Windows)**.  
Fungsi dan shortcut telah dipastikan berjalan dengan baik pada versi ini.  
Namun, beberapa perilaku tampilan atau shortcut key mungkin sedikit berbeda pada versi Word yang lebih baru.

---

## 📬 Kredit

Dibuat oleh **Andi**  
📎 File dan pembaruan bisa diakses melalui repository ini.
