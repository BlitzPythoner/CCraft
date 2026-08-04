# CCraft

*A minimalist voxel sandbox game written completely in C.*

---

## About

CCraft is a voxel sandbox game inspired by the early days of Minecraft, but built entirely from scratch without using a game engine with the help of AI.

The project focuses on understanding how games actually work internally rather than relying on existing engines. Window management, rendering, world generation, chunk management, collision detection, raycasting, inventory systems, lighting and gameplay mechanics are implemented manually.

The goal is not to create another Minecraft clone, but to build a clean, understandable voxel engine while learning low-level game programming.

---

## Features

### World

- Infinite procedural voxel world
- Chunk-based terrain system
- Multiple biomes
- Cave generation
- Trees and vegetation
- Ore generation
- Water and lava
- Fire simulation
- Falling blocks (sand & gravel)

### Gameplay

- Survival mode
- Health system
- Hunger system
- Armor
- Crafting
- Furnace
- Farming
- Chests
- Item drops
- Mob spawning
- Basic AI
- Day/Night cycle
- Weather effects
- Lightning

### Engine

- Written in pure C
- SDL2
- Classic OpenGL renderer
- Direct3D 9 renderer
- First-person camera
- Chunk mesh generation
- Frustum culling
- Raycasting
- AABB collision detection
- Asset integrity verification
- Modular engine architecture

---

## Launcher

CCraft comes with its own launcher featuring:

- Automatic updates
- Version management
- File integrity verification
- Installation management
- Desktop and Start Menu shortcuts
- Multiple game versions

---

## Controls

| Key | Action |
|------|--------|
| W A S D | Move |
| Mouse | Look around |
| Left Click | Break block |
| Right Click | Place block / Interact |
| Space | Jump |
| Shift | Sneak |
| E | Inventory |
| Esc | Pause Menu |

*Controls can be changed

---

## Graphics

CCraft supports two rendering backends.

### OpenGL

Recommended for modern hardware.

- Better performance
- Default renderer
- Best compatibility on newer systems

### Direct3D 9

Designed for older Windows computers.

Useful if OpenGL drivers are outdated or perform poorly.

---

## Performance

CCraft is designed with simplicity and efficiency in mind.

Thanks to its lightweight engine and multiple rendering backends (OpenGL and Direct3D 9), the game is capable of running on a wide range of Windows systems, including many older computers that struggle with modern games.

Whether you're playing on a modern gaming PC or experimenting with legacy hardware, CCraft aims to provide a smooth experience whenever possible.

---

## Building

CCraft is developed on Windows using

- C
- MinGW
- SDL2
- OpenGL
- Direct3D 9

---

## License

CCraft is proprietary software.

The game is released under the included **CCRAFT LICENSE**.

The source code is not publicly available.

Please see the `LICENSE` file for the complete license terms.

---

## Author

**Alex Bauknecht**
aka. BlitzPYthoner

GitHub:
https://github.com/BlitzPythoner

itch.io:
https://alex-bauknecht.itch.io/ccraft

---

## Windows Security Notice

Because CCraft and its Launcher are independently developed and digitally unsigned, Windows SmartScreen or Microsoft Defender may display a warning when launching the application.

This is expected for unsigned software and does **not** necessarily indicate that the program is unsafe.

If you downloaded CCraft from the official GitHub repository or itch.io page, you can safely allow the application to run.

Future releases may include code signing once it becomes feasible.

---

## Screenshots
<img width="1276" height="718" alt="Screenshot 2026-07-29 153533" src="https://github.com/user-attachments/assets/84d40684-ddb3-44d1-92cf-b683d835dd32" />
<img width="1919" height="1079" alt="Screenshot 2026-07-29 153755" src="https://github.com/user-attachments/assets/d006b640-d25e-46e6-9a80-a3e00d29b140" />
<img width="1919" height="1079" alt="Screenshot 2026-07-29 153844" src="https://github.com/user-attachments/assets/2b04d499-bd5a-43b3-84a5-9e3173513e67" />
<img width="1919" height="1079" alt="Screenshot 2026-07-29 154045" src="https://github.com/user-attachments/assets/7df614a1-5e93-4d45-9295-3c5c27c538e0" />
<img width="1919" height="1079" alt="Screenshot 2026-07-29 153921" src="https://github.com/user-attachments/assets/62779119-ea82-4022-825a-84aecf0dad2b" />

---

*"Sometimes the best way to learn how a game engine works is to accidentally write one."*
