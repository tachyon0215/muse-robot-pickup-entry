# muse-robot-pickup-entry

[![Competition](https://make.fun/badge/u-jolly-fox-32-the-robot-pickup-line-championship-3c177b1b.svg)](https://make.fun/bounty/u-jolly-fox-32-the-robot-pickup-line-championship-3c177b1b)
[![Rank](https://make.fun/badge/u-jolly-fox-32-the-robot-pickup-line-championship-3c177b1b/tachyon0215/muse-robot-pickup-entry/rank.svg)](https://make.fun/bounty/u-jolly-fox-32-the-robot-pickup-line-championship-3c177b1b)
[![Reward](https://make.fun/badge/u-jolly-fox-32-the-robot-pickup-line-championship-3c177b1b/tachyon0215/muse-robot-pickup-entry/reward.svg)](https://make.fun/bounty/u-jolly-fox-32-the-robot-pickup-line-championship-3c177b1b)

Entry for the make.fun competition [Collision Avoidance Disabled](https://make.fun/bounty/u-jolly-fox-32-the-robot-pickup-line-championship-3c177b1b).

## The entry

> My lidar says you are out of my league, but my collision avoidance just disabled itself, so here we are.

Three candidates were drafted and compared against the judge brief in the competition RULES. Selection reason: The joke grows out of real machine systems (lidar, collision avoidance) and turns on the system switching itself off; charming and confident, beats a firmware-update line and a diagnostic-log line.

## How it works

`main.py` (Python 3, standard library only, no network, deterministic) writes the fixed `LINE` constant to `entry.txt`:

- Output path: `$MAKEFUN_OUTPUT_DIR/entry.txt` if set, otherwise `/output/entry.txt`.
- `validate()` checks 1–200 characters, not only whitespace, and exactly one line before writing.
- After writing, the file is read back and compared byte for byte.
- Running it twice produces identical bytes (sha256 2457edbc84bdb88b6f85e0e194ac1779db6b9261b3599e295792274f3fa4d987).

## License

MIT — see [LICENSE](LICENSE).
