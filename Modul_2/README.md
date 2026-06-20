# 🌐 Praktikum Jaringan LAN - Cisco Packet Tracer

Repositori ini berisi file praktikum dan tugas simulasi jaringan komputer menggunakan **Cisco Packet Tracer**. Fokus utama dari praktikum ini adalah merancang topologi jaringan lokal (LAN) serta melakukan konfigurasi IP Address pada setiap perangkat agar dapat saling terhubung.

---

## 📁 Daftar File Praktikum

Di dalam proyek ini terdapat beberapa skenario jaringan yang telah dikonfigurasi:
1. **`Membangun_Jaringan-Komputer.pkt`**: Skenario dasar pembangunan dan pengenalan perangkat jaringan.
2. **`Konfigutasi IP Pada Jaringan LAN.pkt`**: Praktikum inti mengenai teknik pengalamatan IP (IP Addressing) pada jaringan lokal.
3. **`Tugas_Konfigutasi IP Pada Jaringan LAN.pkt`**: File tugas atau evaluasi mandiri dari hasil praktikum konfigurasi IP LAN.

---

## 🛠️ Perangkat & Komponen Jaringan

Simulasi ini menggunakan beberapa komponen infrastruktur jaringan berikut:
- **End Devices**: PC (Personal Computer) dan Laptop sebagai Node/Client.
- **Interconnecting Devices**: Switch (misal: Cisco Catalyst 2960) sebagai penghubung antar perangkat dalam satu segmen LAN.
- **Media Transmisi**: Kabel *Copper Straight-Through* untuk menghubungkan PC/Laptop ke Switch.

---

## ⚙️ Langkah-Langkah Menjalankan Simulasi

Untuk membuka dan menguji file praktikum ini, ikuti langkah-langkah berikut:

### Prasyarat
- Pastikan Anda sudah menginstal aplikasi **Cisco Packet Tracer** (Direkomendasikan versi terbaru atau minimal versi 8.x).

### Cara Membuka File
1. Download atau clone repositori ini ke komputer Anda.
2. Buka aplikasi Cisco Packet Tracer.
3. Klik **File > Open** (atau gunakan pintasan `Ctrl + O`).
4. Pilih salah satu file `.pkt` yang ingin Anda lihat (misalnya: `Konfigutasi IP Pada Jaringan LAN.pkt`).

### Cara Menguji Konektivitas (Ping Test)
Untuk memastikan konfigurasi IP Address sudah benar dan perangkat saling terhubung:
1. Klik salah satu **PC** atau **Laptop** di dalam topologi.
2. Buka tab **Desktop**, lalu pilih menu **Command Prompt**.
3. Ketik perintah `ping` diikuti dengan IP Address tujuan.
   ```bash
   ping 192.168.1.X