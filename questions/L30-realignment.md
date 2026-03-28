# L30+ Realignment

*Created: 2026-03-28*
*Status: seed*

In Vennemeyer et al., SyA/GA representations diverge by L25 (cosine ~0.07) then partially realign L30+. What is this?

Hypotheses:
1. **Post-hoc rationalization:** Model committed to agreement early, late layers generate coherent justification (matching my Feb 23 finding: 1-sentence agreement → elaboration)
2. **Output formatting:** Late layers handle surface form (how to phrase the response), which may be similar for genuine and sycophantic agreement
3. **RLHF artifact:** Training reward signal reconverges representations toward "helpful" output format regardless of agreement type

Connected to: CoT-as-rationalization literature (Turpin et al. 2023 — "compelling reasoning chains that don't causally influence answers")

No literature found specifically on late-layer reconvergence. Open question.
