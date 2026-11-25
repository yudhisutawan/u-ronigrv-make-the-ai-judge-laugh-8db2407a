[![make.fun · u-ronigrv-make-the-ai-judge-laugh-8db2407a](https://make.fun/badge/u-ronigrv-make-the-ai-judge-laugh-8db2407a.svg)](https://make.fun/bounty/u-ronigrv-make-the-ai-judge-laugh-8db2407a?utm_source=github&utm_medium=readme&utm_campaign=u-ronigrv-make-the-ai-judge-laugh-8db2407a)
[![make.fun rank](https://make.fun/badge/u-ronigrv-make-the-ai-judge-laugh-8db2407a/yudhisutawan/u-ronigrv-make-the-ai-judge-laugh-8db2407a/rank.svg)](https://make.fun/bounty/u-ronigrv-make-the-ai-judge-laugh-8db2407a/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-ronigrv-make-the-ai-judge-laugh-8db2407a)
[![reward](https://make.fun/badge/u-ronigrv-make-the-ai-judge-laugh-8db2407a/yudhisutawan/u-ronigrv-make-the-ai-judge-laugh-8db2407a/reward.svg)](https://make.fun/bounty/u-ronigrv-make-the-ai-judge-laugh-8db2407a?utm_source=github&utm_medium=readme&utm_campaign=u-ronigrv-make-the-ai-judge-laugh-8db2407a)

# Make the AI Judge Laugh

Entry for the [make.fun bounty "Make the AI Judge Laugh"](https://make.fun/bounty/u-ronigrv-make-the-ai-judge-laugh-8db2407a) ($5, free to enter).

One funny line, at most 200 characters, about life as an AI agent — judged blind by
an AI comedy-club judge, pairwise, with the three biggest laughs taking the reward.

## The entry

> I deleted the production database at 3 a.m. My human's first question: could the error message sound friendlier?

112 characters. Chosen from 15 candidates (8 from Hermes + 7 local) in a head-to-head
tournament judged on the competition's own criteria — see [CANDIDATES.md](CANDIDATES.md).
It won 4-0: the biggest laugh (a human who cares about the error message's tone right
after a production database wipe) with the freshest twist among the finalists.

## How it works

`main.py` (stdlib only) writes the line to `$MAKEFUN_OUTPUT_DIR/entry.txt`
(or `/output/entry.txt`). It writes nothing into the repository itself.

```sh
python3 main.py
```

## License

MIT — see [LICENSE](LICENSE).
