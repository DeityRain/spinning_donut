# ASCII Donut Renderer

## 📌 Overview
This is a simple C program that renders a rotating 3D donut in the terminal using ASCII characters.  
It demonstrates basic 3D math (rotation, projection, and depth buffering) and creative use of terminal control sequences.

---

## 🎯 Features
- Real-time 3D rotation
- ASCII-based rendering
- Depth buffering for correct surface visibility
- Smooth animation using `usleep`
- Runs directly in the terminal

---

## 🛠️ Requirements
- **C compiler** (e.g., `cc`)
- Terminal that supports ANSI escape codes

---

## 📦 Compilation
cc donut.c -o donut -lm

---

## 🚀 Usage
./donut

Press Ctrl+C to stop the animation.

