# PPSSPP 60 FPS Lag Fix

Optimized PPSSPP emulator settings for smooth **60 FPS** gameplay and reduced lag — especially on low-end PCs.  
This pack includes a ready-to-use `ppsspp.ini`, performance tips, and optional lightweight shaders.

---

## 📥 What's Included
- `ppsspp.ini` — Pre-configured settings for 60 FPS and low input latency
- `performance.md` — Extra performance tweaks for Windows/Linux
- `controller.md` — Tips for reducing controller input lag
- `shaders/` — Optional lightweight shaders for visual clarity
- `cheats/` — Guide for game-specific FPS patches

---

## 🖥 Installation

1. **Download this repository**  
   - Click the green **Code** button → **Download ZIP** → Extract it  
   - Or use `git clone https://github.com/YOURUSERNAME/ppsspp-60fps-lagfix.git`

2. **Locate your PPSSPP config folder**  
   - **Windows**: `%APPDATA%\PPSSPP\PSP\`
   - **Android**: `/PSP/SYSTEM/`
   - **Linux**: `~/.config/ppsspp/PSP/`

3. **Replace your `ppsspp.ini`**  
   - Backup your old file if you have one
   - Copy the provided `ppsspp.ini` into the `SYSTEM` or `PSP` folder

4. **Launch PPSSPP**  
   - Open your game
   - Make sure `Settings → Graphics → Frame Rate` shows `60 FPS`

---

## ⚡ Recommended Settings

| Setting                | Value                 |
|------------------------|-----------------------|
| Backend                | Vulkan (or OpenGL if Vulkan is unstable) |
| Frame Limit            | 60 FPS                |
| Frameskip              | 0                     |
| VSync                  | Off (unless screen tearing is bad) |
| Rendering Resolution   | 1x PSP (for low-end) or higher for stronger PCs |
| Texture Filtering      | Linear                |

---

## 🎯 Tips for Best Performance
- Close other apps while playing
- Use a high-performance power plan
- Keep your GPU drivers updated
- Avoid screen recording while gaming on very low-end hardware

---

## 📜 License
MIT License — you’re free to use, modify, and share.
