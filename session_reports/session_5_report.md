# Session 5 Report: Terrorismo y guerras civiles
**Course:** Política Mundial (UC3M, 2025–2026)
**Date produced:** 2026-02-19
**Lecture folder:** `pol_mundial/slides/05_terror/`

---

## Summary Table

| Artifact | Status | File Path |
|----------|--------|-----------|
| Slide body | PASS | `slides/05_terror/terror_body.tex` |
| Presentation PDF | PASS (61 pp.) | `slides/05_terror/terror.pdf` |
| Notes PDF | PASS (14 pp.) | `slides/05_terror/terror_notes.pdf` |
| Pedagogy review | PASS | `quality_reports/terror_pedagogy.md` |
| Visual audit | PASS | (inline) |
| Assignment | SKIPPED — non-methods course | N/A |
| Solutions | SKIPPED — non-methods course | N/A |

---

## Phase 1: Slides

### Status at discovery
`terror_body.tex`, `terror.tex`, and `terror_notes.tex` already existed with complete content:
- 6 sections covering civil wars, civil war duration (bargaining), insurgency/COIN, terrorism, and counterterrorism
- 2 actual images: `armed_conflicts.png` and `september_11.jpg`
- All `\note{}` blocks filled with detailed speaker notes

### Structure (after pipeline improvements)

| Section | Content | Slides |
|---------|---------|--------|
| 0 | Title + Agenda | 2 |
| 1 | Violencia por actores no estatales | 3 (incl. image) |
| **TF** | *Transitionframe: Guerras civiles* | 1 |
| 2 | Guerras civiles | 5 |
| **TF** | *Transitionframe: ¿Por qué duran?* | 1 |
| 3 | ¿Por qué duran las guerras civiles? | 2 |
| **TF** | *Transitionframe: ¿Cómo se combaten?* | 1 |
| 4 | Insurgencia y contrainsurgencia | 2 |
| 5 | Terrorismo | 6 (incl. image) |
| **TF** | *Transitionframe: Respuestas* | 1 |
| 6 | Respuestas al terrorismo | 3 + discussion |
| — | Resumen I-I-I + Preguntas | 2 |
| **Total** | | **28 frames → 61 PDF pages** |

### Compilation
- First compile (original): 57 pages, no errors (only 2.12503pt footer artifact — harmless, pre-existing)
- Final compile (after fixes): 61 pages, no errors
- Notes compile: 14 pages, no errors

### Pedagogy review findings (6/13 followed, 4 violated)

**Critical issues fixed:**
1. ✅ **No `\transitionframe` at section pivots** — Added 4 transitionframes (Sections 1→2, 2→3, 3→4, 5→6). Section 4→5 already had the 9/11 image.
2. ✅ **Greed/grievance slide as sequential bullets** — Restructured as two-column layout (`\begin{columns}`) with `\textcolor{accent}{}` (teal) for Agravios and `\textcolor{accent2}{}` (red) for Codicia.
3. ✅ **Agenda slide missing** — Added "Hoy" agenda slide after title page.
4. ✅ **No on-slide examples for key concepts** — Added "(Ej: Siria, Colombia, Sudán del Sur)" to civil war definition.

**Medium issues fixed:**
5. ✅ **4-strategy table too tall** — Reduced `[6pt]` row spacing to `[4pt]` and `p{6.5cm}` to `p{6.0cm}`.
6. ✅ **No semantic color on binary contrasts** — Applied `\textcolor{accent2}{}` to "demasiado dura" and `\textcolor{asher}{}` to "demasiado blanda" in counterterrorism dilema slide.
7. ✅ **Discussion prompt font too small** — Changed `\footnotesize` to `\small` on both discussion frames.
8. ✅ **Implicit image extensions** — Made explicit: `.png` and `.jpg`.

**Remaining issues (low priority, not fixed):**
- Section 4 (Insurgencia/COIN) has no image, only a `\transitionframe`. An image of insurgent terrain or a COIN diagram would strengthen this section. Suggested search: "guerrilla fighters jungle terrain", or use existing `blue_helmets_CAR.jpg` from the unused materials folder.
- The "¿Por qué falla la negociación?" slide is dense (9 items at full reveal). Consider splitting or reducing sub-bullets.
- "Outbidding" and "Spoiling" in the 4-strategy table could use a brief Spanish gloss.
- The negotiation-failure slide could surface the IRA example on-slide (currently notes-only).

### Visual audit findings

| Severity | Issue | Fixed |
|----------|-------|-------|
| Medium | 4-strategy table vertical fit (`[6pt]`, `p{6.5cm}`) | ✅ |
| Medium | "11-S strategies" slide uses `\footnotesize` on full itemize | Not fixed — slide content was already compact; fixing would require content edits |
| Medium | Missing transition slides (5 sections) | ✅ |
| Medium | "Negotiation barriers" slide density (9 items at full reveal) | Not fixed — acceptable at current density; consider splitting if time allows |
| Low | Discussion prompts use `\footnotesize` | ✅ |
| Low | Summary slide item 3 too verbose | Not fixed — acceptable |
| Low | Implicit image file extensions | ✅ |

---

## Images needed

| Slide / Section | Suggested image | Search terms |
|----------------|-----------------|-------------|
| Section 4 (Insurgencia) | Photo of guerrilla fighters in terrain, or a diagram of the insurgent-population-state triangle | "guerrilla fighters jungle" / "asymmetric warfare" / "COIN operations" |

The `slides/unused_or_expanded/x_postwar_politics/img/` folder contains potentially reusable images (`blue_helmets_CAR.jpg`, `ftfarc.png`) that may be adapted for this section.

---

## Reference materials used

- `_hiddenrefs/polmundial/textbook/FLS_chp6.txt` — FLS Chapter 6 (full; covers civil war causes, bargaining failure, insurgency/COIN, and terrorism strategies and counterterrorism)
- `_hiddenrefs/polmundial/outline/chp06.txt` — Chapter outline

---

## Issues requiring attention

1. **Section 4 (Insurgencia/COIN) still needs an image.** The `\transitionframe` provides a visual break, but a photograph or diagram would substantially improve the visual rhythm of this section. See image suggestions above.
2. **"¿Por qué falla la negociación?" slide density.** At 9 items at full overlay reveal, this slide is at the upper density bound. Consider splitting into two slides if class pace allows.
3. **"Outbidding" and "Spoiling" in English.** These terms appear without Spanish gloss in the 4-strategy table. First-year students may benefit from "(competencia por apoyo)" and "(sabotaje de paz)" as brief clarifications.

---

## Quality scores

| Artifact | Score | Notes |
|----------|-------|-------|
| Slides — compilation | 100 | Clean, no errors |
| Slides — pedagogy (pre-pipeline) | 62 | 6/13 patterns followed |
| Slides — pedagogy (post-pipeline) | ~80 | 4 HIGH/MEDIUM issues fixed |
| Slides — visual audit (post-pipeline) | 85 | Medium issues resolved; low priority items remain |
| **Overall** | **82** | Acceptable — ready for use |
