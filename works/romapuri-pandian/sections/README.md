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

## Boundary safeguard

- outgoing Part001 **17→18 — GENUINE CONTINUATION / AUDITED**
- Part001 assembled file remains terminal at scan17; scan18 is represented only in the Part002 assembled layer
- outgoing Part002 / incoming Part003 **34→35 — GENUINE CONTINUATION / AUDITED**
- Part002 body imported into Part003 assembled layer — **0**
- Part003 body imported backward into Part002 assembled layer — **0**
- outgoing Part003 **52→53 — PENDING Part004 adjacent witness / deferred external boundary evidence**
- Part004 text imported into Part003 assembled layer — **0**

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

Exact next maintained gate — **Part003 English translation planning/setup**.


## Part003 downstream English state

Part003 English E11–E12 — **SOURCE-CHECKED / COMPLETE — 2/2**.

Part003 glossary reconciliation — **RECONCILED / PASS**.

Part003 English editorial review — **PASS / CLOSED**.

Part003 bilingual review — **PASS / CLOSED**.

Part003 release/readiness — **PASS / CLOSED**.

Part003 release-ready synchronization — **PASS / CLOSED**.

Exact next maintained gate — **Part003 final closure / freeze**.
