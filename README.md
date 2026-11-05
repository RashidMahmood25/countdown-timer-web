# Countdown Timer (Web)

A single-page countdown timer. Two modes:

1. **Duration timer** — enter minutes and seconds (or tap a preset: 5 min, 10 min,
   25 min Pomodoro, 1 hour), then Start / Pause / Reset.
2. **Count down to a date** — pick any future date and time and watch the
   days / hours / minutes / seconds tick down.

Shows a live progress bar, and when the timer finishes it displays "Time's up!"
and plays a short beep (if the browser allows sound).

## How to use

1. Open `index.html` in any modern browser (double-click the file, or serve the
   folder with any static server).
2. Choose a mode, set the time, press **Start**.
3. The timer runs in this page only — it stops if you close or reload the tab.

## What was practiced

- Single self-contained HTML/CSS/JS page (no build step, no dependencies)
- `setInterval` ticking, `Date` math, and pause/resume by storing the remaining time
- Progress-bar calculation from elapsed vs total time
- Optional Web Audio beep on completion (wrapped in try/catch so silence never breaks the page)
