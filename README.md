# 🐤 Flappy Bird - HTML5 Responsive & Multilingual Game

<p align="center">
  <b>Bahasa Indonesia</b> | 
  <a href="#-english">English</a>
</p>

---

## 📢 Disclaimer / Penafian

* **🇮🇩 Bahasa Indonesia:** Proyek ini adalah rekreasi independen (fan-made clone) berbasis web yang dibuat hanya untuk tujuan edukasi dan portofolio. Proyek ini **BUKAN** game resmi Flappy Bird® dan tidak memiliki afiliasi, hubungan, atau dukungan resmi dari pencipta aslinya (**Dong Nguyen**) maupun **.GEARS Studios**. Seluruh hak cipta dan merek dagang dari konsep game asli tetap dimiliki oleh pemilik resminya.
 
* **🇬🇧 English:** This project is an independent,web-based fan-made recreation built solely for educational and portfolio purposes. This is **NOT** the official Flappy Bird® game and is not affiliated with, endorsed by, or connected to the original creator (**Dong Nguyen**) or **.GEARS Studios**. All trademarks and copyrights of the original game concept belong to their respective owners.

---

## 🇮🇩 Bahasa Indonesia

Proyek ini adalah rekreasi game **Flappy Bird** berbasis web yang dibuat menggunakan **HTML5 Canvas**, **CSS3**, dan **JavaScript murni (Vanilla JS)** tanpa *framework*. 

Game ini responsif di Desktop dan Mobile, serta dilengkapi sistem pengubah bahasa bawaan.

### ✨ Fitur Utama
* 📱 **Desain Fully Responsive:** Tampilan menyesuaikan otomatis (Frame HP Retro untuk Desktop & Layar Penuh untuk Mobile).
* 🌐 **Dukungan Multi-Bahasa (ID/EN):** Tombol ganti bahasa antarmuka secara instan.
* 🎨 **Tema Dinamis:** Latar belakang (Siang/Malam) dan warna burung (Kuning, Merah, Biru) diacak setiap *restart*.
* 🎯 **Scoring Akurat:** Poin bertambah tepat saat burung memasuki area pipa.
* 🔊 **Audio & Efek Suara Asli:** Dilengkapi efek suara retro (*flap, point, hit, die, swoosh*).

### ⚠️ Catatan Penting (Kenapa Gambar/Tekstur Hilang?)
Jika file `index.html` dibuka langsung dengan cara *double-click* (`file://`), browser akan memblokir gambar/audio karena kebijakan keamanan **CORS**. Game harus dijalankan menggunakan **Local Server**.

### 🚀 Cara Menjalankan Offline (Pilih Salah Satu)

#### Cara 1: Menggunakan VS Code (Paling Mudah)
1. Buka folder proyek di **VS Code**.
2. Install ekstensi **Live Server**.
3. Klik kanan pada file `index.html` -> pilih **"Open with Live Server"**.

#### Cara 2: Menggunakan Python (Tanpa Install Aplikasi Tambahan)
Jika komputer kamu sudah ada Python:
1. Buka terminal / Command Prompt di folder proyek.
2. Jalankan perintah:
   ```bash
   python -m http.server 8000

3. Buka browser dan akses: http://localhost:8000
Cara 3: Menggunakan Node.js / NPX   
 1. Buka terminal di folder proyek.
 2. Jalankan perintah: npx serve
 3. Buka link yang tertera di terminal.
🇬🇧 English
This project is a web-based recreation of the classic Flappy Bird game built using HTML5 Canvas, CSS3, and Vanilla JavaScript without external frameworks.
It is fully responsive across mobile and desktop devices, featuring a built-in language toggle.

✨ Key Features

📱 Fully Responsive Design: Adapts dynamically to Desktop (Retro Smartphone Frame) and Mobile (Full Screen).

🌐 Multi-Language Support (ID/EN): Built-in language toggle for game UI.

🎨 Dynamic Themes: Randomized backgrounds (Day/Night) and bird colors (Yellow, Red, Blue) on every restart.

🎯 Precise Scoring: Score increments instantly upon entering the pipe area.

🔊 Retro Sound Effects: Original audio (flap, point, hit, die, swoosh).

⚠️ Important Note (Why Textures/Images Are Missing?)

Opening index.html directly via double-click (file:// protocol) causes browsers to block assets due to CORS security policies. The game must be run through a Local Server.

🚀 How to Run Offline (Choose One Method)
Method 1: Using VS Code (Easiest)
Open the project folder in VS Code.

Install the Live Server extension.

Right-click index.html -> select "Open with Live Server".

Method 2: Using Python (No Additional Tools Required)
If you have Python installed:
1. Open Terminal / Command Prompt inside the project directory.
2. Run the following command: python -m http.server 8000
3. Open your browser and navigate to: http://localhost:8000

Method 3: Using Node.js / NPX
1. Open terminal inside the project directory.
2. Run: npx serve
3. Open the local address printed in the terminal.
