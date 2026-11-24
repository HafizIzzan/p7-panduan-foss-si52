# Panduan Kontribusi

Terima kasih telah tertarik untuk berkontribusi dalam proyek Panduan FOSS SI52. Proyek ini bertujuan menyediakan informasi dan panduan mengenai penggunaan perangkat lunak Open Source bagi mahasiswa Sistem Informasi.

## 1. Persiapan

Sebelum berkontribusi, pastikan Anda telah memiliki:

- Akun GitHub.
- Git yang sudah terpasang di komputer.
- Pemahaman dasar mengenai penggunaan Git dan GitHub.

## 2. Alur Kontribusi

Ikuti langkah-langkah berikut untuk mengirimkan kontribusi.

### A. Fork Repository

Buka repository utama di GitHub, kemudian klik tombol **Fork** untuk membuat salinan repository ke akun GitHub pribadi.

### B. Clone Repository

Unduh repository hasil fork ke komputer menggunakan perintah:

```bash
git clone https://github.com/USERNAME/p7-panduan-foss-si52.git
```

Ganti USERNAME dengan nama akun GitHub masing-masing.

### C. Tambahkan Upstream

Hubungkan repository utama agar perubahan terbaru dapat diketahui:

```bash
git remote add upstream https://github.com/HafizIzzan/p7-panduan-foss-si52.git
```

### D. Buat Branch Baru

Buat branch khusus untuk pekerjaan yang akan dilakukan:

```bash
git switch -c nama-branch
```

Gunakan nama branch yang jelas dan sesuai dengan pekerjaan.

### E. Lakukan Perubahan dan Commit

Kerjakan perubahan pada file yang diperlukan. Setelah selesai, periksa perubahan menggunakan:

```bash
git status
```

Tambahkan dan simpan perubahan:

```bash
git add .
git commit -m "docs: jelaskan perubahan yang dilakukan"
```

### F. Push ke Repository Fork

Kirim branch ke repository fork:

```bash
git push -u origin nama-branch
```

### G. Buat Pull Request

Buka repository fork di GitHub, lalu pilih **Compare & pull request**. Pastikan tujuan Pull Request adalah repository utama, yaitu HafizIzzan/p7-panduan-foss-si52, pada branch main.

Tuliskan judul dan deskripsi yang menjelaskan perubahan. Hubungkan Pull Request dengan Issue terkait menggunakan kata kunci, misalnya:

```text
Closes #2
```

## 3. Code Review

Setiap Pull Request akan diperiksa oleh pemilik repository. Pemeriksaan dilakukan terhadap:

- Kesesuaian perubahan dengan Issue.
- Kejelasan dan kerapian isi dokumentasi.
- Ketepatan penulisan Markdown.
- Kelengkapan perubahan yang diajukan.

Kontributor perlu memperbaiki perubahan apabila terdapat masukan dari reviewer.

## 4. Kriteria Kontribusi

Kontribusi yang baik harus memenuhi ketentuan berikut:

1. Perubahan sesuai dengan tujuan proyek.
2. Dokumentasi ditulis secara jelas dan mudah dipahami.
3. Format Markdown digunakan secara konsisten.
4. Setiap perubahan diajukan melalui Pull Request.
5. Kontributor bersedia menerima masukan dalam proses Code Review.

Terima kasih telah membantu mengembangkan proyek Panduan FOSS SI52!