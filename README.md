# 🥁 Drum Star

A kid-friendly drum learning app inspired by [Melodics](https://melodics.com) — hit the falling gems right on the beat!

**Live app:** https://drum-star.vercel.app

## Features
- 15 lessons across 4 stages: First Beats → Groove Builder → Rhythm Explorer → Drum Star (60–115 bpm)
- Melodics-style falling-note gameplay with a 4-count lead-in, Perfect/Good/Miss judging, streaks and 1–3 star ratings
- Lessons unlock one at a time — earn at least ★ to open the next
- Practice mode (75% speed) for first tries
- Free play mode with a full 5-piece kit (kick, snare, hi-hat, tom, crash — all synthesized live with Web Audio)
- Play by tapping pads (iPad-optimized) or keyboard keys D F J K L
- Progress saved in localStorage; installable to the iPad home screen as a full-screen web app

## Structure
Zero build step — plain static files:
- `index.html` — the entire app (HTML + CSS + JS)
- `manifest.json` — web app manifest for Add to Home Screen
- `icon-180.png`, `icon-512.png` — app icons

## Deploy
Hosted on Vercel. Any static host works — just serve the folder.
