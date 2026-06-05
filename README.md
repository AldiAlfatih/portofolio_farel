# Portofolio Farel

Portfolio website for Farell Bryan Ursipuny.  
Built with **Next.js**, **Tailwind CSS**, and **Framer Motion**.

---

## 💻 Panduan Setup VS Code untuk Pemula (Step-by-Step)

Jika kamu ingin mengatur website ini di laptop barumu dari awal dan mengeditnya menggunakan **Visual Studio Code (VS Code)** secara mandiri, ikuti langkah-langkah di bawah ini secara berurutan.

### Tahap 1: Instalasi Aplikasi Wajib
Sebelum mulai, pastikan kamu mengunduh dan menginstal 3 aplikasi ini secara berurutan. Biarkan semua pengaturan instalasinya di pilihan bawaan (default/Next terus sampai selesai):

1. **[Git](https://git-scm.com/downloads)** - Agar laptopmu bisa mengambil kode dari GitHub.
2. **[Node.js](https://nodejs.org/)** - Pilih tombol kiri bertuliskan **LTS (Recommended for Most Users)**. Ini adalah mesin agar website bisa berjalan di laptopmu.
3. **[Visual Studio Code (VS Code)](https://code.visualstudio.com/)** - Aplikasi tempat kamu akan mengedit isi websitenya.

### Tahap 2: Mengambil Kode dari GitHub (Clone)
1. Buka aplikasi **VS Code**.
2. Di menu bagian paling atas, klik **Terminal** ➔ **New Terminal**. Akan muncul panel baru di bagian bawah layar.
3. Di panel bawah tersebut, ketikkan perintah ini lalu tekan **Enter**:
   ```bash
   git clone https://github.com/AldiAlfatih/portofolio_farel.git
   ```
4. Setelah proses download selesai (muncul tulisan *done*), di menu bagian paling atas klik **File** ➔ **Open Folder...**
5. Cari folder bernama **`portofolio_farel`** yang baru saja didownload, lalu pilih folder tersebut dan klik **Select Folder**.

### Tahap 3: Menjalankan Website (Hanya Sekali di Awal)
1. Karena foldernya baru dibuka, buka Terminal lagi: **Terminal** ➔ **New Terminal**.
2. Ketikkan perintah ini untuk mendownload sistem pendukung (butuh koneksi internet):
   ```bash
   npm install
   ```
   *(Tunggu beberapa saat sampai prosesnya selesai)*
3. Jika sudah selesai, nyalakan website dengan perintah:
   ```bash
   npm run dev
   ```
4. Buka browsermu (Chrome/Safari) dan buka alamat **`http://localhost:3000`**. Website portofoliomu akan muncul!

---

## 📝 Cara Edit Konten dan Teks Website
Setelah website berjalan, kamu bebas mengubah isi portofolio tanpa merusak desainnya.

1. Di panel kiri VS Code, cari folder **`src`** ➔ lalu folder **`data`** ➔ dan klik file **`portfolio.ts`**.
2. File ini menyimpan semua data profil, pengalaman, dan riwayat karyamu.
3. Cari teks yang ingin kamu ubah, misalnya nama, tahun jabatan, atau deskripsi pekerjaan, lalu ubah seperti mengetik biasa.
4. Jangan lupa **Save** dengan menekan `Ctrl + S` (Windows) atau `Cmd + S` (Mac).
5. Lihat browsermu (`http://localhost:3000`), perubahannya akan otomatis langsung muncul tanpa perlu di-refresh!

### Cara Memasukkan Gambar/Foto Baru:
1. Siapkan fotomu (misalnya: `kantor-baru.jpg`).
2. Di VS Code, cari folder bernama **`public`**.
3. *Drag-and-drop* (seret) file fotomu dari komputermu ke dalam folder **`public`** di VS Code.
4. Buka kembali file **`src/data/portfolio.ts`**, dan arahkan lokasi gambarnya ke file baru tersebut, contoh:
   ```javascript
   image: "/kantor-baru.jpg"
   ```

---

## ☁️ Menyimpan Perubahan ke GitHub
Jika kamu sudah selesai mengedit hari ini dan ingin menyimpannya ke internet (GitHub), lakukan 3 perintah wajib ini di Terminal:

1. Matikan dulu server dengan klik panel Terminal di bawah, lalu tekan tombol **`Ctrl + C`**, dan ketik **`Y`** (lalu Enter).
2. Simpan perubahannya dengan mengetik perintah berurutan ini:
   ```bash
   git add .
   ```
   ```bash
   git commit -m "Update pengalaman kerja"
   ```
   ```bash
   git push
   ```
Perubahanmu kini tersimpan dengan aman di GitHub!
