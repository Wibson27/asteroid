# Asteroid 🪨

<!-- language -->
<p>
  <img src="https://img.shields.io/badge/Python-100%25-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pygame-Framework-6aa84f?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Built%20from%20scratch-%E2%9C%93-brightgreen?style=for-the-badge"/>
</p>

A simple asteroid shooter. Rocks fly at you. You shoot them. That's it.

No frameworks doing the heavy lifting. No AI writing the logic. Just Python, Pygame, and me figuring things out one bug at a time.

---

## how to run

```bash
git clone https://github.com/Wibson27/asteroid.git
cd asteroid
pip install pygame
python main.py
```

---

## controls

| key | action |
|-----|--------|
| `W A S D` | move |
| `Space` | shoot |

---

## structure

```
asteroid/
├── main.py            # game loop
├── player.py          # player ship
├── asteroid.py        # asteroid logic
├── asteroidfield.py   # spawning
├── shot.py            # bullets
├── circleshape.py     # base shape / collision
├── constants.py       # game constants
└── logger.py          # logging
```

---

## why this exists

I've been coding for a while. But looking back, most of what I built had something helping me — a tutorial, a framework, an AI filling in the blanks.

This is the first thing I built where none of that was true.

It's small. There's no score, no game over screen, nothing fancy. But I understood every line before I typed it, and I think that's the point I was trying to reach.

I'm sharing it because I'm at the beginning of something, and I want to remember what that felt like.

---

<p align="center"><sub>rifqi — 2025</sub></p>
