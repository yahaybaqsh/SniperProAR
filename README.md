# SniperProAR — القناص الاحترافي | Arabic Professional Sniper Game

![Arabic RTL](https://img.shields.io/badge/RTL-Arabic-blue?style=for-the-badge&logo=google-chrome)
![No Dependencies](https://img.shields.io/badge/No%20Dependencies-%E2%9C%85-brightgreen?style=for-the-badge)
![Mobile Friendly](https://img.shields.io/badge/Mobile-Friendly-green?style=for-the-badge)
![Web Audio](https://img.shields.io/badge/Web%20Audio-Sound%20Effects-blue?style=for-the-badge)

A breathtaking, fully offline, Arabic-RTL web game that challenges your precision, reflexes, and focus — **SniperProAR** is a professional-grade shooting simulator where you must eliminate threats while avoiding civilians. No installation. No server. Just open and play.

Perfect for Arabic-speaking gamers, developers, or anyone who wants to experience a high-quality, culturally localized HTML5 game with authentic sound effects, dynamic difficulty, and immersive visuals.

---

## 💡 Overview

**SniperProAR** is a single-page, client-side HTML5 game built entirely with vanilla JavaScript, CSS3, and Web Audio API — no frameworks, no libraries, no backend. It runs smoothly on any modern browser (Chrome, Firefox, Safari, Edge) and supports both desktop and mobile touch controls.

You are a professional sniper operating in a high-risk zone. Your mission:  
✅ Shoot only **enemy targets** (💀, 🚗)  
❌ Never shoot **civilians** (👨‍👩‍👧‍👦)  
⏱️ You have **15 seconds per round** — accuracy matters more than speed!

Each hit earns you +10 points. Each civilian shot costs you -5. Missed targets also cost -5.  
Your performance is measured by **accuracy rate**, and levels get progressively harder.

---

## ✨ Key Features

| Feature | Description |
|--------|-------------|
| **Arabic RTL Interface** | Fully localized UI with right-to-left text direction, perfect for Arabic readers. |
| **Realistic Target Types** | Enemies (💀, 🚗), Civilians (👨‍👩‍👧‍👦), and Vehicles — each with unique visual cues. |
| **Dynamic Difficulty** | Level increases every round — targets appear faster and move quicker. |
| **Web Audio Sound Effects** | Immersive sounds for shooting, explosions, misses, and hits — all generated via JavaScript. |
| **Precision Crosshair** | Animated reticle follows mouse/touch movement for accurate aiming. |
| **Accuracy Scoring System** | Track your hit rate: `Hits / Shots × 100`. Encourages skill over spamming. |
| **Level Progression** | Start at Level 1 → Reach Level 10+ for true mastery. |
| **Responsive Design** | Works flawlessly on phones, tablets, and desktops. |
| **Zero Dependencies** | Pure HTML/CSS/JS — no npm, no React, no external files. Just download and play. |
| **Offline First** | Runs completely offline — no internet required after loading. |

---

## 🎮 How to Play

1. **Open `sniper.html`** in any modern browser (Chrome recommended).
2. Click **“ابدأ اللعبة”** to begin.
3. Move your cursor (or finger on mobile) to aim at the targets.
4. **Click or tap** to shoot:
   - 💀 or 🚗 = **+10 points**
   - 👨‍👩‍👧‍👦 = **-5 points** ❌
5. Survive 15 seconds per round — then level up!
6. After each round, view your stats: Score, Accuracy, Level.
7. Click **“لعب مرة أخرى”** to continue to the next level.

> 💡 **Pro Tip**: Don’t rush! Wait for clear shots. One wrong tap can cost you dearly.

---

## 📊 Sample Screenshots
<img width="1846" height="687" alt="لقطة الشاشة 2025-09-13 120527" src="https://github.com/user-attachments/assets/3a064105-b87a-45e4-8e15-b00097e03a7f" />
<img width="1867" height="781" alt="لقطة الشاشة 2025-09-13 120510" src="https://github.com/user-attachments/assets/a5b5c0ba-82c9-4d73-aa45-ec63c663d507" />
<img width="1415" height="632" alt="لقطة الشاشة 2025-09-13 120451" src="https://github.com/user-attachments/assets/83ecb059-1999-4c29-b55e-e0f85f59d375" />

> *Add actual screenshots to `/screenshots` folder after testing.*

---

## 🛠️ Technology Stack

| Layer | Tech Used |
|-------|-----------|
| **Frontend** | HTML5, CSS3 (with RTL support, gradients, animations) |
| **Logic** | Vanilla JavaScript (ES6+) |
| **Audio** | Web Audio API (no .mp3 files — all synthesized) |
| **Storage** | None — state managed in memory |
| **Compatibility** | Chrome, Firefox, Safari, Edge, Android/iOS browsers |
| **Build Tools** | None — direct file execution |

---

## 🔐 Privacy & Security

✅ **100% Private** — No tracking. No cookies. No analytics.  
🔒 **No data sent to servers** — Everything runs locally in your browser.  
📁 **Your device owns all data** — Scores reset when you close the tab.

You play anonymously. You own your score. No cloud. No login. Just pure skill.

---

## 🔄 Export & Backup?

There’s no export feature — because this is designed as a **pure arcade experience**.  
But if you want to save your high score:

1. Take a screenshot of the result screen.
2. Write it down: “Level 7 — 284 pts — 89% Accuracy”

Future versions may add local storage for high scores!

---

## 🚀 Future Enhancements (Roadmap)

- [ ] Save High Scores using `localStorage`
- [ ] Add Background Music (ambient tension theme)
- [ ] Dark/Light Mode Toggle
- [ ] Customizable Targets (e.g., birds, drones, robots)
- [ ] “Training Mode” with unlimited time
- [ ] Share Results via social media (image + score)
- [ ] Multi-language toggle (English, French, Urdu)
- [ ] PWA Installable App (Add to Home Screen)

---

## 🤝 Contributing

Contributions are welcome! Whether you’re a designer, developer, translator, or gamer — help make **SniperProAR** even better.

### Ways to contribute:
- 🐞 Report bugs or suggest improvements
- 🎨 Improve UI/UX design (especially for RTL layout)
- 🌍 Translate UI strings into other languages
- 🔊 Create custom audio effects
- 📸 Add new screenshots or video demos

### Guidelines:
1. Fork the repo
2. Create your branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m 'Add feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a Pull Request

---

## 📜 License

MIT © 2025 [Your Name]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---

## ❤️ Star This Project!

If you enjoyed playing **SniperProAR**, please give it a ⭐ star. It helps others discover this cultural gem — a rare example of a high-quality Arabic-language web game built with pure web tech.

> 🕵️‍♂️ *“In the silence before the shot — precision is power.”*

© 2025 [Your Name] — Built with ❤️ for Arabic digital culture.
