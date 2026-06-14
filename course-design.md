# Course Design: Problem Framing, Systems Design & Sustainable Work
*Working document — evolves as the course develops*

---

## Course premise

In a world where AI tooling makes implementation cheaper and faster, the scarce and valuable skills are shifting:
- **Identifying the right problem** to solve (not just solving the presented problem well)
- **Designing coherent systems** that stay manageable as they grow and change
- **Building work processes** that produce stable, sustainable outcomes rather than short-term wins followed by collapse

This course builds those three skills in sequence — framing before design, design before delivery — through reading, applied assignments on a real project, and reflection.

---

## How this course is paced

This is a **self-paced** course organised into **units**, not weeks. A unit is *one book (or set of excerpts) plus the assignment that applies it to your project*. Units are deliberately uneven: some are a light read you'll finish in a sitting, others are dense and worth two or three. Pacing by the unit instead of the calendar keeps the slow points where the material is genuinely hard, rather than spread evenly for the sake of a grid.

A few principles that matter more than speed:

- **The deliverable is the retention mechanism.** Reading and nodding doesn't stick; applying a concept to a real project under real friction does. Never skip a deliverable to "save time" — the deliverable *is* the learning.
- **Floor, not ceiling.** There's no deadline, but there is a failure mode: if a unit stretches on too long, the spine project goes cold and you lose the thread between sessions. A soft rule — don't let a single unit sit unfinished for more than ~2–3 weeks of wall-clock — protects momentum better than any due date.
- **Let the heavy units breathe.** A few units are flagged **Heavy** below. Budget two or more sittings for them and don't force them into the rhythm of the lighter ones. Forcing Simon or Deming into a single pass is how you end up having "read" them without retaining them.
- **Consolidation is where retention is won.** Between modules there are checkpoints with no new reading — just re-reading your own deliverables and writing the connections. These feel optional. They aren't; spaced retrieval is the highest-leverage thing in the whole structure.

Each unit below carries a rough **load** flag (Light / Moderate / Heavy) so you can plan your time honestly.

---

## Your spine project

**Choose this in Unit 1 and carry it the entire course.**

Pick something real: a tool, a workflow, a system, a side project. It needs:
- A genuine need (a real stakeholder, even if that's just you)
- Enough complexity that the "right problem" isn't obvious
- Ideally: AI tooling involved somewhere, so the course's thesis is lived, not just read

You will reframe it, design it, plan its delivery, and reflect on it as the units progress. Every assignment advances it. Deliverables live in `spine-project/`.

---

## Syllabus

### MODULE 1 — Framing the Right Problem (Units 1–3)

---

#### Unit 1 — The Diagnosis Reflex

**Reading:** *Are Your Lights On?* — Donald C. Gause & Gerald M. Weinberg (1982)
*(Short — read the whole thing. It's a quick read deliberately.)*
**Load:** Light.

**Key ideas to watch for:**
- A problem is a difference between things as desired and things as perceived
- "In spite of appearances, people seldom know what they want until you give them what they ask for"
- Problem displacement: every solution creates the next problem
- Don't take their solution method for a problem definition
- Who owns this problem?

**Further reading that connects here:** Klein's *Sources of Power* explains *why* initial framings are so sticky — experts pattern-match to the first plausible framing and only generate alternatives when it fails. Useful context for understanding your own diagnosis reflex.

**Assignment:** [`spine-project/01-problem-statement.md`](spine-project/01-problem-statement.md)

Write a one-page problem statement for your spine project.

Then answer separately:
1. Who actually owns this problem?
2. Is it worth solving?
3. Is your "problem statement" actually a solution in disguise?

Most people discover on reflection that their first statement was a solution. That's the lesson.

---

#### Unit 2 — Reframing

**Reading:** *What's Your Problem?* — Thomas Wedell-Wedellsborg (2020)
**Load:** Light.

**Key ideas to watch for:**
- The slow elevator problem (the mirror reframe)
- The Frame / Reframe / Move Forward method
- 85% of executives say their orgs are bad at problem diagnosis — and it costs them
- Reframing is not brainstorming; it's deliberately questioning the initial framing

**Assignment:** [`spine-project/02-reframes.md`](spine-project/02-reframes.md)

Produce at least **three genuinely different framings** of your project's core problem. Not three variations on the same framing — three that would lead to meaningfully different solutions.

For each:
- State the framing
- Sketch what solving it would look like
- Identify what it makes visible that the others don't

Then pick one and justify the choice. The deliverable is the reasoning, not just the answer.

---

#### Unit 3 — Strategy as Honest Diagnosis

**Reading:** *Good Strategy / Bad Strategy* — Richard Rumelt (2011)
**Load:** Moderate.

**Key ideas to watch for:**
- The "kernel" of good strategy: diagnosis → guiding policy → coherent actions
- Bad strategy is goals dressed up as strategy ("we will be the best")
- The diagnosis must name a real obstacle, not restate the goal
- Strategy requires choosing what *not* to do
- Why organisations avoid honest diagnosis (it forces hard choices)

**Assignment:** [`spine-project/03-strategic-kernel.md`](spine-project/03-strategic-kernel.md)

Write the **strategic kernel** for your spine project:
1. **Diagnosis:** What is the actual obstacle or challenge? Be honest and specific.
2. **Guiding policy:** What approach will you take to address it?
3. **Coherent actions:** What 3–5 specific actions follow from that policy?

The hard part, and the point, is writing a diagnosis that doesn't just restate the goal.

---

#### Consolidation 1 — Framing (no new reading)

**Assignment:** [`spine-project/04-consolidation-framing.md`](spine-project/04-consolidation-framing.md)

Re-read your three Module 1 deliverables back to back. Then, without opening the books again:
- Write the throughline in your own words — what do Gause/Weinberg, Wedell-Wedellsborg, and Rumelt collectively say about diagnosis?
- Name where they pull in different directions or create tension.
- Note how your understanding of the spine project's *actual problem* has shifted since Unit 1.
- Surface one question you're carrying into the design module.

No new reading. The point is retrieval — pulling the ideas back out from memory is what consolidates them.

---

### MODULE 2 — Seeing and Designing Systems (Units 4–8)

---

#### Unit 4 — Systems Literacy

**Reading:** *Thinking in Systems: A Primer* — Donella H. Meadows (2008)
**Load:** Moderate. Short pages, dense ideas — read slowly.

**Key ideas to watch for:**
- Stocks, flows, feedback loops, delays
- Reinforcing vs. balancing loops
- The twelve leverage points (and why the most powerful ones are most resisted)
- "Every system is perfectly designed to get the results it gets"
- Unintended consequences as a systems property, not a planning failure

**Assignment:** [`spine-project/05-systems-map.md`](spine-project/05-systems-map.md)

Draw your spine project as a system:
- What are the stocks (things that accumulate)?
- What are the flows (rates of change)?
- What are the feedback loops?
- Where are the delays?

Then: identify where you'd intervene and why, using Meadows' leverage-point hierarchy. Aim for the highest leverage point you can actually reach.

---

#### Unit 5 — Design as a Discipline

**Reading:** *The Design of Everyday Things* — Don Norman (1988/2013) *(full book)*
**Load:** Moderate.

**Key ideas to watch for:**
- Affordances, signifiers, mappings, feedback, conceptual models
- The gulf of execution (user doesn't know what to do) and gulf of evaluation (user doesn't know if it worked)
- When people fail with a system, the fault is in the design

**Further reading that connects here:** *Contextual Design* (Holtzblatt & Beyer) covers the empirical user research side that Norman doesn't — how to learn what users actually do rather than what they say. Most relevant if you're designing for people whose work context you don't already inhabit.

**Assignment:** [`spine-project/06-design-gulfs.md`](spine-project/06-design-gulfs.md)

For your spine project, identify:
1. The **gulf of execution**: where will a user (or future-you) not know what to do next?
2. The **gulf of evaluation**: where will they not know if it worked?
3. How does your design need to change to close those gulfs?

---

#### Unit 6 — Decomposition and the Architecture of Complexity

**Reading:** *The Sciences of the Artificial* — Herbert A. Simon (1969/1996), Chapters 3 and 5: "The Psychology of Thinking" and "The Architecture of Complexity"
**Load:** Heavy. Simon is the densest reading in the course — budget two sittings, and don't rush the second chapter.

*(This was previously bundled with Norman. It's now its own unit, positioned as the bridge from human-centred design into the complexity material — Simon's near-decomposability runs straight into Ousterhout's modules and Brooks's conceptual integrity.)*

**Key ideas to watch for:**
- Design as "changing existing situations into preferred ones"
- Bounded rationality: we satisfice, not optimise
- Hierarchical decomposition: complex systems must be broken into near-decomposable subsystems to be manageable
- Why near-decomposability is what makes complex systems comprehensible and evolvable at all

**Assignment:** [`spine-project/07-decomposition.md`](spine-project/07-decomposition.md)

For your spine project:
1. Decompose it into near-decomposable subsystems — parts with strong internal coupling and weak coupling to each other.
2. Define the interfaces between them: what does each subsystem need to know about the others, and what can it ignore?
3. Identify where you're **satisficing** rather than optimising — where bounded rationality is (rightly) shaping your design — and where you're pretending to optimise something you can't.

---

#### Unit 7 — Managing Complexity

**Reading:** *A Philosophy of Software Design* — John Ousterhout (2018)
**Load:** Moderate. Readable; the ideas land fast.

*(If your project isn't software, the concepts still transfer — substitute "module" for any component with an interface and an implementation.)*

**Key ideas to watch for:**
- Complexity defined through three symptoms: change amplification, cognitive load, unknown unknowns
- Deep modules: simple interfaces hiding substantial implementation (good)
- Shallow modules: complex interfaces hiding little (bad)
- Strategic vs. tactical programming
- "Design it twice"
- Ousterhout's view: design matters *more* with AI, because AI-generated code erodes conceptual coherence

**Assignment:** [`spine-project/08-complexity-audit.md`](spine-project/08-complexity-audit.md)

Audit your spine project for complexity:
1. What is the **essential complexity** — inherent in the problem itself, irreducible?
2. What is the **accidental complexity** — complexity you're adding through your design choices, tooling, or habits?
3. Pick one source of accidental complexity and redesign to remove it.

---

#### Unit 8 — Conceptual Integrity

**Reading:** *The Mythical Man-Month* — Frederick P. Brooks Jr. (1975/1995)
*Assign: "The Mythical Man-Month," "No Silver Bullet," and "Aristocracy, Democracy, and System Design"*
**Load:** Light–Moderate (three essays).

**Key ideas to watch for:**
- Brooks's Law: adding people to a late project makes it later (n(n-1)/2 communication channels)
- Essential vs. accidental complexity ("No Silver Bullet")
- Conceptual integrity: "the most important consideration in system design"
- The second-system effect: the most dangerous system you ever design
- No silver bullet: no single advance yields 10x productivity on the essential work

**Assignment:** [`spine-project/09-conceptual-integrity.md`](spine-project/09-conceptual-integrity.md)

Write your project's **conceptual integrity statement** — one paragraph, the single coherent idea that everything in your system must serve.

Then audit your current design against it:
- What belongs?
- What violates it and should be cut?
- Where have you compromised integrity for convenience?

---

#### Consolidation 2 — Design (no new reading)

**Assignment:** [`spine-project/10-consolidation-design.md`](spine-project/10-consolidation-design.md)

Re-read your Module 2 deliverables (Units 4–8). Then, from memory:
- Trace the throughline from Meadows → Norman → Simon → Ousterhout → Brooks. They're all, in different vocabularies, about managing complexity and keeping a system comprehensible. Write that connective tissue in your own words.
- Where do they conflict? (E.g., Meadows' leverage points vs. Brooks's conceptual integrity; Norman's user-centred view vs. Simon's structural one.)
- How has your design for the spine project changed across this module?
- Carry forward: which single design idea most threatens your current plan, and why?

---

### MODULE 3 — Sustainable Work and Delivery (Units 9–13)

---

#### Unit 9 — Constraints and Flow

**Reading:** *The Goal* — Eliyahu M. Goldratt (1984)
*(A business novel — reads fast. Read the whole thing.)*
**Load:** Moderate, but fast — it's a novel.

**Key ideas to watch for:**
- Theory of Constraints: every system has at least one constraint limiting throughput
- Improving non-constraints is largely wasted effort
- The Five Focusing Steps: Identify, Exploit, Subordinate, Elevate, Repeat
- Throughput accounting vs. cost accounting
- The constraint moves once you fix the current one

**Assignment:** [`spine-project/11-constraint-analysis.md`](spine-project/11-constraint-analysis.md)

Identify the **binding constraint** in how your project actually gets built or delivered — not how you wish it worked, how it actually works.

Then:
1. Design a specific intervention at that constraint
2. Identify what you'll need to *stop* optimising (because it's not the constraint)
3. Predict where the constraint will move once you fix the current one

---

#### Unit 10 — Quality as a System Property

**Reading:** *Out of the Crisis* — W. Edwards Deming (1982/1986)
*Assign: The 14 Points and the System of Profound Knowledge*
**Load:** Heavy. Dense and dated even when trimmed to the assigned sections — budget two sittings.

**Key ideas to watch for:**
- Most problems are in the system, not the people
- Variation: common cause (system) vs. special cause (event)
- "Drive out fear" — why psychological safety is a quality issue
- Constancy of purpose: the antidote to short-termism
- Why inspection doesn't create quality (it just sorts it)

**On psychological safety:** Deming's "drive out fear" is the right instinct but he doesn't develop it fully. Amy Edmondson's research (see Further Reading) gives it rigorous treatment — specifically the link between psychological safety, learning behaviour, and team performance. If this thread is important to your project context, read *The Fearless Organization* alongside this unit.

**On organisational learning:** Deming tells you to fix the system; Argyris asks why organisations resist doing so even when they can see the problem. His distinction between single-loop learning (fixing errors within existing rules) and double-loop learning (questioning the rules themselves) is the missing piece. Worth reading alongside this unit or returning to at the Unit 14 retrospective. See Further Reading.

**Assignment:** [`spine-project/12-quality-audit.md`](spine-project/12-quality-audit.md)

Find one place in your project — past or present — where you blamed a person (or yourself) for a problem that was actually a property of the system.

Write:
1. What the system property was that caused it
2. How the system needs to change to prevent recurrence
3. What Deming's 14 Points would say about your current work process — which points are you violating?

---

#### Unit 11 — Intent Over Plans

**Reading:** *The Art of Action* — Stephen Bungay (2011)
**Load:** Moderate.

**Key ideas to watch for:**
- The three gaps: knowledge (plans ≠ reality), alignment (orders ≠ execution), effects (actions ≠ outcomes)
- Auftragstaktik / mission command: give intent, not instructions
- "Directed opportunism": clear goals + freedom to adapt
- Why detailed plans fail and what to do instead
- The briefing model: situation, task, intent, method, service support, command and signals

**Assignment:** [`spine-project/13-commanders-intent.md`](spine-project/13-commanders-intent.md)

Write your project's **commander's intent**:
- The **outcome**: what does success look like?
- The **why**: why does it matter?
- The **constraints**: what must not be compromised?

Make it clear enough that someone (or a future version of you) could make good decisions without you in the room. Then test it: hand it to someone and ask if they could act on it independently.

---

#### Unit 12 — Evidence-Based Delivery

**Reading:** *Accelerate* — Nicole Forsgren, Jez Humble & Gene Kim (2018) *(the capabilities model and DORA metrics)*
**Load:** Moderate. Research-report style — skim the statistical appendices if they're not your thing.

**Key ideas to watch for:**
- The four DORA metrics: deployment frequency, lead time for changes, change failure rate, time to restore service
- Speed and stability are not a trade-off — high performers have both
- The capabilities that predict performance (not the metrics themselves)

**Assignment:** [`spine-project/14-dora-assessment.md`](spine-project/14-dora-assessment.md)

Score your project against the DORA metrics (or their equivalent for non-software projects). Where are you weakest? Design one intervention. Focus on the *capability* behind the metric, not the metric as a target.

---

#### Unit 13 — Forecasting

**Reading:** *How Big Things Get Done* — Bent Flyvbjerg & Dan Gardner (2023) *(the planning chapters: reference-class forecasting, "think slow act fast," modularity)*
**Load:** Moderate.

**Key ideas to watch for:**
- The iron law: only 8.5% of projects hit both cost and time targets
- The optimism bias and how reference-class forecasting corrects it
- "Think slow, act fast": invest in cheap planning to shorten risky delivery
- Modularity as risk management

**Assignment:** [`spine-project/15-forecast.md`](spine-project/15-forecast.md)

Make a **reference-class forecast** for your project's completion:
1. Find a reference class of similar projects (what's the typical outcome?)
2. Make your outside-view estimate
3. Compare it to your gut / inside-view estimate
4. The gap between them is your planning fallacy. What does that tell you?

---

#### Consolidation 3 — Delivery (no new reading)

**Assignment:** [`spine-project/16-consolidation-delivery.md`](spine-project/16-consolidation-delivery.md)

Re-read your Module 3 deliverables (Units 9–13). From memory:
- Connect the throughline: Goldratt (where flow is constrained) → Deming (why quality is systemic) → Bungay (how to direct work you can't fully specify) → Forsgren (what good delivery measures) → Flyvbjerg (how to forecast honestly). They're five angles on *making work flow without it collapsing*.
- Where do they conflict? (E.g., Goldratt's single binding constraint vs. Deming's whole-system view; Bungay's intent-not-instructions vs. DORA's measurement discipline.)
- What did this module reveal about how your spine project *actually* gets delivered, versus how you assumed it did?
- Carry forward into the retrospective: which delivery assumption are you least sure of?

**Technical practice thread (Module 3, Units 9–13):**
If your project involves software, weave in Kent Beck's *Extreme Programming Explained* and Martin Fowler's *Refactoring* as practice, not reading. Try test-driven development on a feature. Refactor something that's gotten messy. These are best encountered as things you do alongside the project, not books you read and nod at. Spread them across the module rather than adding them to any single unit.

---

### MODULE 4 — Synthesis (Unit 14)

**No new reading.**

**On organisational learning (returning thread):** If you haven't read Argyris yet, this is a good time. The Unit 14 retrospective is itself an exercise in double-loop learning — not just "what went wrong" but "what assumptions was I operating under that caused me to miss it."

#### Unit 14 — Retrospective

**Capstone assignment — two parts:** [`spine-project/17-retrospective.md`](spine-project/17-retrospective.md)

*Part 1: Written retrospective*

Answer these questions honestly:
1. How did your problem framing change from Unit 1 to now? Show the before and after.
2. What did you design differently because of it?
3. What did you get wrong — about the problem, the design, or your delivery?
4. Which single concept from the course changed how you think most durably?
5. What would you do differently if you started the project again today?

*Part 2: Revised project*

Produce an updated version of your key Module 1 deliverables — the problem statement, reframes, and strategic kernel — reflecting everything you've learned. The question the revised versions should answer: **did your understanding of the problem actually change?**

If it didn't, that's worth examining honestly too.

---

## Complete Reading List

### Core syllabus (in order)

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

Plus three consolidation checkpoints (after Units 3, 8, and 13) and the Unit 14 retrospective — no new reading for any of these.

### Technical practice (alongside Module 3 / Units 9–13, if applicable)

- *Extreme Programming Explained* — Kent Beck
- *Refactoring* — Martin Fowler

### Further reading (not assigned, high value)

- *Thinking, Fast and Slow* — Kahneman (cognitive bias, decision-making)
- *Upstream* — Dan Heath (prevention over reaction)
- *Thinking in Bets* — Annie Duke (probabilistic reasoning)
- *The Fifth Discipline* — Senge (learning organisations)
- *The Lean Startup* — Ries (validated learning)
- *Team Topologies* — Skelton & Pais (org design for fast flow)
- *Lean Thinking* — Womack & Jones (lean principles)
- *Contextual Design* — Holtzblatt & Beyer (field research methods for understanding what users actually do; most relevant when designing for people whose work context you don't inhabit)
- *Emergent Strategy* — adrienne maree brown (adaptive, relational strategy from a non-corporate tradition; especially valuable in community or social sector contexts; overlaps with Meadows and Bungay from a different angle)
- *Sources of Power* — Gary Klein (naturalistic decision making; how experts actually make decisions under pressure — pattern recognition over option comparison; directly illuminates why initial framings stick, connects to Units 1–2)
- *The Fearless Organization* — Amy Edmondson (psychological safety as a measurable organisational condition; extends and grounds Deming's "drive out fear" with rigorous research; connects to Unit 10)
- *On Organizational Learning* — Chris Argyris (single-loop vs. double-loop learning; espoused theory vs. theory-in-use; explains why organisations resist updating their mental models even when the system shows them the problem; connects to Unit 10 and the Unit 14 retrospective)

---

## Working with Claude on this course

### Suggested prompt to start any session

> "Here's my course document. I'm in Unit [X], working on [assignment/reading]. Here's where I am: [your work so far]. Help me go deeper / push back on my thinking / identify what I'm missing."

### Useful prompts by activity

**Working through a reading:**
> "I just finished [book]. The idea I'm finding most useful is [X]. The idea I'm most skeptical of is [Y]. Push back on both."

**Stuck on an assignment:**
> "I'm working on Unit [X]'s assignment. Here's what I have so far: [paste]. What am I missing or avoiding?"

**Challenging a framing:**
> "Here's my current problem framing: [paste]. Give me three genuinely different reframes that would lead to completely different solutions."

**Connecting concepts (great for consolidation checkpoints):**
> "How does [concept from Unit X] interact with [concept from Unit Y]? Where do they agree and where do they conflict?"

**Applying to your project:**
> "Here's my current project design: [paste]. What would Ousterhout say is wrong with it? What would Brooks say?"

**Retrospective:**
> "Here's my Unit 1 problem statement and my Unit 14 version: [paste both]. Help me articulate what actually changed and what I'm still not seeing."

---

## Course design notes

**Why units instead of weeks?** Because there's no deadline, and the reading load is genuinely uneven. Pacing by the unit lets the hard material (Simon, Deming) take the time it needs while the light material (Gause/Weinberg, Wedell-Wedellsborg) stays light, instead of flattening everything to fit a calendar. The goal is retention, not coverage.

**Why this sequence?** Framing before design, design before delivery — because that's the actual dependency order. A good process applied to a badly framed problem just helps you fail efficiently.

**Why the consolidation checkpoints?** The failure mode of a reading-heavy course is finishing each book and immediately starting the next, so nothing gets revisited and little is retained. The checkpoints force spaced retrieval at the module boundaries — re-encountering ideas after a delay, pulling them from memory, and connecting them. This is deliberately the cheapest activity in the course and one of the highest-value.

**Why a spine project?** The failure mode of this material is intellectual familiarity without behavioural change. Concepts only stick when you apply them to something real and feel the friction.

**Why are some strong books excluded from the syllabus?** *The Fifth Discipline*, *Team Topologies*, *The Lean Startup*, *Thinking in Bets*, *Upstream*, *Contextual Design*, *Emergent Strategy*, *Sources of Power*, *The Fearless Organization*, and Argyris were kept in Further Reading to protect project time, not because they lack merit. Several are called out in specific unit notes where they're most relevant.

**On the AI-era framing:** The course's thesis — that framing and design matter more as implementation gets cheaper — is worth testing against your own experience as you go. Notice where AI accelerates your work and what that reveals about where the real difficulty actually lives.

---

## Change log

| Date | Change |
|------|--------|
| [initial] | Course created |
| [date] | Added Further Reading entries: Contextual Design, Emergent Strategy, Sources of Power, The Fearless Organization, Argyris. Added in-week callouts for psychological safety, double-loop learning, NDM, and Contextual Design. |
| 2026-06-14 | Re-paced from a fixed 12-week grid to a self-paced unit structure. Split the old Week 5 into Unit 5 (Norman) and Unit 6 (Simon, repositioned as the bridge to the complexity material, with a new decomposition assignment). Split the old Week 11 into Unit 12 (Accelerate/DORA) and Unit 13 (Flyvbjerg/forecast). Added three consolidation checkpoints at the module boundaries and per-unit reading-load flags. Renumbered spine-project deliverables (01–17) and renamed `weeks/` to `units/`. |
