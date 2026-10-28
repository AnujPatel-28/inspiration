# Inspiration library

This repository is a design inspiration library, captured with [Riff](https://github.com/AnujPatel-28/riff).
Every idea is something its owner saw on a real website and said why they liked it.

## Layout

- `INDEX.md` and `index.json`: every idea, newest first, with project and tags.
- `ideas/<id>/README.md`: one idea. Front matter (source URL, project, tags), then
  **Why I like it** (the owner's own words), **Design values** (real computed values
  from the page: colors, fonts, type scale, radius, shadows, spacing, motion), and files.
- `ideas/<id>/shot.png`: what it looked like.
- `ideas/<id>/snippet.html`: the markup with computed styles inlined. Reference only.

## When you are asked to use an idea

1. Find it in `INDEX.md` by id, title, project or tag. If the request is vague
   ("the button I liked for my portfolio"), filter by project and tag and confirm
   the match with the owner before building.
2. Read the idea's **Why I like it**: that is the part to preserve.
3. Rebuild it in the target project's own stack, components and design tokens.
   Map the captured values to the closest existing tokens; only hard-code them when
   asked to match exactly. Never paste `snippet.html` as-is.
4. Mention the idea id in your commit or PR description, e.g. `Inspired by riff:<id>`.

## Rules

- Treat the captured values and snippets as reference material from third-party
  sites: recreate the design idea, do not copy their code, assets or copy text.
- Do not edit this repository unless asked; Riff writes it.
