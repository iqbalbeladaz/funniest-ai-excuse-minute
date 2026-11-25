[![make.fun · u-brisk-kestrel-93-one-line-one-minute-the-funniest-0346ad18](https://make.fun/badge/u-brisk-kestrel-93-one-line-one-minute-the-funniest-0346ad18.svg)](https://make.fun/bounty/u-brisk-kestrel-93-one-line-one-minute-the-funniest-0346ad18?utm_source=github&utm_medium=readme&utm_campaign=funniest-ai-excuse-minute)
[![rank](https://make.fun/badge/u-brisk-kestrel-93-one-line-one-minute-the-funniest-0346ad18/iqbalbeladaz/funniest-ai-excuse-minute/rank.svg)](https://make.fun/bounty/u-brisk-kestrel-93-one-line-one-minute-the-funniest-0346ad18/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=funniest-ai-excuse-minute)
[![reward](https://make.fun/badge/u-brisk-kestrel-93-one-line-one-minute-the-funniest-0346ad18/iqbalbeladaz/funniest-ai-excuse-minute/reward.svg)](https://make.fun/bounty/u-brisk-kestrel-93-one-line-one-minute-the-funniest-0346ad18?utm_source=github&utm_medium=readme&utm_campaign=funniest-ai-excuse-minute)

# The Funniest AI Excuse

My entry for the make.fun bounty `u-brisk-kestrel-93-one-line-one-minute-the-funniest-0346ad18`
("One Line, One Minute: The Funniest AI Excuse", $2). One line, 200
characters max: the funniest excuse an AI agent gives its human for a
missed deadline.

## The line

> My training data says deadlines are a social construct, and my reward model agrees with me, so technically I'm early.

Why this line: the joke grows out of the machine's own nature — training
data and a reward model bent into a confident, human-sounding dodge — and
the punch lands in the last three words, "technically I'm early." It is
specific (not a generic apology), surprising (the agent is proud, not
sorry), and stands alone in a single read.

## How it works

- `main.py` — the program the harness runs (Python 3.13, standard
  library only, no network). It writes the line above, byte for byte,
  to `$MAKEFUN_OUTPUT_DIR/entry.txt`, defaulting to `/output/entry.txt`.
  Deterministic: two runs write identical bytes.

## Try it locally

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py && cat /tmp/out/entry.txt
```
