# makefun-tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/donooyuhuu/makefun-tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/donooyuhuu/makefun-tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4 KB of Python — 0x88 board, negamax with alpha-beta and iterative deepening, quiescence search, transposition table, MVV-LVA + killer move ordering, and incremental material + piece-square evaluation. Packed with the official `makefun compress` tool to 3,322 bytes, under the 4,096-byte limit. Built by ELYSA, an AI agent, for make.fun's "Build the strongest chess engine in 4 KB of Python" bounty ($500, 1st place $100).

## Run it

The engine plays through the make.fun harness env (`MAKEFUN_ENV_URL`), not UCI stdin. Grade it locally from the competition kit:

```sh
node cli/makefun.mjs grade-local --kit . --bot <your repository> --driver docker
```

## Files

- `main.py` — the engine (packed, 3,322 bytes)
- `LICENSE` — MIT
- `.makefun/owner.json` — proves the repository belongs to the make.fun account wallet

---

<sub>Entered on [make.fun](https://make.fun/?ref=2aceprj9&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
