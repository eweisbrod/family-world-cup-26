# World Cup 2026 Survivor Pool

A real-time FIFA World Cup 2026 survivor pool web app adapted from the NCAA Survivor Pool.

## How It Works
- There are **8 pick windows** aligned to the knockout stage schedule
- Each window covers a 2-day (or 3-day) block of games
- Pick **one team** per window that you think will win their game
- If your team wins, you survive to the next window
- You can only use each team **once** the entire tournament
- If your team loses, you're eliminated
- **Special rule**: if ALL remaining players pick losing teams in the same window, no one is eliminated — the game continues!

## Pick Windows
| # | Round | Dates | Games |
|---|-------|-------|-------|
| 1 | Round of 32 | Jun 28–29 | 4 |
| 2 | Round of 32 | Jun 30–Jul 1 | 6 |
| 3 | Round of 32 | Jul 2–3 | 6 |
| 4 | Round of 16 | Jul 4–5 | 4 |
| 5 | Round of 16 | Jul 6–7 | 4 |
| 6 | Quarterfinal | Jul 9–11 | 4 |
| 7 | Semifinal | Jul 14–15 | 2 |
| 8 | Final | Jul 19 | 1 |

## Features
- Firebase Realtime Database for shared picks across all players
- Live score fetching from ESPN soccer API with auto-refresh
- Board view to see all players' picks at a glance
- Dynamic bracket building (R16/QF/SF/Final resolved from earlier results)
- Mobile-first dark UI
