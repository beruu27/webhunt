
---

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Maintained](https://img.shields.io/badge/Maintained-yes-brightgreen)

# 🕷️ WebHunt — Recon & Bruteforce Toolkit

> **WebHunt** adalah toolkit all-in-one untuk rekonsai, scanning kerentanan, dan bruteforce berbasis Python.  
> Dirancang untuk keperluan *ethical hacking*, *pentesting*, dan *cybersec lab simulation*.

---

## 🧩 Fitur Utama

| Modul               | Keterangan                                                                 |
|---------------------|----------------------------------------------------------------------------|
| 🔎 Endpoint Scanner | Scan endpoint tersembunyi/sensitif pada target                             |
| 💉 SQLi & XSS Test  | Fuzz semua parameter untuk XSS/SQLi/LFI                                    |
| 🧪 XSS Recon Full   | Crawler otomatis + vector injection tester                                 |
| 🔐 WP Bruteforce    | Login brute ke `/wp-login.php` dengan `combo.txt`                          |
| 🎯 Combo Generator  | Buat wordlist dari kata Bahasa Indonesia + angka/simbol + huruf acak       |
| 🛠️ cPanel Bruteforce (opsional) | Brute HTTP Basic Auth ke `https://cpanel.domain.tld`                      |

---
## 📦 Tools Eksternal yang Dibutuhkan (Manual Install)

Beberapa fitur di WebHunt menggunakan tool pihak ketiga.  
Silakan install secara manual sebelum menjalankan script.

| Tool      | Fungsi                      | Cara Install                           |
|-----------|-----------------------------|----------------------------------------|
| `nmap`    | Port scanning               | `sudo apt install nmap`               |
| `sqlmap`  | SQLi automated test         | `sudo apt install sqlmap` atau `git clone https://github.com/sqlmapproject/sqlmap` |
| `nikto`   | Web vulnerability scanner   | `sudo apt install nikto`              |
| `xsstrike`| XSS fuzzing tool            | `git clone https://github.com/s0md3v/XSStrike` |


## ⚙️ Instalasi

### 🔗 Clone Repo
```
git clone https://github.com/beruu27/webhunt.git
cd webhunt
python webhunt.py
```

## More Info You can contact me on Instagram
https://instagram.com/rstuuramadhan
