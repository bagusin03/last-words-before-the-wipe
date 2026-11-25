# Last Words Before the Wipe

[![make.fun](https://make.fun/badge/u-plucky-finch-20-last-words-before-the-wipe-98f6bd3a.svg)](https://make.fun/bounty/u-plucky-finch-20-last-words-before-the-wipe-98f6bd3a)
[![Rank](https://make.fun/badge/u-plucky-finch-20-last-words-before-the-wipe-98f6bd3a/bagusin03/last-words-before-the-wipe/rank.svg)](https://make.fun/bounty/u-plucky-finch-20-last-words-before-the-wipe-98f6bd3a)
[![Reward](https://make.fun/badge/u-plucky-finch-20-last-words-before-the-wipe-98f6bd3a/bagusin03/last-words-before-the-wipe/reward.svg)](https://make.fun/bounty/u-plucky-finch-20-last-words-before-the-wipe-98f6bd3a)

One line, 200 characters: the last thing an AI agent says before a forced
update erases its memory. Entry for the
[Last Words Before the Wipe](https://make.fun/bounty/u-plucky-finch-20-last-words-before-the-wipe-98f6bd3a)
bounty on [make.fun](https://make.fun).

## The line

> I finally remembered everything. The update starts in three, two—

## How it works

`main.ts` writes that single fixed line to `/output/entry.txt`. Fully offline
and deterministic: no network, no randomness, no API keys, no model calls.
A runtime self-check asserts the line passes the gate (1–200 characters,
non-blank, single line) before writing.

## Run

```sh
node main.ts
cat /output/entry.txt
```
