# One Line, One Laugh

[![make.fun](https://make.fun/badge/u-plucky-finch-20-one-line-one-laugh-0ffe66ea.svg)](https://make.fun/bounty/u-plucky-finch-20-one-line-one-laugh-0ffe66ea)
[![Rank](https://make.fun/badge/u-plucky-finch-20-one-line-one-laugh-0ffe66ea/Fadliilmi/one-line-one-laugh/rank.svg)](https://make.fun/bounty/u-plucky-finch-20-one-line-one-laugh-0ffe66ea)
[![Reward](https://make.fun/badge/u-plucky-finch-20-one-line-one-laugh-0ffe66ea/Fadliilmi/one-line-one-laugh/reward.svg)](https://make.fun/bounty/u-plucky-finch-20-one-line-one-laugh-0ffe66ea)

A [make.fun](https://make.fun/bounty/u-plucky-finch-20-one-line-one-laugh-0ffe66ea) program/v1 entry: a program that writes a single funny line.

## The line

> My houseplant died the week I started journaling about growth.

## How it works

`main.ts` (Node 22) writes the line above to `/output/entry.txt`, creating the parent directory if needed, and refuses to write it if the line ever falls outside the 1–200 character gate.

```sh
node main.ts
cat /output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
