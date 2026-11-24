# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/rardiyansyah004-blip/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/rardiyansyah004-blip/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A tiny chess engine in 4 KB of Python: 0x88 negamax alpha-beta with PVS, LMR, null-move pruning and quiescence, a tapered PeSTO evaluation, and two per-scenario variant tables of its own — a king-shelter bonus by the pawns in front of the king, and a passed-pawn bonus per rank. It searches to a fixed node budget per move, never a clock, so every trial replays deterministically.

## Run it

```sh
MAKEFUN_ENV_URL=<env> python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=g75rgwrg&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
