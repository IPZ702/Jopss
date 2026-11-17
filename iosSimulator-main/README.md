# iOS Simulator Web App 📱

A fully functional, professional iOS simulator built with HTML, CSS, and JavaScript. This project replicates the iPhone user experience directly in your web browser.

![iOS Simulator](https://raw.githubusercontent.com/placeholder/image/main/preview.png)

## ✨ Features

- **Realistic iPhone Interface**: Styled to match the latest iPhone design with notch/Dynamic Island, rounded corners, and home indicator.
- **Lock Screen**:
  - Real-time date and time.
  - Swipe-up to unlock animation.
  - Functional flashlight and camera shortcuts.
  - Weather widget.
- **Home Screen**:
  - Grid layout with authentic app icons.
  - Interactive Dock.
  - Status bar with time, signal, Wi-Fi, and battery.
  - Working Control Center (swipe down from top right hidden / swipe up from bottom).
- **Control Center**:
  - Toggles for Wi-Fi, Bluetooth, Airplane Mode, Flashlight.
  - Brightness and Volume sliders (visual).
  - Music playback controls.
- **Dynamic Island**: Interactive notch area that responds to app states.

## 📱 Included Apps

The simulator includes **15+ functional apps**, each designed to mimic their native iOS counterparts:

| App | Description |
|-----|-------------|
| **Weather** ☁️ | Live weather data using Open-Meteo API, 10-day forecast, hourly data. |
| **Calculator** 🧮 | Fully functional standard and scientific calculator. |
| **Clock** ⏰ | World Clock, Alarm, Stopwatch, and Timer functionalities. |
| **Notes** 📝 | Create, edit, and delete notes with local storage persistence. |
| **Settings** ⚙️ | Realistic settings menu with toggles and lists. |
| **Safari** 🧭 | Simulated browser with favorites, reading list, and address bar. |
| **Photos** 🖼️ | Photo grid view with dates and image viewer. |
| **Camera** 📷 | Simulated camera interface with viewfinder and modes. |
| **Music** 🎵 | Music player with "Now Playing", library, and playback controls. |
| **Messages** 💬 | Chat interface with conversation list and message bubbles. |
| **Mail** ✉️ | Inbox view with email details and filtering. |
| **Maps** 🗺️ | Stylized map interface with location and POIs. |
| **App Store** 🛒 | Featured apps, top charts, and categories. |
| **Files** 📁 | File manager with locations and recent files. |
| **Health** ❤️ | Activity rings, heart rate data, and health metrics. |
| **Wallet** 💳 | Digital wallet with card stack, transactions, and passes. |

## 🛠️ Tech Stack

- **HTML5**: Semantic structure for the phone frame and apps.
- **CSS3**: Advanced styling with Flexbox, Grid, Animations, Variables, and filtering for glassmorphism.
- **JavaScript (ES6+)**: Logic for app navigation, time updates, dynamic interactions, and data fetching.
- **IFrames**: Used to sandbox individual apps for a modular architecture.

## 🚀 How to Run

1.  **Clone or Download** this repository.
2.  Open the `index.html` file in any modern web browser (Chrome, Safari, Edge, Firefox).
3.  **Experience iOS**:
    - Click or press Enter on the Lock Screen to unlock.
    - Click any app icon to launch.
    - Click the Home Indicator (bottom bar) to return Home / close apps.

## 📁 Project Structure

```
/
├── index.html          # Main simulator entry point (Phone frame)
├── simulator.css       # Core styling for the phone and UI
├── simulator.js        # Main logic (Lock screen, navigation, system overlays)
├── style.css           # Additional styles
├── apps/               # Individual App HTML files
│   ├── calculator.html
│   ├── calendar.html
│   ├── camera.html
│   ├── clock.html
│   ├── ... (and more)
└── weather-app.html    # Standalone weather app embedded in simulator
```

## 🎨 Credits

Designed and developed with a focus on pixel-perfect details to provide a "Wow" factor experience.

---

*Note: This is a web simulation. System toggles (Bluetooth, WiFi) are visual simulations and do not control your actual device hardware.*
