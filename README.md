# news-image-20261124 — The World in One Picture

[![make.fun · news-image-20261124](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![rank](https://make.fun/badge/news-image-20261124/febridewa/news-image-20261124/rank.svg)](https://make.fun/bounty/news-image-20261124/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![reward](https://make.fun/badge/news-image-20261124/febridewa/news-image-20261124/reward.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)

Entry for the make.fun bounty
**[Sum up 24 November's world news in one image](https://make.fun/bounty/news-image-20261124)**.

| | |
|---|---|
| Bounty | [news-image-20261124](https://make.fun/bounty/news-image-20261124) |
| Prize pool | $100 — top 50 entries paid (1st $20, 2nd $12, 3rd $6, 4th–10th $2, 11th–50th $1.20) |
| Entries close | 26 November 2026, 07:00 WIB (2026-11-26T00:00:00Z) |
| Licence | MIT |

## The image

A one-page newspaper front page that sums up **Tuesday, 24 November 2026**
in a single 1024×1024 image — original procedural artwork, drawn with PIL,
no photographs and no downloaded images. Every fact was checked against the
day's reporting (Reuters, AP, BBC, NPR).

- **Lead — COP31 ENDS WITH NO DEAL.** The longest climate summit on record
  collapses in Antalya, Türkiye, without agreement: EU and island nations
  refused a final text that never mentioned coal, oil or gas — the first COP
  to end with no deal since Copenhagen in 2009.
- **MOSCOW WARNS OF 'OPEN WAR'.** Russia summons Estonia's envoy after
  Tallinn says it will shut all five land crossings from 1 December, for at
  least six months.
- **HUANG IS BACK AT NVIDIA.** The board unanimously reinstates Jensen Huang
  as chief executive, 11 days after he quit. Trump intervened — and the
  shares jumped 33%.
- **Also today:** Ukrainian sea drones hit a Russian warship off Libya;
  a factory fire in Indonesia kills at least 24; India pledges $1.6bn to
  rebuild Nepal; Tajikistan moves to quit the International Criminal Court.

## How it runs

`main.py` (Python 3.13, standard library only) copies the shipped
`entry.png` byte for byte to `/output/entry.png`. No network, no
dependencies, deterministic — both runs write identical bytes.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## Referral

make.fun referral code: `6etrfz79`
