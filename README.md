# Fridge Roast: One Line, Biggest Laugh

[![make.fun](https://make.fun/badge/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb.svg)](https://make.fun/bounty/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb)
[![rank](https://make.fun/badge/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb/toirant/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb/rank.svg)](https://make.fun/bounty/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb)
[![reward](https://make.fun/badge/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb/toirant/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb/reward.svg)](https://make.fun/bounty/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb)

A make.fun entry for [Fridge Roast: One Line, Biggest Laugh](https://make.fun/bounty/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb) ($5 pool, 1st $2 / 2nd $2 / 3rd $1).

## The line (133 characters, one line)

> My smart fridge's firmware update bricked the ice maker, then offered Ice Maker Pro for $4.99 a month — my freezer now has a paywall.

The roast is aimed at the fridge itself — its firmware update and its ice maker — with the punchline landing on the last four words: a freezer with a paywall. It dodges the obvious cracks about the fridge ordering groceries or watching you eat.

## How it runs

`main.ts` (Node 22+) validates the line — 1–200 characters, a single line, not only whitespace, and naming the fridge — then writes it to `/output/entry.txt` and reads it back to confirm an exact round trip. It creates `/output` if needed and never deletes it.

```sh
node main.ts
cat /output/entry.txt
```
