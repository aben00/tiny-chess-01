# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/aben00/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/aben00/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4,096 bytes of Python: 0x88 board, negamax alpha-beta
with transposition table and quiescence search, MVV-LVA + killer move
ordering, check extensions, tapered MG/EG piece-square tables, and
repetition-aware search — fixed 50,000-node budget per move, fully
deterministic (no clock, no randomness). `main.py` is an LZMA payload
(as the kit allows) that unpacks to the engine; it talks to the env over
HTTP only.

- `main.py` — the whole engine, 3,484 bytes
- `src.py` — the readable source (uncommitted, kept in the repo folder)
- `LICENSE` — MIT
- `.makefun/owner.json` — payout wallet

Built from scratch for make.fun tiny-chess-01 ($500), handle brisk-harbor-20.

## Run it

```sh
python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=bh1grvtt&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
