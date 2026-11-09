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


## 2026-11-09 06:57 KST — Reformer source photos p.8–9
- **reformer-page-8** Running, Drive `1qu8ZTFMQEDVEB3CD6T4xiOi52Yyz3Iba`, printed p.8: original JPG opened and visually inspected all seven numbered frames, Why, Starting Position, 7 breathing steps, Movement Point, Watch Point and two variations. Footbar forefoot contact, neutral pelvis, gaze, alternating ankle motion and pelvis rotation caution recorded. Red handwriting excluded from printed SOURCE. **Verified.**
- **reformer-page-9** Hip Rolls, Drive `1J7WgOmJtlbqmfpXjvDgmv9TGLCHfWGfy`, printed p.9: original JPG opened and inspected five frames, printed rationale, starting position, 6 breathing stages with 2–5 repetitions, muscles, four watch points and two variations. Separate SOURCE and COACHING for spinal articulation, heel/sole contact, gaze, hip extension and safety. Red handwriting excluded from printed SOURCE. **Verified.**
- **reformer-page-10** Single Leg Footwork Part 1, Drive `1JbYgriUKReFydLF6EtzSlmXv061gLXw`: raw original fetch returned HTTP 404 / NOT_FOUND. **NOT VERIFIED; retry** Drive fetch and confirm filename/ID from Apparatus folder listing before marking complete. Proceed to Part 2 and other originals while retry pending.
- Provisional ledger **102/186** (previous 100 + 2; unique original ID reconciliation pending). Next: retry p.10; Reformer Single Leg Footwork Part 2 p.11; Curl Up vs Roll Up direct photo comparison; public Pages QA pending.


## 2026-11-09 08:00 KST — Reformer originals p.10–11
- **reformer-page-10** Single Leg Footwork 1. Bicycle, original Drive `1JbYgriUKReFydLF6EtzSlmXv061gLXwI`: **retry successful** after prior 404; actual JPEG opened. Inspected 3 photos, printed Why, Starting Position, 3 breathing steps, Movement Point, 3 Watch Points, 2 variations. SOURCE and COACHING separated; red handwriting excluded. **Verified.**
- **reformer-page-11** Single Leg Footwork 2. Reach Leg, original Drive `1WQu7dZRATKEa6VJFPZ7LCiLNi1bZb-KG`: actual JPEG opened. Inspected 5 photos, printed Why, Starting Position, 3 breathing steps, Movement Point, 4 Watch Points and heel-on-footbar variation. SOURCE and COACHING separated; intermediate photo transitions not assigned invented breathing. **Verified.**
- Provisional ledger **104/186** (previous 102 + 2; unique original ID reconciliation pending). Next: Reformer other unverified originals, Curl Up vs Roll Up source comparison, public Pages QA. 


## 2026-11-09 09:00 KST — Reformer original images p.21 and p.47
- **reformer-page-21** Adductor Stretch, original Drive `1Es9pfJHlijgv3vR1nIkpt7ylHBng-ldk`: opened actual image, 5 photos, printed Why, Starting Position, four breathing steps, Movement Point, two Watch Points, two Variations. Source vs coaching separated; gaze toward ceiling, feet in straps rather than footbar, hip abduction/adduction and pelvic stability checked. **Verified.**
- **reformer-page-47** Back Rowing Series 2. Flat Back, original Drive `1VzForqg-cUZjur_3UKvbe-0WeeqSngn7`: opened actual image, seven numbered photographs, Why, Starting Position, six printed breathing steps, Movement Point. Notable source peculiarity: last two breath stages both printed INHALE, preserved verbatim rather than silently correcting. No independent Watch Point/Variation printed on this image; coaching explicitly separated. **Verified for visible printed content.**
- Provisional ledger **106/186** (previous 104 + 2; unique-ID audit pending). Next: remaining unverified Reformer originals; Curl Up/Roll Up original photo cross-check; public Pages QA.


## 2026-11-09 10:00 KST — Barrel original-image verification
- **barrel-page-97 Spine Twist**, original Drive `1wuO2zZ7mj9e5g6mOqMC8yCcQj4_s_ug3`: actual original JPG opened. Checked 5 photos, Why, Starting Position, 5-stage breathing, Movement Point, four Watch Points and Reformer (with Box) variation. SOURCE vs COACHING separated, handwritten red notes excluded from printed SOURCE. **Verified.**
- **barrel-page-98 Round Back**, original Drive `1Q0kDyGRBxxz3O5RJLryMKOc8eXRkTFa3`: actual original JPG opened. Checked 5 photos, Why, Starting Position, 5-stage breathing, Movement Point, two Watch Points and Reformer (with Box) variation. SOURCE vs COACHING separated. **Verified.**
- Provisional ledger **108/186** (previous 106 + 2; original-ID deduplication still pending). Next: Barrel Flat Back p.99, Round Back With Twist p.100 and continuation, then other unverified originals. Curl Up vs Roll Up and public Pages QA outstanding.


## 2026-11-09 10:55 KST — Barrel p.99–101 original JPG review
- **barrel-page-99 Flat Back**, Drive `1Ww94wKVfdIC-ngCsslyujLfJ38sL069Y`: actual original opened; 3 sequence photos, Why, Starting Position, 3 breath stages, Movement Point, 4 Watch Points and 2 variations. SOURCE and COACHING separated. **Verified**.
- **barrel-page-100 Round Back With Twist**, Drive `1D-kM-FObiAiwmxsH1XqELWTldCGBHd8q`: actual original opened; Why, Starting Position, 9 breathing stages, Movement Point, Watch Point and Variation reviewed. Ambiguous printed phrase 'Ceiling to the Arm' preserved and flagged, not silently corrected. **Verified for legible content; ambiguous phrase unresolved**.
- **barrel-page-101 Round Back With Twist photo sequence**, Drive `1gNytUvYr2ct-tOZsOCDBz8URufpYzJbA`: actual original opened, all nine numbered photographs visually checked against p.100 breathing stages. No standalone printed breath or cautions; linked p.100 explicitly. **Verified for photo sequence**.
- Provisional ledger **111/186** (previous 108 + 3; unique-ID reconciliation pending). Next: remaining unverified Barrel/Reformer/Mat originals; direct Curl Up vs Roll Up comparison; public Pages final QA. Do not count ambiguous source phrases as resolved.


## 2026-11-09 11:58 KST — Barrel Lean original images p.102–103
- **barrel-page-102 Lean instructions**, original Drive `16Pz_8glqXmaO-YHBWbvV5NHh64JCCx2_`: opened actual JPG; printed Why, Starting Position, 9-step breathing, Movement Point, five Watch Points and Reformer (with Box) Variation checked. SOURCE vs COACHING separately stored in movement-manual.html. **Verified**.
- **barrel-page-103 Lean sequence**, original Drive `1ZYw_6E6Ecdhk9SCM32tJ4ZAhfIqmdxZt`: opened actual JPG; nine numbered photographs checked against p.102 sequence. Red handwriting excluded from printed SOURCE. No independent breathing/Watch Point printed on p.103. **Verified for photo sequence**.
- Provisional ledger **113/186** (previous 111 + 2; original-ID reconciliation pending). Next: Barrel Tree Prep p.104–105, other unverified originals; Curl Up/Roll Up direct comparison and public Pages QA outstanding.

## 2026-11-09 13:01 KST — Barrel Tree Prep p.104–105 original JPG inspection
- **035_Barrel - Tree Prep - Instructions**, printed p.104, Drive `1Joqg1fulSvbOV5wFWRNQf7YQsM54FhQx`: original JPG opened and visually read. Verified Why (balance/control and hamstring stretch), Starting Position (one foot on Ladder, opposite leg held), printed breathing (knee extension/flexion ×3, hand walking/roll down, keep, roll up), Movement Point, Watch Point and variations (Reformer with Box; omit roll down/up). Printed watch-point word **'추골'** is unclear; transcribed with uncertainty, not normalized into a verified interpretation. **Verified for legible source only.**
- **036_Barrel - Tree Prep - Sequence**, printed p.105, Drive `1Hap-fSx3OOLLlhJbdPtoCsReHLHZYnAN`: opened original JPG, visually checked 8 numbered positions, Ladder foot contact, knee flexion/extension, hand walking and trunk roll. This is a photo continuation of p.104, not a new standalone exercise. No independent printed breath or variation on p.105. **Verified photo sequence.**
- Detailed SOURCE and COACHING separated in `movement-manual.html`; commit `504d41856f60f82f3231a80bc4832ac7fb19a678`.
- Provisional verified photo count **115/186** (previous 113 + 2; original Drive ID deduplication outstanding). Next: Barrel Side Bend p.106, Swan p.107, Spinal Extension p.108, then other unverified originals. Retry failures without marking them verified. Public Pages HTTP QA still outstanding.


## 2026-11-09 14:05 KST — Barrel Side Bend p.106 original photograph
- **037_Barrel - Side Bend**, printed p.106, original Drive `1EyyW6J7n4f_dmdKrQvx2bIq1c3TVwAYG`: actual original JPEG opened and visually read, including 3 main sequence photos and 1 variation photo. Verified Why, Starting Position, INHALE Ready → EXHALE One Long Line → INHALE Return, Movement Point, five Watch Points and three Variations. Ladder lower-foot contact, crossed upper leg, lateral pelvis-on-Barrel support, overhead Pole and anti-rotation distinguished. Handwritten red annotations excluded from printed SOURCE; muscle-specific teaching notes labeled COACHING. **Verified for legible printed source and photographed positions.**
- Saved detailed entry to `movement-manual.html`; commit `2b50fd624a2724350e60de80732f12037238a312`.
- Provisional photo verification count **116/186** (previous 115 + 1; unique Drive-ID audit outstanding). Next: Barrel Swan p.107 (`1HnuYCjS-L_Nq7_3DPlS3HfVknTnZhJB4`), Spinal Extension p.108 (`18QrgAfX1z3F-nsFQEQRMO71XLqjZb3EB`), then unverified photos. Curl Up vs Roll Up direct source comparison and public Pages QA remain outstanding.


## 2026-11-09 15:00 KST — Barrel original images p.107–108
- **038_Barrel - Swan**, printed p.107, Drive `1HnuYCjS-L_Nq7_3DPlS3HfVknTnZhJB4`: actual JPG opened; 5 photographed positions and printed Why, Starting Position, INHALE Ready → EXHALE One Long Line & Spinal Extension → INHALE Return, Movement Point, four Watch Points and two Variations visually reviewed. SOURCE vs COACHING separated in movement-manual.html. **Verified**.
- **039_Barrel - Spinal Extension**, printed p.108, Drive `18QrgAfX1z3F-nsFQEQRMO71XLqjZb3EB`: actual JPG opened; 3 photographed positions and printed Why, Starting Position, INHALE Ready (One Long Line) → EXHALE Spinal Extension → INHALE Return, Movement Point, five Watch Points and two Variations reviewed. SOURCE vs COACHING separated. **Verified**.
- Both pages' gaze, hip/foot contact and named muscle explanations clearly distinguish visible/printed SOURCE from inferred COACHING. No extra breath stages inferred from images. HTML commit `a6cfaee4f52ff81d7a8321a972841cde2b6294a3`.
- Provisional verified count **118/186** (previous 116 + 2; unique Drive ID reconciliation still pending). Next: other unverified Barrel/Reformer/Mat originals; prioritize Curl Up vs Roll Up direct comparison, duplicate IDs and public Pages HTTP check. Retry failures without incrementing verified count.


## 2026-11-09 16:02 KST — Cadillac p.41 source cross-check
- Drive `1olHHdBzp4gp8crAzdwLPrsb15xbfPojA`, filename `Reformer - Sitting Away Spring Series (리포머 스프링 반대 방향 앉은 팔 시리즈).jpg`: actual original JPEG opened and read. **Important mismatch:** filename labels Reformer, printed heading clearly says **Cadillac / Sitting Arm Away Spring Series**, p.41. Five listed exercises: Straight Forward, Biceps Curl, Teardrop Outward/Inward, Salute, Hugging Arm. Two photos, starting position, movement guidance and three variations inspected. Original does **not** supply individual inhale/exhale phases or named muscle list; no fabricated SOURCE details. SOURCE/COACHING separated in HTML. **Verified for this image's legible contents, but apparatus filename/category correction pending.**
- Provisional ledger **119/186** (previous 118 + 1, pending unique-ID audit and category reconciliation). Curl Up/Roll Up comparison and public Pages QA outstanding. Next: other unverified originals, prioritizing source-title mismatches; do not count filename as printed equipment classification.


## 2026-11-09 17:37 KST — Chair originals p.86–87
- **chair-page-86 Roll Over**, original Drive `1vg5Az7JQsJp9hTI8cyFIWf3vgWK4X5RX`: actual original JPG opened, inspected four main photos and Jack Knife variation photo, Why, Starting Position, four printed breath phases, Movement Point, four Watch Points and variations. Existing SOURCE/COACHING detail in HTML checked against source. **Verified original image; no duplicate detail added.**
- **chair-page-87 Tendon Stretch**, original Drive `1RPDtrSV9fjzyUAtR1En54bVsAnnIFrCU`: actual original JPG opened and visually inspected two photographed positions, Why, Starting Position, three printed breath phases, Movement Point, four Watch Points and split-pedal variation. SOURCE and COACHING separated in HTML; original specifies heavy initial spring, push rather than pull, stable gaze, no momentum. **Verified.**
- Provisional ledger **121/186** (previous 119 + 2 actual source images; unique Drive-ID deduplication and prior ledger audit pending). Next: unverified Chair p.88 onward or other unverified originals, Curl Up/Roll Up comparison and public Pages HTTP verification. Do not count existing HTML detail alone as proof of source-image inspection.

## 2026-11-09 18:05 KST — Chair Cat Spine Standing Front original JPGs p.88–90
- **chair-page-88 Articulation**, Drive `19nfXq9NftWlYei4DYn5K2ushz5VeI32x`: actual JPG opened; six positions, printed Why spinal segmentation; neutral spine/pelvis, arms overhead, feet pelvic-width; breathing INHALE Ready → EXHALE Roll Down & Pedal Press → INHALE Pedal Up → EXHALE Roll Up → INHALE Return. Movement Point TVA, pelvic floor, spinal articulation, hip flexion/extension, scapula stabilizer. Watch: neck/shoulder tension, elbow rocking/wrist folding, avoid pressing pedal with arms, sequential spine, evenly weighted soles/no knee hyperextension. Red handwritten notes excluded from SOURCE. **Verified.**
- **chair-page-89 AB Press**, Drive `1NpuiqX9cunYaVt512zSZhYMTIsfzOqj8`: actual JPG opened; six photos. Printed Why spinal segmentation awareness and abdominal activation. Same neutral standing start. Breath INHALE Ready → EXHALE Flexion Forward & Pedal Press → INHALE Lightly Roll Up → EXHALE 3 Pulse, Roll Down → INHALE Roll Up → EXHALE Return to Starting Position. Red handwritten abdominal cues excluded from printed SOURCE. No independent printed Movement Point/Watch Point/Variation on this page. **Verified for visible content.**
- **chair-page-90 Arm Press**, Drive `1VNft5pcCuYfBzUIpy0WU20R4rEoKQtPw`: actual JPG opened; six photos. Printed Why spinal segmentation awareness and elbow extensor activation. Neutral standing start; INHALE Ready → EXHALE Flexion Forward & Pedal → INHALE Elbow Flexion → EXHALE Elbow Extension → INHALE Roll Up → EXHALE Return. No standalone printed Movement Point/Watch Point/Variation. **Filename mismatch:** Drive filename says 'Arm Press Variation', printed heading is '3. Arm Press'; printed p.89 is '2. AB Press', despite filename saying Arm Press. **Verified printed contents; filenames need correction.**
- SOURCE and COACHING distinction: printed breathing/why/start above is SOURCE; gaze downward during spinal flexion, pelvis tracking over feet, full-foot pressure, controlled pedal resistance, TVA and triceps emphasis beyond the printed text are COACHING/photographic interpretation, not literal source instructions.
- Provisional ledger **124/186** (previous 121 + 3; unique Drive-ID reconciliation outstanding). Next Chair p.91 onward, then remaining unverified images; Curl Up vs Roll Up direct photo comparison and public Pages check pending.


## 2026-11-09 19:03 KST — Chair original photographs p.91–92
- **chair-page-91 Single Leg Standing**, Drive `1tsSrgjBpuS5t2jhwzzTt0Xuu9On6huxB`: actual original JPG opened and visually inspected. Printed Front and Side setups (one foot on pedal, shoulder-height arms; side foot externally rotated), 4 principal position photos plus 2 handle variations, Why (hip/lower-limb dissociation and balance activation), INHALE Pedal Up → EXHALE Pedal Press, Movement Point (Transverse Abdominis, Pelvic Floor, Prevent Rotation: Oblique & Multifidus, Hip/Knee Flexion & Extension), four Watch Points and handle variation. Red handwriting excluded from printed SOURCE. Existing HTML detail matches the original at this level. **Verified original photograph.**
- **chair-page-92 Step Up**, Drive `1XPhJxHYzTxRnurDXeL7zkC5Q2CVR4R8C`: actual original JPG opened and visually inspected 5 main photos and 2 variation photos. Printed Why (balance, Hip/Knee Flexor/Extensor activation), neutral spine/pelvis, front foot on Chair top and back foot on pedal, hands on handles; INHALE Ankle Dorsiflexion → EXHALE Ankle Plantarflexion & Press Up → INHALE Keep → EXHALE Return; Movement Point (TVA, Pelvic Floor, Hip/Knee Flexion & Extension, Scapula Stabilizer), four Watch Points and three variations (omit ankle motion, change arm position, limit range). Handwritten red cues excluded from SOURCE. Existing HTML detail reviewed. **Verified original photograph.**
- Provisional ledger **126/186** (previous 124 + 2; unique Drive-ID reconciliation outstanding). Next: Chair Spine Press Prep p.93, Rotation Prone p.94, Slow Swan p.95, then other unverified images. Curl Up/Roll Up original comparison and public Pages QA remain pending.


## 2026-11-09 19:58 KST — Chair original photos p.93–94
- **Chair p.93 Spine Press on Chair Prep**, Drive `1Lo2wC02JN3o85XJdiyEYXJs0kpItLrRe`: original JPEG opened, visually inspected six photographed positions and printed Why, Starting Position, 6-phase breathing (3–5 reps), Movement Point, four Watch Points. No printed Variation. SOURCE and COACHING independently added to movement-manual.html. Handwritten red note excluded from verified source. **Verified photograph.**
- **Chair p.94 Rotation Prone**, Drive `15YSsain0I0forfAdQ9H8EAZL1SSf8RkH`: original JPEG opened; five photos and Why, Starting Position (ASIS 2–5 cm below chair front), four-phase breathing, Movement Point, two Watch Points, Variation (omit arm extension) checked. SOURCE and COACHING separately saved. Red handwriting not treated as verified printed instructions. **Verified photograph.**
- Provisional verified total **128/186** (prior 126 + 2; unique-ID reconciliation remains). Next **Chair p.95 Slow Swan** (Drive `16kpNp2E_8YIOH9Aufp1uwq8bnjjIOA5Q`), then other unverified pages. Curl Up/Roll Up prior comparison is documented above; independent site HTTP QA still pending. HTML commit: `58f8271302e93c394421746ac31b29d30dcb36bc`.


## 2026-11-09 21:00 KST — Chair p.95 original-image verification
- **chair-page-95 Slow Swan**, original Drive `16kpNp2E_8YIOH9Aufp1uwq8bnjjIOA5Q`: actual JPG opened and visually inspected three photographed stages, printed Why, Starting Position, INHALE Ready → EXHALE Rock Forward → INHALE Return, four Movement Point groups, three Watch Points and pedal-separation Variation. ASIS 2–5cm below chair front, torso supported on chair, feet airborne, arm/pedal contact, gaze as photo observation rather than printed instruction. SOURCE / PHOTO OBSERVATION / COACHING separated in HTML. Red handwriting excluded from printed SOURCE. **Verified for legible printed source and photographs.**
- Provisional photo verification count **129/186** (previous 128 + 1; unique original Drive-ID reconciliation pending). Next: remaining unverified Mat/Reformer/Cadillac originals, duplicate-ID audit, Curl Up vs Roll Up source check and public Pages QA.


## 2026-11-09 22:05 KST — Mat Curl Up vs Roll Up direct source-image comparison
- **Mat 010 Curl Up**, original Drive `16uB1r23FLt4ACxJwXTIGJPjr8hnk6qtt`, printed **p.12**: original JPG opened and all four photos inspected. SOURCE: purpose basic abdominal exercise; supine neutral spine/pelvis, knees bent hip-width, arms relaxed, gaze ceiling. Breath **INHALE Shoulder Flexion → EXHALE Head Nod & Cervical and Upper Thoracic Flexion → INHALE Keep → EXHALE Return to Starting Position**. Movement Point: TVA, pelvic floor, rectus abdominis/obliques, scapular stabilizers. Watch: avoid shoulder/neck tension; maintain neutral pelvis. Variations: Arc Barrel, circle/spacer/ball, bilateral leg folding, hands behind head. PHOTO: partial upper trunk curl, knees remain bent, feet on mat. Handwritten red marks are not SOURCE. **Verified against image**.
- **Mat 018 Roll Up**, original Drive `1atTLtc94l_vKDXJKMNxJk83NhNsIbaRI`, printed **p.20**: original JPG opened and five photos inspected. SOURCE: purpose spinal segmentation and abdominal strengthening; neutral spine/pelvis, legs extended hip-width, ankles dorsiflexed, arms overhead. Breath **INHALE Shoulder Flexion → EXHALE Roll Up → INHALE Roll Down → EXHALE Starting Position**. Movement Point: TVA, pelvic floor, rectus abdominis/obliques, hip flexors, scapular stabilizers. Watch: segmental spinal movement, scapular stability to avoid shoulder elevation, avoid premature spinal extension when curling forward. Variations: knees bent, towel support, upper-body-only roll-up. PHOTO: full trunk rolls up toward seated position, extended legs/heel contact; not just head and upper thoracic curl. Red handwriting excluded from SOURCE. **Verified against image**.
- **Critical distinction:** Curl Up p.12 is a *partial cervical/upper-thoracic curl with bent knees*, while Roll Up p.20 is a *segmental full-trunk roll with long legs*. Neither page's printed breath should be copied to the other. Instructor-only coaching (e.g., avoid pushing through feet or pulling on neck, control lumbar articulation) must remain labeled COACHING, not SOURCE.
- Both images are directly source-verified in this run. **Do not increment provisional 129/186 yet:** earlier ledger mentions prior Curl Up/Roll Up verification, so unique Drive-ID audit must confirm whether these are already counted. Next: unverified originals and duplicate-ID reconciliation; Pages QA remains pending.


## 2026-11-09 23:05 KST — Barrel Scissors p.109 original image
- **040_Barrel - Scissors**, Drive `1bAiht_yVfduJjFyyUJJOT-JqnSyJeoj0`: original JPG opened and visually checked (printed p.109; five photos). Verified printed Why, Starting Position, 5-step inhale/exhale sequence, Movement Point, seven Watch Points. No printed Variation; handwritten red annotations excluded from SOURCE. PHOTO OBSERVATION distinguishes sacrum-on-Barrel, hands on Ladder, feet airborne, alternating hip flexion/extension, and forward gaze (not a printed gaze instruction). Separate COACHING covers muscle roles, pelvic control, compensations and regression. **Verified.**
- Provisional verified count **130/186** (prior 129 + 1; unique Drive-ID reconciliation outstanding). Next Barrel Bicycle p.110 (Drive `18fQzpeAODhNn6937VDYdPoID6Y3XqFFH`), then Barrel Leg Lower and Lift p.111. Public Pages HTTP check and final audit still pending.


## 2026-11-10 00:02 KST — Barrel Bicycle p.110 original image
- **041_Barrel - Bicycle**, original Drive `18fQzpeAODhNn6937VDYdPoID6Y3XqFFH`: actual JPEG opened, 6 photographed stages, Why, Starting Position, 6 printed breathing/movement lines, Movement Point, six Watch Points and reverse-direction Variation inspected. SOURCE, PHOTO OBSERVATION, COACHING separated in `movement-manual.html`. The printed final **INHALE Return to Starting Position** repeats INHALE after the preceding INHALE; preserved verbatim and flagged as potentially ambiguous, **not corrected without evidence**. **Verified for legible original, breath anomaly unresolved.**
- Provisional ledger **131/186** (previous 130 + 1; unique Drive-ID reconciliation pending). Next Barrel Leg Lower and Lift p.111, then remaining unverified originals; public Pages QA and final audit outstanding.


## 2026-11-10 00:55 KST — Barrel Leg Lower & Lift p.111 original image
- **042_Barrel - Leg Lower and Lift**, Drive `17dxozn0NPRwi37YnO3Ugsm_LwjQwoHOe`: original JPG opened; printed p.111 and three side-view photos visually inspected. SOURCE: Why (hip flexor/lower-abdominal strengthening and hip dissociation), starting sacrum on Barrel Top in imprinting, hands on ends of Ladder, both legs together up; INHALE Ready → EXHALE Lower Leg → INHALE Lift Leg; Movement Point TVA, pelvic floor, hip flexion, scapular stabilizers; six Watch Points (neck/shoulder tension, hip-flexor eccentric control, rib popping, motion from hip, spine shape, stable pelvis). No printed Variation. PHOTO: feet remain airborne, legs straight, sacrum supported, gaze appears forward. COACHING clearly separated; handwritten red notes excluded from SOURCE. **Verified original image.**
- Provisional count **132/186** (previous 131 + 1; unique-ID reconciliation pending). Next Barrel Horse p.112 (Drive `1VxYLqI7gcLXONbvlfCpxg18t0jw6NmEY`), then other unverified originals. Pages final QA outstanding.


## 2026-11-10 02:03 KST — Barrel Horse p.112 original image
- **043_Barrel - Horse**, Drive `1VxYLqI7gcLXONbvlfCpxg18t0jw6NmEY`: original JPEG opened and visually inspected, printed p.112, 2 frontal photos. SOURCE: Why trunk stabilization and hip adductor activation/awareness; neutral spine/pelvis centered on Barrel Top, legs externally rotated and extended, arms spread at shoulder height; INHALE Ready → EXHALE Squeeze; Movement Point TVA, pelvic floor, Hip Adduction, Scapula Stabilizer; four Watch Points; no printed Variation. PHOTO: seated straddle over Barrel, initial bent knees versus extended legs, feet apparently off ground, forward gaze. SOURCE/PHOTO/COACHING separated in HTML. Printed Watch Point contains **'골곡'**; meaning unclear, preserved and flagged rather than silently corrected. Red handwritten annotations excluded. **Verified for legible original image, with ambiguous printed term unresolved.**
- HTML commit `31d94e45699efcd32b628300170667e9064d6c2e`. Provisional verified count **133/186** (prior 132 + 1; unique Drive-ID reconciliation pending). Next Barrel Prone Exercise Series p.113 (file 044), then other unverified originals. Public Pages QA remains outstanding.


## 2026-11-10 03:00 KST — Barrel Prone Exercise Series p.113 original photograph
- **044_Barrel - Prone Exercise Series**, Drive `1jOaqUkekkyHG8ktNuO5WT1dRVXUZ7ecb`: original JPEG directly opened; printed p.113, six photos across Single Leg Extension, Double Leg Extension, Leg Swimming. Common printed Starting Position (hands on Ladder handles, ASIS near Barrel Top, spinal extension, shoulder-width externally rotated legs, optional rotation), four Watch Points (neck/shoulder tension, neutral spine/pelvis, maintain hip extensors against leg sag, hip-only motion), three Variations (Chair, Arc Barrel, Spine Corrector) inspected. No printed Why, Breathing, Movement Point, or explicit gaze instruction on this page; none fabricated as SOURCE. Photo observations and instructor-only coaching separated in HTML. Red handwritten notes excluded from printed SOURCE. **Verified legible original and photo stages.**
- HTML commit `4f00131c597876e96c6f369cba6dccf89d9ed580`. Provisional ledger **134/186** (previous 133 + 1, unique Drive-ID reconciliation outstanding). Next Barrel p.114 or other unverified originals. Public Pages final QA pending.


## 2026-11-10 04:00 KST — Reformer Coordination original p.33
- **Reformer - Coordination**, original Drive `1a28MuHM_5LD9-kGFJlF-oPrcuj2UH4xs`: JPEG directly opened and four side-view photographs and legible printed text inspected. SOURCE: pelvic/scapular stability, elbow extensor/abdominal strengthening and limb coordination; supine carriage, shoulders approximately 5 cm below shoulder rests, imprinting, Leg Folding, upper trunk flexion; INHALE Reach Leg & Arm → EXHALE Hip Abduction & Adduction → INHALE Knee Flexion → EXHALE Elbow Flexion & Return. Movement Point: TVA/pelvic floor, rectus/obliques, hip flexors and abductors/adductors, elbow flexors/extensors, scapular stabilizers. Watch: avoid neck/shoulder tension, retain imprinting and spinal flexion, coordinate tempo. Variations: omit spinal flexion or elbow flexion. PHOTO: feet suspended, pointed feet during extension, bent knees during return, arms lengthen beside torso then bend; gaze toward knees. Handwritten notes excluded from SOURCE; instructor cues remain COACHING. **Verified original image and printed p.33.**
- HTML commit `605419a6bd44842a66a99d3cd17fbf6325d371ff`. Provisional ledger **135/186** (prior 134 + 1; unique-ID reconciliation still pending). Next select another original absent from this ledger, then reconcile all 186 unique IDs and verify public Pages.


## 2026-11-10 05:02 KST — original image checks (2 pages)
- **Reformer Kneeling Arm Forward Footbar Series, Page 2**, Drive `1lIx4Yj8_wHRbnPfykRJ6JaVvT8hcXMgW`, printed **p.40**: actual JPEG opened and inspected. This page contains **3 Teardrop outward/inward** and **4 Salute**, not an independent single movement. Six sequence photos inspected. SOURCE printed Why, kneeling starting positions, shared breath **INHALE Ready → EXHALE outward/inward or Elbow Extension → INHALE Return**, Movement Point and Sitting Position / Offering variation. PHOTO observation and instructor-only shoulder, spine, hip, knee and foot cues kept separate. Red handwritten notes excluded from printed source. Detailed `detail` entry committed `8dd9c63b4c3f88499e1e13a06794bc142f52070c`. **Source verified for legible p.40; related p.39 must be checked independently.**
- **Cadillac Sitting Arm Away Spring Series**, Drive `1olHHdBzp4gp8crAzdwLPrsb15xbfPojA`, printed **p.41**: actual JPEG opened. Filename misleadingly says *Reformer*, but original header is **Cadillac**. Five named movements (Straight Forward, Biceps Curl, Teardrop outward/inward, Salute, Hugging Arm); two sample photos; printed starting position, sequence cross-reference and variations (Kneeling, Unilateral, Reciprocal). Existing manual entry already flags category correction. This page refers to Reformer sequences and does **not** print independent inhale/exhale phases. **Original p.41 inspected; complete cross-page protocol not verified**, so do not count as a newly completed detailed protocol until paired pages are checked.
- Unique-ID audit remains outstanding; provisional count remains **135/186** rather than incrementing on possible earlier overlap. Next: Reformer Kneeling Arm Forward Footbar p.39 (`1E51lPFtjhFE8O9C4pYYR7KRnWhog7wYV`), then other unverified source IDs. Retry public GitHub Pages HTTP QA.


## 2026-11-10 05:56 KST — Chair Roll Over original p.86
- **018_Chair - Roll Over**, Drive `1vg5Az7JQsJp9hTI8cyFIWf3vgWK4X5RX`: actual JPEG opened and visually inspected, printed **p.86**, four main sequence photos and Jack Knife inset. SOURCE: Why (erector-spinae stretch; glute/hamstring/abdominal strengthening; segmental spinal awareness), supine imprinting with head toward Chair, legs together on diagonal and hands gripping both pedal ends; **INHALE Hip Flexion → EXHALE Roll Over → INHALE Roll Down → EXHALE Return**; TVA/pelvic floor, spinal articulation, hip movement, scapular stabilizers; four Watch Points (neck/shoulder tension, excessive pedal pull, head not on frame, no momentum); Variations hip adduction/abduction and Jack Knife. PHOTO: feet off floor, knees extended, sequential hip lift and roll-down; no printed separate gaze transition. SOURCE/PHOTO/COACHING separated in HTML. Handwritten red notes excluded from verified source. **Verified original image and legible printed content.**
- HTML commit `19565584121fad9e56005d4f98c8647ba12d8ef5`. Provisional unique verified count **136/186** (prior 135 + 1; full unique Drive-ID reconciliation still outstanding). Next: Reformer Kneeling Arm Forward Footbar p.39 (`1E51lPFtjhFE8O9C4pYYR7KRnWhog7wYV`), other unverified originals. Public Pages final HTTP check outstanding.
