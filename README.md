# 🎴 AskLara

**AskLara** is a playful, minimalist decision-making Progressive Web App (PWA).  
Tap the mysterious card three times and let fate reveal your answer — **Yes or No** — with a satisfying flip animation and dynamic color change.

🟣 Live Version: [https://leonardboerger.github.io/AskLara/](https://leonardboerger.github.io/AskLara/)

---

## ✨ Features

- 📱 **PWA**: Installable on iOS & Android (add to home screen)
- 🔄 **Realistic Card Flip Animation** with 3D perspective
- 📦 **Offline Support** via Workbox-powered Service Worker
- ✅ Responsive for both portrait and landscape modes
- 💫 Smooth UI and subtle feedback animations

---

## 📸 How It Works

1. Tap the card once → it shakes a little.
2. Tap twice → more tension.
3. Third tap → the card flips and reveals your fate.
4. Answer: YES ✅ or NO ❌ (chosen randomly).
5. Tap again to reset and ask again.

---

## 🧑‍💻 Development

### 🔧 Installation

```bash
git clone https://github.com/leonardboerger/AskLara.git
cd AskLara
```

You can run the app locally using any static file server. For example:

```bash
npx serve
```

Or with Python:

```bash
python3 -m http.server
```

Then open [http://localhost:8000](http://localhost:8000) in your browser.

---

### 🗂️ Project Structure

```
AskLara/
├── index.html            # Main HTML structure + Game logic and flip handling
├── style.css             # Styles and animations
├── images/               # Card images (back, yes, no)
├── manifest.json         # PWA manifest
└── service-worker.js     # Workbox-powered caching logic
```

---

## 📲 Install as PWA

On your mobile browser:

- Open [https://leonardboerger.github.io/AskLara/](https://leonardboerger.github.io/AskLara/)
- Tap **"Share"** → **"Add to Home Screen"**
- Now launch it like a native app

---

## 🔐 Privacy

AskLara stores nothing, sends nothing, and requires no permissions.  
It runs 100% client-side. Your secrets are safe with the card 🤫

---

## 🧙‍♀️ Credits

- Built by [Leonard Börger](https://github.com/leonardboerger)
- Inspired by magic 8-balls, fate, and indecisive minds
- Powered by vanilla JS, CSS3, and ❤️

---

## 🪄 License

This project is open source under the MIT License.

---

Have fun asking Lara! 🌌
