<div align="center">

# 🌿 TANI-SCAN

### Deteksi Penyakit Tanaman Lewat Foto Daun, Cepat dan Berbasis AI

![Status](https://img.shields.io/badge/status-aktif-brightgreen?style=for-the-badge)
![Platform](https://img.shields.io/badge/platform-web-blue?style=for-the-badge)
![AI Powered](https://img.shields.io/badge/AI-powered-orange?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-lightgrey?style=for-the-badge)

<!-- Ganti dengan logo / banner proyek kalian -->
<img src="docs/banner.png" alt="Banner TANI-SCAN" width="85%">

[🚀 Demo](#-demo) · [✨ Fitur](#-fitur-utama) · [⚙️ Instalasi](#️-instalasi) · [👥 Tim](#-tim-pengembang)

</div>

---

## 📖 Tentang Proyek

**TANI-SCAN** adalah aplikasi berbasis web yang memanfaatkan teknologi **Artificial Intelligence (AI)** untuk mendeteksi kemungkinan penyakit tanaman melalui gambar daun.

Petani cukup **mengunggah foto daun**, lalu sistem akan menganalisis gambar dan menampilkan **dugaan jenis penyakit**, **tingkat keyakinan**, serta **saran penanganan awal**. Dengan begitu, penyakit tanaman dapat dikenali lebih dini sebelum menyebar dan merugikan hasil panen.

> ⚠️ **Catatan:** Hasil deteksi bersifat prediksi awal. Untuk penanganan lebih lanjut, tetap konsultasikan dengan penyuluh pertanian atau ahli agronomi.

---

## 🎯 Latar Belakang

- 🌾 Penyakit tanaman adalah salah satu penyebab utama menurunnya hasil panen.
- 👨‍🌾 Tidak semua petani mudah mengakses pakar untuk mendiagnosis penyakit.
- ⏱️ Keterlambatan identifikasi membuat penyakit cepat menyebar.
- 📱 TANI-SCAN hadir sebagai solusi yang praktis, cepat, dan mudah diakses lewat browser.

---

## ✨ Fitur Utama

| Fitur | Deskripsi |
|-------|-----------|
| 📸 **Unggah Gambar Daun** | Upload foto dari galeri atau ambil langsung lewat kamera |
| 🤖 **Deteksi Berbasis AI** | Model AI menganalisis pola dan gejala pada daun |
| 📊 **Tingkat Keyakinan** | Menampilkan persentase akurasi dari setiap prediksi |
| 💊 **Saran Penanganan** | Rekomendasi tindakan awal untuk setiap penyakit |
| 🕘 **Riwayat Pemindaian** | Simpan hasil scan sebelumnya untuk dipantau |
| 🌐 **Berbasis Web** | Tanpa instal, cukup buka lewat browser |

---

## 🔄 Cara Kerja

```
📷 Unggah Foto Daun
        ↓
🧹 Pra-pemrosesan Gambar
        ↓
🧠 Analisis Model AI
        ↓
📋 Hasil: Penyakit + Tingkat Keyakinan + Saran Penanganan
```

---

## 🖼️ Demo

<!-- Ganti dengan screenshot aplikasi kalian -->
| Halaman Beranda | Hasil Deteksi |
|:---:|:---:|
| ![Beranda](docs/screenshot-home.png) | ![Hasil](docs/screenshot-result.png) |

🔗 **Live Demo:** [tani-scan.example.com](https://tani-scan.example.com)

---

## 🛠️ Teknologi yang Digunakan

> Sesuaikan dengan teknologi yang dipakai kelompok kalian.

| Kategori | Teknologi |
|----------|-----------|
| **Frontend** | HTML, CSS, JavaScript |
| **Backend** | Python (Flask) |
| **Model AI** | TensorFlow / Keras (CNN) |
| **Dataset** | PlantVillage |
| **Deployment** | Vercel / Render / Hugging Face Spaces |

---

## ⚙️ Instalasi

### Prasyarat
- Python 3.9+
- pip
- Git

### Langkah-langkah

```bash
# 1. Clone repositori
git clone https://github.com/username/tani-scan.git

# 2. Masuk ke folder proyek
cd tani-scan

# 3. (Opsional) Buat virtual environment
python -m venv venv
source venv/bin/activate      # Linux/Mac
venv\Scripts\activate         # Windows

# 4. Instal dependensi
pip install -r requirements.txt

# 5. Jalankan aplikasi
python app.py
```

Buka browser dan akses **http://localhost:5000** 🎉

---

## 📁 Struktur Proyek

```
tani-scan/
├── app.py                # Aplikasi utama
├── model/                # Model AI terlatih
├── static/               # CSS, JS, dan gambar
├── templates/            # Halaman HTML
├── docs/                 # Dokumentasi & screenshot
├── requirements.txt      # Daftar dependensi
└── README.md
```

---

## 🌱 Penyakit yang Dapat Dideteksi

- 🍅 Tomat: Bercak daun, hawar daun, virus keriting
- 🥔 Kentang: Hawar awal, hawar akhir
- 🌽 Jagung: Karat daun, bercak daun
- 🌶️ Cabai: Bercak bakteri
- ✅ Daun sehat

> *Daftar dapat disesuaikan dengan cakupan model kalian.*

---

## 🗺️ Rencana Pengembangan

- [x] Deteksi penyakit dari foto daun
- [x] Tampilan web responsif
- [ ] Penambahan jenis tanaman dan penyakit
- [ ] Rekomendasi obat dan pestisida organik
- [ ] Dukungan bahasa daerah
- [ ] Versi aplikasi mobile

---

## 👥 Tim Pengembang

| Foto | Nama | Peran |
|:---:|------|-------|
| <img src="https://github.com/username1.png" width="60"> | **Nama Anggota 1** | Project Manager / AI Engineer |
| <img src="https://github.com/username2.png" width="60"> | **Nama Anggota 2** | Frontend Developer |
| <img src="https://github.com/username3.png" width="60"> | **Nama Anggota 3** | Backend Developer |
| <img src="https://github.com/username4.png" width="60"> | **Nama Anggota 4** | UI/UX Designer |

---

## 🤝 Kontribusi

Kontribusi sangat terbuka!

1. Fork repositori ini
2. Buat branch baru (`git checkout -b fitur/nama-fitur`)
3. Commit perubahan (`git commit -m "Menambahkan fitur ..."`)
4. Push ke branch (`git push origin fitur/nama-fitur`)
5. Buka Pull Request

---

## 📄 Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE).

---

<div align="center">

**🌾 TANI-SCAN, teknologi untuk petani Indonesia 🇮🇩**

Jika proyek ini bermanfaat, jangan lupa beri ⭐ pada repositori ini!

</div>
