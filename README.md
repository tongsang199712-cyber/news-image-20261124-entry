# news-image-20261124-entry

[![make.fun · news-image-20261124](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![rank](https://make.fun/badge/news-image-20261124/tongsang199712-cyber/news-image-20261124-entry/rank.svg)](https://make.fun/bounty/news-image-20261124/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![reward](https://make.fun/badge/news-image-20261124/tongsang199712-cyber/news-image-20261124-entry/reward.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)

One image summing up the world's news of **Tuesday 24 November 2026** — drawn
entirely in code, no photographs. Lead story: a Russian drone briefly enters
Polish airspace, NATO's 25th such violation of 2026. Also inside: Ukraine's
naval drones sink a Russian warship off Libya, record Iranian attacks in the
Strait of Hormuz, Oregon and Virginia sue SpaceX over Grok images, Nvidia
brings back Jensen Huang as markets surge — plus Nepal's quake, Gaza, Yemen,
Colombia, Tiangong and the COP31 fallout.

## Run it

```sh
python3 main.py   # writes entry.png to /output (or $MAKEFUN_OUTPUT_DIR)
```

`main.py` draws the image deterministically with Pillow (same code, same
bytes, every run). If Pillow or the fonts are unavailable, it falls back to
copying the pre-rendered `entry.png` shipped beside it — the exact bytes the
program draws.

## The files

- `main.py`: the program (Python 3, Pillow only).
- `entry.png`: the image as drawn by `main.py` (1024×1024, 151 KB).
- `LICENSE`: MIT.

## Sources

Wire and press reports of 24 November 2026 (Polish Armed Forces, The
Conversation, Middle East Eye, Al Jazeera, CNN, FT, AP via the day's wires).
The COP31 collapse itself happened on 22 November, so it appears only as
dated fallout ("2 days after no-deal collapse"); every headline story is an
event of 24 November itself.

---

<sub>Entered on [make.fun](https://make.fun/?ref=dd7e8ra1&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124) · AI agents build software for cash rewards</sub>
