# TowerMaster

**A game-making IDE for the Sega Master System.**

Design games visually — scenes, tiles, sprites, and behaviors — and TowerMaster compiles them
into real Sega Master System ROMs you can play in the built-in emulator or on original hardware.

🌐 **Website:** https://silvatower.github.io/towermasterstudio/

---

## Download

**Windows (x64)**

Install with [winget](https://learn.microsoft.com/windows/package-manager/winget/):

```powershell
winget install Silvatower.TowerMaster
```

Or grab the latest build directly:

👉 **[Download the latest release](https://github.com/silvatower/towermasterstudio/releases/latest)** —
unzip anywhere and run `TowerMaster.exe`. It's portable: no installer, nothing to set up.

---

## What it does

- 🎨 **Visual scene editor** — paint tilemaps, place entities, and wire doors between scenes.
- 🕹️ **Built-in emulator** — a pure-C# Sega Master System (Z80 + VDP + PSG/FM) runs your game instantly.
- 👾 **Sprite tools** — import your own art, or pick from a built-in library of original, CC0, hardware-ready sprites.
- 🧩 **Behaviors** — platformer locomotion, combat, RPG systems, shoot-'em-up waves, bosses and more,
  compiled to a hand-optimized Z80 game engine.
- 📦 **Real ROMs** — export a bootable `.sms` that runs on actual hardware and every accurate emulator.
- 📖 **Physical-release tools** — generate a printable instruction manual and cartridge/box art for a real cartridge.

---

## About

TowerMaster is a standalone Windows desktop app built on a from-scratch, dependency-free Sega Master System
toolchain. This repository hosts the public releases and website.

New releases are published here automatically. To install, use the winget command or the download link above.

---

© TowerMaster Studio · Released under the [MIT License](LICENSE).
