# 🛡️ Payload Generation & Pentest Lab Simulation

Repositori ini mendokumentasikan proses pembuatan *payload* serta simulasi pengujian penetrasi (*penetration testing*) dan analisis kerentanan sistem di dalam lingkungan virtual tertutup (*isolated virtual lab*). Proyek ini bertujuan untuk mempelajari mekanisme kendali sistem, konfigurasi *listener*, dan pemahaman alur komunikasi jaringan secara etis (*ethical hacking*)

---

## 🛠️ Alat & Teknologi yang Digunakan
- **Sistem Operasi Penyerang (Attacker OS):** Parrot OS MATE Edition (Terminal CLI)
- **Sistem Operasi Target (Target OS):** Windows 7 Professional (Virtual Machine)
- **Lingkungan Virtualisasi:** Virt-Manager
- **Framework Utama:** Metasploit Framework (`msfvenom`, `msfconsole`)

---

## 📋 Tahapan Implementasi & Pengujian
1. **Pembuatan Payload:** Menggunakan `msfvenom` di Parrot OS untuk menghasilkan *executable payload* dengan konfigurasi *reverse TCP*
2. **Konfigurasi Listener:** Menyiapkan *multi/handler* pada Metasploit Framework (`msfconsole`) dengan mendefinisikan *LHOST* (IP lokal penyerang) dan *LPORT*
3. **Pengujian & Manajemen Sesi:** Menjalankan *payload* pada mesin virtual target (Windows 7) dan mengelola sesi jarak jauh (*Meterpreter session*) untuk melakukan verifikasi sistem (`sysinfo`, *screenshot*, dll)

---

## ⚠️ Catatan Etis & Keamanan
Seluruh rangkaian pembuatan dan pengujian simulasi di dalam repositori ini dilakukan **hanya untuk tujuan edukasi, penelitian keamanan siber, dan diuji pada lingkungan virtual tertutup milik pribadi**

---

## 🎥 Dokumentasi Video Lab
- [Tonton Video Demonstrasi Praktikum (Dipercepat)](https://drive.google.com/drive/folders/1daRVSQMx9LkMott59zrAmxz2mDKp66XC?usp=sharing)

---

## 👨‍💻 Penulis
**Mochamad Rizky Fidel Purnama**  
*SMK Informatika Al-Irsyad Al-Islamiyyah Cirebon (Teknik Jaringan Komputer dan Telekomunikasi)*
