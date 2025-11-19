# Motion Sparkles - Interactive Art Installation

An interactive motion-tracking particle system that responds to movement with colorful visual effects. Perfect for science museums, interactive exhibits, and art installations!

## ✨ Features

- **Real-time Motion Detection** - Uses webcam to track movement
- **Camera Color Extraction** - Trails reflect actual colors from the camera
- **Precise Direction Tracking** - Particles follow the exact direction of movement
- **Multiple Visual Effects:**
  - 🌈 **Trails** - Flowing particles that follow movement direction with camera colors
  - 🎆 **Fireworks** - Explosive particle effects
  - 🫧 **Bubbles** - Floating bubble effects
  - ⭐ **Sparkles** - Colorful sparkle particles

## 🎮 How to Use

1. Open `index.html` in a web browser (Chrome recommended for best performance)
2. Click "Start Camera" and allow webcam access
3. Move your hands, body, or colorful objects in front of the camera
4. Watch as trails and particles follow your movements!

## 🎨 Interactive Controls

- **Effect Type** - Switch between different particle effects
- **Sensitivity** - Adjust how much movement triggers particles (10-100)
- **Particle Size** - Control the size of particles (2-20)

## 🌟 Best Practices

### For Museum/Exhibition Use:
- Use **"Trails"** effect for best visual impact
- Set sensitivity to 30-40 for responsive interaction
- Particle size 5-8 works well for most displays
- Use in a well-lit environment for better motion detection

### For Best Colors:
- Wear colorful clothing or use colorful objects
- Movement creates trails in those colors!
- Red, blue, green objects create vibrant effects
- White/neutral backgrounds work best

## 🔧 Technical Details

- **Motion Detection:** Optimized 40×30 pixel detection grid
- **Performance:** 500 particle limit, 80ms detection rate
- **Rendering:** HTML5 Canvas with WebGL acceleration
- **Color Extraction:** Real-time RGB sampling from camera feed
- **Direction Tracking:** Nearest-neighbor algorithm with 80-pixel search radius

## 🚀 Performance Optimization

The system is optimized for real-time performance:
- Downscaled motion detection (40×30 resolution)
- Efficient particle pooling (max 500 particles)
- Simple circle rendering (no complex shapes)
- Reduced detection frequency (80ms intervals)
- Hardware-accelerated canvas rendering

## 🎯 Use Cases

- Science museum interactive exhibits
- Art installations
- Educational demonstrations about motion tracking
- Video call backgrounds
- Interactive performances
- Children's play areas

## 🛠️ Technology Stack

- HTML5 Canvas API
- JavaScript (ES6+)
- WebRTC (getUserMedia API)
- Real-time video processing
- Particle system animation

## 📱 Browser Compatibility

- ✅ Chrome (Recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ⚠️ Mobile browsers (performance may vary)

## 🎨 Customization

Want to add more effects or customize behavior? Key parameters to adjust:

- `MAX_PARTICLES` - Maximum particles on screen
- `motionCanvas.width/height` - Motion detection resolution
- `sensitivity` - Motion detection threshold
- Particle `decay` rate - How fast particles fade
- Particle `speed` - How fast particles move

## 📄 License

Free to use for educational and non-commercial purposes.

## 🤖 Credits

Built with Claude Code - Interactive motion tracking system
Created: November 2024

---

**Tip:** For the best museum installation experience, use "Trails" effect with a sensitivity of 30-40. Wave colorful objects to see stunning colored trails that follow your movements perfectly! 🌈✨
