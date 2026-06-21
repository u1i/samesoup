# samesoup

An opinionated, curated list of the words, phrases, and constructions that read as AI-generated, plus a skill that finds them in any text.

There's a beef noodle shop in Bangkok, Wattana Panich, that has kept the same broth simmering for over forty-five years. They never empty the pot. Each day they ladle out what sells and top it back up, so today's bowl still carries something of every bowl before it. The list works the same way. It never gets emptied; it only grows, and what went in early stays in the pot.

The name carries a second meaning, and that one is the real point. Once a word or format reads as AI, your history with it stops mattering. You get sorted into the same soup as everyone else, however you came by it.

This list does one thing. It points. You give it text, it names the tells it finds, and it hands you the result to do with as you like. No rewriting, no fixes, no score.

It's a curated list, biased on purpose, shaped by a small group of people who edit a lot of writing and argue about it. That curation is what makes it worth using, and it's the thing a crowd-sourced word dump can't give you.

## Why this exists

This is here to give writers and editors a fast way to see the patterns that now get text sorted, fairly or not, into the "a machine wrote this" pile. AI-shaming isn't the goal and never was.

The mechanic is uncomfortable. Once a word or a format shows up in enough text that people read as AI-generated, it gets read that way everywhere. Your personal history with it grants you nothing. The marker stops living in your intent and starts living in the reader's pattern-recognition. You might have written with em dashes your whole life, used "tapestry" since school, reached for "quietly" in that exact sense for twenty years, and it stops mattering the moment enough machine-written text carries the same signal.

The signal also keeps moving, because language inflates fast. The single bold opening line followed by a pause, the one everyone now uses to let a message land, was a sharp move right up until it became the move. The same goes for the words. A fresh phrase turns into a tell faster than feels reasonable, and once it does, insisting you came by it honestly drops you into the same soup as everyone else.

None of this is a verdict on anyone's character. The list is a snapshot of where pattern-recognition currently sits, and it keeps growing as new patterns surface.

## What it does and doesn't do

The output is a list of flags, and that's the whole product. There's no rewriting, no "humanized" version, no suggested alternatives.

It also won't tell you a text "was written by AI." Plenty of humans write this way, which is the whole reason the tells exist, so the skill reports only that something reads as a tell.

It isn't a style ban either. Some flagged constructions work fine in the right place, so the skill points and you decide. And one tell on its own is usually nothing; a pile of them together is the signal.

## How it works

`SKILL.md` is the operational file. Wire it into a Claude skill, a Chrome extension, a pre-publish check, whatever you like. It tells the agent what to scan for and how to report it: name the tell, give the category, give a one-line reason, and stop there.

`tells.md` is the reference corpus, with the actual words, phrases, and constructions grouped by type, each with a short reason. Match on the idea rather than the exact string, so every inflection counts ("delve," "delving," "delved," "delves").

## Contributing

Small open project, closed gate. Anyone can open an issue or PR proposing a new tell or a better explanation, and the maintainer reviews and decides. That gate is a feature; an unfiltered list becomes noise, and the opinionated shape is what makes this worth using over a generic word dump.

When proposing a tell, include the word or phrase or construction, the category it belongs to, and a one-line reason it reads as a tell. New tells land in the **Candidates** section of `tells.md` first, then get promoted into a category. See `CONTRIBUTING.md` for the full process.

## License

MIT. Take it, fork it, wire it into whatever you like.
