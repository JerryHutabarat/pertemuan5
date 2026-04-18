# 🛡️ Mission: The Secure Guard

<div align="center">

![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Gerbang masuk yang anti-tembus data sampah dan ramah jempol user.**

</div>

---

## 📱 Preview Aplikasi

> ⚠️ **Ganti bagian ini dengan screenshot atau GIF running program kamu!**

| Login Screen | Register Screen | Home Screen |
|:---:|:---:|:---:|
<img width="270" height="1057" alt="Screenshot home" src="https://github.com/user-attachments/assets/8ae693a0-4e0b-439a-81ca-2d1c807d9beb" />
<img width="494" height="1280" alt="Screenshot register3" src="https://github.com/user-attachments/assets/9fd433e4-7051-49a3-86da-c612db1373ac" />
<img width="497" height="1280" alt="Screenshot login" src="https://github.com/user-attachments/assets/b67090d4-17c0-4779-aa95-f1088d36c8d7" />


## 🔗 Link Demo

| Platform | Link |
|---|---|
| 🚀 **Expo Snack (Test Langsung)** | [▶️ Buka di Expo Snack](https://snack.expo.dev/) |
| 💻 **GitHub Repository** | [Repo ini](https://github.com/JerryHutabarat/pertemuan5.git) |

> ⚠️ **Ganti link Expo Snack:** Buka [snack.expo.dev](https://snack.expo.dev), paste kode kamu, lalu copy link-nya ke sini.

---

## 📋 Fitur Aplikasi

### Screen 1 — Login
- Input **Email** dengan validasi format (RegEx)
- Input **Password** yang tersembunyi
- Tombol **"Masuk"** untuk autentikasi
- Link **"Daftar Disini"** untuk navigasi ke Register

### Screen 2 — Register
- Input **Nama Lengkap**
- Input **Email** dengan validasi format
- Input **Nomor Telepon** — hanya angka, minimal 10 digit
- Input **Password** tersembunyi
- Input **Konfirmasi Password** — harus cocok dengan Password
- Handle keyboard agar tidak menutupi tombol Submit

### Screen 3 — Home
- Menampilkan **Welcome Message** dengan nama user yang telah mendaftar
- Tombol Logout untuk kembali ke halaman Login

---

## 🛡️ Security Logic

```
✅ Validasi Email     → RegEx: /^[^\s@]+@[^\s@]+\.[^\s@]+$/
✅ Validasi Phone     → Hanya angka, minimal 10 digit
✅ Password Match     → Confirm Password harus identik
✅ Empty Field Check  → Semua field wajib diisi
✅ Keyboard Handling  → KeyboardAvoidingView agar tombol tidak tertutup
```

---

## 🚀 Cara Menjalankan Proyek

### Prasyarat
- Node.js (v18 atau lebih baru)
- npm atau yarn
- Expo CLI (`npm install -g expo-cli`)
- Expo Go app di HP (Android/iOS)

### Langkah Instalasi

```bash
# 1. Clone repository ini
git clone https://github.com/USERNAME/REPO_NAME.git

# 2. Masuk ke folder project
cd REPO_NAME

# 3. Install dependencies
npm install

# 4. Jalankan aplikasi
npx expo start
```

### Menjalankan di Device
Setelah `npx expo start` berhasil:
- **Android**: Scan QR code dengan aplikasi **Expo Go**
- **iOS**: Scan QR code dengan **kamera bawaan** HP
- **Emulator Android**: Tekan `a` di terminal
- **Simulator iOS**: Tekan `i` di terminal

---

## 📁 Struktur Proyek

```
📦 secure-guard/
├── 📄 App.js                  # Entry point & navigasi utama
├── 📁 screens/
│   ├── 📄 LoginScreen.js      # Screen 1: Login
│   ├── 📄 RegisterScreen.js   # Screen 2: Register
│   └── 📄 HomeScreen.js       # Screen 3: Welcome
├── 📁 assets/
│   └── 📁 screenshots/        # Screenshot untuk README
├── 📄 package.json
└── 📄 README.md
```

---

## 🧠 Teknologi yang Digunakan

| Teknologi | Kegunaan |
|---|---|
| **React Native** | Framework utama aplikasi mobile |
| **Expo** | Platform pengembangan & build |
| **React Navigation** | Navigasi antar screen |
| **KeyboardAvoidingView** | Mencegah keyboard menutupi input |
| **RegEx** | Validasi format email |
| **useState / useEffect** | State management |

---

## 👨‍💻 Developer

**Nama:** [Benedick Jerry Alfa Hutabarat]  
**NIM:** [243303621281]  
**Kelas:** [4pagiB SI]  

---
