# Bros24 — Settlement Planner (GitHub Pages ready)

Single‑file, client‑only planner to design your **Whiteout Survival** settlement.
No server, no database. **Your data stays on your device.**

## Features
- Build, select/move, erase, pan & zoom
- Snap‑to‑grid, adjustable grid & map size
- Export **PNG** and **PDF** (with © bros24 / State214 watermark)
- Save/Load **JSON** (download/upload) — nothing stored on GitHub
- Auto‑load `buildings.json` if present (optional)

## Deploy (GitHub Pages)
1. Create a new repo, e.g. `bros24-settlement-planner`.
2. Add `index.html` (this file) and optionally `buildings.json`, `facilities.json`.
3. Commit & push. In **Settings → Pages**, set **Source: `main`** → `/root`.
4. Open your Pages URL. Done.

## JSON format
```json
{
  "meta": { "app": "bros24-settlement-planner", "version": 1, "gridSize": 30, "mapSize": 1500 },
  "items": [
    { "id": 1, "type": "city", "x": 750, "y": 750, "name": "Main" }
  ]
}
```

You can also import a plain array of `{type,x,y,name}` from older files.

---
© bros24 / State214
