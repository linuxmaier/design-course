# Problem Framing, Systems Design & Sustainable Work
*A self-guided course*

This repo is the working home for a self-paced course on three skills that matter more as AI makes implementation cheaper:

- **Identifying the right problem** to solve
- **Designing coherent systems** that stay manageable as they grow
- **Building work processes** that produce stable, sustainable outcomes

The course starts with **Unit 0** — a no-reading setup session for choosing your spine project — followed by **14 reading units** across four modules and **three consolidation checkpoints** at the module boundaries. It's paced by the unit, not the calendar — some units are a light read, others are dense and worth two or three sittings. There's no deadline; the goal is retention, not coverage. See `course-design.md` for the full pacing rationale.

## How this repo is organised

- **`course-design.md`** — the full syllabus, pacing guidance, reading list, and assignment prompts. The authoritative reference.
- **`reading-list.md`** — standalone reading list for quick reference.
- **`units/`** — one file per reading unit for reading notes, assignment work-in-progress, and reflections.
- **`spine-project/`** — deliverables for the project carried through the whole course. Each file corresponds to a unit assignment or a consolidation checkpoint. See [`spine-project/README.md`](spine-project/README.md) for the full index.
- **`submit`** — helper script that copies a blank template into the private `submissions/` area so you fill out a copy, not the tracked template.

## Doing the work (your private answers)

The files in `units/` and `spine-project/` are **blank templates** — prompts with placeholders. To keep your filled-in answers out of the published repo, do the work in `submissions/`, which is gitignored.

Start a worksheet by copying its template across:

```
./submit spine-project/01-problem-statement.md
```

This creates `submissions/spine-project/01-problem-statement.md` (mirroring the template path) for you to fill out. Pass several paths at once, and `--force` to overwrite an existing submission. The script never clobbers your work without `--force`.

Notes:
- Relative links inside a copied worksheet (e.g. `../units/unit-01.md`) point at the published tree, not your `submissions/` copy — fine for reference, just not clickable from the copy.
- If a template changes after you've copied it, your submission won't pick up the change automatically. Re-`submit --force` to reset, or merge the change in by hand.

## How to use this with Claude

Drop `course-design.md` into a Claude project (or paste it into a session) as persistent context. Then work through unit sessions using prompts like:

> "I'm in Unit [X], working on [assignment]. Here's where I am: [paste from units/unit-XX.md]. Help me go deeper / push back on my thinking / identify what I'm missing."

Your spine project deliverables live in `spine-project/`. Link to them from your unit notes as you complete them. Don't skip the consolidation checkpoints — re-reading your own deliverables and writing the connections is where the reading actually sticks.
