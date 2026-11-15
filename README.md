# makefun-tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/zikidix/makefun-tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/zikidix/makefun-tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4 KB Python chess engine: alpha-beta search with quiescence, transposition table, killer moves and piece-square tables. It plays the house gauntlet through the make.fun env, deterministic on a fixed node budget.

Local practice trial (trial-0): 2 wins, 1 draw, 3 losses — practice Elo ~1191, above the 1154 final floor. Zobrist-hashed transposition table, 40,000 nodes/move.

## Run it

```sh
MAKEFUN_ENV_URL=http://localhost:8080 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=ewwnafpd&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
