# Writing Log

A single-page tracker for daily novel progress: session timer, word counts, pace against a target date, mood, and voice-dictated notes. No build step, no dependencies, no server — all data stays in your browser.

## Host it on GitHub Pages

1. Create a new repository (e.g. `writing-log`).
2. Add `index.html` to the root of the repo and commit.
3. Repo → **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main`, folder: `/ (root)` → Save.
4. Your app appears at `https://<username>.github.io/writing-log/` within a minute or two.

Use the same browser each time — your log lives in that browser's local storage. Making the repo public is required for Pages on a free account; the repo only contains the app, never your data.

## Using it

- **Target** (top right) sets your starting word count, tracking start date, target word count, and finish date. Pace math needs all four.
- **Start writing / Stop writing** runs a live timer. On stop, the start and end times are dropped into the time fields automatically — just add your word count and log it.
- Or skip the timer: enter minutes directly, or enter start and stop times and the app totals them.
- **Log this session** saves words, time, mood, and notes to the selected day. Multiple sessions per day are fine; they add up.
- Click any calendar day to log or review that day instead of today. Cell shading scales with words written; a gold dot marks days that have a note.
- **Record note** dictates into the notes box (Chrome, Edge, or Safari; the browser will ask for microphone permission once).

## Back up your data

Browser storage can be cleared by the browser. **Export** downloads a JSON backup; **Import** restores one — also how you move your log to another machine.
