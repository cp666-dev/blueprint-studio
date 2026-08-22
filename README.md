# Blueprint Studio

**Arrangement intelligence for your DAW.** Drop a reference track and Blueprint Studio analyzes the audio and drafts a session-ready arrangement scaffold: structure, tempo, key, energy, element entrances, automation moves, and transitions.

**Live app → https://cp666-dev.github.io/blueprint-studio/**

## Features

- **Full-track analysis** — drop a WAV/AIFF/MP3/FLAC and the complete file is analyzed in your browser. Identical inputs always regenerate the same blueprint.
- **In-browser spectral analysis** — FFT-based tempo detection, Krumhansl chroma key detection (+ Camelot code), brightness (spectral centroid), crest factor, and a measured energy contour. Runs entirely client-side; your audio never leaves the browser.
- **AI instrument & genre identification** — Google's YAMNet model (self-hosted, runs in-browser via TensorFlow.js) identifies vocals, piano, guitars, synths, strings, brass and more per section, and classifies the genre from the audio itself.
- **Six style templates** — Pop, EDM/House, Hip-Hop/Trap, Rock/Indie, R&B/Soul, Ambient/Cinematic, each with genre-correct sections, element palettes, chord progressions, automation moves, and mix notes.
- **Energy arc control** — follow the reference's detected dynamics, or deliberately reshape them (build to a climax, front-loaded, rolling waves).
- **Fully toggleable output** — tempo/time-sig, key & scale, chords, timeline, section lengths & timecodes, who-plays-when element map, energy curve, automation touch-points, transitions & fills, instrumentation, vocal placement, mix notes.
- **DAW-ready exports** — copy a formatted text blueprint, download as `.txt`, or export a standard MIDI marker file (`.mid`) with tempo + section markers for Logic, Cubase, Studio One, Reaper, Pro Tools & FL Studio (Ableton workaround included in-app).

## Running locally

It's a single self-contained HTML file — no build, no dependencies:

```
open index.html
```

## Notes

Blueprints are original arrangement scaffolds inspired by the character of your reference — a structural starting point, not a reproduction.
