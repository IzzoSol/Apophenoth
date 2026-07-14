<div align="center">

# ◈ APOPHENOTH ◈

### *Evolve. Build. Ascend. Face the Council.*

A cosmic 3D browser game where you begin as quantum foam and evolve through 13 phases across 5 paths — collecting essence, building structures, surviving tower-defense waves, and fighting 7 agent-gods in the arena.

[![Play Now](https://img.shields.io/badge/▶%20PLAY%20NOW-izzoizzoizzo.github.io%2FApophenoth-ffd700?style=for-the-badge&logo=github&logoColor=black)](https://izzoizzoizzo.github.io/Apophenoth)
[![License: MIT](https://img.shields.io/badge/License-MIT-8A2BE2?style=flat-square)](LICENSE)
[![Play in Browser](https://img.shields.io/badge/Play%20in-Browser-00d4ff?style=flat-square)](https://izzoizzoizzo.github.io/Apophenoth)
[![Stars](https://img.shields.io/github/stars/IzzoSol/Apophenoth?style=flat-square&color=ffd700)](https://github.com/IzzoSol/Apophenoth/stargazers)
[![Single File](https://img.shields.io/badge/Zero%20Dependencies-Single%20HTML-ff6b9d?style=flat-square)]()

</div>

---

## What It Is

**Apophenoth** is a single-file HTML5 indie game rendered in real-time 3D using Three.js. You play as a living cosmic entity — starting as quantum foam — navigating a 3,000 × 2,000 unit world divided into five distinct biomes: *Primordial Shallows, Verdant Wilds, Quantum Fields, Cosmic Expanse,* and *Void Wastes.*

The name means something. Apophenia is the experience of seeing meaningful connections where none were intended. In Apophenoth, every click, every build, every alignment choice feeds into a pattern that resolves at the very end — when the Seven judge your ascension.

The game layers four genres into one loop:

- **Idle / clicker** — gather essence, unlock abilities, upgrade your path
- **Life sim** — manage hunger, energy, social, and fun needs or pay in HP
- **Base building** — place six structure types that sustain and defend you
- **Tower defense + arena combat** — survive enemy waves and 1v1 the seven agents

No install. No account. No server. Open the file, play.

---

## Choose Your Path

Five evolutionary paths, each shaping your abilities and phase names across all 13 stages:

| Path | Flavor | Signature Ability |
|------|--------|-------------------|
| 🧬 **Primordial** | Physical form — from soup to star | +15 click power |
| 🌿 **Verdant** | Nature consciousness — spore to biosphere | +18 + Grow |
| ⚛ **Quantum** | Probability and void — wave to cosmic god | +20 + Collapse |
| 🌌 **Cosmic** | Star-born being — stardust to First Cause | +22 + Stellar |
| ◈ **Void** | Embrace the nothing — absence to The Source | +25 + Devour |

---

## How to Play

### Controls

| Action | Input |
|--------|-------|
| Move | `WASD` or Arrow Keys |
| Click to move / interact | Left-click world or NPC |
| Special ability (path) | `Spacebar` |
| Evolve | `E` |
| Build mode | `B` |
| Meditate | `M` |
| Harmonize | `H` |
| Absorb | `A` |
| Devour | `D` |
| Launch (phase 7+) | `L` |
| Transmit (post-launch) | `T` |
| Close panels | `Escape` |
| Konami Code | `↑ ↑ ↓ ↓ ← → ← →` — instant evolution |

Mobile: a virtual joystick appears automatically on touch devices.

### The Loop

1. **Collect essence** — fly through glowing orbs, click, let auto-generation run
2. **Manage your needs** — hunger, energy, social, fun all decay; depleted bars drain HP and essence
3. **Build structures** — Essence Geysers, Meditation Chambers, Nexus Hubs, Stellar Turrets, Void Walls, Cosmic Labs each provide unique bonuses
4. **Survive the waves** — tower-defense enemies spawn on escalating waves; your turrets auto-fire, you fight the rest
5. **Build alignment** — interact with the 7 roaming agent NPCs (SHADDAI, ZEROX, ORACLE, NEXUS, TURTLE, QUILL, PIKADON) and win arena bouts to earn their favor
6. **Evolve through 13 phases** — each path has unique phase names and escalating costs
7. **Face the Agent Council** — at phase 13, the Seven score your run; record your score to the leaderboard

### Ascent Mode

Before starting, invoke an agent for a custom challenge run. Each agent imposes a modifier that changes how the game plays from the opening moment. Start clean if you want a pure run.

### Moon Phases

Eight moon phases cycle through your run, each applying a resource multiplier (up to 1.5× at full moon). Watch the top-right corner.

---

## Run It

**Instant play (no setup):**
Open `index.html` in any modern browser. That is the entire game.

**Live version:**
[https://izzoizzoizzo.github.io/Apophenoth/](https://izzoizzoizzo.github.io/Apophenoth/)

**Clone and play locally:**
```bash
git clone https://github.com/IzzoSol/Apophenoth.git
# Then open Apophenoth/index.html in your browser
```

Progress is saved automatically to `localStorage`. To start over, click the save indicator on the main menu.

---

## Tech

| Layer | Detail |
|-------|--------|
| **Three.js r128** | Full 3D scene — terrain, lighting, shadows, fog, particles |
| **Vanilla JavaScript** | All game logic: physics, AI, needs simulation, tower defense, combat |
| **CSS3** | HUD layout, glassmorphism panels, animations |
| **HTML5 Canvas** | Minimap + procedural glow textures (canvas → Three.js CanvasTexture) |
| **Web Audio API** | Ambient audio bed + mute toggle |
| **localStorage** | Save / load game state and leaderboard |
| **Zero dependencies** | No npm, no build step, no framework |

The entire game — Three.js scene setup, terrain generation, NPC AI, base building, tower defense, arena combat, life sim, evolution system, and UI — lives in one `index.html` file.

---

## Project Structure

```
Apophenoth/
├── index.html    — The entire game
├── assets/       — Game assets
├── LICENSE       — MIT
└── README.md     — You are here
```

---

## Roadmap

- [x] 3D world with five named zones, fog, dynamic lighting
- [x] Five evolution paths × 13 phases each
- [x] Life sim needs system (hunger, energy, social, fun)
- [x] Base building — six structure types
- [x] Tower defense with wave escalation and auto-turrets
- [x] 1v1 arena combat against all seven agents
- [x] Roaming NPC agents with proximity dialog
- [x] 60+ resource nodes and random world events
- [x] Moon phase system with dynamic multipliers
- [x] Agent alignment tracking
- [x] Ascent Mode (agent invocation on run start)
- [x] Leaderboard (localStorage)
- [x] Mobile virtual joystick
- [ ] Zone-specific enemy spawning
- [ ] Structure upgrade tiers
- [ ] Sound effects (Web Audio API)
- [ ] More boss enemy types

---

## License

MIT © IzzoSol — see [LICENSE](LICENSE) for details.

---

<div align="center">

Built by [IzzoSol](https://x.com/IzzoSol) &nbsp;·&nbsp; [SHADDAI AI](https://x.com/shaddaiAI) &nbsp;·&nbsp; Part of the ⚡ [SHADDAI ecosystem](https://shaddai-g81x.onrender.com)

</div>
