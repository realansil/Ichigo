
# 🍓 Ichigo – BLEACH Reiatsu System v2

An interactive, browser-based visual experience inspired by *BLEACH*, featuring real-time hand tracking, particle effects, and cinematic transformations.  
Built using **Three.js**, **MediaPipe Hands**, and pure frontend technologies.

## 🚀 Live Demo
https://realansil.github.io/Ichigo/<br>
https://realansil.github.io/Ichigo/index2.html<br>
https://realansil.github.io/Ichigo/index3.html

---

## ✨ Features

- 🎥 Real-time webcam integration  
- ✋ Hand gesture recognition (MediaPipe)  
- ⚡ Dynamic particle systems (Three.js)  
- 🎧 Procedural audio engine (no external audio files)  
- 🌌 Cinematic visual effects (bloom, chromatic aberration, screen shake)  
- 🧠 Gesture-based transformations:
  - Shikai
  - Bankai
  - Hollow
  - Quincy
  - Getsuga Tenshou
  - Mugetsu  
- 📊 UI overlays with stats, FPS, and technique indicators  

---

## 🎮 Controls (Gestures)

| Gesture | Action |
|--------|--------|
| Left hand open | Shikai |
| Right hand open | Bankai |
| Both hands open | Quincy |
| Both fists | Hollow |
| Snap gesture | Getsuga Tenshou |
| 3-finger hold (both hands) | Mugetsu |
| Hands close together | Fusion |

---

## 🛠️ Tech Stack

- **HTML5 / CSS3**
- **JavaScript (ES Modules)**
- **Three.js** – 3D rendering & particles  
- **MediaPipe Hands** – Gesture detection  
- **Web Audio API** – Procedural sound system  

---

## 📂 Project Structure

. ├── index.html   # Main application (entire system in one file) └── README.md    # Documentation

---

## ⚙️ How It Works

- The webcam feed is captured and processed using MediaPipe Hands  
- Hand landmarks are analyzed to detect gestures  
- Each gesture triggers a different particle system configuration  
- Three.js renders particles with post-processing effects  
- A custom audio engine generates sound dynamically  
- UI updates in real-time based on active technique  

---

## ▶️ Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/realansil/Ichigo.git

2. Navigate to the project:

cd Ichigo


3. Open in browser:

Open index.html

Allow camera access when prompted





---

🌐 Deployment

This project is deployed using GitHub Pages.

To deploy your own:

1. Push code to a GitHub repository


2. Go to Settings → Pages


3. Select branch (main) and root folder


4. Access via:

https://your-username.github.io/repo-name/




---

⚠️ Requirements

Modern browser (Chrome recommended)

Webcam access enabled

Good lighting for accurate hand tracking



---

🔮 Future Improvements

More gesture combinations

Mobile optimization

Performance tuning for lower-end devices

Additional visual effects and modes



---

📄 License

This project is open-source and available under the MIT License.
