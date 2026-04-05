# Snake Game

A classic Snake game served as a single-page web app on localhost.

## Requirements

- Python 3 (built-in, no extra packages needed)

## Start the server

```bash
python3 server.py
```

The server starts on **http://localhost:8081** and opens the game in your default browser automatically.

To stop the server, press `Ctrl+C` in the terminal.

## Controls

| Key | Action |
|-----|--------|
| `Enter` / `Space` | Start game |
| `Space` | Pause / Resume (during game) |
| `Enter` | Restart (after game over) |
| `Arrow Keys` or `WASD` | Move snake |

## Gameplay

- **Regular food** (red circles) — 2 always on the board; eating one grows the snake by 1 and scores +1.
- **Super food** (gold glowing circle) — 1 per game; eating it grows the snake by 2 and scores +1.
- **Wrap-around walls** — the snake passes through any wall and reappears on the opposite side.
- The game ends only on self-collision.

## Project structure

```
snake_game/
├── index.html   # Game UI + logic (single page)
├── server.py    # Python HTTP server
└── README.md    # This file
```
