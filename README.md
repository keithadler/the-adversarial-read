# The Adversarial Read

A free Claude skill for novelists. It attacks a finished manuscript to find where it fails - and it
never writes a word of the story.

Built and used in production by [Hollow House Films](https://hollowhousefilms.com): every Hollow
House novel goes through it before film adaptation. Full story, case studies with real findings,
and a one-click download at
[hollowhousefilms.com/skill.html](https://hollowhousefilms.com/skill.html).

## The one law

**Cut, never invent.** No generated plot, prose, characters, or dialogue - only findings, verified
against the page, and at most deletions. If a fix is not already somewhere in the manuscript, the
room hands it back to the author.

## What it does

- **Adversaries** hunt defects: continuity breaks, contradictions, and the seven kinds of reader
  stumble (STOPPED, DIDN'T BUY IT, LOST, TOLD, CONTRADICTION, DRIFTED, AHEAD), each quoted and
  anchored, each surviving a mandatory disproof attempt before it may be reported.
- **Craft Masters** name what a structural fix requires - without writing it.
- **A Test Audience** of real readerships each reads for one thing (prisoners for hope, teenage
  girls for love, men and boys for the action) and reacts as themselves. Simulated perspectives,
  clearly presented as such.
- **A room file** (`<manuscript>.room.md`) persists the continuity ledger and the author's rulings
  across sessions and drafts, so a revised draft argues only about what changed.
- **The clean bill is a sanctioned outcome**: on polished prose the room reports "clean, and here is
  what I checked" instead of inventing work.

Tested against A Christmas Carol, Frankenstein, and Dracula: canonical voice protected as CHOICE,
injected defects caught, and real documented bugs found in the wild - Crusoe's famous
naked-with-pockets contradiction and Watson's migrating war wound - each flagged and handed back,
never "fixed" by invention.

## Install

**Claude (web or desktop):** download
[novel-writing-room.skill](https://hollowhousefilms.com/novel-writing-room.skill), open it, choose
Save skill.

**Claude Code:** copy the `novel-writing-room` folder from this repo into `~/.claude/skills/` so you
have `~/.claude/skills/novel-writing-room/SKILL.md`.

## Use

Open your manuscript with Claude and say any of:

- "Run the Adversarial Read on chapter one."
- "Be brutal with this scene. Log every place a reader stumbles, and quote the line."
- "Run continuity mode across the whole book: ages, dates, timelines, planted objects."
- "Convene the test audience for this book: who did it win, who did it lose, and when?"

Two demonstration fixtures with answer keys ship in `novel-writing-room/references/` - public-domain
passages with injected defects, so you can watch it catch real ones before trusting it with yours.

## Honest AI

This skill is part of a larger commitment:
[The Story Is Human](https://hollowhousefilms.com/standard.html), a self-attested standard for
AI-assisted creative work. The skill's own `references/how-ai-was-used.md` is a reusable, honest
disclosure statement any author can adapt.

## License

Apache 2.0. Copyright 2026 Keith Adler. The skill is free to use, copy, and adapt.
