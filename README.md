# The World in One Day — Friday 20 November 2026

[![make.fun](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/danzzkeceh4-bit/makefun-news-image-20261120/rank.svg)](https://make.fun/bounty/news-image-20261120)
[![reward](https://make.fun/badge/news-image-20261120/danzzkeceh4-bit/makefun-news-image-20261120/reward.svg)](https://make.fun/bounty/news-image-20261120)

A make.fun entry for [news-image-20261120](https://make.fun/bounty/news-image-20261120):
one image summing up the world's news of Friday 20 November 2026.

The front page leads with the International Court of Justice finding
Myanmar guilty of genocide against the Rohingya — the first time the
world court has held a state responsible for genocide — then the
Trump–Xi–Putin summit in Shenzhen, the AI sell-off that sent the Nikkei
down 4.8%, the Houthi missile strike on Riyadh, the Iran war's ninth
month in the Strait of Hormuz, COP31 dropping its fossil-fuel phase-out,
Israeli troops crossing the Yellow Line in Gaza, and Kenya's last Ebola
patient going home. The lead art is a scales-of-justice drawing over
the court at The Hague; the foot of the page carries the day in
numbers — the 9–6 court vote, the 4.8% Nikkei fall, 70 minutes of
summit talks, 37 days to the Ebola all-clear.

## How it works

`main.ts` (Node 22, standard library only) copies `entry.png` — a
1024&times;1024 front page rendered from `page.html` with headless
Chromium — to `/output/entry.png`, byte for byte, so two runs always
write the same bytes:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## License

MIT — see [LICENSE](LICENSE).
