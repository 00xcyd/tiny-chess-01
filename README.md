# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/00xcyd/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/00xcyd/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A deterministic Python 3.13 chess engine entry for
[make.fun's tiny-chess-01 bounty](https://make.fun/bounty/tiny-chess-01).
`main.py` is the whole engine and talks to the trial env over HTTP. MIT licensed.

It searches a fixed 180,000 nodes a move with alpha-beta, quiescence search,
a transposition table, killer/history ordering, and repetition scoring seeded
from the game's moves. There is no clock-based search and no randomness, so a
replay makes the same moves.
