# Tetris

A single-file browser Tetris game built with plain HTML, CSS, and JavaScript.

The whole game lives in `index.html`. There is no build step, no package install,
and no backend server required.

## Features

- Full Tetris gameplay
- Move left and right
- Rotate pieces
- Soft drop and hard drop
- Collision detection and piece locking
- Line clear and score system
- Start, pause, game over, and restart flow
- Difficulty selection
- Dark and light theme
- Sound effects with sound toggle
- Visual effects for line clears
- Local best score saving

## How To Run

1. Open `index.html` in a modern browser.
2. Click `Start Game`.
3. Play immediately.

You can also share `index.html` directly with other people. They should be able
to run it locally in browsers like Chrome, Edge, Firefox, or Safari.

## Controls

- `Left / Right Arrow`: move
- `Up Arrow` or `X`: rotate clockwise
- `Z`: rotate counterclockwise
- `Down Arrow`: soft drop
- `Space`: hard drop
- `P`: pause or resume

## Sound

- Use the `Sound On / Sound Off` button in the top-right corner.
- Many browsers require one user interaction before sound playback is allowed.

## Persistence

The game uses browser `localStorage` to save:

- best score
- selected theme
- sound on/off preference

## Files

```text
.
|-- index.html
`-- README.md
```
