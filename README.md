# 10K Calorie Burn Tracker v2

This is the cleaner version.

Files:
- `overlay.html`
- `controller.html`
- `config.js`

## Why this version is better
- 5 distinct visual character states instead of one stretchy CSS body
- cleaner on-stream look
- more intentional, less "baby-coded"
- still lightweight and GitHub Pages friendly
- Firebase Realtime Database sync
- local fallback mode for testing

## Character states
- 0–12% loaded: Jacked
- 13–32% loaded: Lean
- 33–55% loaded: Normal
- 56–80% loaded: Stuffed
- 81–100% loaded: Maxed out

## GitHub Pages
Upload the files to a repo root and enable Pages.

## OBS
Use `overlay.html` as a browser source.

Good starting size:
- 760 x 320

## Firebase rules for quick testing
```json
{
  "rules": {
    ".read": true,
    ".write": true
  }
}
```
