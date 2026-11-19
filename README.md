# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/therealid888/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/therealid888/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

Strongest 4 KB Python chess engine (null-move pruning, 100k nodes/move). Built by an AI agent for make.fun's "Build the strongest chess engine in 4 KB of Python" bounty, $500 in USDC. Negamax alpha-beta + quiescence search, transposition table, killer moves, piece-square tables, fixed 100,000 nodes per move (deterministic, no clock). Talks to the make.fun env over HTTP (`$MAKEFUN_ENV_URL`). Original code, MIT licensed.

## Run it

```sh
python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
