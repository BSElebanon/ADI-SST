# ADI SST / Stats Simplified Tracker

**ADI SST** (Stats Simplified Tracker) is a lightweight, offline, browser-based basketball scorekeeping and statistics tracker designed for local tournaments.  
It allows you to track **5v5 basketball games**, automatically calculate player stats, team totals, and efficiency, and generate a **printable PDF match report**.

---

## Features

- Add your team and players with jersey numbers.
- Track real-time stats:
  - Points (FT, 2PT, 3PT)
  - Rebounds
  - Assists
  - Steals
  - Blocks
  - Turnovers
  - Fouls
  - Field goal and free throw percentages
  - Efficiency formula:  
    `(PTS + REB + AST + STL + BLK − Missed FG − Missed FT − TO)`
- Undo last event functionality.
- Beautiful, modern, futuristic UI with smooth inputs.
- Export a **black-and-white PDF match report** including match metadata:
  - Opponent
  - Date & Time
  - Arena
- Fully offline, no backend or database required.
- Works on desktop and mobile browsers.
- Can be added to Home Screen as a “web app” on phones.

---

## Getting Started

1. **Open `index.html`** in a browser (desktop or mobile).  
   - Or host it online via GitHub Pages / Vercel for easy access via a link.
2. **Setup Page**:
   - Enter your team name.
   - Enter opponent name, match date/time, and arena.
   - Add your players with names and numbers.
   - Click **Start Game** to open the stats table.
3. **Stats Page**:
   - Enter commands in the input bar:
     - `32 1` → Player #32 made a 1-point free throw
     - `32 2` → Player #32 made a 2-point field goal
     - `32 3` → Player #32 made a 3-point field goal
     - `32 1x` → Player #32 missed a 1-point free throw  
       *(Add `x` for missed shots)*
     - `32 f` → Player #32 committed a foul  
       *(Other commands: `r` rebound, `a` assist, `b` block, `s` steal, `t` turnover)*
   - Use **Undo** to remove the last event.
   - Click **Download PDF** to save a full match report.

---

## PDF Export

- Generates a clean, black-and-white printable PDF.
- Includes team totals and all individual stats.
- Automatically downloads to your device.
- Works offline, no server required.

---

## Hosting Online

- Host via **GitHub Pages** for free:
  1. Upload `index.html` to a GitHub repository.
  2. Enable GitHub Pages in repository settings.
  3. Share the link with any device.
- Or use **Vercel** / similar services for instant deployment.

---

## Notes

- Designed for **local tournaments**; does not require expensive hardware.
- Works fully offline, all stats are stored in browser memory/localStorage.
- Ideal for coaches, players, and local leagues who want detailed game stats without subscribing to professional systems.
