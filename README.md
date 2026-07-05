# 📦 Pul's Personal Module Collection

Selamat datang di repository pribadi gue! Repository ini berfungsi sebagai tempat penyimpanan digital sekaligus arsip personal untuk berbagai modul Android (Magisk/KSU) yang gue gunakan untuk optimasi, tweaking sistem, dan kebutuhan harian. 

> **⚠️ PENTING (BACA SEBELUM FLUSH):** 
> Perlu dicatat bahwa **ALL INTEGRITY MODULE IS DEPRECATED**. 
> Jangan gunakan modul integritas lama yang ada di sini untuk melewati Safetynet/Play Integrity terbaru. Silakan gunakan [Kaorios Toolbox by Wuang26](https://github.com/Wuang26/Kaorios-Toolbox) sebagai gantinya.

---

## 🚀 Fitur & Tujuan Repository
* **Personal Archive:** Menyimpan modul-modul andalan secara terpusat agar mudah di-download kapan saja setelah clean flash ROM.
* **Daily Driven Tweaks:** Fokus pada modul yang meningkatkan performa gaming, kualitas audio, dan kustomisasi sistem tanpa merusak stabilitas harian.
* **Pre-Tested Files:** Semua file yang ada di sini sudah melewati uji coba personal untuk meminimalisir risiko kegagalan sistem.

---

## 📱 Current Device & Configuration

Biar gak salah paham saat instalasi, seluruh modul yang aktif di repository ini ditest dan berjalan lancar pada *daily driver* gue dengan konfigurasi berikut:

* **Device:** Redmi Note 8 Pro (6/128)
* **ROM:** HyperOS 2.0.200.0.UGGCNXM Port
* **Root Manager:** ReSukiSU (WildKSU)
* **Kernel:** Suzaku Kernel (Default)
* **Active Environment:** LSPosed, Zygisk Next, YT Morphe

---

## 📋 Prasyarat Sebelum Menggunakan
Sebelum lo mencoba flash modul apa pun dari repo ini, pastikan device lo sudah memenuhi kriteria dasar berikut:
1. **Ter-root** menggunakan Magisk, KernelSU, atau APatch (sesuaikan dengan kompatibilitas modul).
2. Memiliki **Custom Recovery** (TWRP / OrangeFox) versi terbaru yang terinstall.
3. Selalu lakukan **Backup Data** penting sebelum melakukan flashing sistem.

---

## 🛠️ Panduan Penanganan Masalah (Troubleshooting)

Jika lo mengalami masalah seperti *bootloop* setelah memasang salah satu modul, jangan panik. Ikuti langkah-langkah penyelamatan ini:

### 1. Menggunakan Safe Mode
* Matikan device, lalu nyalakan kembali.
* Saat animasi boot (bootanimation) muncul, tekan dan tahan tombol **Volume Down** sampai masuk ke homescreen.
* Sistem secara otomatis akan menonaktifkan seluruh modul Magisk/KSU. Lo tinggal uninstall modul yang bermasalah.

### 2. Melalui Custom Recovery (TWRP/OrangeFox)
* Boot ke recovery mode (Tahan tombol **Power + Volume Up**).
* Masuk ke File Manager bawaan recovery.
* Buka direktori `/data/adb/modules/`.
* Cari folder modul yang baru saja lo install dan hapus folder tersebut.
* Reboot system.

---

## 🚨 Disclaimer
* **Do With Your Own Risk (DWYOR).** Gue gak bertanggung jawab atas kerusakan *hardware*, *bootloop*, *brick*, kehilangan data, atau alarm subuh lo gak bunyi akibat penggunaan modul di repo ini.
* Pastikan lo paham cara kerja sistem Android modding sebelum melakukan eksekusi.
