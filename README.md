<div align="center">

# 📣 LaporTuntas

**Laporkan sekali, kami kawal sampai tuntas.**

Desain UI/UX platform pelaporan masalah publik untuk lomba **TI Fest UI/UX**.

[![Figma](https://img.shields.io/badge/Lihat_di_Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com/design/a6lz0VgPHgNkzdXfp7TQCf/TI-Fest-UIUX---LaporTuntas?node-id=0-1)
![Layar](https://img.shields.io/badge/34_layar-1E4FD8?style=for-the-badge)
![Desktop & Mobile](https://img.shields.io/badge/Desktop_%26_Mobile-0F172A?style=for-the-badge)

<img src="screens/A-halaman-utama/01-beranda.png" alt="Beranda LaporTuntas" width="100%" />

</div>

---

## 💡 Tentang LaporTuntas

Jalan rusak, sampah menumpuk, atau lampu jalan mati sering tidak tertangani karena warga bingung harus melapor ke mana, dan laporan yang sudah masuk jarang ada kabarnya. **LaporTuntas** menyelesaikan dua masalah itu:

- **Satu pintu ke dinas yang tepat.** Warga cukup menceritakan masalahnya. Laporan diteruskan otomatis ke dinas yang bertanggung jawab berdasarkan kategori dan lokasi.
- **Status yang transparan.** Setiap laporan punya nomor dan linimasa: diterima → diteruskan → diverifikasi → diperbaiki → selesai dengan foto bukti.
- **Dikawal sampai tuntas.** Jika tidak ada perkembangan dalam 7 hari, laporan otomatis dinaikkan ke kepala dinas (eskalasi).
- **Kekuatan bersama.** Warga bisa melihat laporan di sekitarnya dan memberi dukungan agar laporan yang sama lebih cepat ditangani, tanpa membuat laporan ganda.

## 🧭 Alur Utama Pengguna

```
Beranda → Form Laporan → Pilih Lokasi → Ringkasan & Dinas Tujuan
       → Verifikasi Nomor HP → Laporan Terkirim → Lacak Status → Laporan Selesai
```

## 🎨 Design System

| Token | Nilai |
|---|---|
| Font | **Plus Jakarta Sans** (Regular, Medium, Bold, ExtraBold) |
| Primary | ![#1E4FD8](https://img.shields.io/badge/-%231E4FD8-1E4FD8?style=flat-square) `#1E4FD8` · Dark `#163BA6` · Soft `#EAF0FF` |
| Teks | `#0F172A` · Muted `#475569` · Placeholder `#94A3B8` |
| Status | ![Sukses](https://img.shields.io/badge/-Sukses-15803D?style=flat-square) `#15803D` · ![Peringatan](https://img.shields.io/badge/-Peringatan-B45309?style=flat-square) `#B45309` · ![Error](https://img.shields.io/badge/-Error-C81E1E?style=flat-square) `#C81E1E` |
| Latar | Halaman `#F8FAFC` · Permukaan `#FFFFFF` · Border `#E2E8F0` |

Token siap pakai tersedia di [`design-tokens/tokens.css`](design-tokens/tokens.css) dan [`design-tokens/tokens.json`](design-tokens/tokens.json).

<details>
<summary><b>Lihat Design System lengkap</b></summary>
<br />
<img src="design-system/design-system.png" alt="Design System LaporTuntas" width="100%" />
</details>

---

## 🖼️ Galeri Layar

### A. Halaman Utama

| | |
|:-:|:-:|
| <img src="screens/A-halaman-utama/01-beranda.png" width="100%" /><br/>**01** Beranda | <img src="screens/A-halaman-utama/02-form-laporan.png" width="100%" /><br/>**02** Form Laporan |
| <img src="screens/A-halaman-utama/03-pilih-lokasi.png" width="100%" /><br/>**03** Pilih Lokasi | <img src="screens/A-halaman-utama/04-ringkasan-dan-dinas-tujuan.png" width="100%" /><br/>**04** Ringkasan & Dinas Tujuan |
| <img src="screens/A-halaman-utama/05-verifikasi-nomor-hp-pop-up.png" width="100%" /><br/>**05** Verifikasi Nomor HP | <img src="screens/A-halaman-utama/06-laporan-terkirim.png" width="100%" /><br/>**06** Laporan Terkirim |
| <img src="screens/A-halaman-utama/07-detail-dan-lacak-status.png" width="100%" /><br/>**07** Detail & Lacak Status | <img src="screens/A-halaman-utama/08-laporan-selesai.png" width="100%" /><br/>**08** Laporan Selesai |

### B. Halaman Pendukung

| | |
|:-:|:-:|
| <img src="screens/B-halaman-pendukung/09-daftar-laporan-saya.png" width="100%" /><br/>**09** Daftar Laporan Saya | <img src="screens/B-halaman-pendukung/10-laporan-di-sekitar-saya.png" width="100%" /><br/>**10** Laporan di Sekitar Saya |

### C. Kondisi Khusus

| | |
|:-:|:-:|
| <img src="screens/C-kondisi-khusus/11-error-form-belum-lengkap.png" width="100%" /><br/>**11** Error: Form Belum Lengkap | <img src="screens/C-kondisi-khusus/12-error-foto-gagal-terunggah.png" width="100%" /><br/>**12** Error: Foto Gagal Terunggah |
| <img src="screens/C-kondisi-khusus/13-error-lokasi-tidak-ditemukan.png" width="100%" /><br/>**13** Error: Lokasi Tidak Ditemukan | <img src="screens/C-kondisi-khusus/14-koneksi-terputus.png" width="100%" /><br/>**14** Koneksi Terputus |
| <img src="screens/C-kondisi-khusus/15-laporan-serupa-ditemukan.png" width="100%" /><br/>**15** Laporan Serupa Ditemukan | <img src="screens/C-kondisi-khusus/16-error-kode-otp-salah.png" width="100%" /><br/>**16** Error: Kode OTP Salah |
| <img src="screens/C-kondisi-khusus/17-kosong-belum-ada-laporan.png" width="100%" /><br/>**17** Kosong: Belum Ada Laporan | <img src="screens/C-kondisi-khusus/18-notifikasi-eskalasi.png" width="100%" /><br/>**18** Notifikasi Eskalasi |

### D. Halaman Tambahan

| | |
|:-:|:-:|
| <img src="screens/D-halaman-tambahan/19-lacak-dengan-nomor-laporan.png" width="100%" /><br/>**19** Lacak dengan Nomor Laporan | <img src="screens/D-halaman-tambahan/20-bantuan-dan-faq.png" width="100%" /><br/>**20** Bantuan & FAQ |
| <img src="screens/D-halaman-tambahan/21-pengaturan-aksesibilitas.png" width="100%" /><br/>**21** Pengaturan Aksesibilitas | <img src="screens/D-halaman-tambahan/22-laporan-dibuka-kembali.png" width="100%" /><br/>**22** Laporan Dibuka Kembali |
| <img src="screens/D-halaman-tambahan/23-penilaian-terkirim.png" width="100%" /><br/>**23** Penilaian Terkirim | <img src="screens/E-mobile-dan-loading/24-loading-laporan-saya.png" width="100%" /><br/>**24** Loading: Laporan Saya |

### E. Mobile

| | | |
|:-:|:-:|:-:|
| <img src="screens/E-mobile-dan-loading/m1-beranda-mobile.png" width="100%" /><br/>**M1** Beranda | <img src="screens/E-mobile-dan-loading/m2-form-laporan-mobile.png" width="100%" /><br/>**M2** Form Laporan | <img src="screens/E-mobile-dan-loading/m3-lacak-status-mobile.png" width="100%" /><br/>**M3** Lacak Status |

### F. Overlay (Prototipe)

| | |
|:-:|:-:|
| <img src="screens/F-overlay/ov-verifikasi-nomor-hp.png" width="100%" /><br/>Verifikasi Nomor HP | <img src="screens/F-overlay/ov-kode-otp-salah.png" width="100%" /><br/>Kode OTP Salah |
| <img src="screens/F-overlay/ov-laporan-serupa.png" width="100%" /><br/>Laporan Serupa | <img src="screens/F-overlay/ov-notifikasi.png" width="100%" /><br/>Notifikasi |

---

## 📁 Struktur Repo

```
.
├── screens/
│   ├── A-halaman-utama/       # 8 layar alur utama pelaporan
│   ├── B-halaman-pendukung/   # daftar laporan & laporan sekitar
│   ├── C-kondisi-khusus/      # error, kosong, koneksi, eskalasi
│   ├── D-halaman-tambahan/    # lacak, FAQ, aksesibilitas, penilaian
│   ├── E-mobile-dan-loading/  # versi mobile & state loading
│   └── F-overlay/             # pop-up untuk prototipe
├── design-system/             # design system & komponen navbar
└── design-tokens/             # tokens.css & tokens.json
```

<div align="center">
<sub>Desain dibuat di Figma · Repo oleh <a href="https://github.com/NahwaKakaa">@NahwaKakaa</a></sub>
</div>
