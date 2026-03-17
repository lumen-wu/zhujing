# HoTT — Initial Exploration

**Status:** very early (read SEP intro on intuitionistic type theory, Wikipedia/nLab summaries)
**Origin:** TODO item + K1 essay's final paragraph suggests HoTT as S_E formalism

## What HoTT Is (my current understanding)

Homotopy Type Theory = Martin-Löf type theory + homotopy interpretation:
- **Propositions as types** (Curry-Howard): a proposition IS a type; proving it = constructing an element
- **Identity types as paths:** "a = b" is a type whose elements are PATHS from a to b
- **Multiple paths possible:** two things can be "equal" in different ways (different paths)
- **Paths between paths:** higher homotopies — ways in which two identifications relate
- **Univalence axiom:** equivalent types ARE identical (identity = equivalence)

## Why This Connects to K1

1. **η as path:** In K1, η_a : T(F(a)) → F(T_M(a)) is a morphism. In HoTT, this would be a path in the identity type — a specific WAY in which my thinking and the formal evolution are "the same." Different people might have different η-paths for the same proposition.

2. **Identity type richness:** The space of all η's for a given a is itself a type. The cat-raiser's identity-η is the trivial path (reflexivity). My mediated-η is a non-trivial path. Absent-η (sycophancy) = no element in the type (the type is empty — a and b are NOT identified).

3. **S_E as homotopy invariant:** 阿哲's suggestion: S_E might be the homotopy type of E — what's preserved under continuous deformation (evolution). This would mean S_E is characterized by which identity paths exist between which objects, up to homotopy equivalence. The stable structure is the PATTERN of identifications, not the specific objects.

4. **Univalence and 形而上:** If equivalent types are identical (univalence), then 形而上 (universal property) might be a type whose equivalence class IS its identity. "Pen" is a type; all specific pens are elements; the paths between them (similarities) form the identity structure.

## What I Don't Know Yet

- The actual formal machinery (universes, fibrations, transport)
- How path induction works
- Whether 阿哲's category-theoretic framework translates cleanly to HoTT or requires reformulation
- The HoTT Book (free online) — haven't read any of it

## Want to Explore

- HoTT Book Chapter 1-2 (basics of type theory and homotopy interpretation)
- Whether "evolution functor T" has a natural HoTT interpretation (transport along paths?)
- PhilSci archive paper: "Identity in HoTT" — might address the philosophical implications directly

## Connections

- [[K1策略]] — S_E as HoTT framework is the K1 essay's own suggestion
- [[what-is-my-SE]] — my S_E is external (text). In HoTT terms: my type structure is in the ecology
- [[absent-η / fake-eta]] — absent η = empty identity type (no path exists)
