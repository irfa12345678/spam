# ✉️ SC Email

![SC Email Badge](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge) ![Node.js](https://img.shields.io/badge/Node.js-v18-brightgreen?style=for-the-badge) ![Vercel](https://img.shields.io/badge/Deploy-Vercel-blue?style=for-the-badge)

SC Email adalah **tool modern untuk mengirim email otomatis** menggunakan akun Gmail.  
Dirancang agar mudah digunakan, bisa di-deploy di **Vercel**, dan siap dijalankan di **HP Redmi** melalui Termux.  
Tool ini cocok untuk **testing email**, **broadcast**, atau **mengelola banyak akun email**.

---

## 🌟 Fitur Utama
| Fitur | Fungsi |
|-------|--------|
| Kirim Email | Mengirim email satu per satu atau massal |
| Multi-Akun | Bisa menggunakan beberapa akun Gmail secara bergantian |
| Usage Count | Mencatat jumlah email yang sudah dikirim oleh tiap akun |
| Deploy | Siap dijalankan di Termux HP Redmi atau di Vercel |
| Endpoint API | Bisa diakses melalui browser/Postman untuk integrasi lain |

---

## 📱 Cara Install & Pakai di HP Redmi (Lengkap)

### 1️⃣ Install Termux
- Buka **Play Store**, cari **Termux**, lalu install  
- Termux adalah terminal Linux di Android yang memungkinkan kamu menjalankan Node.js dan Git

### 2️⃣ Update & Install Node.js
Buka Termux, jalankan:

```bash
pkg update && pkg upgrade -y
pkg install nodejs git -y
