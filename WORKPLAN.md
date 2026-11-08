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


## 2026-11-08 13:00 KST — Reformer Kneeling Arms original photographs verified
- **Kneeling Arms Forward Footbar Series p.39**, Drive JPG `1E51lPFtjhFE8O9C4pYYR7KRnWhog7wYV`: actual photographed page opened and visually read. Distinct movements (1) Straight Forward and (2) Biceps Curl; printed INHALE Ready → EXHALE Shoulder Flexion / Elbow Flexion → INHALE Return. Kneeling position, strap grip, TVA/pelvic floor, scapular stabilizers and printed carriage/pelvic warnings recorded. SOURCE separated from COACHING. **Verified**.
- **Kneeling Arms Forward Footbar Series p.40**, Drive JPG `1lIx4Yj8_wHRbnPfykRJ6JaVvT8hcXMgW`: actual photograph opened and visually read. (3) Teardrop outward/inward and (4) Salute, printed INHALE Ready → EXHALE outward/inward / Elbow Extension → INHALE Return. Source variations Sitting Position 1,3,4 and Sitting Offering sequence recorded separately. Handwriting excluded where uncertain. **Verified**.
- Detailed entries saved to `movement-manual.html`. **Unique source photos verified 56/186** (prior 54 + 2). Next: Reformer Sitting Away Spring, then remaining apparatus. Public manual URL requires independent check.


## 2026-11-08 14:00 KST — source identity mismatch detected
- **Drive file `1olHHdBzp4gp8crAzdwLPrsb15xbfPojA`**, currently named **"Reformer - Sitting Away Spring Series"**: actual JPEG opened and visually inspected. **The photographed page is Cadillac, printed p.41, headed "Sitting Arm Away Spring Series"**, NOT a Reformer page. The existing filename/category is incorrect. **Status: photo inspected / identity mismatch / NOT source-verified as Reformer.** Do not increment verified count (remains 56/186 pending reconciliation).
- Actual printed p.41 lists five movements: **Straight Forward, Biceps Curl, Teardrop Outward/Inward, Salute, Hugging Arm**. Starting Position: sit facing Push-thru Bar, hold handles, legs crossed or sit comfortably with legs forward. Printed notes: follow Reformer movements; keep spring tension constant; stay seated on the support; perform Salute at roughly shoulder height. Printed variations: **Kneeling Position, Unilateral, Reciprocal**. Handwritten annotations are not certified as printed instructions. Source title and equipment are unambiguous.
- **Required next action:** reconcile this file's category, heading and index in `movement-manual.html` without duplicating a Reformer exercise; inspect the next actual Reformer photograph separately. Because the file is mislabeled, do not invent missing Reformer source text. Review other category mismatches across 117 apparatus images.
- **Retry / QC:** revisit source after catalog correction and check the corrected image-to-entry mapping; this is a content classification issue, not a failed image download.

## 2026-11-08 15:00 KST — Cadillac Airplain Prep original photograph
- **001 Cadillac Airplane Prep**, Drive JPG `1ijXEh4h9rlTlOeH2r0Q8YHz4ujZpzof_`, photographed printed **p.68**: opened image directly. Printed heading spells **“Airplain Prep”**; catalog label “Airplane Prep” is a normalized title, not a source quotation. SOURCE verified: supine, hands holding vertical poles, Roll Down Bar behind knees, tabletop Leg Folding; INHALE Ready → EXHALE Hip Extension → INHALE Hip Flexion → EXHALE Roll Up → INHALE Return. Printed points include TVA/pelvic floor, rectus abdominis/obliques and scapular stabilizers. Watch points: shoulder/neck tension, avoid pulling on vertical poles, rib flare, mandatory instructor assistance to keep bar behind knees. Variations: hip-only movement and spine-only movement. COACHING gaze, foot suspension, symmetric hip tracking, spotting and regression explicitly separated; handwriting excluded from verified source.
- Detailed source-separated entry saved in `movement-manual.html`. **Verified total 57/186** (prior 56 + 1). Prior mislabeled Sitting Away Spring remains pending index reconciliation, not counted. Next: Cadillac Breathing and other unverified apparatus photos. Public page requires separate HTTP check.


## 2026-11-08 16:00 KST — Cadillac Breathing source photo verified
- **002 Cadillac Breathing**, original Drive JPG `1lLPOW1Xy3vX7plWXL2FaFqt_8PrYyJ0J`, photographed printed **p.69**, actually opened and visually inspected. SOURCE: supine facing Roll Down Bar; neutral spine/pelvis, externally rotated legs and feet secured in Trapeze straps, hold Roll Down Bar with raised arms. INHALE Ready → EXHALE 5 Counts Roll Up with Push Down & One Long Line → INHALE Return. Printed muscles, 4 watch points and variation (hold vertical poles instead of Roll Down Bar) transcribed/paraphrased in English-first Korean. COACHING gaze, foot suspension, hip symmetry, shoulder safety, compensations, regression separated. Handwritten note excluded from verified text. Detail stored as `cadillac-breathing-69` in `movement-manual.html`.
- **Unique verified source photos: 58/186** (previous 57 + 1; subject to final dedup audit). Next: Cadillac Roll Down p.70 and subsequent unverified apparatus photos. Mislabeled Sitting Away Spring remains a separate classification QC item. Public Pages access not newly checked in this run.


## 2026-11-08 16:05 KST — Cadillac Roll Down photo verification and UI mapping repair
- **Cadillac Roll Down**, Drive original JPG `1z6PqhMl4wBd5Y0uxGYc0wb5AcyEv5TyU`, printed **p.67**: actual image opened and inspected (rotated photo). SOURCE: supine, feet supported on Cadillac vertical poles, hands holding Roll Down Bar. Printed breathing: INHALE Ready → EXHALE Roll Down → INHALE Lying on the Bed → EXHALE Roll Up → INHALE Return to Starting Position. Movement Point: TVA/pelvic floor, rectus abdominis/obliques, scapular stabilizers. Printed watch points: neck/shoulder tension, segmental articulation, elbow/wrist control, avoid shoulder hike/rounding when pressing bar. Printed variations: bar above head; knees bent. COACHING gaze, hip symmetry, foot pressure, safety and regression explicitly separated. Handwriting not certified.
- **UI bug fixed:** Cadillac Breathing p.69 had detail object but the renderer did not select it; mapped both Cadillac Breathing and Roll Down entries to their source-grounded detail objects. **Verified total 59/186** (previous 58 + 1; pending final unique-photo recount). Next: remaining unverified Cadillac photos. Classification QC for mislabeled Sitting Away Spring still open. Public Pages individual route not checked in this pass.


## 2026-11-08 16:30 KST — batch source verification and efficient workflow
- Workflow: fetch GitHub plan/index once; inspect a batch of source images; identify printed titles and discrepancies; add separate SOURCE/COACHING records; update index routing; commit manual once and ledger once. Never infer missing source; keep uncertainty pending.
- **Double Leg Pump p.70**: actual original JPG opened and visually inspected; SOURCE breathing: INHALE Knee Flexion → EXHALE Knee Extension & Roll Up & One Long Line → INHALE Keep → EXHALE Double Leg Pump 3 Pulse → INHALE Knee Extension & Roll Up & One Long Line → EXHALE Roll Down & Neutral → INHALE Knee Flexion → EXHALE Knee Extension & Return. Printed variation: Prep: 다리의 움직임만 해보기 (Push-thru Bar 움직임 인지). Detailed SOURCE/COACHING saved under `cadillac-p70`.
- **Single Leg p.71**: actual original JPG opened and visually inspected; SOURCE breathing: INHALE Knee Flexion → EXHALE Knee Extension & Roll Up & One Long Line → INHALE One Leg Hip Flexion with Reach Ceiling → EXHALE Hip Extension & One Long Line → INHALE Other Leg Hip Flexion with Reach Ceiling → EXHALE Hip Extension & One Long Line → INHALE Roll Down → EXHALE Knee Flexion & Return. Printed variation: 팔 다리만 하기; 뻗는 다리 구부리기. Detailed SOURCE/COACHING saved under `cadillac-p71`.
- **Single Leg Pump p.72**: actual original JPG opened and visually inspected; SOURCE breathing: INHALE Knee Flexion → EXHALE Roll Up & One Long Line → INHALE One Leg Hip Flexion with Reach Ceiling → EXHALE Single Leg Pump 3 Pulse → INHALE Knee Extension → EXHALE Hip Extension & One Long Line → INHALE Roll Down → EXHALE Knee Flexion & Return. Printed variation: Pulse 제외하기; 뻗는 다리 구부리기. Detailed SOURCE/COACHING saved under `cadillac-p72`.
- **Critical mismatch**: Drive filename for `18fM97YwcEfwIMWS4wjk9voF4pz_9rKij` says *Leg Circles* but photographed p.72 is **3. Single Leg Pump**. Corrected displayed title and recorded mismatch; Drive filename remains unchanged.
- **Unique verified source photographs 62/186** (previous 59 + 3; pending final duplicate audit). Next: Cadillac Spread Eagle, Pull Up and remaining originals. No new public URL verification this batch.


## 2026-11-08 17:00 KST — Cadillac original photos batch
- **006 Cadillac Spread Eagle** original Drive `1Ax0525i9QbLAcmNrS6ytACETCH6zvSHl`, printed **p.73**, opened and visually inspected. SOURCE breathing INHALE Ready → EXHALE Roll Up & One Long Line → INHALE Elbow Flexion & Cervical and Thoracic Extension → EXHALE Elbow Extension & Spinal Articulation → INHALE Return. Printed variation omit spinal extension. Full SOURCE/COACHING entry saved `cadillac-p73`; verified.
- **007 Cadillac Pull Up** original Drive `1Qdi9QISyZmZGDoAmDEUIDV5SRLgaU06t`, printed **p.74**, opened and visually inspected. SOURCE breathing INHALE Ready → EXHALE Roll Up & One Long Line → INHALE Keep → EXHALE Elbow Flexion → INHALE Elbow Extension → EXHALE Return. Printed muscle points and warnings; no separate variation. Full SOURCE/COACHING entry saved `cadillac-p74`; verified.
- **008 Cadillac Ballet Stretch** original Drive `1jcSJFhZMa-ZxdfEML8JD_KSzcJr0frtf`, printed **p.75**, opened and inspected. Page contains eleven numbered photographs but no visible full textual breathing/muscle/variation instructions. **Status: visually inspected, SOURCE details incomplete; NOT verified**. Next action: record visual 1–11 sequence separately without inventing breathing; check adjacent pages for printed continuation. Do not count as verified.
- **Verified total 64/186** (previous 62 + 2). Next: Cadillac Guillotine, Lat Press, Leg Press, Monkey and other originals; retry p.75 for image sequence transcription. No new public Pages HTTP test in this run.


## 2026-11-08 18:00 KST — Cadillac original batch (4)
- **Cadillac Guillotine printed p.63**: opened original JPG and visually checked printed title, breathing (INHALE Lengthen — Knee, Ankle → EXHALE Roll Up → INHALE Flexion — Hip, Knee, Ankle → EXHALE Extension — Hip, Knee, Ankle → INHALE Keep → EXHALE Roll Down → INHALE Return to Starting Position), muscles (Transverse Abdominis, Pelvic Floor; Hip & Knee Flexion/Extension; Ankle Plantar Flexion & Dorsi Flexion; Scapula Stabilizer), photographs, bar/foot positions and variation status. SOURCE vs COACHING separated in `movement-manual.html` using `cadillac-page-63`.
- **Cadillac Lat Press printed p.66**: opened original JPG and visually checked printed title, breathing (INHALE Ready → EXHALE Lat Press → INHALE Return to Starting Position), muscles (Transverse Abdominis, Pelvic Floor; Neutral Spine; Scapula Stabilizer; Scapula Depression), photographs, bar/foot positions and variation status. SOURCE vs COACHING separated in `movement-manual.html` using `cadillac-page-66`.
- **Cadillac Leg Press printed p.62**: opened original JPG and visually checked printed title, breathing (INHALE Lengthen — Hip, Knee, Ankle → EXHALE Dorsi Flexion → INHALE Plantar Flexion → EXHALE Return to Starting Position), muscles (Transverse Abdominis, Pelvic Floor; Hip & Knee Flexion/Extension; Ankle Plantar Flexion & Dorsi Flexion; Scapula Stabilizer), photographs, bar/foot positions and variation status. SOURCE vs COACHING separated in `movement-manual.html` using `cadillac-page-62`.
- **Cadillac Monkey printed p.64**: opened original JPG and visually checked printed title, breathing (INHALE Lengthen — Elbow, Knee, Ankle → EXHALE Dorsi Flexion → INHALE Plantar Flexion → EXHALE Return to Starting Position), muscles (Transverse Abdominis, Pelvic Floor; Hip & Knee Flexion/Extension; Ankle Plantar Flexion & Dorsi Flexion; Scapula Stabilizer), photographs, bar/foot positions and variation status. SOURCE vs COACHING separated in `movement-manual.html` using `cadillac-page-64`.
- Verified unique source-photo total **68/186** (prior 64 + 4; final dedup pending). **Ballet Stretch p.75** remains visually inspected but incomplete and NOT verified. Next: Push Thru Cat Spine Stretch, Push-thru on Back Roll Up, Push-thru on Stomach Back Extension, Push-thru with Feet pages 1–3. Recheck handwriting and source image if ambiguous. Public manual URL not checked this pass.


## 2026-11-08 18:45 KST — site structure/content enhancement from user's other chat
- User's other-chat requirements retrieved: avoid sparse list-only navigation; organize by topic with substantive educational pathways and explicit links from anatomy to function, observation, assessment, movement, cueing and reassessment. Separate 25-minute teaching exam and non-teaching random two exercises from general textbook.
- Updated `index.html`: added five-stage practical Learning Path with specific shoulder, pelvis/hip, movement assessment, exercise application, and class design study links; inserted separate **Instructor Practical Exam** sidebar section linking random-2/shuffled practice and sequence versions. Kept main educational content independent of exam.
- This is an initial concrete site-content improvement, not completion of all requested deep curriculum; remaining 118 source photographs are still pending as of latest verified ledger (68/186). Sparse-content complaint remains an open whole-site audit item. Next photo target: Cadillac Push Thru Cat Spine Stretch, Push-thru on Back, Push-thru on Stomach, then Feet pages 1–3. Ballet Stretch p.75 remains image-inspected but printed text incomplete; provide instructor-derived description as COACHING rather than invent SOURCE.


## 2026-11-08 19:04 KST — Original-photo verification (3)
- **cadillac-page-65**: original image visually opened and checked, including printed title, photograph order, Starting Position, exact breathing labels, Movement Point, Watch Point, Variation; transcription and distinct COACHING committed to movement-manual.html. Drive file: `1eE2y14AG3JLAhzT_8ZD0og7fbz79V-N9`. Verified.
- **cadillac-page-58**: original image visually opened and checked, including printed title, photograph order, Starting Position, exact breathing labels, Movement Point, Watch Point, Variation; transcription and distinct COACHING committed to movement-manual.html. Drive file: `1yWRKd2LmQXqF2KM158u5u-tF9-kC_bYV`. Verified.
- **cadillac-page-61**: original image visually opened and checked, including printed title, photograph order, Starting Position, exact breathing labels, Movement Point, Watch Point, Variation; transcription and distinct COACHING committed to movement-manual.html. Drive file: `1u_OoNz29GH2RBU-parXTlUKXjpWFWpuz`. Verified.
- **Ledger total 71/186** (prior 68 + 3; unique-ID audit still pending). Next: Cadillac Push-thru with Feet pages 1–3, Sit Up Combo, Spread Eagle Prep, Teaser; Ballet Stretch p75 still requires source/visual distinction. Do not infer SOURCE for unprinted material. Public deployment not yet checked this pass.


## 2026-11-08 20:02 KST — Original-photo verification (3)
- **cadillac-page-70**, Drive `19-lFyng_66hyy4XCUqPhsBdEhL_GD-bj`: visually opened printed p.70 Double Leg Pump, photographs 1–8, Why, Starting Position, 8-step printed breathing/movement, Movement Point, Watch Point, Prep variation. Added SOURCE/COACHING to manual. Verified.
- **cadillac-page-71**, Drive `1glorJAvjF5zRXCRRyEBQdHr1Y8ATIaKK`: visually opened printed p.71 Single Leg, photographs 1–8, Why, Starting Position, 8-step printed breathing/movement, printed variations; separate coaching for gaze, hip stability and bar contact. Verified.
- **cadillac-page-72**, Drive `13l3LOV_HuDPCvisBWpufLdInW1z0-Mm9`: visually opened printed p.72 Single Leg Pump, photographs 1–8, Why, Starting Position, 8-step printed breathing/movement, printed variations; separate coaching for support and safety. Verified.
- **Verified ledger 74/186** (previous 71 + 3; unique-ID audit still pending). Next: Cadillac Sit Up Combo, Spread Eagle Prep, Teaser; Ballet Stretch p.75 still visually inspected but incomplete source text. Public deployment not yet tested. 


## 2026-11-08 20:55 KST — Cadillac original-photo batch (3)
- **cadillac-page-57** Spread Eagle Prep, Drive `1Lhk49S9O5Cs7GvFkPd_y0Sp42KWqoknF`, printed p.57: actual original JPG visually opened; five photographs, Why, Starting Position, five breathing steps, Movement Point, Watch Point, printed variation reviewed. SOURCE and COACHING separately recorded. **Verified**.
- **cadillac-page-59** Sit Up Combo, Drive `1-I__2oIKOtFHHfa6Dt9TuKhvdS7Vrv5s`, printed p.59: actual original JPG visually opened; five photographs, six breathing steps, bar grip, feet against wall, Watch Point and empty Variation heading reviewed. SOURCE and COACHING separately recorded. **Verified**.
- **cadillac-page-60** Teaser, Drive `1vEcD_TFUQmDc1hlT_YBnJDEB6K3e16Sr`, printed p.60: actual original JPG visually opened; five photographs, four breathing steps, bar grip, legs on/off mat, Watch Point and knee-flexion variation reviewed. SOURCE and COACHING separately recorded. **Verified**.
- **Ledger: 77/186** (previous 74 + 3, unique-ID audit pending). Next: Cadillac Roll Down p.?, Ballet Stretch p.75 source-vs-coaching retry, remaining apparatus and mat photos. Public Pages HTTP check remains pending. 


## 2026-11-08 21:55 KST — Cadillac original photo inspection
- **cadillac-page-67 Roll Down**, Drive `1z6PqhMl4wBd5Y0uxGYc0wb5AcyEv5TyU`, printed p.67: opened original image and inspected 5 photographs, Why, Starting Position, 5-step breathing sequence, Movement Point, Watch Point and two printed variations. Transcribed to `movement-manual.html` as SOURCE, with separate COACHING for gaze, foot contact, spinal articulation and modifications. **Verified**.
- **cadillac-page-75-visual Ballet Stretch**, Drive `1jcSJFhZMa-ZxdfEML8JD_KSzcJr0frtf`, printed p.75: reopened actual original image. Eleven photographs depict front, side, back-leg supported stretches and lateral flexion; printed instructions for breath, muscle, cautions and variation are absent. Added image-only SOURCE and separate instructor COACHING with explicit caveats; **NOT VERIFIED** for missing source text. Retry if adjacent source continuation found; do not invent printed breathing.
- **Ledger 78/186** (previous 77 + Roll Down 1; Ballet Stretch excluded). Next: unverified Chair, Barrel, Reformer and Mat originals; reconcile duplicate-ID ledger and test public Pages when source audit complete.


## 2026-11-08 22:57 KST — Chair original inspection
- **chair-page-86 Chair Roll Over**, original Drive `1vg5Az7JQsJp9hTI8cyFIWf3vgWK4X5RX`, printed p.86: opened full original JPEG and visually inspected four main photos plus Jack Knife variation, Why, Starting Position, printed four-breath sequence, Movement Point, Watch Point and Variation. SOURCE and COACHING separated in `movement-manual.html`. Printed red handwriting treated as annotations rather than source instructions. **Verified**.
- Ledger **79/186** (previous 78 + 1; unique-ID reconciliation still pending). Continue other unverified Chair/Reformer/Barrel originals. Public Pages check outstanding.


## 2026-11-08 23:35 KST — Chair original source review (2)
- **chair-page-87**, Chair Tendon Stretch, original Drive `1RPDtrSV9fjzyUAtR1En54bVsAnnIFrCU`, printed p.87. Actual JPG opened. SOURCE verified: 2 photos, Why, starting seated on chair edge with raised heels/feet on pedal, C-curve, INHALE Ready → EXHALE Pull Up → INHALE Return, movement muscles (TVA/pelvic floor, rectus abdominis/obliques, scapula stabilizers), four watch points, printed variation Split Pedal. COACHING separate for gaze/foot contact/safety and regression. **Verified.**
- **chair-page-88**, Chair Cat Spine Standing Front 1. Articulation, original Drive `19nfXq9NftWlYei4DYn5K2ushz5VeI32x`, printed p.88. Actual JPG opened. SOURCE verified: 6-photo sequence, neutral standing facing chair, hip-width feet, 5-step breath (Ready → Roll Down & Pedal Press → Pedal Up → Roll Up → Return), movement muscles, watch points on neck/shoulder, elbows, wrist, arm vs spinal effort, whole-foot loading and knee hyperextension. Handwritten red markings treated as separate annotations, not printed SOURCE. COACHING separate for gaze, foot support and scaled range. **Verified.**
- **Ledger 81/186** (previous 79 + 2; deduplicate original IDs before final claim). Next: Chair Cat Spine Standing Front Arm Press and Variation, then other Chair originals. Public Pages full QA pending.


## 2026-11-08 23:57 KST — Chair p.89–92 original JPGs visually reviewed
- **chair-page-89** 021_Chair - Cat Spine Standing Front - Arm Press (캣 스파인 스탠딩 프런트 암 프레스).jpg; Drive https://drive.google.com/file/d/1NpuiqX9cunYaVt512zSZhYMTIsfzOqj8/view; printed page 89. Original image opened; checked all photographed steps, Why, Starting Position, printed breathing, and where present Movement Point, Watch Point and Variation. SOURCE and COACHING separately transcribed to movement-manual.html. Red handwritten notes are not printed SOURCE. **Verified**.
- **chair-page-90** 022_Chair - Cat Spine Standing Front - Arm Press Variation (캣 스파인 스탠딩 프런트 암 프레스 변형).jpg; Drive https://drive.google.com/file/d/1VNft5pcCuYfBzUIpy0WU20R4rEoKQtPw/view; printed page 90. Original image opened; checked all photographed steps, Why, Starting Position, printed breathing, and where present Movement Point, Watch Point and Variation. SOURCE and COACHING separately transcribed to movement-manual.html. Red handwritten notes are not printed SOURCE. **Verified**.
- **chair-page-91** 023_Chair - Single Leg Standing (싱글 레그 스탠딩).jpg; Drive https://drive.google.com/file/d/1tsSrgjBpuS5t2jhwzzTt0Xuu9On6huxB/view; printed page 91. Original image opened; checked all photographed steps, Why, Starting Position, printed breathing, and where present Movement Point, Watch Point and Variation. SOURCE and COACHING separately transcribed to movement-manual.html. Red handwritten notes are not printed SOURCE. **Verified**.
- **chair-page-92** 024_Chair - Step Up (스텝 업).jpg; Drive https://drive.google.com/file/d/1XPhJxHYzTxRnurDXeL7zkC5Q2CVR4R8C/view; printed page 92. Original image opened; checked all photographed steps, Why, Starting Position, printed breathing, and where present Movement Point, Watch Point and Variation. SOURCE and COACHING separately transcribed to movement-manual.html. Red handwritten notes are not printed SOURCE. **Verified**.
- Ledger **85/186** (prior 81 + 4; final unique-ID audit still needed). Next: Chair Spine Press on Chair Prep p.93, subsequent Chair originals. Public Pages access check remains pending.


## 2026-11-09 01:01 KST — Chair p.93–95 original-image verification
- **chair-page-93**, Spine Press on Chair Prep, Drive `1Lo2wC02JN3o85XJdiyEYXJs0kpItLrRe`: opened original JPG, inspected six photographs and printed Why, Starting Position, 6-step breathing (including 3–5 pedal repetitions), Movement Point and Watch Point. Foot on Box, hands toward pedals, spinal articulation, gaze as COACHING. **Verified**.
- **chair-page-94**, Rotation Prone, Drive `15YSsain0I0forfAdQ9H8EAZL1SSf8RkH`: opened original JPG, inspected five photographs, ASIS placement 2–5 cm, prone hip extension, four-step breathing, rotation muscles, caution against replacing rotation with extension, and printed variation excluding arm extension. **Verified**.
- **chair-page-95**, Slow Swan, Drive `16kpNp2E_8YIOH9Aufp1uwq8bnjjIOA5Q`: opened original JPG, inspected three photographs, ASIS placement, hand/pedal contact, 3-step breathing, spinal/hip extensor and scapular muscles, wrist/elbow watch points, Split Pedal variation. **Verified**.
- All entries split printed **SOURCE** from inferred **COACHING**; red handwritten annotations excluded from printed source. Ledger **88/186** (prior 85 + 3, final unique-ID reconciliation pending). Next: Chair Footwork Page 1 and Page 2, then remaining unverified Barrel/Reformer/Mat originals. Public Pages access check pending.


## 2026-11-09 01:57 KST — Chair Footwork original-image inspection
- **chair-footwork-page-77**, original Drive `1BNlCPVbAmv0OKS0ul6IX95q_Jgh2ESdf`, printed p.77: opened original JPG, visually checked 2 photographs, Why, starting neutral seated position, heels on pedal, 3-step breathing, Movement Point, Watch Point. SOURCE separated from COACHING on gaze, foot contact, joint tracking and regression. **Verified.**
- **chair-footwork-page-78**, original Drive `1RL0UZOlWEFGW54-fSHOnj0UTVcz6aXpk`, printed p.78: opened original JPG, visually checked Frog Position, Heels Up, two photo examples, printed starting positions, 3-step breathing, variations (feet together, split pedal, foot placement). No independent printed Movement Point/Watch Point on this page; any precautions recorded as COACHING, not SOURCE. **Verified.**
- Ledger **90/186** (previous 88 + 2, unique original-ID audit pending). Next: unverified Reformer, Barrel and Mat pages, prioritize Curl Up vs Roll Up direct image comparison. Public Pages accessibility test pending.


## 2026-11-09 03:01 KST — Chair original p.79
- **chair-page-79 Sitting Ankle Exercise**, Drive `1183hYSGcdMAVtWONJypXYQqZ2fqEN3oc`: actual original JPG opened, visually inspected three photographs, printed Why, Starting Position, breathing sequence, Movement Point, Watch Point and three variations. SOURCE includes neutral spine/pelvis, pelvis aligned with chair edge, lifted heels and light pedal pressure, handles held, INHALE pedal up/dorsiflexion → EXHALE push pedal → INHALE return, transverse abdominis/pelvic floor and ankle dorsiflexion/plantarflexion, neck/shoulder and thigh-level cautions, split pedal/arm position/back prop variations. COACHING independently identifies gaze, forefoot contact, hip/knee stabilization and regression. Handwritten red notes excluded from printed SOURCE. **Verified.**
- Reopened Chair Footwork p.77–78 originals (Drive `1EmQJNRpA3Z8TrosjNI7NqQQYXLqg90fS`, `1ByKfjPyG_UOtsmjLWY2Mji-3sHtFriAf`) to inspect named images; these are **different Drive IDs** from the prior p.77–78 verification IDs (`1BNlCPVbAmv0OKS0ul6IX95q_Jgh2ESdf`, `1RL0UZOlWEFGW54-fSHOnj0UTVcz6aXpk`). **Do not increment verified ledger for duplicates without reconciling unique original photos.**
- Provisional ledger **91/186** (prior 90 + 1; unique-ID reconciliation still required). Next: Chair Standing Ankle Exercise p.80, Running p.81, and unverified Reformer/Barrel/Mat originals. Public Pages access and Curl Up/Roll Up direct comparison outstanding.


## 2026-11-09 04:00 KST — Chair p.80–82 actual original-image review
- **chair-page-80 Standing Ankle Exercise**, Drive `1Jh2TvUGd6gT__AfZM4Hbz-knswWiRWPA`: original JPG opened; 3 photos, Why, starting standing heels raised with forefeet on pedal, breath Ready/EXHALE Dorsi Flexion/INHALE Return, TVA/pelvic floor/ankle/body alignment, 2 watch points checked. No printed Variation. SOURCE and COACHING separated. **Verified.**
- **chair-page-81 Running**, Drive `1uEFaJQAU-AIB_qD522jIShQ_dfuEhL8d`: original JPG opened; 5 photos, alternating feet and bent knee, 5-step printed breath Ready/Running/Heel Up/Running/Return, same listed movement points and 2 alignment watch points. Handwritten red markings not treated as printed instructions. SOURCE and COACHING separated. **Verified.**
- **chair-page-82 Lying Leg Press**, Drive `1SdB2gad99b1ohSeNybm2IyGgGEP1wus8`: original JPG opened; 3 photos, supine heel-on-pedal, pelvis neutral, hip/knee movement, 3-step breath Ready/Push The Pedal/Return, hip extensor/knee flexor and TVA/pelvic floor, 3 watch points, printed split-pedal variation checked. Handwritten red notes excluded from printed SOURCE. SOURCE and COACHING separated. **Verified.**
- Provisional ledger **94/186** (prior 91 + 3; reconcile unique original IDs before final total). Next: Chair Lying Leg Press with Articulation p.83, Lying Frog Leg Press p.84, AB Press Sitting p.85; Curl Up/Roll Up original comparison and public Pages QA still pending.


## 2026-11-09 05:00 KST — Chair original images p.83–85
- **chair-page-83** Lying Leg Press with Articulation, printed p.83, original Drive `1h3QvkI5sc8WVR6APXugmpCaQrO5vzCw_`: original JPG visually opened; photo sequence, Why, Starting Position, printed breathing, movement muscles, Watch Point and Variation reviewed. SOURCE separated from COACHING; red handwritten annotations not attributed to printed source. **Verified.**
- **chair-page-84** Lying Frog Leg Press, printed p.84, original Drive `1aY8guYPZQrdQ37Nwdjg5cpUZKfLo7ayh`: original JPG visually opened; photo sequence, Why, Starting Position, printed breathing, movement muscles, Watch Point and Variation reviewed. SOURCE separated from COACHING; red handwritten annotations not attributed to printed source. **Verified.**
- **chair-page-85** AB Press Sitting, printed p.85, original Drive `1qaL9O0KE6XB4gMjagmlX_IgmgDwCjGW5`: original JPG visually opened; photo sequence, Why, Starting Position, printed breathing, movement muscles, Watch Point and Variation reviewed. SOURCE separated from COACHING; red handwritten annotations not attributed to printed source. **Verified.**
- Provisional ledger **97/186** (prior 94 + 3; unique-ID audit pending). Next: other unverified Reformer, Barrel, Mat/Small Props originals, direct Curl Up vs Roll Up comparison, and public Pages accessibility check. Retry any unreadable originals rather than marking verified.


## 2026-11-09 06:00 KST — Reformer originals p.5–7
- **reformer-page-5** Footwork 1. Heels on Footbar, Drive `15JJPVZEwdQuubxZ2wYKmpnTjIAcjjRKP`: opened original JPG and verified 3 photographs, Why, starting position, 3-stage printed breath, Movement Point and Watch Point. SOURCE vs COACHING separated. **Verified.**
- **reformer-page-6** Footwork 2. Wrap Toes, 3. Frog Position, 4. Heels Up, Drive `1cfbTuk9AkcbZrRw5GQCilylzaDrdulZ-`: opened original JPG and verified 3 foot close-ups, three separate printed starting positions and Variation (reverse breath; hip-width parallel/lateral/medial rotation). **Filename mismatch:** the Drive filename says Wide Heels Frog Position Heels Up but actual printed first heading is Wrap Toes on Footbar. No independent breath, movement-muscle or Watch Point section is printed on this page; coaching suggestions labeled separately. **Verified for actual printed content, not for inferred breathing.**
- **reformer-page-7** Ankle Exercise, Drive `1mUUY5-K90tJ0zuo34T8sSO-VEZ0RUx5I`: opened original JPG and verified 5 photos, starting forefoot contact, INHALE Push Out → EXHALE Dorsiflexion → INHALE Plantarflexion (1–6 repeats) → EXHALE Return, Movement Point, Watch Point, and 2 variations. SOURCE vs COACHING separated. **Verified.**
- Provisional ledger **100/186** (prior 97 + 3; unique original ID reconciliation pending). Next: Reformer Running, Hip Rolls, Single Leg Footwork originals; Curl Up/Roll Up comparison and public Pages check remain pending.
