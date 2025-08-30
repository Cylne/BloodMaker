# 🪨 Blood Maker by CYLNE PROJECT v1

![BloodMaker](https://img.shields.io/badge/Game-BloodStrike-red?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Termux%20%7C%20Linux%20%7C%20Windows-green?style=for-the-badge)



## 📖 Deskripsi

**Blood Maker by CYLNE PROJECT v1** adalah tools berbasis Python untuk **membongkar, membaca, dan mengedit file konfigurasi `.bin` (Graphics.bin) dari game BloodStrike**.
Dengan tools ini kamu bisa dengan mudah:

* Membaca value pada offset file bin (FrameLimit, VSync, ShadowMapSize, dll)
* Mengubah value secara manual (`set FrameLimit 144`)
* Menerapkan preset otomatis (Ultra / Low / Competitive)
* Menyimpan hasil modifikasi ke file baru

Didesain dengan **tampilan elegan (CLI + Rich)** sehingga nyaman digunakan di **Termux, Linux, maupun Windows**.



## ⚙️ Fitur

* 🗂️ **Parser** otomatis untuk key penting (`FrameLimit`, `VSync`, `ShadowMapSize`, dll)
* 🎮 **Preset Gaming** → Ultra / Low / Competitive
* 📝 **Edit Manual** → bebas ubah key sesuai kebutuhan
* 💾 **Export File** → simpan hasil modifikasi `.bin`
* 🌍 **Cross Platform** → bisa di Termux (Android), Linux, dan Windows



## 🛠️ Tech Stack

* **Python 3.x**
* [Rich](https://github.com/Textualize/rich) → tampilan CLI modern dan elegan



## 📲 Instalasi

### Termux / Linux

```bash
pkg install python git -y
pip install rich
git clone https://github.com/Cylne/BloodMaker
cd BloodMaker
```

### Windows

1. Install [Python 3](https://www.python.org/downloads/)
2. Install library:

   ```bash
   pip install rich
   ```
3. Clone repository:

   ```bash
   git clone https://github.com/USERNAME/BloodMaker
   cd BloodMaker
   ```



## ▶️ Menjalankan Tools

```bash
python blood_maker.py
```

Lalu ikuti menu yang tersedia:

```
Menu Options:
 1 - Lihat Config
 2 - Ubah Value Manual
 3 - Terapkan Preset
 4 - Simpan File
 5 - Simpan Semua Preset (Ultra, Low, Competitive)
 6 - Keluar
```



## 📷 Tampilan

> Tampilan di Termux:

![Screenshot](https://i.ibb.co/0h4W27K/termux-preview.png)
*(Tambahkan screenshot hasil run di Termux/PC kalian di sini)*



## 👑 Credits

* Tools : **Blood Maker v1**
* Author : **CYLNE PROJECT**
* Telegram Channel : [t.me/Cylneee](https://t.me/Cylneee)



## ⚠️ Disclaimer

Tools ini dibuat hanya untuk **keperluan edukasi & modifikasi pribadi**.
Segala bentuk penyalahgunaan di luar tanggung jawab developer.
