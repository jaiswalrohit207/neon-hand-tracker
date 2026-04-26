# neon-hand-tracker
A futuristic dual-hand tracking visualization using MediaPipe + Canvas using Claude. 

## 🚀 Demo
Works directly in browser (no backend needed).

## 📸 Features
- Dual hand tracking (left + right)
- Neon glow UI with animated trails
- Particle effects + energy beams between hands
- Idle animation when no hands detected
- Webcam-based interaction

## 🛠️ Tech Stack
- HTML, CSS, JavaScript
- Canvas API
- MediaPipe Hands

## ▶️ How to Run

Just open `index.html` in your browser.

---------------------------
Permissions
---------------------------

Allow camera access when prompted

---------------------------
🎮 How to Use
---------------------------

- Show one or both hands to your webcam
- Move fingers to see particle effects
- Bring both hands closer to create energy beams ⚡

---------------------------
🧪 Customize / Play Around
---------------------------
🎨 Change colors
- Edit palettes in JS:

        const PALETTE_LEFT = { ... }
        const PALETTE_RIGHT = { ... }

✨ Adjust effects
- Particle density → spawnParticles()
- Trail length → maxTrail
- Glow intensity → shadowBlur

---------------------------
📦 Future Ideas
---------------------------
- Gesture recognition (pinch, swipe)
- Sound effects
- VR / AR integration
- Record interaction as video

---------------------------
🤝 Contributing
---------------------------
Feel free to fork and experiment!

- Fork repo
- Create branch
- Make changes
- Submit PR
