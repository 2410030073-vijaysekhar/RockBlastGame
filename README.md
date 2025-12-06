# 🔥 Rock Blast – Fire Ball

A professional 2D arcade game built with pure HTML5, CSS3, and JavaScript. Destroy falling rocks with fireballs in this action-packed sci-fi themed game!

![Game Banner](https://img.shields.io/badge/Game-Rock%20Blast-blue?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 🎮 Game Overview

**Rock Blast – Fire Ball** is an exciting arcade shooter where you control a spaceship at the bottom of the screen, firing fireballs to destroy descending rocks. Featuring power-ups, combo systems, and increasingly challenging gameplay!

### ✨ Features

- 🎯 **Smooth Gameplay** - Responsive controls with keyboard and mouse support
- 💥 **Power-ups** - Shield protection and double-fire abilities
- 🏆 **Scoring System** - Combo multipliers and high score tracking
- 🎨 **Sci-Fi Design** - Professional UI with animated gradients and particle effects
- 📱 **Responsive** - Works on desktop and mobile browsers
- 🎵 **Sound System** - Audio support (assets not included)

## 🚀 Quick Start

### Play Now

1. Clone the repository:
```bash
git clone https://github.com/vijaysekhar/rock-blast.git
cd rock-blast
```

2. Open the game:
```bash
# Simply open index.html in your browser
# On Windows:
start www/index.html

# On Mac:
open www/index.html

# On Linux:
xdg-open www/index.html
```

**Or** just double-click `www/index.html` to play!

### 🎮 Controls

- **Move**: Arrow Keys or Mouse
- **Shoot**: Spacebar or Left Click
- **Pause**: P or ESC
- **Restart**: R (when game over)

## 📁 Project Structure

```
Game_Rockbalst/
└── www/
    ├── index.html    # Main game file
    └── main.js       # Game logic and mechanics
```

## 🎯 Gameplay

### Objective
Destroy falling rocks before they hit the ground. Each destroyed rock increases your score and combo multiplier!

### Power-ups
- **🛡️ Shield** - Protects you from one rock collision
- **🔥 Double Fire** - Fire two fireballs simultaneously for 15 seconds

### Scoring
- Base points per rock: **10**
- Combo multiplier: Up to **5x**
- Bonus for chain destruction
- High score saved locally

## 🛠️ Technologies Used

- **HTML5 Canvas** - Game rendering
- **Vanilla JavaScript** - Game logic (no frameworks!)
- **CSS3** - Animated UI and styling
- **Web Audio API** - Sound effects system

## 🎨 Customization

### Adding Sound Effects

Place audio files in this structure (create folders as needed):
```
www/assets/audio/
├── shoot.mp3       # Shooting sound
├── explosion.mp3   # Rock destruction
├── powerup.mp3     # Power-up collection
├── gameover.mp3    # Game over
└── shield.mp3      # Shield break
```

### Modifying Difficulty

Edit `main.js` to adjust:
- Rock spawn rate
- Rock speed
- Power-up frequency
- Player speed

## 🌐 Browser Support

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

Created with ❤️ by vijay sekhar

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🐛 Known Issues

- Audio assets not included (references in code only)
- Best played on desktop for optimal experience

## 🎯 Future Enhancements

- [ ] Add background music
- [ ] Implement difficulty levels
- [ ] Add more power-up types
- [ ] Leaderboard system
- [ ] Touch controls optimization
- [ ] Progressive Web App (PWA) support

⭐ **Star this repo if you enjoyed the game!** ⭐
