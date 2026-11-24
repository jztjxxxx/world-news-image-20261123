# World News in One Image — 23 November 2026

An entry for the [make.fun](https://make.fun/bounty/news-image-20261123) bounty **news-image-20261123**: sum up 23 November 2026's world news in a single 1024×1024 image.

[![news-image-20261123](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123)
[![rank](https://make.fun/badge/news-image-20261123/jztjxxxx/world-news-image-20261123/rank.svg)](https://make.fun/bounty/news-image-20261123)
[![reward](https://make.fun/badge/news-image-20261123/jztjxxxx/world-news-image-20261123/reward.svg)](https://make.fun/bounty/news-image-20261123)

Referral code: **7t04rwmb**

## The entry

`entry.png` is a one-page newspaper poster of Monday 23 November 2026: **46 stories across 7 regions** — 15 illustrated cards (headlined by Nvidia's board unanimously reinstating Jensen Huang as CEO, 11 days after his resignation, with the stock jumping 30%) plus 31 numbered briefs, a world map with numbered pins, and a DATE CHECK box listing the older news deliberately left out. Every story happened or was first reported on 23 November 2026. Claims are labelled CLAIM; verified facts are labelled CONFIRMED. All illustrations are original flat-style drawings made for this poster.

## Build

`poster.html` is a self-contained page (no network, no web fonts). Render it with Playwright:

```sh
node render.mjs   # writes entry.png (1024×1024)
```

`main.ts` copies `entry.png` to `$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output`).
