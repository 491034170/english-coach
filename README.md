# English Coach

A [Claude Code](https://docs.anthropic.com/en/docs/claude-code) skill that turns every conversation into an English practice session.

## What it does

When activated, Claude will:

1. **Answer your question normally** — it does its actual job first
2. **Correct your English** — grammar, spelling, word choice, punctuation, expression
3. **Teach something new** — a useful phrase, grammar tip, or more natural way to say things

Designed for **non-native English speakers** (especially Chinese speakers) who want to improve their English through real daily use rather than textbook exercises.

## Features

- Categorized corrections (Spelling / Grammar / Word Choice / Punctuation / Expression)
- Adapts to your level — focuses on basics for beginners, naturalness for advanced users
- Tracks recurring mistakes and highlights patterns
- Rotates learning content: idioms, grammar tips, advanced rephrasing, common mistakes
- Friendly tone — like a helpful coworker, not a strict teacher

## Install

```bash
npx skills add 491034170/english-coach -a claude-code -g -y
```

## Usage

In Claude Code, type:

```
/english-coach
```

Then just chat normally in English. The skill will automatically correct and teach as you go.

## Example

**You say:**
> dose this work for practice my english?

**Claude responds:**

*(answers your question)*

---

**English Corrections:**

> ~~dose this work for practice my english?~~ → **Does this work for practicing my English?**
>
> **[Spelling]** "dose" → "does"
> **[Grammar]** "for practice" → "for practicing" — after "for", use the -ing form
> **[Punctuation]** "english" → "English" — language names are always capitalized

**Phrase of the day:** "get the hang of" — to become comfortable with something new.
*Example: "I'm starting to get the hang of English prepositions."*

## License

MIT
