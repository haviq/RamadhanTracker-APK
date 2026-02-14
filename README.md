 RamadhanTracker-APK
A modern, comprehensive Flutter application to help Muslims track and enhance their spiritual journey during the holy month of Ramadan. 
## Fitur Utama

**Konten Islami**
- Al-Qur'an dengan 3 mode (Baca per Ayat, per Surah, per Halaman) + Audio Murottal
- Jadwal Imsyakiyah berdasarkan data Kemenag / GPS
- Tasbih Digital, Asmaul Husna, Doa & Hadits Harian

**Monitoring Ibadah**
- Checklist shalat wajib, sunnah, tarawih, dan tilawah harian
- Grafik statistik progres ibadah mingguan & bulanan
- Leaderboard antar pengguna (opsional, butuh akun)

**Fitur Lanjutan**
- Admin Dashboard untuk kelola data pengguna
- Cloud Sync untuk backup data ibadah ke server
- Mode Tamu — bisa pakai fitur tanpa login
- Force Update untuk pastikan semua user di versi terbaru

## Tech Stack

- **Frontend**: Flutter, Riverpod, GoRouter, Hive, Adhan
- **Backend**: Node.js, Express, MySQL, JWT Auth
- **Design**: Material 3 + Dark Mode support

## Setup Development

1. Clone repo ini
 
   git clone https://github.com/yourusername/ramadan-tracker.git
  

2. Setup backend
   - Masuk ke folder `backend-node/`
   - Buat file `.env` dari template yang tersedia
   - Jalankan `npm install` lalu `node server.js`

3. Setup Flutter
   - Jalankan `flutter pub get`
   - Update `AppConstants.apiBaseUrl` sesuai IP server
   - Jalankan `flutter run`

## Lisensi

Proyek ini untuk penggunaan pribadi dan komunitas.


Made with love by Hans

