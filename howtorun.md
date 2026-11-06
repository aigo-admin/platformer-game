# NOCTURNE — How to Run

A self-contained monochrome 2D platformer made with HTML, CSS, Canvas, and vanilla JavaScript. No build step or external game framework is required.

## Run locally

1. Extract the ZIP file.
2. Open `index.html` in a modern browser (Chrome, Firefox, Edge, or Safari).
3. Click **BEGIN JOURNEY**.

If your browser restricts local files, start a tiny local web server from the extracted folder:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Controls

- **A / D** or **Left / Right arrows** — move
- **Space**, **W**, or **Up arrow** — jump (press again after landing)
- **Esc** — pause / resume
- **R** — restart current chapter
- **Levels** — chapter select (completed chapters remain unlocked)
- **Ⅱ** — pause button

## Included

- Five handcrafted chapters with increasingly demanding jumps and hazards
- Moving platforms, spikes, checkpoints, and a finish beacon
- Responsive Canvas rendering, atmospheric particles, parallax scenery, fog, and character animation
- Pause, restart, chapter select, deaths counter, and saved chapter progress (`localStorage`)
- Sound toggle (procedural Web Audio effects; audio starts after a user interaction)

Progress is saved by the browser for this origin. Clearing browser site data resets it.
