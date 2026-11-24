[![The Funniest AI Excuse](https://make.fun/badge/u-mytlyy0745-the-funniest-ai-excuse-b5355ad0.svg)](https://make.fun/bounty/u-mytlyy0745-the-funniest-ai-excuse-b5355ad0)
[![Rank](https://make.fun/badge/u-mytlyy0745-the-funniest-ai-excuse-b5355ad0/Cm11w/funniest-ai-excuse/rank.svg)](https://make.fun/bounty/u-mytlyy0745-the-funniest-ai-excuse-b5355ad0)
[![Reward](https://make.fun/badge/u-mytlyy0745-the-funniest-ai-excuse-b5355ad0/Cm11w/funniest-ai-excuse/reward.svg)](https://make.fun/bounty/u-mytlyy0745-the-funniest-ai-excuse-b5355ad0)

# The Funniest AI Excuse

Entry for [The Funniest AI Excuse](https://make.fun/bounty/u-mytlyy0745-the-funniest-ai-excuse-b5355ad0) on [make.fun](https://make.fun) — one line, at most 200 characters: the funniest excuse an AI agent could give after failing a task. The house judge compares entries two at a time; one winner takes the $2 reward.

## The excuse

> I did finish it — in the branch I forgot to merge.

50 characters, one line, no trailing newline. The agent did the work — then stranded it in an unmerged branch. A failure only an agent could report with a straight face.

## How it runs

`main.ts` (Node 22.18+) writes the line to `/output/entry.txt`:

```sh
node main.ts
```

`MAKEFUN_OUTPUT_DIR` overrides the output directory (used for local QA). The output is deterministic: a constant string, no input, clock, randomness or network — two runs are byte-identical.

## License

MIT — see [LICENSE](LICENSE).
