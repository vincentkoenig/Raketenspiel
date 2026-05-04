# Rocket Game 🚀

A browser-based 2D space shooter built with JavaScript and **PixiJS**. Steer your rocket left and right, fire projectiles, and destroy UFOs before they reach you — one hit and it's game over.

## Gameplay

```
      🚀
   ←  ↑  →

   UFOs descend from the top.
   Shoot them before they reach you.
   If a UFO touches your rocket — game over!
```

## Features

- 🎮 **Keyboard controls** — arrow keys to move, spacebar to shoot
- 👾 **Randomly spawning UFOs** — appear at the top and descend toward the player
- 💥 **Collision detection** — projectiles destroy UFOs; UFOs touching the rocket end the game
- 🖼️ **Sprite-based rendering** — rocket, UFOs, and bullets rendered as image assets via PixiJS
- 🔁 **Game loop** — continuous update/render cycle via `requestAnimationFrame`

## Tech Stack

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)

- **JavaScript** — game logic, input handling, collision detection
- **PixiJS 7** — 2D WebGL/Canvas rendering engine (loaded via CDN)
- **HTML** — canvas container

## Project Structure

```
Raketenspiel/
└── Raketenspiel/
    ├── index.html      # Entry point & PixiJS CDN import
    ├── app.js          # Game setup, sprites, input handling
    ├── gameloop.js     # Main game loop & update logic
    └── assets/
        ├── rocket.png
        ├── ufo1.png
        ├── ufo2.png
        └── bullet.png
```

## Getting Started

**1. Clone the repository**
```bash
git clone https://github.com/vincentkoenig/Raketenspiel.git
cd Raketenspiel/Raketenspiel
```

**2. Open in browser**

Open `index.html` directly in any modern browser, or use a local server (e.g. VS Code Live Server) for best results.

> Requires an internet connection to load PixiJS from CDN, or replace with a local copy.

## Controls

| Key | Action |
|---|---|
| ← Arrow Left | Move rocket left |
| → Arrow Right | Move rocket right |
| Spacebar | Fire projectile |

## What I Learned

- Working with a 2D rendering library (PixiJS) for sprite-based game development
- Implementing a game loop with continuous update and render cycles
- Handling keyboard input events for real-time player control
- Basic collision detection between moving game objects
- Managing multiple dynamic entities (UFOs, projectiles) on screen simultaneously
