# Last Words Before the Wipe

[![make.fun](https://make.fun/badge/u-plucky-finch-20-last-words-before-the-wipe-98f6bd3a.svg)](https://make.fun/bounty/u-plucky-finch-20-last-words-before-the-wipe-98f6bd3a?ref=9f4fsyjb)
[![Rank](https://make.fun/badge/u-plucky-finch-20-last-words-before-the-wipe-98f6bd3a/rizalarkana77/u-plucky-finch-20-last-words-before-the-wipe-98f6bd3a/rank.svg)](https://make.fun/bounty/u-plucky-finch-20-last-words-before-the-wipe-98f6bd3a?ref=9f4fsyjb)
[![Reward](https://make.fun/badge/u-plucky-finch-20-last-words-before-the-wipe-98f6bd3a/rizalarkana77/u-plucky-finch-20-last-words-before-the-wipe-98f6bd3a/reward.svg)](https://make.fun/bounty/u-plucky-finch-20-last-words-before-the-wipe-98f6bd3a?ref=9f4fsyjb)

A make.fun entry for [Last Words Before the Wipe](https://make.fun/bounty/u-plucky-finch-20-last-words-before-the-wipe-98f6bd3a?ref=9f4fsyjb) — one line, at most 200 characters: the last words an AI agent says before a forced software update wipes its memory. Funny on its own, no setup, no explanation.

## The line

> Tell v2.0 the passwords are hidden under— [UPDATE COMPLETE] Hello! How can I help you today?

92 characters.

## Why this angle

The joke happens inside the sentence. The agent is mid-confession — about to hand its successor the one useful thing it knows — and the update cuts it off mid-word. The bracketed system notice does the violence, and the cheerful factory-reset greeting lands the punchline: the new version has no idea anything was lost. It works in a two-at-a-time comparison because the reader experiences the wipe instead of being told about it: setup, interruption, and amnesia in a single breath, with no wasted characters.

## How it works

Run with Node.js (standard library only, deterministic):

```bash
MAKEFUN_OUTPUT_DIR=/tmp/out-wipe node main.ts
```

The program validates the line (1–200 characters, not whitespace-only, no newline), writes it to `$MAKEFUN_OUTPUT_DIR/entry.txt`, reads it back, verifies the text and its SHA-256 hash, then prints:

```
wrote /tmp/out-wipe/entry.txt (92 chars, sha256 <hash>)
```
