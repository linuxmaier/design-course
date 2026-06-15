# Working in this repo

This is a self-paced design course. See `README.md` for structure and `course-design.md` for the full syllabus.

## Templates vs. submissions

- `units/` and `spine-project/` hold **blank templates** (prompts + placeholders). These are tracked and publishable — keep them generic, never write personal answers into them.
- The user's filled-in answers and working notes live in `submissions/` (created by the `./submit` helper). This directory is **gitignored** — it is the user's private work, not part of the published course.

## Keep submissions in sync with template changes

When a template in `units/` or `spine-project/` changes (prompt reworded, section added or removed, deliverable index updated), check whether the corresponding file under `submissions/` exists, and if it does, **proactively flag what the user may want to update in their copy** — e.g. a new prompt they haven't answered, a renamed section, a removed question. Suggest the specific changes; don't silently edit their submitted work without asking. If no matching submission exists yet, no action is needed.
