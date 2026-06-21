# samesoup

A curated, growing list of the words and constructions that read as AI-generated, plus a skill that finds them in any text. It points. It doesn't rewrite, suggest, or score.

## Example

Give it a piece of text:

> Here's the thing: it's not about the slides, it's about the journey. What's fascinating is how this delves into the intricate tapestry of human potential. The future isn't coming. It's already here.

It hands you the flags:

| Flag | Category | Why |
|---|---|---|
| "Here's the thing:" | announcement pause | promises a payoff, delivers a colon |
| "it's not about the slides, it's about the journey" | false-contrast | manufactures depth by negating a strawman |
| "What's fascinating is…" | announcement pause | tells you to be interested instead of being interesting |
| "delves into" | filler word | the single most reliable tell |
| "intricate tapestry" | filler word | two decorative nouns stacked |
| "The future isn't coming. It's already here." | false-contrast | the time-flavored template, split for gravity |

**Read:** saturated. Six tells in three sentences. The register, not a stray word.

What you do with the flags is your business. samesoup stops at pointing.

## Install & use

Drop `SKILL.md` and `tells.md` into wherever your agent reads skills.

**Claude Code**
```bash
git clone https://github.com/u1i/samesoup ~/.claude/skills/samesoup
```

**Any agent that reads SKILL.md** (Cursor, Cline, Codex, Copilot, a Claude.ai Project): clone the repo and point the agent at `SKILL.md`, or paste its contents into the tool's rules/instructions field. The skill reads `tells.md` from the same folder.

Then ask:

> "Scan this post for AI tells"
> "Flag what reads as AI in this draft"
> "Run samesoup on this"

You get back a list of flags, each with its category and a one-line reason. No rewrite, no score.

## Contributing

Small open project, closed gate. Open an issue or PR proposing a new tell with: the word or construction, the category, and a one-line reason it reads as a tell. New entries land in **Candidates** in `tells.md`, then get promoted. The maintainer decides what lands; that curation is the product. See `CONTRIBUTING.md`.

## Why it works this way

There's a beef noodle shop in Bangkok, Wattana Panich, that has kept the same broth simmering for over forty-five years. They never empty the pot. Each day they ladle out what sells and top it back up, so today's bowl still carries something of every bowl before it. The list works the same way. It never gets emptied; it only grows, and what went in early stays in the pot.

The name carries a second meaning, and that one is the real point. Once a word or format reads as AI, your history with it stops mattering. You get sorted into the same soup as everyone else, however you came by it. You might have written with em dashes your whole life, used "tapestry" since school, reached for "quietly" in that exact sense for twenty years, and it stops mattering the moment enough machine-written text carries the same signal.

The signal also keeps moving, because language inflates fast. A fresh phrase turns into a tell faster than feels reasonable. So the list is a snapshot of where pattern-recognition currently sits, and it grows as new patterns surface.

A few things worth being clear about. samesoup never claims a text "was written by AI"; plenty of humans write this way, which is the whole reason the tells exist, so it reports only that something reads as a tell. It isn't a style ban; some flagged constructions work fine in the right place, so it points and you decide. And one tell on its own is usually nothing. A pile of them together is the signal.

This is here to give writers and editors a fast way to see those patterns. AI-shaming isn't the goal and never was.

## License

MIT.
