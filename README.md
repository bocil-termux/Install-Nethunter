# Install Kali Nethunter di Termux (Non-Root)

Tools ini memungkinkan Anda menginstal Kali Nethunter di perangkat Android melalui Termux tanpa perlu root access.

## 📋 Prasyarat

- Android 7.0 atau lebih tinggi
- Termux aplikasi (dapat diunduh dari F-Droid)
- Koneksi internet yang stabil
- Storage minimal 3GB tersedia

## 🚀 Cara Penggunaan

### Step 1: Install Termux
Unduh Termux dari F-Droid (disarankan)

### Step 2: Jalankan Tools
```bash
# Download script
wget https://raw.githubusercontent.com/bocil-termux/Install-Nethunter/main/install-nethunter-termux

# Berikan izin eksekusi
chmod +x install-nethunter-termux

# Jalankan instalasi
./install-nethunter-termux
```

### Step 3: Proses Instalasi

Script akan secara otomatis:

1. Mengupdate package Termux
2. Menginstal dependencies yang diperlukan
3. Mendownload image Kali Nethunter
4. Mengkonfigurasi environment
5. Menyiapkan filesystem

### Step 4: Menjalankan Nethunter

Setelah instalasi selesai, jalankan:

```bash
./install-nethunter-termux start
```

Atau untuk masuk ke environment Nethunter:

```bash
nh
```

⚡ Fitur yang Tersedia

· ✅ Kali Linux tools  
· ✅ Metasploit framework  
· ✅ Nmap network scanner  
· ✅ Wireshark  
· ✅ SQLMap  
· ✅ Hydra  
· ✅ Dan berbagai tools penetration testing lainnya

🛠️ Troubleshooting

Jika terjadi error storage:

```bash
termux-setup-storage
```

Jika instalasi terhenti:

```bash
# Hapus cache dan coba lagi
rm -rf ~/.nethunter
./install-nethunter-termux
```

Permission denied:

```bash
chmod +x install-nethunter-termux
```

📝 Catatan Penting

· Tools ini TIDAK memerlukan root access
· Instalasi membutuhkan waktu 15-30 menit tergantung koneksi
· Pastikan perangkat tidak sleep selama proses instalasi
· Disarankan menggunakan koneksi WiFi

⚠️ Disclaimer

Tools ini hanya untuk tujuan edukasi dan penetration testing yang legal. Pengguna bertanggung jawab penuh atas penggunaan tools ini.

🔄 Update

Untuk update ke versi terbaru:

```bash
./install-nethunter-termux update
```

---

Dibuat untuk komunitas security Indonesia 🔒

Jika mengalami masalah, buka issue di repository ini atau kontak developer.
