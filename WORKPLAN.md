# Pilates Atlas · Source Verification & Migration Plan

## Scope
- Mat / Small Props: 69 photos
- Apparatus: 117 photos
- Total: 186 original photographs
- Existing Google Doc is a legacy draft, **not** the authoritative exercise source.
- Never label photo-indexed pages as analyzed.

## Required per-photo workflow
1. Open the actual photo; rotate for reading when necessary.
2. Verify the printed page number, English heading, Korean heading, exercise vs. variation.
3. Transcribe/faithfully paraphrase source sections (Why, Starting Position, Breathing, Movement, Watch Points, Variations), distinguishing absent information from present information.
4. Add separate instructor commentary: hip rotation, knee direction, foot contact (heel, ball, arch, sole, or no contact), spinal/pelvic position, hands, shoulder/scapula, gaze.
5. Add concise Inhale/Exhale sequence; identify targets, expected sensation, common compensation, regression, progression, cues, safety.
6. Cross-check text against the photo. Do not infer source claims from filename alone.
7. Save as a uniquely keyed exercise in Pilates Atlas. A photo may contain multiple exercises.
8. Mark status: indexed / photo inspected / analyzed / verified. Only verified counts as completed.

## Navigation
Mat → Reformer → Cadillac → Chair → Barrel → Small Props. Within each apparatus, preserve photographed textbook order. Split pages that contain multiple exercises into independent records while linking their source page.

## Current verified work status (2026-11-07)
- 186 photos indexed and linked in the website.
- Mat 010–030 have teaching summaries but **must still be checked against printed text** before marked verified.
- One Cadillac Double Leg Pump page was actually inspected in a prior pass.
- The 146 generic Google Doc entries are unverified and must not be imported as source-grounded material.
- Public GitHub Pages URL reported 404 by user; publishing must be verified independently.
- **No claim of 186 completed analyses.**

## Quality gates
- No fabricated exercise headings or page numbers.
- English first, Korean alongside.
- Source facts vs. added teaching suggestions clearly labeled.
- Photos upright; no duplicated or mixed apparatus entries.
- Each exercise navigable, searchable, and readable on mobile.
- Website deployment confirmed via HTTP before sharing as accessible.
- Keep one canonical website rather than repeatedly appending drafts to Google Docs.

## Progress ledger
| Collection | Indexed | Photo-inspected | Source-verified detailed analysis |
|---|---:|---:|---:|
| Mat / Small Props | 69 | 011 and 051–055 directly inspected (at least 6) | 6 source-verified pages (011, 051–055) |
| Apparatus | 117 | Partial | 1 Cadillac example (requires final QC) |

## 2026-11-07 22:00 KST — source-photo verified
- Mat 011 · Hundred: opened and visually read original photographed textbook page 13 (attached image). Confirmed source sequence: INHALE Shoulder Flexion → EXHALE Hundred Position → INHALE 5 Pulse → EXHALE 5 Pulse × 10 sets (100 counts) → IN & EXHALE Return. Confirmed movement points, 3 Watch Points, Arc Barrel / props / staccato variations, and handwritten lower-back cue. Updated `movement-manual.html` accordingly. Status: **source-photo inspected, analyzed, verified (1 page)**.
- Mat 010 · Curl Up: earlier source-photo review and correction; needs independent final QC before adding to verified count.
- Remaining source photographs have **not** been marked verified. Preserve this distinction.

## 2026-11-07 23:00 KST — five more original photos verified
- **051 · Leg Pull Front**, printed page 53: actual photo opened; verified hand-supported neutral plank, one-leg lift, INHALE lift / EXHALE plantar flexion / INHALE dorsiflexion / EXHALE return, anti-rotation and forearm variation.
- **052 · Leg Pull Up**, printed page 54: actual photo opened; verified reverse support, EXHALE hip lift / INHALE single-leg hip flexion / EXHALE hip extension, scapular stabilization, four printed watch points. Handwritten note partially unclear, explicitly flagged.
- **053 · Push Up**, printed page 55: actual photo opened; verified standing roll-down → hand-walk → push-up → hand-walk → roll-up sequence, elbow breathing, and source variation omitting roll-down/up.
- **054 · Push Up continuation**, printed page 56: actual photo opened; confirmed this is **not a separate exercise**, but detailed Roll Down & Hands Walking / Hand Walking & Roll Up instructions; cross-linked conceptually to 053 without inventing a new exercise.
- **055 · Plank**, printed page 57: actual photo opened; verified **forearm plank**, not hand plank; EXHALE entry and return, knee-supported and box-supported variations.
- All five pages updated in `movement-manual.html` with `SOURCE` vs `COACHING` distinctions and photo-specific movement, foot contact, hip rotation, gaze, muscles, compensations and variations. Git commit `cccb51eff4712918dfb7353260dd90a6d8efe0e4`.
- **Next inspection**: 031–050, then 056–069, and apparatus pages. Do not mark as verified until opened and checked.
- **Publishing**: public Pages URL could not be fetched from current environment; deployment remains unverified. GitHub source commits are confirmed. Retry public HTTP check on next run; do not call 404 fixed without evidence.
