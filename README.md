# Three.js Procedural Circuit Racer

Een volledig procedural circuit racer gebouwd met Three.js. Alles (track, auto’s, omgeving, textures) wordt in code gegenereerd — geen externe assets.

## Features
- Gesloten circuit met heuvels
- 10 AI-tegenstanders (aanpasbaar)
- Medium fysica (acceleratie, grip, remmen, barriers)
- Chase camera + HUD (ronde, positie, snelheid)
- Procedural auto’s en bomen
- Basis engine sound via Web Audio API

## Spelen
1. Clone of download de repo
2. Open `index.html` in een moderne browser (Chrome, Edge, Firefox)

Of host het via GitHub Pages.

## Besturing
- **W / ↑** = gas
- **S / ↓** = achteruit / rem
- **A/D of ←/→** = sturen
- **Space** = handrem
- **R** = reset naar start

## Aanpassen
Bovenaan de script-sectie:
- `NUM_AI` — aantal tegenstanders (8–16)
- `TOTAL_LAPS`
- Trackvorm in `generateTrack()`
- Fysica-parameters in `updateCar()`

Gebouwd als speelbare basis. Verbeteringen (betere AI, drift, meerdere tracks, post-processing) zijn welkom!
