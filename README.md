# 📼 Retro Cassette Player

> A fully functional, nostalgic audio player built with pure CSS Art and the Web Audio API.
<img width="1409" height="903" alt="Screenshot 2025-11-25 230022" src="https://github.com/user-attachments/assets/626785fa-2b77-4520-84f1-7736bd016124" />



## 📖 About
This project is an exploration of **Skeuomorphism** in the modern web. It replicates the tactile feel of a physical cassette player using digital tools. 

The most unique aspect of this player is that **zero external image assets were used**. Every texture, screw, shadow, and reel is rendered programmatically using CSS gradients and box shadows.

## ✨ Features

### 🎨 Visuals & UI
- **Pure CSS Art:** No PNGs or SVGs. The cassette body, screws, and reels are drawn with code.
- **Dynamic Theming:** 8 interchangeable color themes (Orange, Blue, Green, Purple, Red, Pink, Cyan, Yellow) using CSS Variables.
- **Responsive Design:** Utilizes `transform: scale()` calculations to fit perfectly on mobile and desktop screens.
- **Animations:** Rotating reels that spin only during playback.

### 🎧 Audio Engineering
- **Drag & Drop Support:** Play local MP3/WAV files directly from your computer using the **File API**.
- **Real-Time Visualizer:** An HTML5 Canvas spectrum analyzer that visualizes audio frequencies using the **Web Audio API (FFT)**.
- **Mechanical SFX:** Synthetic "click" and "clunk" sounds generated via JavaScript oscillators for tactile feedback.

## 🕹️ Controls

| Key | Action |
| :--- | :--- |
| **Spacebar** | Play / Pause |
| **Right Arrow** | Fast Forward (5s) |
| **Left Arrow** | Rewind (5s) |
| **Shift + Right** | Next Track |
| **Shift + Left** | Previous Track |

## 🚀 How to Use

1. **Open the Player:**  https://pv2004.github.io/Retro-Cassette-Player/
2. **Insert a Tape:** - **Click** the Eject button (⏏) to select files.
   - **OR Drag & Drop** your MP3 files anywhere on the screen.
3. **Customize:** Click the colored dots at the top to change the player casing.




