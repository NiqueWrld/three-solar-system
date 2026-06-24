# Three Solar System

An interactive 3D solar system in a single HTML file, built with [Three.js](https://threejs.org/) and [Tailwind CSS](https://tailwindcss.com/).

Scroll to fly past every planet — or hit **F** to take the controls of your own spaceship.

## Features

- Textured Sun and all 8 planets (NASA-derived maps), with Earth's rotation synced to real UTC.
- Moons for Earth, Mars, Jupiter, Saturn, Uranus and Neptune, with real sidereal rotation rates.
- Saturn's rings, asteroid belt, and Kuiper belt (instanced for performance).
- Procedural twinkling starfield with custom shader and a warm point-light Sun.
- Three nearby exoplanet systems: Alpha Centauri, TRAPPIST-1, Kepler-90.
- Scroll-driven cinematic camera that focuses each body on its sun-lit side.
- Flyable, textured spaceship with chase camera, FOV boost, banking, engine glow, and sphere-vs-body collisions.
- Mode and ship transform persisted in `localStorage`.

## Controls

| Action | Key |
|---|---|
| Toggle flight mode | `F` / Esc |
| Thrust forward / back | `W` / `S` |
| Yaw | `A` / `D` |
| Pitch | `↑` / `↓` |
| Roll | `Q` / `E` |
| Boost | `Space` |
| Brake | `Shift` |
| Look | Mouse (click canvas to lock) |

## Run

No build step. Open `index.html` in a modern browser, or serve it locally:

```powershell
npx serve .
```

## Credits

Planet textures from [jeromeetienne/threex.planets](https://github.com/jeromeetienne/threex.planets) (NASA-derived, public domain).
