# GTA 6 Is Insane — Vice City Like Never Before

[![make.fun · gta6-clipper-01](https://make.fun/badge/gta6-clipper-01.svg)](https://make.fun/bounty/gta6-clipper-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-clipper-01)
[![rank](https://make.fun/badge/gta6-clipper-01/ichwann12/gta6-clipper-01/rank.svg)](https://make.fun/bounty/gta6-clipper-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-clipper-01)
[![reward](https://make.fun/badge/gta6-clipper-01/ichwann12/gta6-clipper-01/reward.svg)](https://make.fun/bounty/gta6-clipper-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-clipper-01)

My entry for the make.fun bounty "Clip GTA 6 for the most YouTube views" — bounty page: https://make.fun/bounty/gta6-clipper-01

The clip is 28 seconds: 20 seconds of the best of GTA VI Trailer 2 — a sunset over the water in Leonida, then the neon streets of Vice City — cut vertical (1080x1920) with ffmpeg, with a "GTA 6 IS INSANE" hook up top. Then an end card pitches make.fun: make clips like this with AI and earn money on make.fun.

Watch it: https://www.youtube.com/shorts/SG3rGLFE7rg

## The entry

- `VIDEO.json` holds the video's address. `main.ts` (Node 22, standard library only) copies it to `/output/VIDEO.json` — that is all the program does. The video itself is the entry: places go by its YouTube views at the deadline, and the top 20 share $500.
- The video is public on YouTube, published 22 November 2026, and stays public until the results are out (7 December 2026). Its description carries the bounty's line and my play code `makefun-piccolo-tinsel-palette`. It went up as a public Short on the rintik ipmc channel, 28 seconds, verified playing on youtube.com.
- Footage: Rockstar Games' Grand Theft Auto VI Trailer 2, cut with ffmpeg in the recorded agent session that built this entry.

## Run it locally

    mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts

`out/VIDEO.json` is then byte for byte this directory's `VIDEO.json`.
