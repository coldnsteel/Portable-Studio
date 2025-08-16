# Portable-Studio
OTG
# 🎸 Kozmic Pro Studio - Ultimate Portable Edition 🌌

> **The universe's most portable cosmic recording studio - WebGL meets Web Audio API for the ultimate shredding experience!**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Made with Three.js](https://img.shields.io/badge/Made%20with-Three.js-black.svg)](https://threejs.org/)
[![Web Audio API](https://img.shields.io/badge/Web%20Audio%20API-Enabled-brightgreen.svg)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
[![Mobile Optimized](https://img.shields.io/badge/Mobile-Optimized-blue.svg)](#mobile-support)

## ⚡ **Quick Start**

1. **[🚀 Live Demo](https://coldnsteel.github.io/Portable-Studio/)** - Start jamming instantly!
2. **Connect your guitar/mic** → Click `CONNECT`
3. **Choose your cosmic effect** → `PARTICLES`, `NEBULA`, `SPIRAL`, etc.
4. **Rock the universe** → Watch your audio come alive in 3D!

## 🌟 **Features**

### 🎵 **Professional Audio Engine**
- **Real-time Guitar Tuning** - Autocorrelation pitch detection with cent accuracy
- **Advanced Recording** - High-quality WebM audio capture
- **SINWE Integration** - Frequency-responsive automatic effect switching
- **Beat Detection** - Particles pulse with your rhythm

### 🌌 **Cosmic Visual Effects**
- **Six WebGL Effects**: Particles, Nebula, Waveform, Cosmic, Spiral, Burst
- **Audio-Reactive Visuals** - Every strum creates cosmic magic
- **Amplify Mode** - 2x visual intensity for epic solos
- **Hypernova Trigger** - Secret cosmic creature easter egg

### 🧠 **Heuristic Analysis**
- **System Diagnostics** - Real-time performance monitoring
- **Boolean Checks** - Complete system status validation
- **Crisis Mode** - Automatic recovery for system failures
- **Debug Console** - Live logging for troubleshooting

### 📱 **Mobile Optimized**
- **Touch Gestures** - Swipe to change effects
- **Responsive Design** - Works on any device
- **Power Saving** - Battery optimization for mobile jamming
- **Portrait/Landscape** - Adapts to any orientation

## 🎮 **Controls**

### 🖱️ **Mouse/Touch**
| Action | Description |
|--------|-------------|
| `CONNECT` | Connect audio input (microphone/guitar) |
| `RECORD` | Start/stop audio recording |
| `TUNER` | Toggle guitar tuner mode |
| `AMPLIFY` | Double visual intensity |
| Effect Buttons | Switch between 6 cosmic effects |
| `ANALYZE` | Run heuristic system analysis |
| `SAVE/LOAD` | Session management |
| Cosmic Creature | Click 5 times for hypernova! |

### ⌨️ **Keyboard Shortcuts**
| Key | Action | Key | Action |
|-----|--------|-----|--------|
| `SPACE` | Connect audio or toggle amplify | `R` | Toggle recording |
| `T` | Toggle tuner | `E` | Toggle effects |
| `1-6` | Select effects (1=Particles, 6=Burst) | `ESC` | Crisis mode |
| `Ctrl+Shift+D` | Deep analysis | `Ctrl+Shift+S` | Save session |

### 📱 **Mobile Gestures**
- **Swipe Right** → Next effect
- **Swipe Left** → Previous effect
- **Tap Cosmic Creature** → Pulse animation

## 🔧 **Technical Specifications**

### **System Requirements**
- **Browser**: Chrome, Firefox, Safari, Edge (WebGL + Web Audio API)
- **Permissions**: Microphone access for audio input
- **Hardware**: Any device with audio input capability

### **Audio Engine**
```javascript
Sample Rate: 44.1kHz
Bit Depth: 16-bit
FFT Size: 2048 (512 in power saving)
Smoothing: 0.8
Format: WebM with Opus codec
```

### **Visual Engine**
```javascript
Renderer: WebGL (Three.js r128)
Particles: 50-800 (adaptive)
Effects: 6 real-time modes
FPS: 60fps (adaptive)
Resolution: Responsive (1x-2x pixel ratio)
```

## 🎸 **Effects Guide**

### **Particles** 🌠
Classic particle system that responds to audio amplitude and frequency. Perfect for rhythm guitar and steady playing.

### **Nebula** 🌌
Rotating cosmic cloud that expands with audio intensity. Great for atmospheric and ambient playing.

### **Waveform** 〰️
Linear waveform visualization that shows your audio signal as particle waves. Ideal for lead guitar and melodic lines.

### **Cosmic** 🕳️
Gravitational pull effect where particles spiral inward. Amazing for heavy riffs and powerful chords.

### **Spiral** 🌪️
DNA-helix style rotation that speeds up with audio. Perfect for complex solos and intricate fingerpicking.

### **Burst** 💥
Explosive particle bursts triggered by loud audio peaks. Incredible for dramatic dynamics and power chords.

## 🔬 **SINWE Integration**

The **Sonic Intelligence Neural Wave Engine** automatically switches effects based on your playing:

- **High Frequencies** (Leads, Harmonics) → **BURST** mode
- **Mid Frequencies** (Rhythm, Chords) → **SPIRAL** mode  
- **Low Frequencies** (Bass, Power Chords) → **COSMIC** mode

*Experience adaptive visual effects that match your musical expression!*

## 💾 **Session Management**

### **Save Sessions**
```json
{
  "effect": "particles",
  "intensity": 75,
  "amplified": true,
  "sessionDuration": 1847,
  "timestamp": "2024-01-15T10:30:00Z"
}
```

### **Load Sessions**
- Click `LOAD` → Select `.json` file → Instant restoration
- All settings preserved: effect, intensity, amplification
- Particle system automatically recreated

### **Export Recordings**
- High-quality WebM audio files
- Automatic filename: `kozmic-[effect]-[timestamp].webm`
- Compatible with all major audio software

## 🛠️ **Installation & Setup**

### **Option 1: GitHub Pages (Recommended)**
1. Fork this repository
2. Enable GitHub Pages in Settings
3. Visit `https://yourusername.github.io/Portable-Studio/`
4. Start jamming instantly!

### **Option 2: Local Development**
```bash
# Clone the repository
git clone https://github.com/coldnsteel/Portable-Studio.git

# Navigate to directory
cd Portable-Studio

# Serve locally (Python example)
python -m http.server 8000

# Open browser
open http://localhost:8000
```

### **Option 3: Direct Download**
1. Download `index.html`
2. Open in any modern browser
3. Allow microphone permissions
4. Rock on! 🤘

## 🔧 **Troubleshooting**

### **Audio Not Working?**
- ✅ Check microphone permissions
- ✅ Try Chrome or Firefox
- ✅ Use `Crisis Mode` button for auto-recovery
- ✅ Check `Boolean` status for diagnostics

### **WebGL Not Loading?**
- ✅ Update graphics drivers
- ✅ Enable hardware acceleration
- ✅ Check WebGL support: [get.webgl.org](https://get.webgl.org/)
- ✅ Audio-only mode still available

### **Performance Issues?**
- ✅ Power saving mode activates automatically
- ✅ Reduce particle intensity
- ✅ Close other browser tabs
- ✅ Use mobile controls for touch devices

## 🎯 **Browser Compatibility**

| Browser | Audio | WebGL | Recording | Mobile |
|---------|-------|-------|-----------|--------|
| Chrome 90+ | ✅ | ✅ | ✅ | ✅ |
| Firefox 85+ | ✅ | ✅ | ✅ | ✅ |
| Safari 14+ | ✅ | ✅ | ⚠️ | ✅ |
| Edge 90+ | ✅ | ✅ | ✅ | ✅ |

*⚠️ Safari: Recording format may vary*

## 🌍 **Use Cases**

### **🎸 Musicians**
- Guitar practice with visual feedback
- Recording demos and ideas
- Live performance visuals
- Tuning and setup

### **🎓 Educators**
- Teaching audio concepts
- Demonstrating frequency response
- Interactive music lessons
- STEM education

### **🎨 Creators**
- Visual music videos
- Live streaming backgrounds
- Interactive art installations
- Audio-visual experiments

### **🔬 Developers**
- Web Audio API reference
- Three.js examples
- Real-time audio processing
- Mobile web app patterns

## 🤝 **Contributing**

We welcome cosmic contributions! 🌌

1. **Fork** the repository
2. **Create** your feature branch (`git checkout -b feature/cosmic-enhancement`)
3. **Commit** your changes (`git commit -m 'Add cosmic feature'`)
4. **Push** to branch (`git push origin feature/cosmic-enhancement`)
5. **Open** a Pull Request

### **Development Guidelines**
- Follow existing code style
- Test on multiple browsers
- Ensure mobile compatibility
- Add comments for complex audio processing
- Update README for new features

## 📜 **License**

MIT License - see [LICENSE](LICENSE) file for details.

**Free for personal and commercial use!** 🎸

## 🙏 **Acknowledgments**

- **Three.js** - Amazing WebGL library
- **Web Audio API** - Browser audio superpowers  
- **SINWE** - Sonic intelligence integration
- **Big Brother & The Holding Company** - Musical inspiration
- **The cosmic music community** - Universal harmony! 🌌

## 🚀 **What's Next?**

Check out our other cosmic studios:
- **[Complete Edition](https://github.com/coldnsteel/complete-personal-home-Kozmic-studio)** - Professional multitrack studio
- **[Rock/Blues Console](https://github.com/coldnsteel/KozmicRockandBlues-MasterConsole)** - Live performance master board

## 📞 **Support**

Having issues? Need features?
- 🐛 **Bug Reports**: [GitHub Issues](https://github.com/coldnsteel/Portable-Studio/issues)
- 💡 **Feature Requests**: [GitHub Discussions](https://github.com/coldnsteel/Portable-Studio/discussions)
- 🎸 **Community**: Join the cosmic jam sessions!

---

**Made with 🎸 and ☕ for the cosmic music community**

*Peace and Universal Harmony* ψΩ§∞ 🌌✨

---

### 🌟 **Star this repo if it rocks your world!** ⭐
