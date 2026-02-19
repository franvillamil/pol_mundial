# Pedagogical Review: guerra2_body.tex
**Date:** 2026-02-19
**Reviewer:** pedagogy-reviewer agent

## Summary
- **Patterns followed:** 8/13
- **Patterns violated:** 1/13 (Pattern 4 — Standout Slides at Conceptual Pivots)
- **Patterns partially applied:** 4/13 (Patterns 2, 5, 7, 11)
- **Overall assessment:** Well-structured, example-rich lecture that successfully covers two FLS chapters (Domestic Politics and International Institutions). Strong motivational opening, vivid examples, and excellent I-I-I framework integration. Key weaknesses: (1) no `\transitionframe` standout slides at section pivots, (2) three commented-out opening images leave sections 3–5 text-first, (3) minor gap in semantic color usage for binary contrasts.

---

## Pattern-by-Pattern Assessment

### Pattern 1: Motivation Before Formalism — FOLLOWED
The deck opens by directly challenging the unitary-actor assumption from Lecture 3 before introducing any formal actor typology. "Can there be actors who benefit from war?" precedes the pyramid diagram. All section openings lead with motivating questions before definitions.

### Pattern 2: Worked Example After Every Definition — PARTIALLY APPLIED
Every formal concept receives a concrete example within one or two slides. Minor concern: the "Las organizaciones internacionales y la negociación" slide (line 546–559) lists three abstract mechanisms with no visible example on the slide (examples exist in notes only). Rwanda and Srebrenica for peacekeeping are also notes-only.

**Recommendation (Low):** Add a brief parenthetical example to at least one of the three mechanism bullets, e.g., "(Ej: OIEA y programa nuclear iraní)".

### Pattern 3: Progressive Complexity — FOLLOWED
Correct ordering: sub-state actors → regime-type (dyadic) → alliances (structural) → collective security (systemic/institutional). Within each section, observation → mechanism → critique/limitation.

### Pattern 4: Standout Slides at Conceptual Pivots — VIOLATED (HIGH)
None of the five section transitions uses `\transitionframe`. The three commented-out image frames were intended to serve as visual hooks for sections 3–5; their absence leaves abrupt section-to-section jumps. Discussion slides (Malvinas, democracy promotion, alliances selectivity) partially function as breaks but are thematic questions, not standout slides. No visual pivot exists between sections 1→2 or 2→3.

**Recommendation (High):** (1) Add `\transitionframe` at Section 1→2 pivot (no image planned here). (2) Add `\transitionframe` at Section 2→3 pivot (largest conceptual jump in the deck — from sub-state actors to regime-type effects). (3) Until the three image frames are uncommented, add temporary `\transitionframe` blocks for sections 3–5.

### Pattern 5: Semantic Color Usage — PARTIALLY APPLIED
The pyramid diagram and democracy mechanisms table use structural color correctly. However, binary contrasts (abandonment vs. entrapment; peacekeeping vs. peace enforcement) use only `\textbf` for both poles without color differentiation.

**Recommendation (Low):** In the two-column peacekeeping slide, consider `\textcolor{accent}{\textbf{Peacekeeping}}` vs. `\textcolor{accent2}{\textbf{Peace enforcement}}`.

### Pattern 6: Socratic Embedding — FOLLOWED
Four embedded discussion frames (Malvinas; democracy promotion; alliance selectivity; and transitional prompts within content). Excellent distribution — one per major section break. This is a strength.

### Pattern 7: Visual-First for Complex Concepts — PARTIALLY APPLIED
The pyramid diagram correctly precedes explanation. Three image frames for sections 3–5 are correctly placed architecturally but commented out, making three section openings text-first in practice.

**Recommendation (Medium):** Obtain and uncomment the three image frames. Prioritize: UN peacekeeping map (freely available from peacekeeping.un.org), Cold War Europe blocs map (widely available), and democratic peace dyadic scatter (FLS Figure 4.4 or Correlates of War data).

### Pattern 8: Two-Column Definition Comparisons — FOLLOWED
The peacekeeping/peace-enforcement two-column layout is correct and effective. The democracy mechanisms table is functional. Minor opportunity: Abandono/Trampa could be side-by-side.

### Pattern 9: Narrative Arc — FOLLOWED
Strong arc: opens by breaking from Lecture 3's unitary-actor assumption; closes with I-I-I summary that maps the lecture back to the course-level framework; final note announces next week's topic. The bargaining model from Lecture 3 is referenced at lines 199, 365 (notes), and 553–556. Minor gap: no visible agenda/roadmap slide for students.

**Recommendation (Low–Medium):** Add a brief agenda slide after the title page listing the four substantive sections.

### Pattern 10: Pacing — FOLLOWED
Maximum 3–4 consecutive theory-heavy slides before a discussion break or visual pause. The final stretch (OO.II. → Resumen) is slightly long (4 slides) but acceptable.

### Pattern 11: Visual Rhythm — PARTIALLY APPLIED
`\section{}` markers are invisible in projected slides (AtBeginSection is commented out in preamble; `\transitionframe` is never used). In current state (3 image frames commented out), the deck has only 1 original diagram + 1 table + 1 two-column layout across 23 content slides — text-heavy.

**Recommendation (Medium):** Activate `\transitionframe` at all major pivots (see Pattern 4). This resolves Pattern 11 as a side effect.

### Pattern 12: Notation Consistency — FOLLOWED
Minimal formal notation, consistently handled. I-I-I framework used consistently across lectures. English technical terms italicized on first use. "OO.II." could be spelled out at first use (line 547).

### Pattern 13: Pre-empting Student Concerns — FOLLOWED
Deck anticipates key objections: diversionary war weak evidence (line 103), democracy doesn't mean more peaceful overall (line 250), democratic peace correlation ≠ causation (line 290), Security Council veto paralysis (lines 472–499). Two important caveats are notes-only: (a) not all military leaders are hawkish; (b) interest groups can be pro-peace.

**Recommendation (Low):** Surface at least one of these on a slide bullet. "Pero: no todos los militares son belicistas (ej: generales en Irak 2003)" prevents an oversimplified reading of the military-industrial complex argument.

---

## Deck-Level Analysis

### Narrative Arc
One of the deck's genuine strengths. The "opening of the black box" framing is sustained throughout. The connection to the Lecture 3 bargaining model is woven explicitly into Sections 1, 4, and 5. The closing I-I-I summary elegantly maps three sections onto the course's organizing framework. The Malvinas case thread in Section 1 is a particularly effective sustained illustration.

Minor gap: the lecture title "Guerras y organizaciones" somewhat undersells the domestic-politics half (first ~40% of the lecture).

### Pacing
Good. The pattern of 3–4 theory slides followed by a discussion question is consistently maintained across all sections. Four discussion prompts are well-placed. The lecture is ambitious (two FLS chapters) — if class is 75–90 minutes, the instructor should plan for the discussion prompts to be short (not full class discussions).

### Visual Rhythm
The main structural weakness. In current state (3 images commented out), nearly all content is text-based. `\transitionframe` is defined in the preamble but unused. Adding `\transitionframe` at the two unprotected section boundaries (1→2 and 2→3), plus temporary replacements for the commented-out image sections, would substantially improve visual rhythm.

### Cross-Lecture Connection
The collective action problem (acción colectiva) appears in two distinct contexts: Section 2 (small groups vs. diffuse public, line 158–184) and Section 5 (free-rider in collective security, line 472–499). The connection between these two uses is implicit but not stated. An explicit cross-reference would turn an implicit echo into a pedagogical payoff.

**Recommendation (Low):** Add a brief parenthetical in the collective security slide, e.g., "(el mismo problema que en los grupos de interés domésticos)."

---

## Top 5 Critical Recommendations

1. **[HIGH] Add `\transitionframe` at Section 1→2 and Section 2→3 pivots.** These are the two section boundaries with no visual/thematic break of any kind. Section 2→3 is the largest conceptual jump (sub-state actors → regime-type effects).

2. **[MEDIUM] Add temporary `\transitionframe` for sections 3–5 openings** until image frames are uncommented. The commented-out image architecture is correct; `\transitionframe` serves as a placeholder.

3. **[MEDIUM] Add an agenda/roadmap slide after the title page.** The lecture covers two chapters across five sections — students benefit from knowing the scope upfront.

4. **[LOW] Surface the "gambling for resurrection" hockey analogy on the slide**, not only in presenter notes. This analogy is the clearest explanation of why diversionary war is rare and should be visible to students.

5. **[LOW] Add "not all military leaders are hawkish" caveat on the "El complejo militar-industrial" slide.** Prevents an oversimplified reading. The note (line 154) has the correct examples (Iraq 2003 generals).
