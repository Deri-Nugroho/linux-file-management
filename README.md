# 🐧 Basic Linux File Management

## 📌 Objective

Dalam task ini, kamu akan belajar:

* Navigasi directory (`pwd`, `cd`, `ls`)
* Manajemen file & folder (`mkdir`, `touch`, `cp`, `mv`, `rm`)
* Edit file menggunakan `nano`
* Melihat & mencari isi file (`cat`, `head`, `tail`, `grep`, `wc`)
* Permission file (`chmod`)
* Visualisasi struktur project (`tree`)

---

## 🧪 Scenario

Kamu adalah seorang **Junior Linux Engineer** yang diminta untuk:

1. Membuat project sederhana
2. Mengelola file HTML
3. Membuat backup
4. Mengatur permission
5. Melakukan pengecekan isi file

---

## 📁 Step 1 — Mengetahui Lokasi Saat Ini

```bash
pwd
```

---

## 📂 Step 2 — Membuat Project Directory

```bash
mkdir ~/web-lab
cd ~/web-lab
ls
```

---

## 📁 Step 3 — Membuat Struktur Folder

```bash
mkdir assets backup
ls
```

---

## 📄 Step 4 — Membuat File HTML

```bash
touch index.html
ls
```

---

## ✏️ Step 5 — Edit File dengan Nano

```bash
nano index.html
```

Isi dengan:

```html
<!DOCTYPE html>
<html>
<head>
    <title>My First Linux Project</title>
</head>
<body>
    <h1>Hello dari UP 🚀</h1>
    <p>Nama: [ISI NAMA KAMU]</p>
</body>
</html>
```

Simpan:

```
CTRL + O → Enter → CTRL + X
```

---

## 🔍 Step 6 — Melihat Isi File

```bash
cat index.html
head index.html
tail index.html
```

---

## 🔎 Step 7 — Mencari Teks dalam File

```bash
grep "Hello" index.html
```

---

## 📊 Step 8 — Menghitung Isi File

```bash
wc index.html
```

---

## 📋 Step 9 — Backup File

```bash
cp index.html backup/index.html.bak
ls backup
```

---

## 🔄 Step 10 — Rename File

```bash
mv index.html home.html
ls
```

---

## 🔐 Step 11 — Permission File

```bash
ls -l
chmod 644 home.html
ls -l
```

---

## ❌ Step 12 — Hapus File Tidak Terpakai

```bash
touch test.txt
ls
rm test.txt
ls
```

---

## 📂 Step 13 — Navigasi Directory

```bash
cd backup
ls
cd ..
```

---

## 🧹 Step 14 — Membersihkan Terminal

```bash
clear
```

---

## 🎯 Expected Result

Struktur project:

```
web-lab/
├── home.html
├── assets/
└── backup/
    └── index.html.bak
```

---

## 🔥 Challenge Mode (No Guidance)

Selesaikan semua tugas berikut.

---

### 🎯 Task 1 — Setup Project

Buat sebuah project dengan nama:

* `web-lab`

Di dalamnya, buat struktur:

* folder `assets`
* folder `backup`
* file utama `index.html`

---

### 🎯 Task 2 — Modify HTML

Edit file `index.html`:

* Ubah judul menjadi: **"Linux File Management Project"**
* Tambahkan nama kamu di dalam halaman
* Tambahkan minimal 1 paragraf bebas

---

### 🎯 Task 3 — Backup File

* Buat salinan dari file HTML ke dalam folder `backup`
* Gunakan nama file backup yang berbeda dari file asli

---

### 🎯 Task 4 — Rename File

* Ubah nama file utama dari `index.html` menjadi `home.html`

---

### 🎯 Task 5 — File Inspection

* Tampilkan isi file HTML
* Cari kata tertentu di dalam file (contoh: nama kamu)
* Hitung jumlah baris dalam file tersebut

---

### 🎯 Task 6 — Permission

* Pastikan file `home.html` bisa dibaca oleh semua user
* Verifikasi perubahan permission

---

### 🎯 Task 7 — Asset File

* Buat file baru di dalam folder `assets`
* Isi file tersebut dengan styling sederhana (bebas)

---

### 🎯 Task 8 — Navigation

* Masuk ke folder `backup`
* Tampilkan isinya
* Kembali ke root project

---

### 🎯 Task 9 — Cleanup

* Buat file sementara (bebas nama)
* Hapus file tersebut

---

### 🎯 Task 10 — Final Check

Pastikan struktur akhir project:

* `web-lab/`

  * `home.html`
  * `assets/`
  * `backup/` (berisi file backup)

---

## 🏁 Goal

Jika kamu bisa menyelesaikan semua task ini, berarti kamu sudah:

* Memahami dasar Linux File Management

---

## 🧠 Key Learning

* Navigasi filesystem Linux
* File & directory management
* Editing file dengan nano
* Searching dalam file (basic DevOps skill)
* Permission dasar

---

💡 *Real skill is built when you solve problems without guidance.*

---

## 👨‍💻 Author

Deri Nugroho
Cloud & DevOps Enthusiast ☁️
