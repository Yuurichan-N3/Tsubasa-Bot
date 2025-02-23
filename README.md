## ⚡ Tsubasa Bot - Automated Mining

Skrip ini adalah bot otomatis untuk game Tsubasa Rivals yang membantu Anda mengelola akun, mengklaim hadiah harian, menjalankan tugas, dan meng-upgrade kartu secara otomatis.

## 🚀 Fitur Utama

🧠 Manajemen Akun Otomatis: Memproses banyak akun sekaligus menggunakan multi-threading.

🛡️ Proxy Support: Bisa menggunakan proxy untuk menghindari pembatasan IP.

🎁 Hadiah Harian: Mengklaim hadiah harian secara otomatis.

✅ Eksekusi Tugas: Menyelesaikan tugas yang tersedia dan mengklaim hadiahnya.

📈 Upgrade Kartu: Meng-upgrade kartu hingga batas yang ditentukan dalam konfigurasi.

📊 Logger & Progress Bar: Menampilkan log berwarna dan progress bar untuk memantau aktivitas.


## 🛠️ Persyaratan

🟩 Node.js

📦 Paket npm berikut:

axios

winston

cli-progress

cli-table3

https-proxy-agent



## 📂 Struktur File

bot.js: Skrip utama bot

config.json: Konfigurasi bot

data.txt: Berisi query/initData akun

proxy.txt: Daftar proxy (opsional)


## ⚙️ Cara Menggunakan

1. Install Dependencies:


```
npm install
```

2. Siapkan Data Akun:
Isi file data.txt dengan query initData untuk tiap akun, satu per baris.


3. Konfigurasi (Opsional):
Atur preferensi bot di config.json, misalnya level maksimal upgrade kartu.


4. Jalankan Bot:

```
node bot.js
```

## 📜 Lisensi  

Script ini didistribusikan untuk keperluan pembelajaran dan pengujian. Penggunaan di luar tanggung jawab pengembang.  

Untuk update terbaru, bergabunglah di grup **Telegram**: [Klik di sini](https://t.me/sentineldiscus).


---

## 💡 Disclaimer
Penggunaan bot ini sepenuhnya tanggung jawab pengguna. Kami tidak bertanggung jawab atas penyalahgunaan skrip ini.
