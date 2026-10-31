# Catatan Kolaborasi - 315251020011

Repositori ini dibuat untuk memenuhi **Tugas 1: Repositori Git Pertama** pada mata kuliah **Komputasi Kolaboratif** (Pertemuan 3 - Version Control I).

## 👤 Identitas Mahasiswa

* **Nama:** HELDHI STIYOSO
* **NIM:** 315251020011
* **Kelas:** STI

---

## 📌 Deskripsi Repositori

Repositori `catatan-kolaborasi-315251020011` berisi kumpulan rangkuman materi perkuliahan, dokumentasi penggunaan perintah dasar Git (seperti `git log`, `git status`, dll.), serta refleksi pengalaman pertama dalam mengimplementasikan version control system.

---

## 📁 Struktur Berkas

```text
.
├── 1.txt
├── 2.txt
├── 3.txt
├── rangkuman_pertemuan_1.md   # Catatan & rangkuman materi pertemuan 1
├── rangkuman_pertemuan_2.md   # Catatan & rangkuman materi pertemuan 2
├── oneline.png               # Tangkapan layar dari keluaran `git log --oneline`
├── status.png                # Tangkapan layar dari keluaran `git status`
└── README.md                 # Dokumentasi utama repositori
```

---

## 🛠️ Perintah Git yang Digunakan

Berikut adalah beberapa perintah dasar Git yang diterapkan dalam pengerjaan tugas ini:

1. **Inisialisasi & Konfigurasi**
   ```bash
   git init
   git config --global user.name "HELDHI STIYOSO"
   git config --global user.email "email-anda@example.com"
   ```

2. **Pencatatan Perubahan**
   ```bash
   git add <nama_file>
   git commit -m "Pesan commit deskriptif"
   ```

3. **Pemeriksaan Status & Log**
   ```bash
   git status
   git log --oneline
   ```

4. **Koneksi Remote & Push**
   ```bash
   git remote add origin <url-repositori-github>
   git push -u origin main
   ```