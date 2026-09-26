# English Translation Plan — ரோமாபுரிப் பாண்டியன்

Status: **PARTS001–005 FINAL CLOSED / FROZEN — PART006 E18 SOURCE-CHECKED / COMPLETE — E19 NEXT**

This is the cumulative control plan for the project-created English translation. Parts001–005 are final closed/frozen. Part006 Tamil and assembled Tamil gates are closed, English planning/setup is complete, E18 is source-checked complete, and E19 is the next authorized English batch.

## Authority hierarchy

1. `works/romapuri-pandian/pages/` — canonical audited Tamil; controlling authority.
2. `works/romapuri-pandian/sections/` — **PASS / CLOSED** assembled Tamil reading layer.
3. `works/romapuri-pandian/translations/en/` — derived project-created English only.

If English conflicts with canonical Tamil, Tamil governs.

English work must never silently correct, regularize, modernize, fact-correct or rewrite the Tamil source layer.

## Translation objective

Produce readable English that remains reversible to the verified Part001 Tamil evidence.

Preserve:

- speaker and narrator agency;
- chronology and knowledge state;
- rhetorical questions, repetition, exclamations, irony and emphatic phrasing;
- paragraph and displayed-text structure where meaningful;
- source-visible section structure;
- source-specific names, titles, offices and place names;
- historical, literary and political framing as presented by the source;
- quoted verse only from the verified project Tamil;
- source-visible English already printed in bibliographic matter;
- the open Part001 ending at scan17.

Do not add explanatory history, biography, politics, literary criticism or factual reconciliation inside translation prose unless the Tamil source supplies it.

## Verified Tamil inputs

Part001 assembled Tamil contains **6 verified section files**:

1. `../../sections/00-front-matter.md` — scans1–4
2. `../../sections/01-moondram-pathippin-munnurai.md` — scan5
3. `../../sections/02-kaanikkai.md` — scans6–7
4. `../../sections/03-pathippurai.md` — scan8
5. `../../sections/04-devaneyap-paavanar-thalaimai-urai.md` — scans9–11
6. `../../sections/05-ananthanarayanan-paarattu-urai.md` — scans12–17

Scan2 is copy-specific donation-label material and is not rendered in the maintained assembled publication-reading layer. No separate English translation unit is created for that copy-specific label.

## Reserved Part001 English units

| Batch | Tamil input | Planned English file | Scans | Planning state |
|---|---|---|---:|---|
| **E1** | `../../sections/00-front-matter.md` | `sections/00-front-matter.md` | 1–4 | **RESERVED / NEXT** |
| **E2** | `../../sections/01-moondram-pathippin-munnurai.md` | `sections/01-preface-to-the-third-edition.md` | 5 | **RESERVED** |
| **E3** | `../../sections/02-kaanikkai.md` | `sections/02-dedication.md` | 6–7 | **RESERVED** |
| **E4** | `../../sections/03-pathippurai.md` | `sections/03-publishers-note.md` | 8 | **RESERVED** |
| **E5** | `../../sections/04-devaneyap-paavanar-thalaimai-urai.md` | `sections/04-devaneya-pavanar-presidential-address.md` | 9–11 | **RESERVED** |
| **E6** | `../../sections/05-ananthanarayanan-paarattu-urai.md` | `sections/05-ananthanarayanan-appreciation-address.md` | 12–17 | **RESERVED** |

Batch discipline:

**E1 closes draft + source-check before E2 begins; E2 before E3; E3 before E4; E4 before E5; E5 before E6.**

No batch may be marked complete merely because a draft exists.

## Names, titles and source variants

The glossary uses conservative source-facing project romanizations.

Initial locked handling includes:

- `ரோமாபுரிப் பாண்டியன்` → **Romapuri Pandiyan**
- `கலைஞர் மு. கருணாநிதி` → **Kalaignar M. Karunanidhi**
- `தேவநேயப் பாவாணர்` → **Devaneya Pavanar**
- `அனந்த நாராயணன்` / `அனந்தநாராயணன்` → **Ananthanarayanan** unless source spacing must be represented in a quoted bibliographic form
- `கவியரசு கண்ணதாசன்` → **Kaviyarasu Kannadasan**
- source-visible work titles and literary names are handled in `GLOSSARY.md`

Do not normalize a source-sensitive Tamil form merely because an external spelling is more familiar.

## Section-title handling

Working English section labels:

- `மூன்றாம் பதிப்பின் முன்னுரை` → **Preface to the Third Edition**
- `காணிக்கை` → **Dedication**
- `பதிப்புரை` → **Publisher's Note**
- `தேவநேயப் பாவாணர் தலைமை உரை` → **Devaneya Pavanar's Presidential Address**
- `அனந்தநாராயணன் பாராட்டு உரை` → **Ananthanarayanan's Appreciation Address**

These are project English labels. Tamil section metadata remains authoritative.

## Quotations and verse

Translate only from verified project Tamil.

Rules:

- preserve meaningful lineation;
- preserve quotation boundaries;
- do not import published, remembered or web English versions;
- if a quoted literary line is difficult or ambiguous, translate conservatively from the canonical Tamil and record any unresolved hold;
- source claims within speeches remain source-attributed speech, not project assertions.

This rule applies especially to the Tirukkural quotations and the Kalinkattupparani verse in the speeches.

## Source-visible English

Where the source itself already prints English bibliographic or quoted wording, preserve that source-visible English rather than re-translating it through Tamil.

Examples include bibliographic matter on scan4 and the quoted English proverb on scan12.

## Political / historical source framing

Part001 contains historical and political statements inside authorial front matter and speeches.

English must:

- translate those statements as source voice;
- preserve attribution and rhetorical force;
- not insert external verification, endorsement or correction into translation prose;
- not silently modernize offices, party labels or political descriptions.

## Cross-page and Part-boundary rules

Verified internal joins remain represented naturally in English without losing provenance.

Special internal join:
- scans12→13: canonical Tamil `வந்திருக்கின்` + `றன.` = assembled `வந்திருக்கின்றன.`

Permanent outgoing Part001 rule:
- scan17 ends `ஜராத் என்ற அவளது பணிப்பெண்ணும் அது`;
- **17→18 = GENUINE CONTINUATION / AUDITED**;
- scan18 belongs to Part002;
- no scan18 wording may be translated or inferred in Part001;
- E6 must end visibly incomplete in English.

## Source-check requirements per batch

Each E-batch closes only after checking:

1. complete sentence/paragraph coverage against its Tamil section;
2. names/titles against `GLOSSARY.md`;
3. quotation and verse structure;
4. source-sensitive historical/political framing;
5. no added explanation;
6. no omitted Tamil meaning;
7. no Part002 leakage;
8. canonical/assembled Tamil mutations caused by English work = **0**.

A durable `E#_SOURCE_CHECK.md` record is created when each batch closes.

## Post-drafting sequence

After E6 closes:

1. whole-Part glossary reconciliation;
2. English editorial review;
3. whole-Part bilingual review against verified Tamil;
4. release/readiness report;
5. release-ready synchronization;
6. no-post-release textual-drift verification;
7. Part001 final closure / freeze.

## Current lifecycle frontier

E1–E6 are **SOURCE-CHECKED / COMPLETE**. Whole-Part glossary reconciliation, editorial review, bilingual review, release/readiness and release-ready synchronization are all **PASS / CLOSED**.

## Final lifecycle state

Part001 English is **FINAL CLOSED / FROZEN**.

- E1–E6 — **SOURCE-CHECKED / COMPLETE**
- glossary reconciliation — **RECONCILED / PASS**
- editorial review — **PASS / CLOSED**
- bilingual review — **PASS / CLOSED**
- release/readiness — **PASS / CLOSED**
- release-ready synchronization — **PASS / CLOSED**
- final Part001 closure — **PASS / CLOSED / FROZEN**

## Historical Part001 next activity — SUPERSEDED

**Part002 Pass1 — global scans18–27 / local pages1–10.**

This historical frontier is superseded by the closed Part002 lifecycle recorded below.


## Part002 planning/setup — COMPLETE / PASS

Part001 history above remains **FINAL CLOSED / FROZEN** and is not reopened by this extension.

Part002 English prerequisites are now closed:

- canonical Tamil — **17/17 verified**
- visual fidelity — **17/17 verified**
- Tamil archival-ready — **PASS / CLOSED**
- assembled Tamil — **PASS / CLOSED — 4/4 VERIFIED**
- unresolved Tamil / glyph / visual / structural blockers — **0**
- Part003 canonical/body leakage — **0**

Verified Part002 assembled inputs:

1. `../../sections/06-ananthanarayanan-paarattu-urai-part002-continuation.md` — scan18
2. `../../sections/07-kaviyarasu-kannadasan-urai.md` — scans19–22
3. `../../sections/08-arimugam.md` — scans23–28
4. `../../sections/09-chapter-01-karikaar-chozhanum-peruvazhuthi-pandiyanum.md` — scans29–34

### Reserved Part002 English units

| Batch | Tamil input | Planned English file | Scans | Planning state |
|---|---|---|---:|---|
| **E7** | `../../sections/06-ananthanarayanan-paarattu-urai-part002-continuation.md` | `sections/06-ananthanarayanan-appreciation-address-part002-continuation.md` | 18 | **SOURCE-CHECKED / COMPLETE** |
| **E8** | `../../sections/07-kaviyarasu-kannadasan-urai.md` | `sections/07-kaviyarasu-kannadasan-address.md` | 19–22 | **SOURCE-CHECKED / COMPLETE** |
| **E9** | `../../sections/08-arimugam.md` | `sections/08-introduction.md` | 23–28 | **SOURCE-CHECKED / COMPLETE** |
| **E10** | `../../sections/09-chapter-01-karikaar-chozhanum-peruvazhuthi-pandiyanum.md` | `sections/09-chapter-01-karikala-cholan-and-peruvazhuthi-pandiyan.md` | 29–34 | **SOURCE-CHECKED / COMPLETE** |

Batch discipline:

**E7 closes draft + source-check before E8 begins; E8 before E9; E9 before E10.**

A draft alone does not close a batch. Each batch requires a durable source-check record.

### Part002 translation safeguards

Incoming boundary:

- **17→18 = GENUINE CONTINUATION / AUDITED**;
- Part001 E6 remains frozen and incomplete;
- E7 translates only the verified Part002 scan18 unit;
- E7 must not alter or backfill the Part001 English file.

Internal verified Tamil joins are already resolved in the assembled Tamil authority and must not be reinterpreted:

- scan25→26 — `கொண்டானாம்.`
- scan33→34 — `முத்தாரத்தையெடுத்து`

Outgoing boundary:

- scan34 ends at `குதிரைகள்`;
- **34→35 = PENDING Part003 adjacent witness**;
- E10 must remain visibly incomplete;
- no Part003 wording may be inferred, translated or imported.

Part002 source-check requirements remain the same as Part001, with the leakage check now applying to **Part003**.

### Planning integrity

This planning/setup activity creates or changes English control metadata only.

- canonical Tamil changes caused by planning — **0**
- assembled Tamil changes caused by planning — **0**
- English section drafts created in planning — **0**
- Part001 English section changes — **0**
- Part003 leakage — **0**
- unresolved planning holds — **0**

## Historical Part002 post-draft frontier — SUPERSEDED

**Part002 whole-Part glossary reconciliation across E7–E10.**

This historical frontier is superseded by the final Part002 state below.


## Part002 post-draft closure state

- E7–E10 — **SOURCE-CHECKED / COMPLETE — 4/4**
- Part002 glossary reconciliation — **RECONCILED / PASS**
- Part002 English editorial review — **PASS / CLOSED**
- Part002 bilingual review — **PASS / CLOSED**
- Part002 release/readiness — **PASS / CLOSED**
- Part002 release-ready synchronization — **PASS / CLOSED**
- Part002 final closure — **PASS / CLOSED / FROZEN**
- unresolved Part002 English blockers — **0**

Part001 remains **FINAL CLOSED / FROZEN**.

## Part002 final lifecycle state

Part002 English is **FINAL CLOSED / FROZEN**.

- E7–E10 — **SOURCE-CHECKED / COMPLETE**
- glossary reconciliation — **RECONCILED / PASS**
- editorial review — **PASS / CLOSED**
- bilingual review — **PASS / CLOSED**
- release/readiness — **PASS / CLOSED**
- release-ready synchronization — **PASS / CLOSED**
- final closure — **PASS / CLOSED / FROZEN**

## Exact next activity

**Part003 source intake + 34→35 adjacent-boundary witness inspection/setup.**

Part003 is not supplied / registered. Do not infer scan35.


## Part003 planning/setup — COMPLETE / PASS

Parts001–002 remain **FINAL CLOSED / FROZEN** and are not reopened by this extension.

Part003 English prerequisites are closed:

- canonical Tamil — **18/18 verified**
- visual fidelity — **18/18 verified**
- Tamil archival-ready — **PASS / CLOSED**
- assembled Tamil — **PASS / CLOSED — 2/2 VERIFIED**
- unresolved Tamil / lexical / historical-glyph / visual / structural blockers — **0**
- Part004 leakage — **0**

Verified Part003 assembled inputs:

1. `../../sections/10-chapter-01-karikaar-chozhanum-peruvazhuthi-pandiyanum-part003-continuation.md` — scans35–44
2. `../../sections/11-chapter-02-muthunagai.md` — scans45–52

### Reserved Part003 English units

| Batch | Tamil input | Planned English file | Scans | Planning state |
|---|---|---|---:|---|
| **E11** | `../../sections/10-chapter-01-karikaar-chozhanum-peruvazhuthi-pandiyanum-part003-continuation.md` | `sections/10-chapter-01-karikala-cholan-and-peruvazhuthi-pandiyan-part003-continuation.md` | 35–44 | **SOURCE-CHECKED / COMPLETE** |
| **E12** | `../../sections/11-chapter-02-muthunagai.md` | `sections/11-chapter-02-muthunagai.md` | 45–52 | **SOURCE-CHECKED / COMPLETE** |

Batch discipline:

**E11 closes draft + source-check before E12 begins.**

A draft alone does not close a batch. Each batch requires a durable source-check record.

### Part003 translation safeguards

Incoming boundary:

- **34→35 = GENUINE CONTINUATION / AUDITED**;
- Part002 E10 remains frozen and visibly incomplete;
- E11 translates only the verified Part003 assembled unit;
- E11 must not backfill or alter Part002 English.

Verified Tamil joins/structure are already resolved in the assembled authority and must not be reinterpreted:

- scan38→39 — `ஒப்பிடுவதற்கரிய`
- scan41→42 — direct-speech continuation
- scan44 — blank separator represented by provenance only
- scan45 — illustrated Chapter 2 title page
- scan47→48 — `மறைத்து வைக்கப்பட்டிருப்பதை`
- scan49→50 — `இந்த ஆபத்து வந்திருக்காதல்லவா?`

Outgoing boundary:

- scan52 ends on a complete narrative sentence;
- **52→53 = PENDING Part004 adjacent witness / deferred external boundary evidence**;
- Part004 is not supplied / registered;
- E12 must not infer, translate or import scan53 wording.

### Planning integrity

This planning/setup activity changes English control metadata only.

- canonical Tamil changes caused by planning — **0**
- assembled Tamil changes caused by planning — **0**
- Part001/Part002 English section changes — **0**
- E11/E12 drafts created in planning — **0**
- Part004 leakage — **0**
- unresolved planning holds — **0**

## Current exact English activity

**E11 — draft + source-check Part003 Chapter 1 continuation / scans35–44.**

Do not begin E12 until E11 is **SOURCE-CHECKED / COMPLETE**.


## Part003 post-draft closure state

- E11–E12 — **SOURCE-CHECKED / COMPLETE — 2/2**
- Part003 glossary reconciliation — **RECONCILED / PASS**
- Part003 English editorial review — **PASS / CLOSED**
- Part003 English editorial corrections — **0**
- Part003 bilingual review — **PASS / CLOSED — 2/2 pairs**
- Part003 release/readiness — **PASS / CLOSED**
- Part003 release-ready synchronization — **PASS / CLOSED**
- unresolved Part003 English blockers — **0**
- canonical / assembled Tamil edits caused by English — **0**
- Parts001–002 English section edits — **0**
- Part004 leakage — **0**

## Current exact English activity

**Part004 source intake + 52→53 adjacent-boundary witness inspection/setup.**


## Part003 final lifecycle state

Part003 English is **FINAL CLOSED / FROZEN**.

- E11–E12 — **SOURCE-CHECKED / COMPLETE**
- glossary reconciliation — **RECONCILED / PASS**
- editorial review — **PASS / CLOSED**
- bilingual review — **PASS / CLOSED**
- release/readiness — **PASS / CLOSED**
- release-ready synchronization — **PASS / CLOSED**
- final closure — **PASS / CLOSED / FROZEN**
- unresolved blockers — **0**
- Part004 leakage — **0**

## Exact next activity

**Part004 source intake + 52→53 adjacent-boundary witness inspection/setup.**

Part004 is not supplied / registered. Do not infer scan53.


## Part004 planning/setup — COMPLETE / PASS

Parts001–003 remain **FINAL CLOSED / FROZEN** and are not reopened by this extension.

Part004 English prerequisites are closed:

- canonical Tamil — **16/16 verified**
- visual fidelity — **16/16 verified**
- documentation synchronization — **PASS / COMPLETE**
- Tamil archival-ready — **PASS / CLOSED**
- assembled Tamil — **PASS / CLOSED — 3/3 VERIFIED**
- assembled physical coverage — **16/16 / scans53–68**
- publication-text coverage — **14/14**
- blank scans56 and 66 — **represented by provenance only**
- unresolved Tamil / lexical / historical-glyph / visual / structural blockers — **0**
- Part005 leakage — **0**

Verified Part004 assembled inputs:

1. `../../sections/12-chapter-02-muthunagai-part004-continuation.md` — scans53–56
2. `../../sections/13-chapter-03-maravar-maanam.md` — scans57–66
3. `../../sections/14-chapter-04-pulavar-magal-purappattaal.md` — scans67–68

### Reserved Part004 English units

| Batch | Tamil input | Planned English file | Scans | Planning state |
|---|---|---|---:|---|
| **E13** | `../../sections/12-chapter-02-muthunagai-part004-continuation.md` | `sections/12-chapter-02-muthunagai-part004-continuation.md` | 53–56 | **SOURCE-CHECKED / COMPLETE** |
| **E14** | `../../sections/13-chapter-03-maravar-maanam.md` | `sections/13-chapter-03-the-warriors-honour.md` | 57–66 | **SOURCE-CHECKED / COMPLETE** |
| **E15** | `../../sections/14-chapter-04-pulavar-magal-purappattaal.md` | `sections/14-chapter-04-the-poets-daughter-sets-out.md` | 67–68 | **SOURCE-CHECKED / COMPLETE** |

Batch discipline:

**E13 closes draft + source-check before E14 begins; E14 before E15.**

A draft alone does not close a batch. Each batch requires a durable source-check record.

### Part004 translation safeguards

Incoming boundary:

- **52→53 = GENUINE CONTINUATION / AUDITED**;
- Part003 E12 remains frozen;
- E13 translates only the verified Part004 Chapter 2 continuation unit;
- E13 must not backfill or alter Part003 English.

Verified Tamil joins / structure are already resolved in the assembled authority and must not be reinterpreted:

- scan53→54 — `தன்பால் மிக்க அன்பு கொண்டவர் என்றும் காரிக்கண்ணனார்...`
- scan56 — blank separator represented by provenance only
- scan57 — illustrated Chapter 3 title `மறவர் மானம்`
- scan61→62 — `நேரத்தில்தான் செழியன் குறுக்கிட்டுவிட்டான்.`
- scan64→65 — `அமைச்சரின் உத்திரவில் ஏதாவது அர்த்தமிருக்கும்...`
- scan66 — blank separator represented by provenance only
- scan67 — illustrated Chapter 4 title `புலவர் மகள் புறப்பட்டாள்`

Outgoing boundary:

- scan68 ends on a complete narrative sentence;
- **68→69 = PENDING Part005 adjacent witness / deferred external boundary evidence**;
- Part005 is not supplied / registered;
- E15 must not infer, translate or import scan69 wording.

### Working Part004 English labels

- `முத்துநகை` → **Muthunagai**
- `மறவர் மானம்` → **The Warrior's Honour**
- `புலவர் மகள் புறப்பட்டாள்` → **The Poet's Daughter Sets Out**

These are project English labels. Verified Tamil section metadata remains authoritative.

### Planning integrity

This planning/setup activity changes English control metadata only.

- canonical Tamil changes caused by planning — **0**
- assembled Tamil changes caused by planning — **0**
- Parts001–003 English section changes — **0**
- E13/E14/E15 English draft files created in planning — **0**
- Part005 leakage — **0**
- unresolved planning holds — **0**

## Part004 E13 completion state

- E13 — **SOURCE-CHECKED / COMPLETE**
- E13 Tamil/English block accounting — **21/21 total; 18/18 rendered; 3/3 standalone provenance**
- E13 omitted / duplicated source blocks — **0 / 0**
- E13 unresolved source-check holds — **0**
- canonical Tamil edits caused by E13 — **0**
- assembled Tamil edits caused by E13 — **0**
- Parts001–003 English edits caused by E13 — **0**
- Part005 leakage — **0**
- durable source-check — `E13_SOURCE_CHECK.md`

## Part004 E14 completion state

- E13 — **SOURCE-CHECKED / COMPLETE**
- E14 — **SOURCE-CHECKED / COMPLETE**
- E15 — **RESERVED / NEXT**
- completed/source-checked — **2/3**
- E14 Tamil / English block accounting — **58/58 total; 51/51 rendered; 7/7 standalone provenance**
- E14 omitted / duplicated source blocks — **0 / 0**
- E14 unresolved source-check holds — **0**
- canonical / assembled Tamil edits caused by E14 — **0**
- Parts001–003 / E13 English edits caused by E14 — **0**
- Part005 leakage — **0**
- durable source-check — `E14_SOURCE_CHECK.md`

## Part004 E15 completion state

- E13–E15 — **SOURCE-CHECKED / COMPLETE — 3/3**
- E15 Tamil / English block accounting — **8/8 total; 6/6 rendered; 2/2 standalone provenance**
- E15 omitted / duplicated source blocks — **0 / 0**
- E15 unresolved source-check holds — **0**
- canonical / assembled Tamil edits caused by E15 — **0**
- Parts001–003 / E13–E14 English edits caused by E15 — **0**
- Part005 leakage — **0**
- durable source-check — `E15_SOURCE_CHECK.md`

## Part004 post-source-check state

- E13–E15 — **SOURCE-CHECKED / COMPLETE — 3/3**
- whole-Part glossary reconciliation — **RECONCILED / PASS**
- unresolved source-check holds — **0**
- unresolved glossary holds — **0**
- canonical / assembled Tamil edits caused by English — **0**
- Parts001–003 English edits — **0**
- Part005 leakage — **0**

## Part004 closed English review gates

- E13–E15 — **SOURCE-CHECKED / COMPLETE — 3/3**
- whole-Part glossary reconciliation — **RECONCILED / PASS**
- English editorial review — **PASS / CLOSED**
- editorial corrections — **2**
- whole-Part bilingual review — **PASS / CLOSED — 3/3**
- release/readiness — **PASS / CLOSED**
- release-ready synchronization — **PASS / CLOSED**
- unresolved English/release blockers — **0**
- canonical / assembled Tamil edits caused by English/release work — **0**
- Parts001–003 English edits — **0**
- Part005 leakage — **0**

## Part004 final lifecycle state

Part004 English is **FINAL CLOSED / FROZEN**.

- E13–E15 — **SOURCE-CHECKED / COMPLETE — 3/3**
- glossary reconciliation — **RECONCILED / PASS**
- English editorial review — **PASS / CLOSED**
- whole-Part bilingual review — **PASS / CLOSED — 3/3**
- release/readiness — **PASS / CLOSED**
- release-ready synchronization — **PASS / CLOSED**
- final closure — **PASS / CLOSED / FROZEN**
- unresolved blockers — **0**
- Part005 leakage — **0**

## Current exact English activity

**None until Part005 source intake authorizes the next Part.**


## Part005 planning/setup — COMPLETE / PASS

Parts001–004 remain **FINAL CLOSED / FROZEN** and are not reopened by this extension.

Part005 English prerequisites are closed:

- canonical Tamil — **17/17 verified**
- visual fidelity — **17/17 verified**
- Part audit — **PASS / COMPLETE**
- Tamil archival-ready — **PASS / CLOSED**
- assembled Tamil — **PASS / CLOSED — 2/2 VERIFIED**
- assembled physical coverage — **17/17 / scans69–85**
- publication-text coverage — **17/17**
- missing / duplicate coverage — **0 / 0**
- unsupported Tamil insertion — **0**
- Part006 leakage — **0**
- unresolved Tamil / lexical / historical-glyph / visual / structural blockers — **0**

Verified Part005 assembled inputs:

1. `../../sections/15-chapter-04-pulavar-magal-purappattaal-part005-continuation.md` — scans69–80
2. `../../sections/16-chapter-05-sivanadiyaar-thirukkoottam.md` — scans81–85

### Reserved Part005 English units

| Batch | Tamil input | Planned English file | Scans | Planning state |
|---|---|---|---:|---|
| **E16** | `../../sections/15-chapter-04-pulavar-magal-purappattaal-part005-continuation.md` | `sections/15-chapter-04-the-poets-daughter-sets-out-part005-continuation.md` | 69–80 | **SOURCE-CHECKED / COMPLETE** |
| **E17** | `../../sections/16-chapter-05-sivanadiyaar-thirukkoottam.md` | `sections/16-chapter-05-the-gathering-of-siva-devotees.md` | 81–85 | **SOURCE-CHECKED / COMPLETE** |

Batch discipline:

**E16 closes draft + source-check before E17 begins.**

A draft alone does not close a batch. Each batch requires a durable source-check record.

### Part005 translation safeguards

- incoming **68→69 = GENUINE CONTINUATION / AUDITED**;
- frozen Part004 E15 must not be backfilled or altered by E16;
- verified assembled Tamil joins and displayed-text boundaries remain authoritative;
- scan69 and scan79 displayed written material must remain structurally distinct where meaningful;
- scan81 is the illustrated Chapter 5 title page;
- scan84 contains displayed written material to the Siva devotees;
- outgoing **85→86 = PENDING Part006 adjacent witness / deferred external boundary evidence**;
- E17 must not infer, translate or import Part006 wording.

### Working Part005 English labels

- `புலவர் மகள் புறப்பட்டாள்` → **The Poet's Daughter Sets Out**
- `சிவனடியார் திருக்கூட்டம்` → **The Gathering of Siva Devotees**
- `தாமரை` → **Thamarai**
- `திருநீற்றடியார்` → **Thiruneettradiyar**
- `யவனக் கிழவர்` / `யவனக்கிழவர்` → **Yavana elder**
- `அன்பே சிவம்! பண்பே சைவம்!` → **Love is Siva! Virtue is Saivism!**

These are project English labels/choices. Verified Tamil section metadata remains authoritative.

### Planning integrity

- canonical Tamil changes caused by planning — **0**
- assembled Tamil changes caused by planning — **0**
- Parts001–004 English section changes — **0**
- E16/E17 English draft files created in planning — **0**
- Part006 leakage — **0**
- unresolved planning holds — **0**

## Current exact English activity

**E16 — draft + source-check Part005 Chapter 4 continuation / scans69–80.**

Do not begin E17 until E16 is **SOURCE-CHECKED / COMPLETE**.


## Part005 E16 completion state

- E16 — **SOURCE-CHECKED / COMPLETE**
- E17 — **RESERVED / NEXT**
- completed/source-checked — **1/2**
- E16 Tamil / English block accounting — **108/108 total; 101/101 rendered; 7/7 standalone provenance**
- source-boundary comments retained — **10/10**
- E16 omitted / duplicated source blocks — **0 / 0**
- unresolved E16 source-check holds — **0**
- canonical / assembled Tamil edits caused by E16 — **0**
- Parts001–004 English edits caused by E16 — **0**
- E17 draft created by E16 — **0**
- Part006 leakage — **0**
- durable source-check — `E16_SOURCE_CHECK.md`

## Current exact English activity

**E17 — draft + source-check Part005 Chapter 5 `சிவனடியார் திருக்கூட்டம்` / scans81–85.**


## Part005 E17 completion state

- E16–E17 — **SOURCE-CHECKED / COMPLETE — 2/2**
- completed/source-checked — **2/2**
- E17 Tamil / English block accounting — **31/31 total; 28/28 rendered; 3/3 standalone provenance**
- source-boundary comments retained — **4/4**
- outgoing-boundary comment retained — **1/1**
- E17 omitted / duplicated source blocks — **0 / 0**
- unresolved E17 source-check holds — **0**
- canonical / assembled Tamil edits caused by E17 — **0**
- Parts001–004 / E16 English edits caused by E17 — **0**
- Part006 leakage — **0**
- durable source-check — `E17_SOURCE_CHECK.md`

## Current exact English activity

**Part005 whole-Part glossary reconciliation across E16–E17.**


## Part005 post-source-check glossary state

- E16–E17 — **SOURCE-CHECKED / COMPLETE — 2/2**
- whole-Part glossary reconciliation — **RECONCILED / PASS**
- accidental recurring-term drift — **0**
- glossary-driven English section edits — **0**
- unresolved glossary holds — **0**
- canonical / assembled Tamil edits caused by glossary work — **0**
- Parts001–004 English edits — **0**
- Part006 leakage — **0**
- durable reconciliation record — `PART_005_GLOSSARY_RECONCILIATION.md`

## Current exact English activity

**Part005 English editorial review across E16–E17.**


## Part005 editorial-review closure

- E16–E17 — **SOURCE-CHECKED / COMPLETE — 2/2**
- whole-Part glossary reconciliation — **RECONCILED / PASS**
- English editorial review — **PASS / CLOSED**
- editorial corrections — **5**
- E16 / E17 corrections — **3 / 2**
- structural block counts changed — **0**
- provenance comments removed — **0**
- locked glossary decisions changed — **0**
- unresolved editorial holds — **0**
- canonical / assembled Tamil edits caused by editorial review — **0**
- Parts001–004 English edits — **0**
- Part006 leakage — **0**
- durable editorial record — `PART_005_TRANSLATION_REVIEW.md`

## Current exact English activity

**Part005 whole-Part bilingual review across the 2 Tamil/English section pairs.**


## Part005 bilingual-review closure

- E16–E17 — **SOURCE-CHECKED / COMPLETE — 2/2**
- whole-Part glossary reconciliation — **RECONCILED / PASS**
- English editorial review — **PASS / CLOSED**
- whole-Part bilingual review — **PASS / CLOSED — 2/2**
- editorial corrections — **5**
- bilingual-review corrections — **2**
- structural block parity retained — **139/139 total; 129/129 rendered**
- provenance block parity retained — **10/10**
- unresolved bilingual holds — **0**
- canonical / assembled Tamil edits caused by bilingual review — **0**
- Parts001–004 English edits — **0**
- Part006 leakage — **0**
- durable bilingual record — `PART_005_BILINGUAL_REVIEW.md`

## Current exact English activity

**Part005 release/readiness review and report.**


## Part005 release/readiness closure

- E16–E17 — **SOURCE-CHECKED / COMPLETE — 2/2**
- glossary reconciliation — **RECONCILED / PASS**
- English editorial review — **PASS / CLOSED**
- whole-Part bilingual review — **PASS / CLOSED — 2/2**
- release/readiness — **PASS / CLOSED**
- total structural parity — **139/139**
- total rendered parity — **129/129**
- provenance parity — **10/10**
- unresolved release/readiness blockers — **0**
- canonical / assembled Tamil edits caused by release review — **0**
- Parts001–004 English edits — **0**
- Part006 leakage — **0**
- durable release report — `PART_005_RELEASE_REPORT.md`

## Current exact English activity

**Part005 release-ready synchronization.**


## Part005 release-ready synchronization closure

- E16–E17 — **SOURCE-CHECKED / COMPLETE — 2/2**
- glossary reconciliation — **RECONCILED / PASS**
- English editorial review — **PASS / CLOSED**
- whole-Part bilingual review — **PASS / CLOSED — 2/2**
- release/readiness — **PASS / CLOSED**
- release-ready synchronization — **PASS / CLOSED**
- unresolved release-ready synchronization blockers — **0**
- canonical / assembled Tamil edits during synchronization — **0**
- maintained Part005 English body edits during synchronization — **0**
- frozen Parts001–004 English edits — **0**
- Part006 leakage — **0**

## Current exact English activity

**Part005 final closure / freeze.**


## Part005 final lifecycle closure

- E16–E17 — **SOURCE-CHECKED / COMPLETE — 2/2**
- glossary reconciliation — **RECONCILED / PASS**
- English editorial review — **PASS / CLOSED**
- whole-Part bilingual review — **PASS / CLOSED — 2/2**
- release/readiness — **PASS / CLOSED**
- release-ready synchronization — **PASS / CLOSED**
- final closure — **PASS / CLOSED / FROZEN**
- unresolved blockers — **0**
- canonical / assembled Tamil edits caused by final closure — **0**
- Parts001–004 English edits — **0**
- Part006 leakage — **0**

## Current exact English activity

**None until Part006 source intake authorizes the next Part.**

Repository frontier: **Part006 source intake + 85→86 adjacent-boundary witness inspection/setup.**

## Part006 planning/setup — COMPLETE / PASS

Parts001–005 remain **FINAL CLOSED / FROZEN** and are not reopened by this extension.

Part006 English prerequisites are closed:

- canonical Tamil — **17/17 verified**
- visual fidelity — **17/17 verified**
- Part audit — **PASS / COMPLETE**
- final metadata/status synchronization — **PASS / CLOSED**
- documentation synchronization — **PASS / COMPLETE**
- Tamil archival-ready — **PASS / CLOSED**
- assembled Tamil — **PASS / CLOSED — 2/2 VERIFIED**
- assembled physical coverage — **17/17 / scans86–102**
- publication-text coverage — **16/16 + blank scan94 provenance**
- missing / duplicate assembled coverage — **0 / 0**
- unsupported Tamil insertion — **0**
- Part005 body duplication — **0**
- Part007 leakage — **0**
- unresolved Tamil / lexical / historical-glyph / visual / structural / documentation blockers — **0**

Verified Part006 assembled inputs:

1. `../../sections/17-chapter-05-sivanadiyaar-thirukkoottam-part006-continuation.md` — scans86–94
2. `../../sections/18-chapter-06-viragu-vetti.md` — scans95–102

### Reserved Part006 English units

| Batch | Tamil input | Planned English file | Scans | Planning state |
|---|---|---|---:|---|
| **E18** | `../../sections/17-chapter-05-sivanadiyaar-thirukkoottam-part006-continuation.md` | `sections/17-chapter-05-the-gathering-of-siva-devotees-part006-continuation.md` | 86–94 | **SOURCE-CHECKED / COMPLETE** |
| **E19** | `../../sections/18-chapter-06-viragu-vetti.md` | `sections/18-chapter-06-the-woodcutter.md` | 95–102 | **RESERVED / NEXT** |

Batch discipline:

**E18 closes draft + source-check before E19 begins.**

A draft alone does not close a batch. Each batch requires a durable source-check record.

### Part006 translation safeguards

- incoming **85→86 = GENUINE CONTINUATION / AUDITED**;
- frozen Part005 E17 must not be backfilled or altered by E18;
- verified assembled Tamil joins and displayed-text boundaries remain authoritative;
- scan88 contains a displayed palm-leaf message/signature;
- scan94 is blank and carries provenance only, with no English body text;
- scan95 is the illustrated Chapter 6 title `விறகுவெட்டி`;
- scan101 contains displayed written palm-leaf text;
- outgoing **102→103 = PENDING Part007 adjacent witness / deferred external boundary evidence**;
- E19 must not infer, translate or import Part007 wording.

### Working Part006 English labels

- `சிவனடியார் திருக்கூட்டம்` → **The Gathering of Siva Devotees**
- `விறகுவெட்டி` → **The Woodcutter**
- `முத்துநகை` → **Muthunagai**
- `முத்து` → **Muthu**
- `செழியன்` → **Sezhiyan**
- `கரிகாலன்` → **Karikalan**
- `பெருவழுதி` / `பெருவழுதிப் பாண்டியன்` → **Peruvazhuthi / Peruvazhuthi Pandiyan**
- `காரிக்கண்ணனார்` → **Karikannanar**
- `இருங்கோவேள்` → **Irungovel**
- `தாமரை` → **Thamarai**
- `யவனக் கிழவர்` → **Yavana elder**
- `வீரன்` → **Veeran** when used as the source-given personal name/alias
- `பெருந்தேவி` → **Perunthevi**
- `வேளிர்குடி` → **Velir clan / Velir people**, by local syntax

These are project English labels/choices. Verified Tamil section metadata remains authoritative.

### Planning integrity

- canonical Tamil changes caused by planning — **0**
- assembled Tamil changes caused by planning — **0**
- Parts001–005 English section changes — **0**
- E18/E19 English draft files created in planning — **0**
- E18/E19 source-check records created in planning — **0**
- Part007 leakage — **0**
- unresolved planning holds — **0**
- durable planning control — `../../PART_006_ENGLISH_PLANNING_SETUP.md`

## Current exact English activity

**E18 — draft + source-check Part006 Chapter 5 `சிவனடியார் திருக்கூட்டம்` continuation / scans86–94.**

Do not begin E19 until E18 is **SOURCE-CHECKED / COMPLETE**.

## Part006 E18 completion state

- E18 — **SOURCE-CHECKED / COMPLETE**
- E19 — **RESERVED / NEXT**
- completed/source-checked — **1/2**
- E18 Tamil / English total blocks — **88 / 88**
- E18 Tamil / English rendered blocks — **80 / 80**
- standalone provenance comments — **8 / 8**
- source-boundary comments retained — **7 / 7**
- incoming-boundary comment retained — **1 / 1**
- blank scan94 provenance retained — **1 / 1**
- omitted / duplicated source blocks — **0 / 0**
- source-check corrections — **2**
- unresolved E18 source-check holds — **0**
- canonical / assembled Tamil edits caused by E18 — **0**
- Parts001–005 English edits caused by E18 — **0**
- E19 draft created by E18 — **0**
- Part007 leakage — **0**
- durable source-check — `E18_SOURCE_CHECK.md`

## Current exact English activity

**E19 — draft + source-check Part006 Chapter 6 `விறகுவெட்டி` / scans95–102.**
