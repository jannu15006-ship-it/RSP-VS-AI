<div align="center">

# 🎮 ARIA vs Rock Paper Scissors AI

[![Live Demo](https://img.shields.io/badge/Play_Live_Demo-Online-brightgreen?style=for-the-badge&logo=googlechrome&logoColor=white)](https://jannu15006-ship-it.github.io/RSP-VS-AI/)
[![MediaPipe](https://img.shields.io/badge/MediaPipe-Hands_Vision-blue?style=for-the-badge&logo=google&logoColor=white)](https://mediapipe.dev/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

An interactive, computer vision-powered Rock Paper Scissors game where **ARIA** (an adaptive AI) reacts in real-time to your hand gestures using webcam landmark detection.

[👉 **Click Here to Play the Live Game in Your Browser**](https://jannu15006-ship-it.github.io/RSP-VS-AI/)

</div>

---

## ✨ Features

- 📹 **Real-Time Gesture Recognition:** Powered by Google MediaPipe Hands tracking 21 3D hand landmarks directly in the browser.
- 🤖 **Adaptive AI Behavior:** Multiple difficulty modes (Easy, Medium, Hard) that analyze opponent move patterns.
- 🏆 **Match Formats:** Play Best-of-3 or Best-of-5 competitive rounds.
- 📊 **Live Analytics:** Real-time scoreboard, win-rate percentage, round history tracker, and victory celebrations.
- 🎨 **Responsive UI:** Clean, modern pastel aesthetic with smooth animations and zero installation required.

---

## 🕹️ How to Play

1. Open the [Live Demo](https://jannu15006-ship-it.github.io/RSP-VS-AI/) in your browser.
2. Grant camera permissions when prompted.
3. Select your match mode (Best of 3 / Best of 5) and difficulty.
4. Click **Play Round**, follow the countdown, and hold your gesture (Rock ✊, Paper ✋, or Scissors ✌️) steady.
5. ARIA detects your gesture, counters with its prediction, and updates the score instantly!

---

## 💻 Run Locally

No build tools or servers required!

1. Clone the repository:
   ```bash
   git clone https://github.com/jannu15006-ship-it/RSP-VS-AI.git
   cd RSP-VS-AI
   ```
2. Open `index.html` directly in any web browser:
   ```bash
   # On Windows
   start index.html

   # Or serve locally using Python
   python -m http.server 8000
   ```
3. Navigate to `http://localhost:8000` in your browser.

---

## 🛠️ Tech Stack

- **Computer Vision:** Google MediaPipe Hands (WebAssembly / CDN)
- **Frontend / Logic:** Vanilla JavaScript (ES6+), HTML5 Canvas, Modern CSS3
- **Hosting:** GitHub Pages

---

## 👩‍💻 Author
**Jahnavi Lalitha**
- GitHub: [@jannu15006-ship-it](https://github.com/jannu15006-ship-it)
