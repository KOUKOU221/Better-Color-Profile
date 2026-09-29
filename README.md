<p align="center">
  <img src="assets/app_logo.png" alt="Better Color Profile Logo" width="128" />
</p>

<h1 align="center">Better Color Profile</h1>
<p align="center">
  <em>Change your screen colors in one click • The modern Windows color profile manager</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Windows-11%20%7C%2010-0078D6?logo=windows&logoColor=white" alt="Windows Support" />
  <img src="https://img.shields.io/badge/Anti--Cheat-100%25%20Safe-success" alt="Anti-Cheat Safe" />
  <img src="https://img.shields.io/badge/Release-v1.04-EAB308" alt="Version" />
  <img src="https://img.shields.io/badge/License-All%20Rights%20Reserved-red" alt="License" />
</p>

---

**Better Color Profile** is the modern, lightweight display calibration and color profile manager that Windows always needed. 

Built for **Windows 11 and Windows 10**, it completely replaces the clunky, buried Windows Color Management applet (`colorcpl.exe`) with a sleek interface, global hotkeys, and real-time display tuning — allowing you to effortlessly create, customize, and cycle through color profiles with zero lag.

---

## 📦 Installation & Download

Compatible with **Windows 11 and Windows 10** (64-bit and 32-bit):

1. [**Download `BetterColorProfileSetup.exe`**](https://github.com/KOUKOU221/Better-Color-Profile/releases/latest/download/BetterColorProfileSetup.exe) (Direct download — automatically gets the latest release).
2. Run the setup wizard:
   - Modern installation wizard with custom destination directory selection (automatically creates and installs into a dedicated `BetterColorProfile` folder).
   - Optional Start with Windows and desktop/start-menu shortcuts (enabled by default).
   - Clean uninstallation support via Windows Settings / Installed Apps.

---

## 🛡️ 100% Anti-Cheat Friendly & Gamer Safe

Unlike shader injectors (such as ReShade) or custom overlays that hook into game processes, **Better Color Profile is 100% safe for all competitive online games**:

* **Zero Game Injection**: It never touches, hooks, or inspects game memory, DirectX, Vulkan, or OpenGL pipelines.
* **Official Windows APIs Only**: It interacts exclusively with official Microsoft Windows Color Management (`mscms.dll` / `WcsSetDefaultColorProfile`) and hardware display drivers (`gdi32!SetDeviceGammaRamp`).
* **Approved by Modern Anti-Cheats**: Kernel-level anti-cheat software (including **Riot Vanguard, Easy Anti-Cheat, BattlEye, Ricochet, and VAC**) recognize it as standard Windows display settings.
* **Zero Input Lag & Zero FPS Drop**: Because adjustments are applied at the GPU/monitor hardware LUT level, there is no performance penalty.

---

## 🎮 Why It's a Game-Changer for Gamers & Creators

* **Spot Enemies in Dark Corners**: Boost shadow visibility and contrast in competitive shooters (*CS2, Valorant, Apex Legends, Warzone, Escape from Tarkov*) without washing out bright areas.
* **Custom Digital Vibrance & Color Temperature**: Give your display punchy colors, vibrant highlights, or a warm eye-friendly night tint per game.
* **Instant Hotkey Switching (`Ctrl + Shift + C`)**: Switch instantly between your high-visibility gaming profile and accurate sRGB desktop profile without Alt-Tabbing or closing your game.
* **Color Accuracy for Creators**: Switch back to true, calibrated sRGB for Photoshop, Premiere, or web browsing in a single click.

---

## 🚀 Key Features

### 1. ⚡ Instant Profile Application & Sidebar Slots
* **One-Click Apply**: Preview profiles in your sidebar without interrupting your display until you click the prominent **Apply** button.
* **Slot Management**: Organize your favorite profiles into custom slots (Slot 1, Slot 2, Slot 3...).
* **Protected Default Profile**: Your default Windows sRGB color profile is protected in a hidden internal directory (`.internal\`) — impossible to delete or corrupt accidentally.
* **Ghost Profile Cleanup**: Automatically synchronizes with installed Windows profiles and unregisters orphaned or deleted display associations from Windows Color Management.

### 2. 🎛️ 7-Slider Real-Time Display Tuner
* **Fine-Grained Hardware Calibration**:
  - Master Brightness (-100% to +100%)
  - Master Contrast (-100% to +100%)
  - Color Temperature (Warm to Cool)
  - Color Balance: Red, Green, and Blue fine-tuning
  - Gamma Curve adjustment
* **Automatic Sequential Naming**: Creating a new profile? If no name is provided, names are automatically pre-filled sequentially (`Profile 1`, `Profile 2`, etc.).
* **Instant ICC Generation**: Saves calibrated profiles directly into the `list\` directory and auto-associates them with your primary monitor.

### 3. ⌨️ Global Hotkeys & Shortcuts
* Press **`Ctrl + Shift + C`** anywhere to cycle between your configured profile slots instantly:
  $$\text{Slot 1} \;\longrightarrow\; \text{Slot 2} \;\longrightarrow\; \text{Slot 3} \;\longrightarrow\; \text{...} \;\longrightarrow\; \text{Slot 1}$$
* Fully customizable hotkey bindings in the Options tab.
* Subtle balloon toast notifications confirm the active profile name.

### 4. 🧰 System Tray & Background Daemon
* Minimizing or closing the window sends it directly to the system tray so the hotkey remains active.
* Right-click tray menu provides quick slot switching, status overview, and settings.
* Enable **Start with Windows** to keep your preferred profiles ready on startup.

---

## 🛠️ Building from Source

To compile from source using the built-in Microsoft .NET C# compiler:

```cmd
build.bat
```

This compiles both:
* `dist\BetterColorProfile.exe` (Standalone portable application)
* `dist\BetterColorProfileSetup.exe` (Complete setup wizard installer)
* Copies the standalone executable to the root directory for immediate local testing.

---

<!--
## ☕ Support the Project

If **Better Color Profile** enhances your gaming experience, competitive visibility, or daily workflow, consider supporting ongoing development!

<p align="left">
  <a href="https://buymeacoffee.com/KOUKOU221" target="_blank">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" height="48" />
  </a>
</p>

---
-->

## 📄 License & Copyright
Copyright © 2026 KOUKOU221. All rights reserved.

This software and associated documentation files are proprietary. Unauthorized copying, distribution, modification, reverse engineering, or commercial use of this software, in source or binary form, is strictly prohibited without explicit written permission from the copyright owner.

