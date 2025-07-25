# Stopwatch Application

## Project Overview

A precision digital stopwatch application built with HTML, CSS, and JavaScript. Features accurate time measurement with millisecond precision, essential timing controls (Start/Pause/Reset), and lap functionality for recording split times. Demonstrates vanilla JavaScript timing mechanisms and responsive UI design without external dependencies.

## Data Flow Model

<img width="1357" height="155" alt="image" src="https://github.com/user-attachments/assets/b1ddc9d2-6cb3-4fe6-b1c6-852f738fd834" />

## Technical Details

**Technology Stack:**
- **Frontend**: HTML5, CSS3, JavaScript ES6+ (Vanilla)
- **Timing API**: `performance.now()` for high-precision measurements
- **Architecture**: Modular JavaScript with separation of concerns

**Core Features:**
- Millisecond precision timing using `performance.now()` API
- Start/Pause/Reset controls with state management
- Lap time recording with split calculations
- Responsive design and keyboard shortcuts

## User Interface

<img width="1856" height="825" alt="image" src="https://github.com/user-attachments/assets/d0a931e7-28bd-4911-84d2-7ce254ddd430" />

## How to Use and Play

### Installation
```bash
git clone https://github.com/chiragbansal511/stop-watch.git
cd stop-watch
# Open index.html in browser or serve locally
```

### Gameplay
1. Click **START** to begin timing
2. **PAUSE** to stop temporarily, **RESET** to clear
3. **LAP** to record split times during operation
4. View lap history with time differences

### Controls & Features
- **Controls**: Click buttons or keyboard shortcuts (Space/R/L keys)
- **Features**: Millisecond precision, lap tracking, responsive design, session persistence
