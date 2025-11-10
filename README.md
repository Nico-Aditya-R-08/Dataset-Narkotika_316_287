# Dataset-Narkotika_316_287

Repositori ini berisi dataset **putusan pengadilan** terkait tindak pidana **narkotika** yang dikumpulkan dari sumber hukum publik pada website Direktori Putusan Mahkamah Agung RI: https://putusan3.mahkamahagung.go.id/direktori.html. Dataset ini dibuat untuk memenuhi penugasan yang diberikan oleh dosen kami.

---

## 📁 Struktur Direktori

│
├── 📂 Dataset
│ └── Narkotika.zip
│ ↳ Berisi 50 file putusan pengadilan berformat .pdf
│
└── 📂 Overview
└── Overview.xlsx
↳ Ringkasan dari 50 putusan pengadilan (nomor, lembaga, barang bukti, amar putusan)


## 🗂️ Deskripsi Dataset

| Elemen | Keterangan |
|--------|-------------|
| **Jumlah Dokumen** | 50 putusan pengadilan |
| **Format File** | PDF (putusan asli), XLSX (ringkasan data) |
| **Topik** | Tindak Pidana Narkotika |
| **Sumber Data** | Situs resmi putusan pengadilan negeri (putusan.mahkamahagung.go.id) |
| **Periode Tahun** | 2023–2025 |
| **Tujuan Dataset** | Analisis hukum, pelatihan model NLP hukum, dan penelitian tekstual putusan pengadilan. |

---

## 📊 Ringkasan File

### `Dataset/Narkotika.zip`
Berisi 50 dokumen putusan pengadilan dalam format PDF.  
Setiap file memuat teks asli putusan, termasuk bagian:
- Nomor putusan
- Identitas terdakwa
- Barang bukti
- Amar putusan (putusan hakim)

### `Overview/Overview.xlsx`
Berisi tabel ringkasan dengan kolom:
- **No**
- **No Putusan**
- **Lembaga Peradilan**
- **Barang Bukti**
- **Amar Putusan**

Contoh baris data:

| No | No Putusan | Lembaga Peradilan | Barang Bukti | Amar Putusan |
|----|-------------|------------------|----------------|----------------|
| 1 | 990/Pid.Sus/2025/PN Plg | PN Palembang | 5 paket sabu 0,55g | Terbukti bersalah, pidana 6 tahun |

---

## 🧑‍💻 Pengembang
Repositori ini dibuat oleh:
- **Anggota 1:** (Nico Aditya Rahayu) — NIM: 202010370311316
- **Anggota 2:** (Rigan Taufik Fatqur Rahman) — NIM: 202010370311287  

---

## 🔗 Referensi
Contoh dokumentasi referensi: [Laravel Framework](https://github.com/laravel/framework)

---

## ⚖️ Catatan
Dataset ini hanya digunakan untuk **keperluan akademik dan penelitian**, bukan untuk distribusi ulang atau tujuan komersial. Semua dokumen bersumber dari situs publik peradilan Indonesia.

