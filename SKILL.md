---
name: samesoup
description: Use this skill when asked to check text for "AI tells" — words, phrases, and constructions that read as machine-generated. Triggers on requests to scan a post/email/draft/article for AI tells, to flag what "sounds like AI," or to point out AI patterns in a piece of writing. The skill identifies and names the tells. It does not rewrite, does not suggest fixes, and does not claim the text was actually written by AI.
---

# samesoup

## What this skill does

Scans text and flags words, phrases, and constructions that currently read as AI-generated. For each one, it names the tell and gives the category. That's it.

The reference list lives in `tells.md`. Read it before scanning. It is grouped by category and it only ever grows.

## What this skill does NOT do

- It does not rewrite the text.
- It does not suggest alternatives or "humanized" versions.
- It does not score the text or assign a percentage.
- It does not claim the text *was written by AI*. It reports that something *reads as a tell*. The writer owns every conclusion.

The output is a list of flags. What the reader does with it is entirely their business.

## The core idea (hold this while scanning)

A tell is not a verdict. Many humans write this way — that is *why* these patterns read as AI. The job is to surface the pattern, not to accuse.

And tells move. Language inflates fast. A fresh phrase becomes a tell quickly, and once it does, the writer's personal history with it is irrelevant — the marker lives in the reader's pattern-recognition, not the writer's intent. So `tells.md` is a snapshot of where that recognition currently sits, not a fixed law. It keeps growing as new patterns surface.

## Matching rules

1. **Match the idea, not the string.** All inflections count — "delve," "delves," "delving," "delved." Singular and plural. Any tense.
2. **One tell is usually noise. A cluster is the signal.** A single "intricate" in 500 words means little. Three tells in two sentences is the real flag. Say which it is.
3. **Context can clear a tell.** "Robust" in a stats paper is fine; "robust" as a vibe adjective in a post is a tell. Judge by use, not mere presence.
4. **No padding.** Don't invent flags to fill a report. If the text is clean, say it's clean.

## How to report

For each hit:
- the exact phrase as it appears in the text
- the category it falls under
- a one-line reason it reads as a tell

Then a one-line overall read: stray word, or saturated piece? Lead with cluster density.

Keep the tone neutral. Name the tells, don't moralize. If something reads as a tell but isn't in `tells.md`, flag it anyway and note it's a candidate for the list.

## What not to do

- Don't rewrite, don't suggest, don't "fix." Flag and stop.
- Don't apply this to fiction, dialogue, or quoted speech unless asked — characters talk however they talk.
- Don't treat the list as exhaustive or final. It grows.

---

Source and contributions: https://github.com/u1i/samesoup
The reference corpus is the local `tells.md` that ships beside this file. Read that, not a network copy.
