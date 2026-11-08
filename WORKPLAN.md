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


## 2026-11-08 04:00 KST — Mat 045–050 original photographs inspected and verified
- **045 Spinal Release**, printed p.47: source image opened; seated flexion with hips supported; breathing INHALE/EXHALE spinal release, INHALE keep, EXHALE articulation. Source variation supine knee-to-chest. Handwriting partly uncertain.
- **046 Single Leg Extension**, printed p.48: prone external rotation, one leg hip extension, INHALE ready / EXHALE lift / INHALE keep / EXHALE return. Arc Barrel and ASIS-pad variations.
- **047 Double Leg Extension**, printed p.49: prone bilateral leg extension, source INHALE/EXHALE/INHALE/EXHALE sequence; ASIS-pad and two-stage-breath variations.
- **048 Hamstring Curl**, printed p.50: prone knee flexion → small extension → flexion → extension with six printed breathing phases; ASIS pad and single-curl variation.
- **049 Heel Squeeze**, printed p.51: prone, knees bent, slightly externally rotated hips, heels meet; INHALE ready / EXHALE heel squeeze. No printed variation section; not invented.
- **050 Leg Pull Front Prep**, printed p.52: quadruped knee hover with alternating leg lifts, detailed printed eight-phase breathing; band variation. Repeated 'Knee Off' text preserved without silently correcting.
- All six actual JPG pages opened and read, with printed Why/Starting Position/Breathing/Movement Point/Watch Point/Variation separately captured and instructor additions labeled COACHING. Detailed entries committed to movement-manual.html at 0e4205d32dd508a238989e2940ad68784e4ec9f0.
- **Verified count 26/186** (prior 20 + 6). Next: 056–069 Mat/Small Props and apparatus; also independent Curl Up 010 vs Roll Up 018 recheck. Site deployment still unverified.


## 2026-11-08 05:00 KST — source photographs 056–066 inspected (11 pages)
- **056 (printed p.59)** Arc Barrel upper-thoracic overview: Curl Up, Hundred, Single Leg Stretch, Criss Cross; the page explicitly says Mat sequence/breathing/cautions unchanged. No new breathing invented.
- **057 (p.60)** Arc Barrel upper-thoracic Scissor/Double Leg Stretch, and pelvic-support Scissor/Double Leg Lower & Lift/Shoulder Bridge. Support indications and distinct contact points recorded. No independent breathing printed.
- **058 (p.61)** seated Arc Barrel (=Box): Spine Stretch Forward, Spine Roll Back, Spine Lean Back, Roll Down, Spine Twist, Mermaid with Rotation. Six separate pictured adaptations, no new printed breathing.
- **059 (p.62)** prone Arc Barrel: Breast Stroke Prep Hand by Shoulder, Slow Swan, Single Leg Extension, Double Leg Extension; lumbar tension/anterior tilt support indicated. No new breathing printed.
- **060 (p.63)** Gym Ball introduction, sizing guidance and Curl Up/Hundred/Criss Cross photos; source says Mat breath and cautions remain unchanged.
- **061 (p.64)** Gym Ball Bridge and Single Leg Lift are TWO distinct exercises. Printed breathing recorded verbatim, including ambiguous 'Leg Off' labels, not silently corrected.
- **062 (p.65)** Gym Ball Double Leg Lower & Lift (no printed breath on this page) and Back Extension (INHALE Ready → EXHALE Spinal Extension → INHALE Return).
- **063 (p.66)** Gym Ball Scapula Movement (INHALE Reach Arm bend → EXHALE Return), plus separate Pec Stretch without printed breathing.
- **064 (p.67)** Circle Lat Press (INHALE Ready → EXHALE Circle Press), Single Lat Press, Mermaid, Arm Press AB, Hundred. Important correction: Mermaid photo uses ONE hand on upright Circle, not a two-hand Circle grip.
- **065 (p.68)** Circle Double Leg Stretch, Adductor Press, Hamstring Curl, Double Leg Extension. No printed breathing; Double Leg Extension knee-angle warning preserved.
- **066 (p.69)** Circle Hamstring/Adductor/IT-Band Stretch, three directions with printed EXHALE phases; pelvic/shoulder contact cautions preserved.
- All eleven actual JPG images opened and visually read. SOURCE/COACHING separately entered in `movement-manual.html`; photo overview pages are **verified as source-photo overviews**, not fabricated independent exercise protocols. Commits `d4ce635a58e25d46ed62a55b9bda12f2a92bd203`, `8564b6eb4eed19bfa21f90d2811f52e2aee5c3c1`.
- **Verified source-photo pages 37/186** (previous 26 + 11). Next: **067–069**, then 010 Curl Up vs 018 Roll Up independent photo comparison, then apparatus folder. If a photo fetch fails, log it and continue with another page.
- Public GitHub Pages deployment remains **unverified**; do not present a public URL as functioning until HTTP success.


## 2026-11-08 06:00 KST — additional Mat originals 067–069 checked
- **067 · Roll Over, printed p.24**: opened original JPG; confirmed Roll Over (not Roll Up), supine imprinting, arm support, five-phase printed breath (INHALE hip flexion → EXHALE roll over → INHALE leg abduction → EXHALE roll down → INHALE leg adduction), TVA/pelvic floor, rectus abdominis/obliques/hip flexor, segmental spinal control, no arm push, fixed hip angle, same rolling speed, printed omit-Ab/Ad variation. Handwritten top note not fully legible; excluded.
- **068 · Side Leg Series 3 Knee Open, printed p.40**: original photo opened; duplicate of 038 exercise, not a new exercise. Side-lying, knees bent, feet together, EXHALE open / INHALE close, hip abductor and TVA/pelvic floor; avoid pelvis rotation, shoulder tension, bottom waist collapse. Printed feet-lift variation. Handwriting uncertain, flagged.
- **069 · Circle four-exercise overview, printed p.68**: original photo opened; duplicate photographed Circle overview of 065 (Double Leg Stretch, Adductor Press, Hamstring Curl, Double Leg Extension), not four new independent movements. Circle location and posture visually confirmed. Printed warning to maintain knee angle in Double Leg Extension; no independent breath printed.
- All 3 source-photo pages have detailed SOURCE vs COACHING entries in movement-manual.html. **Verified unique source photographs: 40/186** (37 + 3; duplicates still count as distinct photos, not distinct exercises).
- **Next** independent 010 Curl Up vs 018 Roll Up photo check, then apparatus originals. Do not mark remaining pages verified without opening images. Public site accessibility still unverified.


## 2026-11-08 07:00 KST — independent Curl Up / Roll Up source-photo QC
- **010 Curl Up · printed p.12**: opened original JPG directly (Drive file `16uB1r23FLt4ACxJwXTIGJPjr8hnk6qtt`). Source: supine neutral pelvis, knees bent hip width, feet planted, gaze ceiling; INHALE Shoulder Flexion → EXHALE Head Nod & Cervical and Upper Thoracic Flexion → INHALE Keep → EXHALE Return. Movement: TVA, pelvic floor, rectus abdominis/obliques, scapular stabilizers. Watch: shoulder/neck tension, pelvis neutral. Variations: Arc Barrel, Circle/Spacer/Ball, both legs Leg Folding, hands behind head. **Verified original photo**, not a full sit-up.
- **018 Roll Up · printed p.20**: opened original JPG directly (Drive file `1atTLtc94l_vKDXJKMNxJk83NhNsIbaRI`). Source: supine neutral pelvis, legs STRAIGHT hip width, ankles dorsiflexed, arms overhead; INHALE Shoulder Flexion → EXHALE Roll Up → INHALE Roll Down → EXHALE Starting Position. Movement: TVA/pelvic floor, rectus abdominis/obliques, hip flexors, scapular stabilizers. Watch: sequential spinal articulation, rib cage stabilization, avoid rigid extension when rounding. Variations printed: bend knees, press backs of hands down (손등 눌러주기), rise only to upper thorax. **Verified original photo**, full roll to seated unlike Curl Up.
- Both entries now have detailed SOURCE vs COACHING separation in `movement-manual.html`; commit `b96de3c09b25ff32ec94269ad52ba0ef134f4a80`. **Do not add +2 to unique verified photo count**: these photos had been included in prior verified set; this is targeted recheck. Verified remains **40/186**.
- Next: apparatus original-photo verification, starting Reformer. Do not infer printed instructions from filenames. Continue failed items on later runs. Public site accessibility still requires independent HTTP confirmation.


## 2026-11-08 08:00 KST — Reformer original photos inspected (3)
- **Reformer Stag · printed p.25**, original Drive file `1P4lM_wQJXfcDO5xWIopEjSZL2giEdNFa`: verified actual page image, alternating one-leg Frog and other-leg hip abduction/adduction; INHALE movement → EXHALE return. Source pelvic rotation, strap tension, carriage stillness cautions. No separate printed variation.
- **Reformer Short Spine Prep · printed p.26**, original Drive file `13X5YnQQPjsL0ZMVsd2tNeqWM5xslyhAs`: verified photo, 4-phase INHALE Parallel / EXHALE Hip Flexion & Lateral Rotation / INHALE Frog / EXHALE Return. Pelvis remains on carriage; Imprinting printed variation.
- **Reformer Short Spine · printed p.27**, original Drive file `1hwXQTyjWq7vhlA3aa10MUVVp2MnqAgEd`: verified photo, six phases with Roll Up & Over and Roll Down, distinct from Prep. Imprinting printed variation. Cervical-loading caution marked COACHING, not printed SOURCE.
- Three apparatus entries stored in `movement-manual.html`, keyed by original filenames, with SOURCE vs COACHING separated. Source-photo count **43/186** (prior 40 + 3).
- Next: Reformer Long Spine, Mid-Back Series pages 1–4, Coordination; then other apparatus. Public Pages remains unverified; do not claim it is live without HTTP success.


## 2026-11-08 09:00 KST — apparatus original-photo verification (3)
- **Reformer Long Spine · printed p.28**: opened actual Drive JPG `1Ilt2psezx4_z89X6F5SROivMw6n0suM5`. Confirmed five-phase breathing (INHALE Hip Flexion → EXHALE Roll Over → INHALE Abduction & Lateral Rotation → EXHALE Roll Down → INHALE Adduction/Return), strap-supported supine starting position, TVA/pelvic floor and hip movements, printed omit-Abduction/Adduction variation. Neck-load cautions labeled COACHING; unclear handwriting excluded.
- **Reformer Mid-Back Series page 1 · printed p.29**: opened JPG `1q-hP2Ncuph_xuZ14TZjvN40vDU9QojX-`. Two exercises, Straight Press Down (INHALE Ready/EXHALE Press Down/INHALE Return) and Triceps Press Down (INHALE Elbow Flexion/EXHALE Press Down). Imprinting, Leg Folding, strap grip and shoulder support distinguished. No invented printed variations.
- **Reformer Mid-Back Series page 2 · printed p.30**: opened JPG `1ksXr4RmPOUVKHQrVq6xsKMMeh5S0V3Pg`. Side Press Down (INHALE Ready/EXHALE Press Down/INHALE Return) and Arm Circle (FORWARD INHALE Flexion/EXHALE Horizontal Abduction & Adduction; REVERSE INHALE Abduction/EXHALE Horizontal Adduction & Press Down). Original vs coaching separated; no invented muscle list.
- All three photo-level entries committed to `movement-manual.html`. **Verified source photos: 46/186** (previous 43 + 3). **Next** Reformer Mid-Back Series pages 3–4 and Coordination; retry failures and continue remaining apparatus. Public site still not verified.



## 2026-11-08 — active whole-site work
- Whole-site scope restored in REQUIREMENTS.md; the source-photo denominator is not site completion.
- Reformer Mid-Back p.31/p.32 and Coordination p.33 actual JPGs opened and read. p.32 explicitly describes Cadillac adaptation and must not remain misclassified as a Reformer-only protocol. Detailed SOURCE/COACHING entries added. Verified photo ledger: 49/186 (46 + 3), subject to final unique-photo recount.
- Public root HTTP 200 confirmed directly with curl. Earlier web retrieval failure did not establish a 404.
- exam-practice.html already contains random-2 and shuffle; earlier status report omitted this file. Audit and improve existing function rather than recreate it.
- Original user v12 read in full: max 3 repetitions TOTAL, not 2 per side. Existing A/B drafts require correction and rejected two-hand Circle Mermaid must be removed.

## 2026-11-08 10:00 KST — original Reformer Back Rowing Prep photographs
- **Back Rowing Series Prep — Round Back**, original Drive JPG `1OE8hmDRxTbpXHtP94ebpumX6J8yDXep2`, printed p.34: image opened directly. SOURCE verified: INHALE Ready → EXHALE Elbow Flexion & Roll Back → INHALE Keep → EXHALE Spinal Flexion Forward → INHALE Return; spinal flexion/neutral phases, core/scapular movement points, carriage and neck cautions. Instructor-added foot/hip/gaze guidance explicitly marked COACHING. Handwriting not independently certified.
- **Back Rowing Series Prep — Flat Back**, original Drive JPG `1_cqubVVZaCnYWLVylpk1-0nGdD7IKTjT`, printed p.35: image opened directly. SOURCE verified: INHALE Ready → EXHALE Elbow Flexion & Lean Back → INHALE Elbow Extension → EXHALE Biceps Curl (printed 3–5 reps) → INHALE Hip Flexion & Spine Elongation → EXHALE Return. Neutral spine, no rocking, scapular and carriage control verified. COACHING separated. Note printed repetitions do not override exam 3-total rule.
- Both detailed entries committed to `movement-manual.html` at `914e61538d9ade1ad746a5942b4a98d25f658343`. **Unique source-photo verified 51/186**, subject to final recount (previous 49 + 2). Remaining photos unverified. Next: Reformer Chest Expansion, Sitting/Kneeling Arms, Sitting Away Spring; continue through apparatus.
- Public deployment: prior ledger records root HTTP 200; no new HTTP check in this pass, so do not claim individual manual URL verified here.


## 2026-11-08 11:00 KST — Reformer Chest Expansion source photograph verified
- **Reformer Chest Expansion**, original Drive JPG `1oYdKa5ItFdB1r8YS0YXwiPaLuV4PCxhV`, printed p.38: actual image opened and visually inspected. Five-phase breathing INHALE Ready → EXHALE Shoulder Extension → INHALE Turn One's Head Sideways → EXHALE Look a Head → INHALE Return. Kneeling, hip-width knees, toes extended on carriage, neutral spine, upright trunk, forward gaze, strap grip. Printed Watch Points: pelvis rocking, carriage shake, elbows bending, shoulder hyperextension, upper trapezius overuse. Printed Variation: Chest Expansion With Pulse. No additional printed variations inferred; uncertain handwriting excluded. SOURCE and COACHING separated in manual.
- **Verified photo total 52/186** (prior 51 + 1). Next: Sitting Arms Forward Footbar Series p.1–2, Kneeling Arms p.1–2, Sitting Away Spring. Public manual URL still requires independent check.


## 2026-11-08 12:00 KST — Sitting Arms source-photo verification
- **Reformer Sitting Arms Forward Footbar Series p.36**, original JPG `1HUDOyrFyOiQkxPPWBuz8NvpOAxKCjIOI`: actual image opened; two distinct movements Straight Forward (1), Hugging Arm (2). Source breathing INHALE Ready → EXHALE Shoulder Flexion (1) / Horizontal Adduction (2) → INHALE Return. Printed alignment, muscles and warnings separated from COACHING; uncertain handwritten notes excluded. Status **verified**.
- **Reformer Sitting Arms Forward Footbar Series p.37**, original JPG `1RUJDFzInYCmXywuZS5cMSYW-r3rtZamd`: actual image opened; Salute (3), INHALE Ready → EXHALE Elbow Extension → INHALE Return. Source variation sequence INHALE Ready → EXHALE Shoulder Flexion → INHALE Horizontal Abduction → EXHALE Horizontal Adduction → INHALE Return. Status **verified**.
- Details committed to movement-manual.html, SOURCE and COACHING distinguished. **Verified photos 54/186** (52 + 2). Next: Reformer Kneeling Arms Forward Footbar p.1–2, Sitting Away Spring, then remaining apparatus. Unverified photographs not counted.
