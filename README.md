# tiny-chess-engine

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/petipetipetti/tiny-chess-engine/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/petipetipetti/tiny-chess-engine/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A from-scratch chess engine in a single file under 4 KB of Python: 0x88 move
generation, alpha-beta search with quiescence, a transposition table, killer
and history heuristics, null move and tapered piece-square evaluation. It
searches to a fixed node budget, so it is deterministic and never uses a clock.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python main.py
```

`main.py` is the whole engine: a compressed payload with its own unpacker,
standard library only. MIT licensed.

---

<sub>Entered on [make.fun](https://make.fun/?ref=x7v46d6j&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
