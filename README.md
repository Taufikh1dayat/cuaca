Weather App - Real-Time Weather Forecast 🌦️
Aplikasi Website untuk menampilkan informasi cuaca secara real-time di seluruh daerah menggunakan API OpenWeather. Dibangun dengan desain yang responsif dan user-friendly agar pengguna merasa nyaman saat mengaksesnya.

Fitur Utama ✨
✅ Pencarian Cuaca per Kota
✅ Info Cuaca Lengkap (Suhu, Kelembapan, Angin, dll)
✅ Tampilan Visual Cuaca (Icon Dinamis)
✅ Mode Gelap/Terang
✅ Responsif (Desktop, Tablet, Mobile)
✅ Penyimpanan Riwayat Pencarian

Teknologi yang Digunakan 🛠️
Frontend: HTML, CSS, JavaScript (React/Vue.js)

Backend: Node.js (Express) (Opsional)

API: OpenWeatherMap


Cara Install & Menjalankan ⚙️
1. Clone Repository
bash
Copy
git clone https://github.com/username/weather-app.git
cd weather-app
2. Dapatkan API Key dari OpenWeather
Daftar di OpenWeather

Dapatkan API Key Gratis (untuk 60 request/min)

3. Setup Environment
Buat file .env dan masukkan API Key:

env
Copy
OPENWEATHER_API_KEY=your_api_key_here
4. Install Dependencies & Jalankan
bash
Copy
npm install  # Install dependencies
npm start   # Jalankan di localhost:3000
Screenshot Tampilan 📸
Desktop	Mobile
Desktop	Mobile
Desain UI/UX 🎨
Warna Dominan: Biru (Tenang & Informatif)

Animasi: Transisi halus & efek hover

Font: Google Fonts (Poppins, Roboto)

Ikon: Font Awesome

Contoh Respons API 🌐
json
Copy
{
  "city": "Jakarta",
  "temp": 28.5,
  "humidity": 78,
  "wind_speed": 5.2,
  "weather": "Cloudy",
  "icon": "04d"
}
Roadmap Pengembangan 🚀
Tambahkan Prediksi Cuaca 5 Hari

Integrasi Maps (Google Maps API)

Notifikasi Cuaca Ekstrem

Cara Berkontribusi 🤝
Fork repository

Buat branch baru (git checkout -b fitur-baru)

Commit perubahan (git commit -m "Tambahkan fitur X")

Push ke branch (git push origin fitur-baru)

Buat Pull Request
