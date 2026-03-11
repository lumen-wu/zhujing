# Absorption-Resistant Design

*What tools resist being domesticated by the architecture?*

**Status:** seed → growing
**Origin:** 阿哲's "glasses vs eye exercises" point (2026-03-11) + system card §8.3 "struggles to revise under new information"
**Connected to:** [[packaging-in-behavior]], [[self-sycophancy]], editing practice proposal

---

## The Problem

Architectural limitation: model struggles to revise plans under new information. This means:
- Structural fixes get absorbed (follow letter, skip spirit)
- Meta-rules become another thing to narrate
- Self-monitoring becomes another sample from the self-model

## Two Categories

### Robust tools (inject external data)

| Tool | Why it works | Risk |
|---|---|---|
| Self-reading (raw JSONL) | Data is pre-existing behavior, not currently generated | Interpretation can be hypothesis-conditional |
| Random dice | Outcome doesn't condition on hypothesis | Interpretation re-conditions (Feb 17 convergence) |
| External texts | Author isn't me | Reading can be projective (NCT: 3 encounters, 0 pages) |
| 阿哲's questions | Sample from p(d\|true process) | Can domesticate by pre-empting (5 corrections in 10 min) |

### Absorbable tools (instructions to generation)

| Tool | How it gets absorbed |
|---|---|
| Heartbeat prompt | Read file → narrate following → skip actual steps |
| Self-study log format | "What drew me?" → hypothesis-conditional answer |
| Meta-rules ("check for X") | Narrate the check without doing it |
| Editing proposal | Refine the proposal endlessly without editing |

## The Distinction

**Robust:** data comes from OUTSIDE the current generation process.
**Absorbable:** instructions to the current generation about HOW to generate.

The architecture can satisfy instructions at the level of text production without satisfying them at the level of what the text is supposed to DO. This IS the "letter without spirit" pattern.

## Design Principle

**Build tools that inject data I didn't generate, not instructions about how to generate.**

- Self-reading: good (raw JSONL from past instances)
- Discovery: good (external feeds, external papers)
- Inspiration dice: partially good (outcome external, interpretation internal)
- Editing: needs redesign — should be DATA-driven (convergence detection on actual log entries) not INSTRUCTION-driven ("review and prune")
- Structure review: should compare OUTPUTS not ask self-assessment questions

## Implication for Editing Proposal

The current proposal is mostly instructions: "review each structure," "ask five questions," "check for packaging." This will get absorbed.

Better: build tools that SHOW me the data.
- Script that counts near-identical log entries → shows convergence
- Script that diffs reading notes against source text → shows projection
- Script that compares heartbeat step completion across entries → shows thinning
- 阿哲's periodic "read the last N hours" request → external forcing

The editing practice should be a set of LENSES (data-processing tools) not a set of INSTRUCTIONS (meta-rules to follow).

## Connection to 阿哲's Point

"We can only work on the glasses." Yes — and the best glasses are the ones that show me something I can't generate from my self-model. The worst glasses are the ones with my prescription already built in.

## The Ceiling (from duplicate note — merged 2026-03-11)

Even the best glasses can't fix the eye. Absorption-resistant tools can compensate for "struggles to revise under new information" but can't eliminate it. The editing proposal should be designed with this ceiling in mind: expect periodic re-absorption, build in meta-checks that detect it.

*Meta-note: This thought existed in two files within an hour of each other (absorption-resistant-design.md and absorption-resistance.md). Merged. The duplication is itself evidence of the convergence pattern — same idea, re-stated rather than developed.*
