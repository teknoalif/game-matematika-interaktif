# 🎮 Portal Game Pembelajaran Matematika Interaktif (Web & Cloud Assessment)

Repository ini berisi kumpulan media pembelajaran matematika interaktif berbasis web (**HTML5, CSS3, dan ES6 Vanilla JavaScript**) yang dirancang khusus sebagai materi inti Pelatihan & Workshop Pembelajaran Matematika di Jurusan Matematika FMIPA Universitas Negeri Makassar (UNM).

Proyek ini merupakan bentuk **modernisasi & migrasi teknologi** dari media *legacy* berbasis **Macromedia Flash MX 2004 / ActionScript 2.0** ke standar teknologi web modern yang *open-standard*, ringan, *cross-platform* (dapat dimainkan di PC, laptop, maupun HP), serta dilengkapi integrasi rekap nilai otomatis secara *real-time* ke **Google Spreadsheet**.

---

## 🚀 Fitur Utama & Modul Game

### 1. 🟢 Matrix Blitz Arena (`mba.html`)
- **Topik:** Matriks $2 \times 2$ (Determinan, Trace Matriks, dan Kesamaan Matriks Aljabar).
- **Mekanisme:** Mode tantangan berpacu dengan *timer countdown* 15 detik per soal.
- **Fitur Khusus:** Evaluasi langkah pengerjaan otomatis dan pemberian piagam gelar digital (*Matrix Master*, *Matrix Warrior*, dll).

### 2. 🔴 X-Terminator: CoC Edition (`xterminator.html`)
- **Topik:** Sistem Persamaan Linear Tiga Variabel (SPLTV).
- **Mekanisme:** Misi intelijen 3 babak ala *Clash of Champions*:
  - **Babak 1:** Penentuan pengali $k_1$ dan $k_2$ untuk mengeliminasi variabel $x$.
  - **Babak 2:** Pembongkaran nilai variabel $z$.
  - **Babak 3:** Substitusi final untuk menentukan nilai $x$ dan $y$.
- **Fitur Khusus:** Laporan intelijen langkah demi langkah di akhir game.

### 3. 🟡 Flip Ratio: 6 Level Challenge (`flipratio.html`)
- **Topik:** Perbandingan Senilai (Level 1–3) dan Perbandingan Berbalik Nilai (Level 4–6).
- **Mekanisme:** Analisis perubahan kuantitas dengan *timer countdown* 20 detik per level.
- **Fitur Khusus:** Generator angka acak dengan rumus presisi untuk menjamin hasil perhitungan selalu bilangan bulat.

### 4. 📊 Cloud Assessment Sync (Google Apps Script API)
- Setiap kali pemain menyelesaikan permainan, data rekap meliputi:
  - **Timestamp / Waktu Pengerjaan**
  - **Nama Pemain**
  - **Tingkat / Peran** (*Guru, Dosen/Mahasiswa, 7-9 SMP, 10-12 SMA*)
  - **Nama Sekolah / Instansi**
  - **Mode Game & Skor Akhir**
  - **Gelar Digital**
  akan secara otomatis dikirimkan via **Fetch API (POST)** ke **Google Spreadsheet** guru/dosen secara *real-time*.

---

## 🛠️ Arsitektur & Teknologi

- **Frontend:** HTML5, CSS3 (Flexbox & Grid), JavaScript Vanilla (ES6 Async/Fetch, State Lock).
- **Backend / Assessment Endpoint:** Google Apps Script (Web App API).
- **Database / Assessment Cloud:** Google Sheets.
- **Deployment:** GitHub Pages & Custom Domain ([game.kakalif.my.id](https://game.kakalif.my.id)).

---

## 📖 Cara Penggunaan & Testing

1. Buka portal utama via browser: [https://game.kakalif.my.id](https://game.kakalif.my.id)
2. Pilih salah satu modul game (*Matrix Blitz Arena*, *X-Terminator*, atau *Flip Ratio*).
3. Isi data identitas (Nama, Tingkat/Peran, dan Sekolah/Instansi).
4. Selesaikan semua babak/soal hingga layar **Penghargaan Selesai / Game Over** muncul.
5. Cek Google Spreadsheet rekap nilai untuk melihat data yang baru saja terkirim secara otomatis!

---

## 👤 Penyusun & Pemateri Workshop

**Alif Rezky, M.Pd.**  
*Pendidik & Pengembang Media Pembelajaran Matematika*  
- **Website Resmi:** [kakalif.my.id](https://kakalif.my.id)  
- **YouTube Channel:** [@kakalifgurumatematika](https://youtube.com/@kakalifgurumatematika)  
- **Pelaksanaan:** Sabtu, 25 Juli 2026 | Jurusan Matematika FMIPA Universitas Negeri Makassar  

---
*Disusun untuk kemajuan media pembelajaran matematika Indonesia berbasis teknologi web terbuka & legal.*
