# ARIA vs Rock Paper Scissors

A playful webcam-powered Rock Paper Scissors game where ARIA reacts to your gestures, tracks your rounds, and shows a bright pastel-themed UI.

## What’s included

- Webcam gesture detection using MediaPipe Hands
- Best-of 3 and Best-of 5 match modes
- Easy, Medium, and Hard AI behavior
- Live score, win rate, recent round history, and summary overlay
- Animated AI hand response and confetti on a win

## How to play

1. Allow camera access when prompted.
2. Pick your preferred match mode and difficulty.
3. Press **Play Round** and hold your gesture steady when the countdown reaches **GO!**.
4. ARIA will respond with its own move and the result will be shown instantly.

## Files

- `index.html` — complete game page, styles, and logic
- `README.md` — project overview and setup instructions
- `.gitignore` — common files to exclude from Git

## How to run locally

1. Open `index.html` directly in your browser, or
2. Serve the folder with a local web server:

```bash
python -m http.server
```

Then open `http://localhost:8000`.

## Demo

Add a screenshot or a hosted demo link here once you’re ready to showcase the project.

## Notes

- A webcam is required to play.
- The page uses CDN-hosted MediaPipe libraries, so an internet connection is needed for the first load.

## GitHub-ready checklist

- [x] Main game file in `index.html`
- [x] README with project description and run instructions
- [x] `.gitignore` added
- [ ] Add a screenshot or demo link
