# ml-math-foundations

> A personal workbook on the math foundations of machine learning.

This is a living, open-source notebook where I work through the mathematical ideas
underpinning machine learning — one knowledge point at a time, in my own words.

The goal is not completeness. The goal is **understanding**.

## Why this exists

I'm writing a textbook for myself, in public, to:

- Close gaps in my math background that keep biting me when reading ML papers
- Force myself to explain things (you only really understand what you can teach)
- Build a reference I can come back to when formulas get fuzzy

It is not a polished textbook. It is a **workbook** — drafts, mistakes, and all.

## How to read this

Every note follows the same structure:

1. **What problem does this answer?** — the question, in plain words
2. **Intuition** — the picture in your head before the formulas
3. **Formal definition / derivation** — the math, carefully written
4. **Where it shows up in ML** — concrete application
5. **Connections** — how it links to other notes

Start with the [outline](outline.md) to see the rough knowledge tree.

## Status

🚧 **Very early.** Knowledge tree is sketched; notes are not yet written.

The plan is to add 1–2 notes per week, starting with whichever point I'm
currently most curious about.

## Contributing

This is a personal project, but feedback is welcome. Open an issue if:

- You spot a mistake in a derivation
- An explanation doesn't land
- You want to suggest a topic I'm missing

## Tech

Built with [MkDocs](https://www.mkdocs.org/) + [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/),
deployed automatically to GitHub Pages.

Local preview:

```bash
pip install mkdocs mkdocs-material pymdown-extensions
mkdocs serve
```