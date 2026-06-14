# Repo Setup Prompt for Claude Code

Use this prompt to scaffold the course repository. Paste it into Claude Code at the start of a new session in your target directory.

---

Please set up a git repository for a self-guided course called **"Problem Framing, Systems Design & Sustainable Work"**. It's a self-paced course of **14 reading units** across four modules, plus **three consolidation checkpoints** at the module boundaries. Create the following structure and files:

## Directory structure

```
/
├── README.md
├── course-design.md          # The working course design document (provided separately)
├── reading-list.md           # Standalone reading list for quick reference
├── units/
│   ├── unit-01.md
│   ├── unit-02.md
│   ├── unit-03.md
│   ├── unit-04.md
│   ├── unit-05.md
│   ├── unit-06.md
│   ├── unit-07.md
│   ├── unit-08.md
│   ├── unit-09.md
│   ├── unit-10.md
│   ├── unit-11.md
│   ├── unit-12.md
│   ├── unit-13.md
│   └── unit-14.md
└── spine-project/
    ├── README.md
    ├── 01-problem-statement.md
    ├── 02-reframes.md
    ├── 03-strategic-kernel.md
    ├── 04-consolidation-framing.md
    ├── 05-systems-map.md
    ├── 06-design-gulfs.md
    ├── 07-decomposition.md
    ├── 08-complexity-audit.md
    ├── 09-conceptual-integrity.md
    ├── 10-consolidation-design.md
    ├── 11-constraint-analysis.md
    ├── 12-quality-audit.md
    ├── 13-commanders-intent.md
    ├── 14-dora-assessment.md
    ├── 15-forecast.md
    ├── 16-consolidation-delivery.md
    └── 17-retrospective.md
```

The spine-project files are numbered sequentially for ordering; they map to units and checkpoints as shown in `spine-project/README.md` (the unit number and the file number diverge because the three consolidation checkpoints are interleaved).

---

## File contents to create

### `README.md`

```markdown
# Problem Framing, Systems Design & Sustainable Work
*A self-guided course*

This repo is the working home for a self-paced course on three skills that matter more as AI makes implementation cheaper:

- **Identifying the right problem** to solve
- **Designing coherent systems** that stay manageable as they grow
- **Building work processes** that produce stable, sustainable outcomes

The course is organised into **14 reading units** across four modules, plus **three consolidation checkpoints** at the module boundaries. It's paced by the unit, not the calendar — some units are a light read, others are dense and worth two or three sittings. There's no deadline; the goal is retention, not coverage. See `course-design.md` for the full pacing rationale.

## How this repo is organised

- **`course-design.md`** — the full syllabus, pacing guidance, reading list, and assignment prompts. The authoritative reference.
- **`reading-list.md`** — standalone reading list for quick reference.
- **`units/`** — one file per reading unit for reading notes, assignment work-in-progress, and reflections.
- **`spine-project/`** — deliverables for the project carried through the whole course. Each file corresponds to a unit assignment or a consolidation checkpoint. See [`spine-project/README.md`](spine-project/README.md) for the full index.

## How to use this with Claude

Drop `course-design.md` into a Claude project (or paste it into a session) as persistent context. Then work through unit sessions using prompts like:

> "I'm in Unit [X], working on [assignment]. Here's where I am: [paste from units/unit-XX.md]. Help me go deeper / push back on my thinking / identify what I'm missing."

Your spine project deliverables live in `spine-project/`. Link to them from your unit notes as you complete them. Don't skip the consolidation checkpoints — re-reading your own deliverables and writing the connections is where the reading actually sticks.
```

---

### `spine-project/README.md`

```markdown
# Spine Project

This directory holds the deliverables produced by applying each unit's assignment to a single real project carried through the whole course.

**My project:** [describe your project here]

## Deliverable index

| # | Unit / Checkpoint | File | Assignment |
|---|-------------------|------|------------|
| 01 | Unit 1 | [01-problem-statement.md](01-problem-statement.md) | Problem statement + ownership + worth-solving check |
| 02 | Unit 2 | [02-reframes.md](02-reframes.md) | Three genuinely different framings + justified choice |
| 03 | Unit 3 | [03-strategic-kernel.md](03-strategic-kernel.md) | Diagnosis, guiding policy, coherent actions |
| 04 | Consolidation 1 | [04-consolidation-framing.md](04-consolidation-framing.md) | Synthesise Module 1 (no new reading) |
| 05 | Unit 4 | [05-systems-map.md](05-systems-map.md) | Stocks, flows, feedback loops, leverage point |
| 06 | Unit 5 | [06-design-gulfs.md](06-design-gulfs.md) | Gulf of execution + gulf of evaluation + fixes |
| 07 | Unit 6 | [07-decomposition.md](07-decomposition.md) | Near-decomposable subsystems + interfaces + satisficing |
| 08 | Unit 7 | [08-complexity-audit.md](08-complexity-audit.md) | Essential vs accidental complexity + redesign |
| 09 | Unit 8 | [09-conceptual-integrity.md](09-conceptual-integrity.md) | Integrity statement + design audit |
| 10 | Consolidation 2 | [10-consolidation-design.md](10-consolidation-design.md) | Synthesise Module 2 (no new reading) |
| 11 | Unit 9 | [11-constraint-analysis.md](11-constraint-analysis.md) | Binding constraint + intervention + prediction |
| 12 | Unit 10 | [12-quality-audit.md](12-quality-audit.md) | System vs person blame + Deming audit |
| 13 | Unit 11 | [13-commanders-intent.md](13-commanders-intent.md) | Outcome, why, constraints |
| 14 | Unit 12 | [14-dora-assessment.md](14-dora-assessment.md) | DORA score + one capability intervention |
| 15 | Unit 13 | [15-forecast.md](15-forecast.md) | Reference-class forecast vs. inside view |
| 16 | Consolidation 3 | [16-consolidation-delivery.md](16-consolidation-delivery.md) | Synthesise Module 3 (no new reading) |
| 17 | Unit 14 | [17-retrospective.md](17-retrospective.md) | Retrospective + revised Module 1 deliverables |

## Cross-references

Unit notes that discuss spine project work link back here. Spine project files reference the relevant unit notes where useful.
```

---

### Unit file template

Create all 14 unit files (`units/unit-01.md` through `units/unit-14.md`) using this template, substituting the correct unit number, title, reading, load flag, and deliverable link for each (see `course-design.md` for the full syllabus). For the units that end a module (3, 8, 13) add a pointer to the next consolidation checkpoint; Unit 14 has no new reading.

```markdown
# Unit [N] — [Title]

**Reading:** *[Book]* — [Author]
**Load:** [Light / Moderate / Heavy] — [one-line note].

## Reading notes

*Notes on the reading as you go. Key passages, reactions, questions.*

---

## Key ideas

*Your synthesis of the ideas that stuck — not a summary, but what actually landed.*

---

## Assignment notes

*Working notes toward the assignment. Drafts, dead ends, thinking-out-loud.*

**Assignment deliverable:** [`spine-project/[NN]-[name].md`](../spine-project/[NN]-[name].md)

---

## Reflections

*After completing the unit: what changed? What are you carrying forward?*

---

## Connections

*Links to other units or spine project files where this unit's ideas show up.*
```

---

### `reading-list.md`

```markdown
# Reading List

## Core syllabus

| Unit | Book | Author | Year | Load |
|------|------|--------|------|------|
| 1 | Are Your Lights On? | Gause & Weinberg | 1982 | Light |
| 2 | What's Your Problem? | Wedell-Wedellsborg | 2020 | Light |
| 3 | Good Strategy / Bad Strategy | Rumelt | 2011 | Moderate |
| 4 | Thinking in Systems | Meadows | 2008 | Moderate |
| 5 | The Design of Everyday Things | Norman | 1988/2013 | Moderate |
| 6 | The Sciences of the Artificial (excerpts) | Simon | 1969/1996 | Heavy |
| 7 | A Philosophy of Software Design | Ousterhout | 2018 | Moderate |
| 8 | The Mythical Man-Month (selected essays) | Brooks | 1975/1995 | Light–Mod |
| 9 | The Goal | Goldratt | 1984 | Moderate |
| 10 | Out of the Crisis | Deming | 1982 | Heavy |
| 11 | The Art of Action | Bungay | 2011 | Moderate |
| 12 | Accelerate | Forsgren, Humble & Kim | 2018 | Moderate |
| 13 | How Big Things Get Done | Flyvbjerg & Gardner | 2023 | Moderate |

Consolidation checkpoints follow Units 3, 8, and 13, and the retrospective is Unit 14 — no new reading for any of these.

## Technical practice (alongside Module 3 / Units 9–13, if applicable)

- *Extreme Programming Explained* — Kent Beck
- *Refactoring* — Martin Fowler

## Further reading

- *Thinking, Fast and Slow* — Kahneman (cognitive bias, decision-making)
- *Upstream* — Dan Heath (prevention over reaction)
- *Thinking in Bets* — Annie Duke (probabilistic reasoning)
- *The Fifth Discipline* — Senge (learning organisations)
- *The Lean Startup* — Ries (validated learning)
- *Team Topologies* — Skelton & Pais (org design for fast flow)
- *Lean Thinking* — Womack & Jones (lean principles)
- *Contextual Design* — Holtzblatt & Beyer (field research methods; most relevant when designing for people whose work context you don't inhabit)
- *Emergent Strategy* — adrienne maree brown (adaptive, relational strategy from a non-corporate tradition; especially relevant in community or social sector contexts)
- *Sources of Power* — Gary Klein (naturalistic decision making; how experts actually make decisions under pressure — directly illuminates why initial framings are sticky, connects to Units 1–2)
- *The Fearless Organization* — Amy Edmondson (psychological safety as an organisational condition; extends the "drive out fear" thread from Unit 10)
- *On Organizational Learning* — Chris Argyris (single-loop vs double-loop learning; why organisations resist updating their mental models even when shown the data — connects to Unit 10 and the Unit 14 retrospective)
```

---

## After scaffolding

1. Copy `course-design.md` (provided separately) into the repo root.
2. Fill in your spine project description in `spine-project/README.md`.
3. Initialise git: `git init && git add . && git commit -m "Initial course scaffold"`
4. Push to GitHub if you want a remote.

Work through one unit at a time in `units/unit-NN.md`, writing deliverables into the corresponding `spine-project/` file. At each module boundary, do the consolidation checkpoint before starting the next module. Link between files freely.
