# Portfolio Website - Tugas Akhir PPW

Website portofolio pribadi yang dibuat untuk memenuhi Tugas Akhir mata kuliah Praktikum Pemrograman untuk praktik Git workflow.

## Git Workflow yang Diterapkan

Berikut adalah alur kerja Git yang saya terapkan dalam pengerjaan proyek ini:

### 1. Inisialisasi Repository
```bash
git init
git config --global user.name "Luthfi Muthathohirin"
git config --global user.email "luthfirg2502@gmail.com"
```

### 2. Commit Bertahap
Saya membuat commit secara bertahap sesuai dengan perkembangan proyek:

- **Commit pertama**: Menambahkan file `index.html` dan foto profil
  ```
  70c118020 - Menambahkan file index.html dan juga foto
  ```

- **Commit kedua**: Menambahkan file `style.css` untuk styling
  ```
  05e835b47 - Menambahkan file style.css
  ```

- **Commit ketiga**: Mengubah deskripsi proyek di portofolio
  ```
  16cd53418 - Mengubah deskripsi proyek di portofolio
  ```

### 3. Branching untuk Eksperimen
Saya membuat branch baru bernama `fitur-ubah-deskripsi` untuk bereksperimen dengan perubahan deskripsi tanpa mempengaruhi branch utama:

```bash
git branch fitur-ubah-deskripsi
git checkout fitur-ubah-deskripsi
```

Di branch ini saya melakukan modifikasi pada deskripsi proyek di dalam file HTML.

### 4. Merge Branch
Setelah perubahan di branch `fitur-ubah-deskripsi` selesai dan sudah sesuai, saya merge kembali ke branch `master`:

```bash
git checkout master
git merge fitur-ubah-deskripsi
```

Setelah merge berhasil, branch `fitur-ubah-deskripsi` sudah tidak diperlukan lagi sehingga saya hapus:

```bash
git branch -d fitur-ubah-deskripsi
```

### 5. Push ke GitHub
Terakhir, saya push semua perubahan ke repository GitHub:

```bash
git remote add origin https://github.com/HyLuthfi/TA-PPW2
git push -u origin master
```

## Hasil Git Log

Berikut adalah visualisasi commit history menggunakan `git log --graph --oneline`:

```
* 16cd534 (HEAD -> master, origin/master) Mengubah deskripsi proyek di portofolio
* 05e835b Menambahkan file style.css
* 70c1180 Menambahkan file index.html dan juga foto
```

## Link Repository

Repository: [https://github.com/HyLuthfi/TA-PPW2](https://github.com/HyLuthfi/TA-PPW2)

---

**oleh:** Luthfi Muthathohirin  
**NPM:** 2315061112
**Mata Kuliah:** Praktikum Pemrograman Web  
**Tahun:** 2025
