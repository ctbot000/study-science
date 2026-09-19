# study-science

This repository is for science notes. The deliverable is prose, notation and
numbers — not code. Do not scaffold projects, add build tooling, or set up tests
here unless asked. A short script to check a calculation is fine, but it does not
get committed unless it is the thing being learned.

## Where notes come from

Anything I learn about science, in any session, in any project — a mechanism
that finally clicked, a constant I had to look up twice, a distinction between
two terms I kept confusing. Recording it is a standing instruction everywhere;
this repository is the one place the results accumulate.

Notes are written in the same reply as the learning, not at session end. A
session can be interrupted, and an unwritten note is a lost one.

## Structure

- `INDEX.md` — one line per note, grouped by area. This is what gets read first,
  so the hook has to say what the note is actually good for.
- `notes/<area>/<topic>.md` — one idea per file.

Areas: `astronomy`, `biology`, `chemistry`, `earth-science`, `physics`,
`method` (measurement, experiment design, how a claim gets established). Add a
new one only when nothing existing fits — and add its section to `INDEX.md` too.

Filenames are kebab-case and name the idea, not the occasion:
`entropy-is-not-disorder.md`, not `today-thermodynamics.md`.

## Note format

```markdown
---
title: <the claim or the concept, as a phrase>
area: <one of the areas above>
tags: [<3 or fewer>]
added: <YYYY-MM-DD, Korean calendar day>
---

## Idea

One or two sentences. What this is, in plain language, before any notation.

## Key facts

The quantitative core — equation, constant, rule of thumb. Notation as `$…$`
inline or `$$…$$` display. Every quantity carries its unit.

## Mechanism

Why it happens, in outline. The one step that makes it work, not a derivation
unless the derivation is the point.

## Example

The smallest concrete case with real numbers, including the order of magnitude.

## Pitfalls

What I got wrong, the term it is confused with, or the regime where it stops
holding.

## See also

Links to related notes: `[title](../area/file.md)`.
```

**Every section is optional except `Idea`.** A note that is three lines and an
equation is a good note. Sections exist to keep the shape predictable, not to be
filled in.

## Writing rules

**Brief beats complete.** If a note cannot be reread in under a minute, it is
two notes, or it is a textbook chapter that does not belong here.

**Write the idea, not the session.** "Entropy measures the number of
microstates, not untidiness" is a note. "Read about thermodynamics today" is not.
No dates in the body, no "I was trying to…".

**One idea per file.** When a note starts covering two things, split it.

**Say where the model breaks.** A science fact has a regime. Note the
approximation being made and where it fails — that is usually the part worth
remembering.

**Units and magnitudes, always.** A number without a unit is not a fact. Give
the order of magnitude even when the exact value is not the point.

**Add a note only when it is new.** Read `INDEX.md` first. If the idea is already
recorded, sharpen that note rather than adding a second one, and say so in the
reply.

**Update the index in the same commit.** A note missing from `INDEX.md` is a note
that will never be found.

## What does not go here

- Copied textbook material or lecture transcripts. Record what it taught, not
  what it said.
- Per-session or per-date files. No study logs.
- Mathematics for its own sake — that goes to `../study-math`. A formula used to
  explain a physical mechanism belongs here; a theorem does not.
- General engineering knowledge — that belongs in the knowledge base at
  `../knowledge-base`.
- Notes about my English — those go to `../study-english`.
