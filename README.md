# 🎮 Cyber Sequence // 2085

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)

**A futuristic cyberpunk memory sequence game with procedural music**

[Play Now](#-play-online) • [Features](#-features) • [Installation](#-installation) • [How to Play](#-how-to-play)

<img src="Screenshot.png" alt="Game Preview" width="600">

</div>

---

## 🌟 Features

### 🎨 **Stunning Cyberpunk Design**
- Neon color scheme with vibrant blue, red, green, and yellow highlights
- Smooth animations and glow effects
- Responsive design for desktop and mobile devices
- Glassmorphism and gradient effects

### 🎵 **Procedural Background Music**
- Original multi-layered electronic soundtrack
- Dynamic melody with counterpoint, bass, and pulse layers
- Reverb effects for atmospheric depth
- Plays during menu, pauses during gameplay

### 🎮 **Engaging Gameplay**
- Classic Simon-style memory game with modern twist
- Progressive difficulty (sequences get faster)
- 5 lives system with visual feedback
- Score tracking for competitive play

### 🌐 **Bilingual Support**
- **English (EN)** - Full interface translation
- **Ukrainian (UK)** - Повна локалізація інтерфейсу
- Easy language switching with one click

### 📱 **Cross-Platform**
- Works on desktop, tablet, and mobile
- Touch and click input support
- Optimized for all screen sizes
- No installation required - runs in browser

---

## 🎯 How to Play

### Rules
1. **Watch** the colored pads light up in sequence
2. **Remember** the pattern
3. **Repeat** by clicking the pads in the same order
4. Each successful round adds one more step to the sequence
5. Make a mistake and lose one life (you have 5 total)
6. The game speeds up as you progress!

### Controls
- **Mouse/Touch**: Click or tap the colored pads
- **Language Toggle**: Switch between EN/UK in the top right corner
- **Start Button**: Begin or restart the game

### Tips
- 🎧 **Play with sound on** for the best experience
- 👀 **Watch carefully** - sequences get longer and faster
- 🧠 **Use patterns** - create mental associations with colors
- 💪 **Stay focused** - concentration is key!

---

## 🚀 Play Online

### GitHub Pages
Visit the live demo: **[Play Cyber Sequence](https://dneese.github.io/cyber-sequence/)**

### Local Play
Simply download `index.html` and open it in any modern web browser. No server required!

---

## 💻 Installation

### Quick Start
```bash
# Clone the repository
git clone https://github.com/dneese/cyber-sequence.git

# Navigate to the folder
cd cyber-sequence

# Open in browser
# Just double-click index.html or use a local server
```

### Using Python Server
```bash
# Python 3
python -m http.server 8000

# Then visit http://localhost:8000
```

### Using Node.js Server
```bash
# Install http-server globally
npm install -g http-server

# Run server
http-server

# Visit the displayed URL
```

---

## 🛠️ Technical Details

### Built With
- **Pure HTML5** - Semantic markup
- **Vanilla JavaScript** - No frameworks or dependencies
- **CSS3** - Modern animations and effects
- **Web Audio API** - Real-time sound synthesis

### Browser Compatibility
- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

### Key Technologies
- `AudioContext` for dynamic sound generation
- CSS Grid for responsive layout
- CSS Animations for visual effects
- Event delegation for performance
- Touch event handling for mobile

---

## 📂 Project Structure

```
cyber-sequence/
│
├── index.html          # Main game file (self-contained)
├── README.md           # This file
├── README_UK.md        # Ukrainian version of README
└── LICENSE             # MIT License
```

---

## 🎨 Color Palette

| Color | Hex Code | Usage |
|-------|----------|-------|
| Neon Blue | `#0066FF` | Primary accent, pad 1 |
| Neon Red | `#FF0033` | Secondary accent, pad 2 |
| Neon Green | `#00FF66` | Success states, pad 3 |
| Neon Yellow | `#FFFF00` | Highlights, pad 4 |
| Deep Space | `#05001c` | Background |

---

## 🎵 Audio Features

### Game Sounds
- **Pad Tones**: Four distinct frequencies (659-932 Hz)
- **Success Sound**: Harmonic two-tone chord
- **Fail Sound**: Descending sawtooth sweep
- **Duration Scaling**: Sounds speed up with game progression

### Background Music
- **30-note melodic sequence** (F3-C5 range)
- **12-note counterpoint layer** (C5-Bb5 range)
- **8-note bass line** (F2-C3 range)
- **4-beat pulse pattern** (C2 square wave)
- **Reverb processing** for spatial depth

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### Ideas for Contributions
- 🌍 Add more language translations
- 🎨 Create alternative color themes
- 🎵 Compose additional music tracks
- 🎮 Add difficulty modes or game variations
- 📊 Implement high score leaderboard
- 🏆 Add achievements system

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2025 [Your Name]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software...
```

---

## 👨‍💻 Author

**[Dneese]**
- GitHub: [@Dneese](https://github.com/Dneese)
- Website: [jukebox.pp.ua](https://jukebox.pp.ua)

---

## 🙏 Acknowledgments

- Inspired by the classic Simon electronic game (1978)
- Font families: [Orbitron](https://fonts.google.com/specimen/Orbitron) & [Rajdhani](https://fonts.google.com/specimen/Rajdhani) from Google Fonts
- Cyberpunk aesthetic influences from Blade Runner, Tron, and modern synthwave culture

---

## 📊 Game Statistics

- **Initial Sequence Length**: 1 pad
- **Starting Lives**: 5
- **Sound Duration Range**: 0.4s → 0.2s (decreases with level)
- **Base Delay Between Pads**: 120ms
- **Maximum Theoretical Level**: Unlimited!

---

## 🐛 Known Issues

Currently there are no known critical bugs. If you find any issues, please [report them here](https://github.com/yourusername/cyber-sequence/issues).

---

## 🔮 Future Plans

- [ ] Add difficulty settings (Easy/Medium/Hard)
- [ ] Implement local high score storage
- [ ] Create 6-pad and 9-pad game modes
- [ ] Add more music tracks
- [ ] Create "zen mode" with no lives limit
- [ ] Add color-blind friendly mode
- [ ] Implement keyboard controls
- [ ] Add achievements and unlockables

---

## 📸 Screenshots

<div align="center">

### Main Menu
<img src="https://via.placeholder.com/600x400/05001c/0066FF?text=Main+Menu" alt="Main Menu" width="500">

### Gameplay
<img src="Screenshot.png" alt="Gameplay" width="500">

### Game Over
<img src="https://via.placeholder.com/600x400/05001c/FF0033?text=Game+Over" alt="Game Over" width="500">

</div>

---

<div align="center">

**Made with ❤️ and lots of ☕**

**[⬆ Back to Top](#-cyber-sequence--2085)**

</div>
