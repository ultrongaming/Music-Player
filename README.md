# Aura — Music Player (web edition)

A modern, dark-themed music player that runs entirely in your browser — no
Python, no Tkinter, no install. All 8 of your original tracks are included.

## How to use it
1. Unzip this folder somewhere on your computer.
2. Double-click **index.html** (or right-click → Open with → your browser).
3. That's it — your library loads on the left, click any song to play it.

Keep `index.html` and the `music` folder together in the same directory —
the player loads songs from `music/` next to it.

## Controls
- **Click a track** in the sidebar to play it instantly
- **Play / Pause** — big center button, or press `Space`
- **Previous / Next** — side buttons (Previous restarts the song if you're
  more than 3 seconds in, like most players)
- **Shuffle** — toggles a randomized play order (button glows amber when on)
- **Repeat** — cycles Off → Repeat All → Repeat One (a small "1" badge shows
  when repeating a single track)
- **Seek bar** — click or drag anywhere on the progress bar to jump
- **Volume slider** — bottom left
- **Search** — filter your library by song or artist name

## Adding more music
Drop more `.mp3` files into the `music/` folder, then add a matching entry
to the `TRACKS` array near the top of the `<script>` section in
`index.html` (file name, title, artist). No build step needed — just save
and refresh the page.

## Notes
- Album art is generated on the fly as a colorful gradient unique to each
  song (no embedded cover art in the source files).
- Works fully offline once the page is open — it only needs internet the
  first time to load the two Google Fonts (Fraunces + Manrope); if you're
  offline it'll fall back to your system fonts automatically.
