# Assembled Tamil Reading Layer — ரோமாபுரிப் பாண்டியன்

This `sections/` directory is the maintained source-faithful Tamil reading layer derived only from verified canonical `../pages/` records.

Canonical `pages/` remains authoritative if any conflict is ever discovered.

## Part001 — PASS / CLOSED

- physical coverage — **scans1–17**
- verified canonical pages represented structurally — **17/17**
- publication-text source-transcription pages represented — **16/16**
- copy-specific scan2 donation-label text — **excluded by maintained reading-layer policy / provenance retained**
- assembled files — **6/6 VERIFIED**
- omitted publication-text pages — **0**
- duplicate canonical publication-text pages — **0**
- unsupported Tamil insertion — **0**
- audit-note leakage — **0**
- Part002 text leakage — **0**
- canonical page mutations caused by assembly — **0**
- validation — `../PART_001_ASSEMBLED_TAMIL_VALIDATION.md`

## Part002 — PASS / CLOSED

- physical coverage — **scans18–34**
- verified canonical pages represented structurally — **17/17**
- publication-text source-transcription pages represented — **17/17**
- assembled files — **4/4 VERIFIED**
- omitted publication-text pages — **0**
- duplicate canonical publication-text pages — **0**
- unsupported Tamil insertion — **0**
- audit-note leakage — **0**
- Part003 text leakage — **0**
- canonical page mutations caused by assembly — **0**
- validation — `../PART_002_ASSEMBLED_TAMIL_VALIDATION.md`

## Part003 — PASS / CLOSED

- physical coverage — **scans35–52**
- verified canonical pages represented structurally — **18/18**
- publication-text source-transcription pages represented — **17/17**
- blank scan44 — **represented by provenance only; no rendered Tamil text**
- assembled files — **2/2 VERIFIED**
- omitted publication-text pages — **0**
- duplicate canonical publication-text pages — **0**
- unsupported Tamil insertion — **0**
- audit-note leakage — **0**
- Part004 text leakage — **0**
- canonical page mutations caused by assembly — **0**
- validation — `../PART_003_ASSEMBLED_TAMIL_VALIDATION.md`

## Part004 — PASS / CLOSED

- physical coverage — **scans53–68**
- verified canonical pages represented structurally — **16/16**
- publication-text source-transcription pages represented — **14/14**
- blank scans56 and 66 — **represented by provenance only; no rendered Tamil text**
- assembled files — **3/3 VERIFIED**
- omitted publication-text pages — **0**
- duplicate canonical publication-text pages — **0**
- unsupported Tamil insertion — **0**
- audit-note leakage — **0**
- Part005 text leakage — **0**
- canonical page mutations caused by assembly — **0**
- validation — `../PART_004_ASSEMBLED_TAMIL_VALIDATION.md`

## Part005 — PASS / CLOSED

- physical coverage — **scans69–85**
- verified canonical pages represented structurally — **17/17**
- publication-text source-transcription pages represented — **17/17**
- blank physical scans — **0**
- assembled files — **2/2 VERIFIED**
- omitted publication-text pages — **0**
- duplicate canonical publication-text pages — **0**
- unsupported Tamil insertion — **0**
- audit-note leakage — **0**
- Part006 text leakage — **0**
- canonical page mutations caused by assembly — **0**
- validation — `../PART_005_ASSEMBLED_TAMIL_VALIDATION.md`

## Section inventory

| Order | Part | File | Source scans | Source structure | Status |
|---:|---:|---|---:|---|---|
| 0 | 001 | `00-front-matter.md` | 1–4 | cover/title/bibliographic front matter; scan2 copy-specific donation label excluded | **VERIFIED** |
| 1 | 001 | `01-moondram-pathippin-munnurai.md` | 5 | `மூன்றாம் பதிப்பின் முன்னுரை` | **VERIFIED** |
| 2 | 001 | `02-kaanikkai.md` | 6–7 | `காணிக்கை` | **VERIFIED** |
| 3 | 001 | `03-pathippurai.md` | 8 | `பதிப்புரை` | **VERIFIED** |
| 4 | 001 | `04-devaneyap-paavanar-thalaimai-urai.md` | 9–11 | தேவநேயப் பாவாணர் தலைமை உரை | **VERIFIED** |
| 5 | 001 | `05-ananthanarayanan-paarattu-urai.md` | 12–17 | அனந்தநாராயணன் பாராட்டு உரை; Part001 terminal continuation | **VERIFIED** |
| 6 | 002 | `06-ananthanarayanan-paarattu-urai-part002-continuation.md` | 18 | அனந்தநாராயணன் பாராட்டு உரை continuation / close | **VERIFIED** |
| 7 | 002 | `07-kaviyarasu-kannadasan-urai.md` | 19–22 | கவியரசு கண்ணதாசன் உரை | **VERIFIED** |
| 8 | 002 | `08-arimugam.md` | 23–28 | `அறிமுகம்` | **VERIFIED** |
| 9 | 002 | `09-chapter-01-karikaar-chozhanum-peruvazhuthi-pandiyanum.md` | 29–34 | Chapter 1 title + narrative opening | **VERIFIED** |
| 10 | 003 | `10-chapter-01-karikaar-chozhanum-peruvazhuthi-pandiyanum-part003-continuation.md` | 35–44 | Chapter 1 continuation / close; scan44 blank separator represented by provenance | **VERIFIED** |
| 11 | 003 | `11-chapter-02-muthunagai.md` | 45–52 | Chapter 2 illustrated title + narrative opening / continuation | **VERIFIED** |
| 12 | 004 | `12-chapter-02-muthunagai-part004-continuation.md` | 53–56 | Chapter 2 continuation / close; scan56 blank separator represented by provenance | **VERIFIED** |
| 13 | 004 | `13-chapter-03-maravar-maanam.md` | 57–66 | Chapter 3 illustrated title + narrative / close; scan66 blank separator represented by provenance | **VERIFIED** |
| 14 | 004 | `14-chapter-04-pulavar-magal-purappattaal.md` | 67–68 | Chapter 4 illustrated title + narrative opening | **VERIFIED** |
| 15 | 005 | `15-chapter-04-pulavar-magal-purappattaal-part005-continuation.md` | 69–80 | Chapter 4 continuation / close | **VERIFIED** |
| 16 | 005 | `16-chapter-05-sivanadiyaar-thirukkoottam.md` | 81–85 | Chapter 5 illustrated title + narrative / continuation | **VERIFIED** |

## Assembly rules

1. Source text comes only from verified canonical page `## Source transcription` blocks.
2. Preserve source spelling, punctuation, paragraph/display order and historical forms.
3. Preserve physical-page provenance with non-rendering HTML boundary comments.
4. Exclude review/audit notes, page YAML, copy-specific stamps/handwriting, and scan2 donation-label text already classified as copy-specific front matter.
5. Join a physical split word only where the closed canonical evidence explicitly establishes the join.
6. Canonical `pages/` always governs; this reading layer never authorizes silent correction of canonical Tamil.
7. Do not cross a Part boundary by importing adjacent-Part body text merely to make a section self-contained.

## Part001 special cases

- scan2 — copy-specific donation-label text excluded from the maintained publication reading layer; the physical scan remains represented by provenance comments.
- scan9→10 — verified same-sentence continuation retained.
- scan10→11 — verified same-sentence continuation retained.
- scan12→13 — physical split word rendered continuously as `வந்திருக்கின்றன.` with a non-rendering provenance marker.
- scan15→16 — verified same-sentence continuation retained.
- scan16→17 — verified same-sentence continuation retained.
- scan17 — remains terminal at `ஜராத் என்ற அவளது பணிப்பெண்ணும் அது`.

## Part002 special cases

- scan18 — begins with the source continuation from Part001 scan17; Part001 body text is not duplicated into the Part002 assembled file.
- scan19→20 — same-sentence continuation retained with a non-rendering source-boundary marker.
- scan20→21 and scan21→22 — physical continuations retained.
- scan25→26 — physical split word rendered continuously as `கொண்டானாம்.` with a non-rendering provenance marker.
- scan28 — `அறிமுகம்` closes.
- scan29 — illustrated Chapter 1 title page retained at the start of the Chapter 1 assembled file.
- scan30→31→32→33 — Chapter 1 physical continuations retained.
- scan33→34 — physical split word rendered continuously as `முத்தாரத்தையெடுத்து` with a non-rendering provenance marker.
- scan34 — remains terminal at `குதிரைகள்`; no Part003 continuation is imported.

## Part003 special cases

- scan35 — begins with the audited continuation from Part002 scan34; Part002 body text is not duplicated into the Part003 assembled file.
- scan38→39 — physical split word rendered continuously as `ஒப்பிடுவதற்கரிய` with a non-rendering provenance marker.
- scan41→42 — direct-speech continuation retained across the physical page boundary.
- scan43 — Chapter 1 closes with a large intentional lower blank field.
- scan44 — fully blank physical separator page represented by provenance only; no rendered Tamil text.
- scan45 — illustrated Chapter 2 title page retained at the start of the Chapter 2 assembled file.
- scan46 — Chapter 2 narrative opens after the title page.
- scan47→48 — sentence continuation retained as `மறைத்து வைக்கப்பட்டிருப்பதை`.
- scan49→50 — sentence continuation retained as `இந்த ஆபத்து வந்திருக்காதல்லவா?`.
- scan52 — ends on the complete sentence `முத்துநகைக்குத் தூக்கமே வரவில்லை. புரண்டு புரண்டு படுத்தாள்.`; no Part004 continuation is imported.

## Part004 special cases

- scan53 — begins the audited Chapter 2 continuation from Part003 scan52; Part003 body text is not duplicated into the Part004 assembled file.
- scan53→54 — same-sentence continuation retained as `தன்பால் மிக்க அன்பு கொண்டவர் என்றும் காரிக்கண்ணனார்...`.
- scan55 — Chapter 2 closes with a large intentional lower blank field.
- scan56 — fully blank physical separator represented by provenance only; no rendered Tamil text.
- scan57 — illustrated Chapter 3 title page retained at the start of the Chapter 3 assembled file.
- scan58 — Chapter 3 narrative opens after the title page.
- scan61→62 — same-sentence continuation retained as `நேரத்தில்தான் செழியன் குறுக்கிட்டுவிட்டான்.`.
- scan64→65 — same-sentence continuation retained as `அமைச்சரின் உத்திரவில் ஏதாவது அர்த்தமிருக்கும்...`.
- scan65 — Chapter 3 closes with a large intentional lower blank field.
- scan66 — fully blank physical separator represented by provenance only.
- scan67 — illustrated Chapter 4 title page retained at the start of the Chapter 4 assembled file.
- scan68 — Chapter 4 narrative opening; Part005 text is not imported.

## Boundary safeguard

- outgoing Part001 **17→18 — GENUINE CONTINUATION / AUDITED**
- Part001 assembled file remains terminal at scan17; scan18 is represented only in the Part002 assembled layer
- outgoing Part002 / incoming Part003 **34→35 — GENUINE CONTINUATION / AUDITED**
- Part002 body imported into Part003 assembled layer — **0**
- Part003 body imported backward into Part002 assembled layer — **0**
- outgoing Part003 / incoming Part004 **52→53 — GENUINE CONTINUATION / AUDITED**
- Part003 body imported into Part004 assembled layer — **0**
- Part004 body imported backward into Part003 assembled layer — **0**
- outgoing Part004 / incoming Part005 **68→69 — GENUINE CONTINUATION / AUDITED**
- Part004 body imported into Part005 assembled layer — **0**
- Part005 body imported backward into Part004 assembled layer — **0**
- outgoing Part005 **85→86 — PENDING Part006 adjacent witness / deferred external boundary evidence**
- Part006 text imported into Part005 assembled layer — **0**

## Downstream state

Part001 Tamil archival-ready — **PASS / CLOSED**.

Part001 assembled Tamil — **PASS / CLOSED — 6/6 VERIFIED**.

Part001 English E1–E6, glossary reconciliation, editorial review, bilingual review, release/readiness and release-ready synchronization are **PASS / CLOSED**.

Part001 final closure — **PASS / CLOSED / FROZEN**.

Part002 Tamil archival-ready — **PASS / CLOSED**.

Part002 assembled Tamil — **PASS / CLOSED — 4/4 VERIFIED**.

Part002 English translation planning/setup — **COMPLETE / PASS**.

Part002 English E7–E10 — **SOURCE-CHECKED / COMPLETE — 4/4**.

Part002 glossary reconciliation — **RECONCILED / PASS**.

Part002 English editorial review — **PASS / CLOSED**.

Part002 bilingual review — **PASS / CLOSED**.

Part002 release/readiness — **PASS / CLOSED**.

Part002 release-ready synchronization — **PASS / CLOSED**.

Part002 final closure — **PASS / CLOSED / FROZEN**.

Part002 English E7–E10 — **SOURCE-CHECKED / COMPLETE — 4/4**.

Part003 Tamil archival-ready — **PASS / CLOSED**.

Part003 assembled Tamil — **PASS / CLOSED — 2/2 VERIFIED**.

Historical Part003 post-assembly next gate — **Part003 English translation planning/setup**.


## Part003 downstream English state

Part003 English E11–E12 — **SOURCE-CHECKED / COMPLETE — 2/2**.

Part003 glossary reconciliation — **RECONCILED / PASS**.

Part003 English editorial review — **PASS / CLOSED**.

Part003 bilingual review — **PASS / CLOSED**.

Part003 release/readiness — **PASS / CLOSED**.

Part003 release-ready synchronization — **PASS / CLOSED**.

Part003 final closure — **PASS / CLOSED / FROZEN**.

Part004 Tamil archival-ready — **PASS / CLOSED**.

Part004 assembled Tamil — **PASS / CLOSED — 3/3 VERIFIED**.

Part004 assembled Tamil coverage — **16/16 physical scans / 14/14 publication-text pages + blank scans56 and 66 provenance**.

Part004 assembled Tamil validation blockers — **0**.

Exact next maintained gate — **Part004 English translation planning/setup**.


## Part004 downstream English / release state

Part004 assembled Tamil remains **PASS / CLOSED — 3/3 VERIFIED**.

Downstream English/release gates:

- E13–E15 — **SOURCE-CHECKED / COMPLETE — 3/3**
- glossary reconciliation — **RECONCILED / PASS**
- English editorial review — **PASS / CLOSED**
- whole-Part bilingual review — **PASS / CLOSED — 3/3**
- release/readiness — **PASS / CLOSED**
- release-ready synchronization — **PASS / CLOSED**
- unresolved blockers — **0**

Current frontier:

**Part004 final closure / freeze.**


## Part004 final frozen state

Part004 is **FINAL CLOSED / FROZEN**.

- assembled Tamil — **PASS / CLOSED — 3/3 VERIFIED**
- E13–E15 — **SOURCE-CHECKED / COMPLETE — 3/3**
- glossary reconciliation — **RECONCILED / PASS**
- editorial review — **PASS / CLOSED**
- bilingual review — **PASS / CLOSED — 3/3**
- release/readiness — **PASS / CLOSED**
- release-ready synchronization — **PASS / CLOSED**
- final closure — **PASS / CLOSED / FROZEN**
- Part005 leakage — **0**

Current frontier:

**Part005 source intake + 68→69 adjacent-boundary witness inspection/setup.**


## Part005 special cases

- scan69 — begins the audited continuation from Part004 scan68; Part004 body is not duplicated into the Part005 assembled file.
- scan69→70 — same-sentence continuation retained as `சோழ நாட்டுக்கு...`.
- scan71→72 — physical split word rendered continuously as `இருப்பார்கள்!` with a non-rendering provenance marker.
- scan75→76 — same-sentence continuation retained as `பாறையின் விளிம்பில் புரண்டாள்.`.
- scan77→78 — same-sentence continuation retained as `அந்தச் செய்கை...`.
- scan78→79 — same-sentence continuation retained as `கரிகாற்சோழனை நான் பழி வாங்கப் போகிறேன்...`.
- scan80 — Chapter 4 closes with a large intentional lower blank field.
- scan81 — illustrated Chapter 5 title page retained at the start of the Chapter 5 assembled file.
- scan82 — Chapter 5 narrative opens after the title page with a large intentional upper blank field.
- scan82→83 — same-sentence continuation retained as `வேறு ஏதோ சூழ்ச்சியில்...`.
- scan83→84 — same-sentence continuation retained as `ஒரு மூட்டையையும் களவு போவதில்லை.`.
- scan85 — ends on a complete sentence; no Part006 text is imported.

## Part005 assembled Tamil state

Part005 Tamil archival-ready — **PASS / CLOSED**.

Part005 assembled Tamil — **PASS / CLOSED — 2/2 VERIFIED**.

Part005 assembled Tamil coverage — **17/17 physical scans / 17/17 publication-text pages**.

Part005 assembled Tamil validation blockers — **0**.

Current frontier:

**Part005 English translation planning/setup.**


## Part005 release-ready state

- assembled Tamil — **PASS / CLOSED — 2/2 VERIFIED**
- physical coverage — **17/17**
- publication-text coverage — **17/17**
- English E16–E17 — **SOURCE-CHECKED / COMPLETE — 2/2**
- glossary reconciliation — **RECONCILED / PASS**
- editorial review — **PASS / CLOSED**
- bilingual review — **PASS / CLOSED — 2/2**
- release/readiness — **PASS / CLOSED**
- release-ready synchronization — **PASS / CLOSED**
- unresolved blockers — **0**
- Part006 leakage — **0**

Exact next lifecycle activity:

**Part005 final closure / freeze.**


## Part005 final frozen state

- Part005 — **FINAL CLOSED / FROZEN**
- assembled Tamil — **PASS / CLOSED — 2/2 VERIFIED**
- physical coverage — **17/17**
- publication-text coverage — **17/17**
- English E16–E17 — **SOURCE-CHECKED / COMPLETE — 2/2**
- glossary reconciliation — **RECONCILED / PASS**
- editorial review — **PASS / CLOSED**
- bilingual review — **PASS / CLOSED — 2/2**
- release/readiness — **PASS / CLOSED**
- release-ready synchronization — **PASS / CLOSED**
- final closure — **PASS / CLOSED / FROZEN**
- unresolved blockers — **0**
- Part006 leakage — **0**

Exact next lifecycle activity:

**Part006 source intake + 85→86 adjacent-boundary witness inspection/setup.**


## Part006 intake boundary state

Part006 source intake is **PASS / COMPLETE**.

- source — **REGISTERED / AUTHORIZED — scans86–102 / 17 pages**
- incoming 85→86 — **GENUINE CONTINUATION / AUDITED**
- canonical Part006 records — **0/17**
- Pass1 — **NOT STARTED**
- assembled Part006 Tamil — **NOT STARTED**
- scan94 — **blank separator**
- scan95 — **illustrated Chapter 6 title `விறுவெட்டி`**
- outgoing 102→103 — **PENDING Part007 adjacent witness**
- frozen Parts001–005 assembled/body mutations — **0**

Exact next lifecycle activity:

**Part006 Pass1 Batch 1 — scans86–95 / local1–10.**
