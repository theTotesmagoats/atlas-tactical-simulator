# ATLAS TERMINAL: TACTICAL SIMULATOR

A fun physics-based mission simulator with a retro-cool tactical interface. Built for young pilots ages 8-12.

## 🎮 How to Play

### Quick Start:
1. **Click anywhere** on the console to initialize systems
2. Read your mission instructions in the teletype display
3. Adjust **Voltage** (slider) and toggle **FUEL/LOX** switches to match requirements
4. When the gauge turns green and "MASTER ARMED" appears, press the **MASTER ARM** button
5. Watch the payload deploy and impact confirmed!

### Mission Types:
- **Mission 1: Primary Depot** - Full systems prime (75-85 volts, both switches ON)
- **Mission 2: Stealth Insertion** - Low power mode (30-40 volts, LOX only)
- **Mission 3: Maximum Override** - High power surge (90-100 volts, FUEL only)

## 🛠️ Features

### Fixed Issues:
✅ Particle cleanup bug (now uses reverse iteration to prevent memory leaks)  
✅ Canvas rendering with proper DPI scaling for high-resolution displays  
✅ Mission boundary logic with correct inclusive bounds (>= and <=)  
✅ Audio debouncing to prevent too many updates per second  
✅ Teletype text animation without overlapping intervals  

### Educational Elements:
- Real-world physics concepts (pressure, temperature, frequency)
- Problem-solving challenges with multiple difficulty levels
- Visual feedback systems for system status monitoring

## 🎨 Technical Details

### Built With:
- HTML5 Canvas & CSS Grid Layout
- Vanilla JavaScript (no frameworks!)
- Web Audio API for sound effects
- Responsive design with high-DPI support

### System Requirements:
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Sound enabled (for audio feedback)

## 🚀 Running the Simulator

### Option 1: GitHub Pages (Recommended)
1. Go to https://github.com/theTotesmagoats/atlas-tactical-simulator
2. Click "Settings" → "Pages"
3. Under "Build and deployment", select branch `main` and folder `/root`
4. Click "Save"

### Option 2: Local File
1. Download [index.html](https://raw.githubusercontent.com/theTotesmagoats/atlas-tactical-simulator/main/index.html)
2. Open in your web browser

## 🛠️ For Parents & Educators

This simulator teaches:
- Basic physics concepts (pressure, energy, systems)
- Problem-solving and strategic thinking
- Reading comprehension and following instructions
- Visual feedback interpretation

**Parental Note:** This is a simulation game only. All "missions" and "explosions" are visual/auditory effects with no real-world applications.

## 📝 Changelog

### v2.1 (Current Release)
- Fixed particle array cleanup bug
- Improved canvas rendering for high-DPI displays  
- Added audio debouncing to prevent excessive updates
- Enhanced mission boundary validation logic
- Added helpful hints that change per mission type
- Better error handling and graceful degradation

## 🎯 Future Enhancements

Potential features:
- More mission types (reconnaissance, rescue operations)
- Achievement system for completed missions
- Difficulty levels (Easy/Medium/Hard)
- Multiplayer cooperative mode

---

Made with ❤️ for young pilots everywhere!
