# WordPress Bruteforce Tool

![WPBrute](https://img.shields.io/badge/WPBrute-WordPress%20Bruteforce-red)
![Python](https://img.shields.io/badge/Python-3.x-blue)

WordPress Bruteforce adalah alat untuk melakukan brute force pada sistem login WordPress. Tool ini dikembangkan oleh ToSoon Squad untuk tujuan pengujian keamanan dan penetrasi.

## ⚠️ Peringatan

Tool ini hanya boleh digunakan untuk:
- Pengujian keamanan pada sistem yang Anda miliki
- Tujuan pendidikan dan pembelajaran
- Penetrasi testing yang sah

Penggunaan tool ini untuk aktivitas ilegal atau tanpa izin adalah tanggung jawab pengguna sepenuhnya.

## 🚀 Fitur

- Pencarian username otomatis melalui WordPress REST API
- Fallback ke metode alternatif jika API tidak tersedia
- Logging detail untuk debugging
- Mendukung multiple username

## 📋 Persyaratan

- Python 3.x

## 🛠️ Instalasi

1. Clone repository ini:
```bash
git clone git@github.com:Expuz66/WordPress-BruteForce-Expuz.git
cd WordPress-BruteForce-Expuz
```

2. Install dependencies:
```bash
pip install requests
```

## 💻 Penggunaan

1. Jalankan script:
```bash
python3 wpbrute.py
```

2. Masukkan URL target WordPress (contoh: https://example.com)
3. Masukkan path ke file wordlist password
4. Pilih username dari daftar yang ditemukan
5. Tunggu proses brute force selesai

## 📝 Contoh Penggunaan

```bash
$ python3 wpbrute.py
Masukkan URL target (contoh: https://example.com): https://example.com
Masukkan path file password list: wordlist.txt
```

## 🔍 Cara Kerja

1. Script akan mencari username yang tersedia di target WordPress
2. Menampilkan daftar username yang ditemukan
3. User memilih username yang akan digunakan
4. Melakukan brute force dengan wordlist yang diberikan
5. Menampilkan hasil proses brute force

## ⚡ Disclaimer

Tool ini dibuat untuk tujuan pendidikan dan pengujian keamanan. Penulis tidak bertanggung jawab atas penyalahgunaan tool ini. 
