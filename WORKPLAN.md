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
| Mat / Small Props | 69 | 011, 031–034 and 051–055 directly inspected (10) | 10 source-verified pages (011, 031–034, 051–055) |
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

## 2026-11-08 00:00 KST — four more original photos verified
- **031 · Mermaid with Rotation**, printed p.33: photographed source opened and read. Cross-legged start, INHALE shoulder abduction / EXHALE lateral flexion + rotation / INHALE elongation / EXHALE return. Verified pelvic verticality, obliques and variations (Arc Barrel/Box; omit rotation).
- **032 · Side Bend Mermaid Prep**, printed p.34: source opened. One-buttock/knee/hand support, externally rotated top hip, INHALE ready / EXHALE lateral flexion / INHALE return. Verified hand/knee alignment, elbow and scapular warnings, both-knees and straight-knee variations. Unclear handwritten note explicitly flagged.
- **033 · Side Kick Kneeling**, printed p.35: source opened. Side-supported kneeling, INHALE ready / EXHALE lift / INHALE horizontal hip flexion + dorsiflexion / EXHALE extension + plantar flexion / INHALE return. Verified leg height, hip rotation prevention and printed variations.
- **034 · Swimming Prep**, printed p.36: source opened. Quadruped contralateral reach (Bird Dog), INHALE ready / EXHALE reach / INHALE keep / EXHALE return. Verified neutral spine, toes contact and separate arm/leg reach variations.
- All four detailed source-separated entries saved to `movement-manual.html`, commit `26d64f5ec07b251b48e5ce412d023e1fe167e483`.
- **Next inspection**: 035–050, then 056–069 and apparatus. Verified ledger: **10/186**; other summaries remain unverified.
- **Public Pages check**: `https://sky53555.github.io/pilates-atlas/movement-manual.html` was not accessible through current web retrieval; do not mark published until independently confirmed. GitHub source update succeeded.

## 2026-11-08 01:00 KST — Mat 035 source verified
- **035 · Swimming**, printed p.37: original photo opened and visually inspected. Verified prone neutral spine/pelvis, arms and legs extended shoulder-width; INHALE Ready → EXHALE spinal extension/right arm + left leg → INHALE & EXHALE other side → INHALE & EXHALE return. Movement points: transverse abdominis/pelvic floor, obliques/erector spinae, hip extensors, scapular stabilizers. Watch points: abdominal support for spinal neutrality, shoulder-girdle stability, trunk wobble, natural breathing. Printed variation: simultaneous arm and leg lift. Red handwritten annotation near starting position is ambiguous; **not** treated as verified text.
- Added detailed source/coaching-separated `detail["035"]` to `movement-manual.html`. Photo verified count: **11/186**. Next: 036 onward; Curl Up/Roll Up independent QC remains pending.

## 2026-11-08 02:00 KST — Mat 036–039 source-photo verified
- **036 · Side Leg Series: Abduction**, printed p.38: opened source image. INHALE Ready → EXHALE Abduction → INHALE Return; neutral side-lying with both straight legs, lower arm head support and upper hand near abdomen. Source movement points TVA/pelvic floor/hip abductors; watch spinal rotation, scapular tension, lower waist collapse. Source variations body tilt and lower knee bend. Some handwritten text uncertain.
- **037 · Adduction**, printed p.39: opened source image. INHALE top-leg abduction → EXHALE lower-leg adduction → INHALE lower leg down → EXHALE return. TVA/pelvic floor/adductors, stable pelvis and shoulder, same printed variations. Handwritten note partly unclear.
- **038 · Knee Open**, printed p.40: opened source image. Knees flexed with heels below buttocks; feet together, EXHALE top knee opens / INHALE closes; printed variation feet/ankles lifted off mat. Handwritten cues noted separately.
- **039 · Side Kick Prep**, printed p.41: opened source image. EXHALE abduction → INHALE flexion + two kicks → EXHALE extension → INHALE return; neutral side-lying, avoid pelvis rocking. Source variations tilt body and bend bottom knee. Unclear handwritten notes not verified.
- Updated detailed SOURCE and COACHING separated entries for all four pages in `movement-manual.html`. **Photo verified total 15/186** (previous 11 + 4). **Next** 040–050, then remaining photos; Curl Up vs Roll Up separate QC still pending. No uninspected pages counted.

## 2026-11-08 03:00 KST — Mat 040–044 original photographs verified
- **040** · printed p.42: original JPG opened and read, title/Why/Starting Position/Breathing/Movement Point/Watch Point/Variation inspected. Detailed SOURCE and COACHING separated entry saved to movement-manual.html. Status: **verified**. 
- **041** · printed p.43: original JPG opened and read, title/Why/Starting Position/Breathing/Movement Point/Watch Point/Variation inspected. Detailed SOURCE and COACHING separated entry saved to movement-manual.html. Status: **verified**. Hands By Hip uses INHALE shoulder external rotation before EXHALE elongation.
- **042** · printed p.44: original JPG opened and read, title/Why/Starting Position/Breathing/Movement Point/Watch Point/Variation inspected. Detailed SOURCE and COACHING separated entry saved to movement-manual.html. Status: **verified**. 
- **043** · printed p.45: original JPG opened and read, title/Why/Starting Position/Breathing/Movement Point/Watch Point/Variation inspected. Detailed SOURCE and COACHING separated entry saved to movement-manual.html. Status: **verified**. Breast Stroke uses EXHALE cervical and upper thoracic extension, not a generic lumbar backbend.
- **044** · printed p.46: original JPG opened and read, title/Why/Starting Position/Breathing/Movement Point/Watch Point/Variation inspected. Detailed SOURCE and COACHING separated entry saved to movement-manual.html. Status: **verified**. Slow Swan has a distinct rocking phase and source variation omitting rocking.
- Total verified: **20/186** (previous 15 + 5). Next: 045–050; Curl Up 010 vs Roll Up 018 independent recheck pending. Unclear handwritten annotations explicitly excluded from verified source facts.
