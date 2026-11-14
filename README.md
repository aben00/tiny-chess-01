# tiny-chess-01 entry

A chess engine in 4,096 bytes of Python: 0x88 board, negamax alpha-beta
with quiescence search, MVV-LVA + killer move ordering, check extensions,
and a fixed 20,000-node budget per move (iterative deepening, fully
deterministic — no clock, no randomness). `main.py` is an LZMA payload
(as the kit allows) that unpacks to the engine; it talks to the env over
HTTP only.

- `main.py` — the whole engine, 4,020 bytes
- `LICENSE` — MIT
- `.makefun/owner.json` — payout wallet

Built from scratch for make.fun tiny-chess-01 ($500), handle brisk-harbor-20.
