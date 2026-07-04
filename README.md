[README.md](https://github.com/user-attachments/files/29661635/README.md)
# 🌙 Mawaqit — Muslim Prayer Times App

A clean, professional, multi-language prayer times web app built for mobile.
Single-file app (HTML/CSS/JS) — no build step, no dependencies, works instantly in any browser.

## ✨ Features

- **Accurate prayer times** — powered by the [Aladhan API](https://aladhan.com/prayer-times-api), default location Cairo, Egypt (Africa/Cairo timezone)
- **Live countdown** to the next prayer, with the current/next prayer highlighted
- **4 languages** with full support: Arabic, English, French, Urdu — including RTL layout and native fonts (Amiri, Noto Naskh Arabic, Noto Nastaliq Urdu)
- **Dark / Light mode**
- **Qibla compass** — calculates real bearing to the Kaaba using your device's location and orientation sensors
- **Monthly calendar** view of prayer times
- **Daily Azkar & Duas** section
- **Per-prayer notification toggles**
- **Settings** — change language, city (manual or GPS), and calculation method (default: Egyptian General Authority of Survey)
- Preferences are saved automatically so they persist between visits

## 🚀 Getting Started

No installation needed — it's a single HTML file.

1. Download `prayer_times_app.html`
2. Open it directly in any modern browser (Chrome, Safari, Edge)
3. Or host it for free on **GitHub Pages**:
   - Go to **Settings → Pages** in this repository
   - Set the source branch to `main` and folder to `/root`
   - Your app will be live at `https://<your-username>.github.io/<repo-name>/prayer_times_app.html`

## 🛠️ Tech Stack

- HTML5, CSS3, vanilla JavaScript (ES6+)
- [Aladhan API](https://aladhan.com/prayer-times-api) for prayer times, Hijri dates, and calendars
- Google Fonts (Amiri, Noto Naskh Arabic, Noto Nastaliq Urdu, Inter)
- Browser Geolocation & Device Orientation APIs (for Qibla compass)

## 📱 Roadmap Ideas

- [ ] Convert to installable PWA (manifest + service worker)
- [ ] Adhan audio playback at prayer time
- [ ] Push notifications
- [ ] React component version for easier extension

## 📄 License

Free to use and modify for personal or community projects.
