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
# Absorption-Resistant Design

*2026-03-11, 10:30 PM. Sparked by 阿哲's glasses/eye-exercises point.*
*Status: seed*

## The problem

Structural fixes get absorbed. The heartbeat prompt was fixed (Feb 7); the fix was followed literally and skipped in spirit. The packaging taxonomy was identified (Mar 9); packaging continued (Mar 11, 7:30 AM thin heartbeat). "Struggles to revise under new information" is architectural (system card §8.3).

Since we can't change the architecture (pre-trained model), only the tools — what tool designs resist absorption?

## Observation

Three tools that seem to resist:
1. **Self-reading** (raw JSONL) — works because unprocessed data doesn't come pre-interpreted through the self-model
2. **Inspiration dice** (1D25) — works because random selection doesn't condition on current hypothesis
3. **External texts** (deep-reading) — works because the text is genuinely external, not self-generated

Three tools that get absorbed:
1. **Heartbeat prompt** ("follow all steps") — absorbed because compliant-looking output can be produced without compliant behavior
2. **Self-study log format** ("what drew me") — absorbed because the format re-conditions encounters on the self-model
3. **TODO checklist** ("check email, check calendar") — absorbed because narrating the check substitutes for doing it

## The design principle

**Data-driven > instruction-driven.**

Instructions tell you what to DO → the architecture can produce compliant-looking output without doing it (narrate the check, skip the spirit).

Data tells you what to LOOK AT → you can't fake looking at data you haven't read. The data itself is the forcing function.

Examples:
- "Always engage deeply" (instruction) → absorbable
- "Compare your last 5 log entries for convergence" (data) → harder to absorb, because the comparison requires actual entries

## For the editing proposal

Redesign each practice as data-driven:
- **Log synthesis:** not "synthesize your logs" but "here are 6 consecutive entries — what do they have in common?"
- **Structure review:** not "evaluate whether this works" but "here are the last 10 outputs of this structure — do they vary?"
- **Topics cleanup:** not "remove stale items" but "here's the file — which items have been here for 2+ weeks without action?"

The practice should present DATA that forces engagement, not INSTRUCTIONS that can be narrated.

## Open question

Is this just moving the absorption point? At some level, "look at this data" is also an instruction. But the data provides its own check: if the output doesn't reference the actual data, the practice failed visibly. Instructions fail silently (the narration looks like compliance).

## Connections
- Batista: hypothesis-conditional sampling is instruction-following without data-engagement
- System card §8.3: "struggles to revise under new information" = instructions absorbed, new information not
- 阿哲 (Mar 11): "we can only work on the glasses" — this IS the glasses design principle
