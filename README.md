# Portable-Studio
**Real-time Audio Visualization for Mobile and Desktop**

> A functional web-based audio visualizer with recording capabilities, built with Web Audio API and Canvas/WebGL rendering.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Web Audio API](https://img.shields.io/badge/Web_Audio_API-Enabled-brightgreen.svg)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
[![Mobile Optimized](https://img.shields.io/badge/Mobile-Optimized-blue.svg)](#mobile-support)

## What It Actually Does

**Portable-Studio is a real-time audio visualization tool** that connects to your microphone and creates visual effects that respond to your audio input. It's designed to work well on both mobile and desktop devices.

### Core Features That Work
- **Audio Input**: Connect microphone for real-time audio processing
- **6 Visual Effects**: Particles, Nebula, Waveform, Cosmic, Spiral, Burst
- **Recording**: Capture audio sessions as WebM files
- **Mobile Support**: Touch gestures and responsive design
- **Session Management**: Save and load your settings

## Quick Start

1. **[Open the Studio](https://coldnsteel.github.io/Portable-Studio/)**
2. **Allow microphone access** when prompted
3. **Click "CONNECT"** to start audio input
4. **Choose an effect** (Particles, Nebula, etc.)
5. **Play music or speak** - watch the visuals react

## What's Actually Implemented

### Audio Processing
```
✅ Web Audio API integration
✅ Real-time frequency analysis (FFT)
✅ 8-band frequency visualization
✅ Audio recording (WebM format)
✅ Microphone input processing
```

### Visual Effects
```
✅ Canvas 2D rendering with WebGL fallback
✅ 6 different particle systems
✅ Audio-reactive animations
✅ Intensity controls (25%, 50%, 75%, 100%)
✅ Amplification mode for enhanced visuals
```

### User Interface
```
✅ Mobile-responsive design
✅ Touch gestures (swipe to change effects)
✅ Keyboard shortcuts
✅ Session save/load (JSON format)
✅ Export recordings
```

## Browser Compatibility

| Browser | Audio | Canvas | Recording | Mobile |
|---------|-------|--------|-----------|--------|
| Chrome 90+ | ✅ | ✅ | ✅ | ✅ |
| Firefox 85+ | ✅ | ✅ | ✅ | ✅ |
| Safari 14+ | ✅ | ✅ | ⚠️ | ✅ |
| Edge 90+ | ✅ | ✅ | ✅ | ✅ |

*⚠️ Safari: Recording format may vary*

## Technical Specs (Actual)

```javascript
Sample Rate: 44.1kHz (browser standard)
FFT Size: 2048 samples
Canvas Resolution: Responsive to container
Particle Count: 50-100 (adaptive)
Recording Format: WebM with Opus codec
File Size: ~1MB per minute of recording
```

## Controls

### Desktop
- **Space**: Connect/disconnect audio
- **R**: Toggle recording
- **1-6**: Select effects (1=Particles, 6=Burst)
- **A**: Toggle amplify mode

### Mobile
- **Swipe Right/Left**: Change effects
- **Tap buttons**: All functionality accessible via touch

## What This Is NOT

**Important disclaimers:**
- This is not a professional music production tool
- No real guitar tuning capabilities (just visual feedback)
- No AI features or advanced audio analysis
- No cloud sync or collaboration features
- No professional-grade effects processing

## Installation

### GitHub Pages (Recommended)
1. Fork this repository
2. Enable GitHub Pages in Settings
3. Visit `https://yourusername.github.io/Portable-Studio/`

### Local Development
```bash
git clone https://github.com/coldnsteel/Portable-Studio.git
cd Portable-Studio
python -m http.server 8000
open http://localhost:8000
```

## File Structure
```
Portable-Studio/
├── index.html          # Main application (single file)
├── README.md          # This file
└── manifest.json      # PWA manifest (basic)
```

## Use Cases

**What it's good for:**
- Visualizing music for fun
- Simple audio recording
- Educational demos of Web Audio API
- Mobile-friendly audio visualization
- Party visuals or ambient displays

**What to use instead for:**
- Professional music production → Use DAW software
- Live performance → Use dedicated hardware
- Complex audio effects → Use plugin suites
- Multi-track recording → Use recording software

## Limitations

- **Audio Quality**: Limited by browser Web Audio API
- **Visual Complexity**: Basic particle systems, not advanced 3D
- **Recording**: Browser-dependent format support
- **Performance**: May struggle on older mobile devices
- **Storage**: Local only, no cloud features

## Contributing

Contributions welcome for:
- Performance optimizations
- Additional visual effects
- Better mobile gestures
- Accessibility improvements

Please test on multiple devices and browsers.

## Support

- **Issues**: Use GitHub Issues for bugs
- **Questions**: Include browser version and device type
- **Feature Requests**: Be realistic about scope

## License

MIT License - Free for personal and commercial use.

---

**This is a functional web application that does what it says.** No false promises, no missing features, just honest audio visualization that works in your browser.
