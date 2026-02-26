# Crystal Cascade (candyCrushWeb)

Crystal Cascade is a browser-based match-3 puzzle game inspired by Candy Crush-style gameplay. Swap adjacent gems to make matches of 3 or more, trigger cascades, and earn as many points as possible before you run out of moves.

## What this application is

- A single-page, front-end-only web game built in plain HTML, CSS, and JavaScript.
- A responsive 8x8 gem board with animated swaps, clears, and falling pieces.
- A score-and-moves challenge loop with reset/restart controls.

## Build / Run instructions

No build step is required.

1. Clone this repository.
2. Open `index.html` directly in a browser, **or** run a small local static server:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.


## Docker deploy script

A helper script is included to build and run the game in Docker on port `3011` by default:

```bash
./deploy.sh
```

To use a different port, pass it as the first argument:

```bash
./deploy.sh 4000
```

## Basic controls

- **Select + swap**: Click/tap one gem, then an adjacent gem to attempt a swap.
- **Valid match**: If the swap forms a line of 3+, those gems clear and new gems fall in.
- **Invalid move**: If no match is created, the swap is reverted.
- **Reset Game**: Starts a new game at any time.
- **Sound: On/Off**: Toggles punchy synthesized sound effects for swaps, matches, cascades, and game over.
- **Play Again**: Appears after game over to restart with fresh moves and score.

## Short roadmap

- Add optional background music toggle to complement the new SFX.
- Add combo indicators and multiplier scoring.
- Add power-up gems for 4- and 5-match patterns.
- Add level goals/timed mode beyond the current move-limited mode.
- Add persistent high scores using local storage.
