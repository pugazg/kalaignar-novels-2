# ரோமாபுரிப் பாண்டியன் — Part-by-Part Archival Guidelines

## Controlling-source rule

The user-supplied split PDFs are the controlling source. Preserve source wording, punctuation, paragraphing, dialogue structure, historical glyph identity, printed pagination, illustrations, blank fields and page structure.

Rendered source pixels remain authoritative even when a PDF text layer exists.

## Multipart design

- complete source: **39 supplied split PDFs**
- original source size: approximately **1.85 GB** (user-reported)
- each supplied split: **<=50 MB**
- split basis: **file size**, so local page counts may vary
- Parts: **Part001–Part039** in supplied order
- total physical scan extent: **to be established by intake**
- canonical `scan_page`: global physical order across the whole work; never resets
- every page record carries exact `part`, `part_page`, `source_filename` and source-visible `printed_page` when present

Never infer equal Part sizes and never infer a Part's global range before inspecting that split.

## Mandatory Part lock

> **Finish the entire maintained workflow for the active Part before beginning canonical transcription of the next Part.**

A later Part may be opened only as an adjacent boundary witness when needed for direct split-boundary classification.

## Tamil Part workflow

1. **Source intake**
   - exact filename
   - bytes
   - SHA-256
   - local physical PDF page count
   - global scan start/end
   - archive/source identity where source-visible
   - text-layer availability
   - rendered-page authority
2. **Pass 1 — complete physical capture/transcription**
   - canonical page records for every physical scan in the active Part
   - source-visible text only
   - preserve printed pagination and page type
   - record source-reading holds explicitly
3. **Pass 2A — direct textual verification**
   - word-by-word text
   - punctuation
   - paragraph/dialogue structure
   - printed pagination
   - physical page boundary
4. **Pass 2B — independent lexical / historical-glyph reread**
   - word boundaries
   - spacing
   - punctuation-sensitive readings
   - historical Tamil glyph identity
   - no silent modernization
   - **batch cadence: 9 physical pages per iteration; only the final Pass2B iteration may contain fewer pages when the Part remainder is <9**
5. **Pass 3 — meaningful full-page visual / structural verification**
   - headings
   - chapter boundaries
   - illustrations
   - captions
   - blank lower fields
   - spreads
   - recurring furniture
   - page-type classification
6. **Part audit**
   - complete continuous scan coverage
   - no duplicate/missing canonical records
   - Pass evidence complete
   - printed-page mapping reconciled
   - boundaries reconciled
   - unresolved issues explicitly counted
7. **Final metadata/status synchronization**
   - only after the Part audit passes
   - promote `status` and `visual_fidelity` to `verified`
   - do not alter canonical Tamil merely to perform status promotion
8. **Documentation synchronization**
   - handover
   - work README
   - source intake
   - page map
   - progress/audit records
9. **Tamil archival-ready checkpoint**
   - canonical Tamil verified
   - visual fidelity verified
   - unresolved Tamil/glyph/visual/structural/documentation blockers = 0

Final `verified` status is assigned only after the whole-Part Tamil verification chain closes.

## Pass separation

- Pass 2A cannot begin until Pass 1 covers the full active Part.
- Pass 2B cannot begin until Pass 2A closes.
- Pass 3 cannot begin until Pass 2B closes.
- Part audit cannot begin until Pass 3 closes.
- Metadata promotion cannot occur before Part audit passes.
- Assembled Tamil cannot begin before Tamil archival-ready closes.
- English cannot begin before assembled Tamil closes.
- Final closure must occur before the next Part's canonical transcription begins.

Pass 1 may be executed in smaller scan batches for practical handling; the Part gate remains open until all physical scans in the Part are text-complete.

## Boundary rule

For each split boundary `N→N+1`:

- inspect only the two adjacent controlling source scans;
- classify the boundary from direct evidence, for example **CLEAN**, **GENUINE CONTINUATION**, or another source-supported structural state;
- do not reconstruct missing wording across the boundary;
- do not import next-Part body text into the active Part;
- preserve a durable boundary-audit record when the outgoing witness becomes available.

The final Part has no outgoing next-Part witness.

## Canonical page-record schema

Each canonical page record follows the Paayum Puli model:

```yaml
---
scan_page: <global physical scan>
part: <1-39>
part_page: <local physical page>
printed_page: <source-visible printed page or null>
work: "romapuri-pandian"
section: "<source-visible chapter/section label or structural description>"
page_type: "<body|title|contents|illustration|spread|other source-supported type>"
status: "needs-review"
visual_fidelity: "needs-review"
language: "ta"
source_filename: "<exact supplied PDF filename>"
transcription_method: "direct source-pixel transcription; <Part/Pass1 batch>"
---
```

Use `needs-review` through Pass 1, Pass 2A, Pass 2B, Pass 3 and Part audit. Promote only during final metadata/status synchronization after the audit passes.

## Assembled Tamil workflow

After Tamil archival-ready:

1. construct maintained section/chapter files from verified canonical `pages/` only;
2. audit exact canonical coverage;
3. missing coverage = 0;
4. duplicate coverage = 0;
5. unsupported Tamil insertion = 0;
6. audit-note leakage = 0;
7. canonical page mutations caused by assembly = 0;
8. next-Part body leakage = 0;
9. close assembled Tamil as **VERIFIED / PASS / CLOSED**.

Canonical `pages/` remains the controlling Tamil authority.

## English workflow

After assembled Tamil closes:

1. English translation planning/setup;
2. reserve sequential E-batches without collision;
3. create Part translation plan, glossary and progress controls;
4. draft and source-check each English batch sequentially;
5. each batch must become **SOURCE-CHECKED / COMPLETE** before the next batch;
6. whole-Part glossary reconciliation;
7. English editorial review;
8. whole-Part bilingual review against verified Tamil;
9. release/readiness report;
10. release-ready synchronization;
11. verify no unauthorized canonical/assembled/English textual drift;
12. final closure — **PASS / CLOSED / FROZEN**.

English work must not modify verified canonical Tamil. Occurrence-sensitive names, titles and historical/source variants must not be silently homogenized.

## Source-file policy

Source PDFs are controlling evidence but remain outside Git. Repository records store source provenance, hashes, mappings, transcriptions, audits and derived maintained text.

## Current frontier

- Part001 source — **REGISTERED / scans1–17**
- Part002 source — **REGISTERED / scans18–34 / FINAL CLOSED / FROZEN**
- Part001 canonical page records — **17/17**
- Part001 Pass1 — **COMPLETE / PASS — 17/17 TEXT-COMPLETE**
- Part001 Pass2A — **COMPLETE / PASS — 17/17 REVIEWED**
- Pass2A source-supported corrections — **19**
- Pass2A unresolved textual questions — **0**
- Part001 Pass2B — **COMPLETE / PASS — 17/17 REVIEWED**
- Pass2B source-text / lexical / spacing / punctuation corrections — **7**
- Pass2B historical-glyph corrections — **0**
- Pass2B unresolved lexical / historical-glyph questions — **0**
- Part001 Pass3 — **COMPLETE / PASS — 17/17 REVIEWED**
- Pass3 source-text corrections — **0**
- Pass3 structural metadata corrections — **7**
- Pass3 unresolved visual / structural questions — **0**
- Part001 Part audit — **PASS / COMPLETE**
- Part001 audit missing canonical pages — **0**
- Part001 audit duplicate canonical pages — **0**
- Part001 audit unresolved blockers — **0**
- Part001 final metadata/status synchronization — **PASS / CLOSED**
- Part001 status — **17/17 verified / 0 needs-review**
- Part001 visual_fidelity — **17/17 verified / 0 needs-review**
- Part001 documentation synchronization — **PASS / COMPLETE**
- Part001 Tamil archival-ready — **PASS / CLOSED**
- Part001 assembled Tamil — **PASS / CLOSED — 6/6 VERIFIED**
- Part001 English translation planning/setup — **COMPLETE / PASS**
- Part001 English E1–E6 — **SOURCE-CHECKED / COMPLETE — 6/6**
- Part001 glossary reconciliation — **RECONCILED / PASS**
- Part001 English editorial review — **PASS / CLOSED**
- Part001 bilingual review — **PASS / CLOSED**
- Part001 release/readiness — **PASS / CLOSED**
- Part001 release-ready synchronization — **PASS / CLOSED**
- Part001 final closure — **PASS / CLOSED / FROZEN**
- outgoing 17→18 — **GENUINE CONTINUATION / AUDITED**
- Part002 canonical records — **17/17 / scans18–34**
- Part002 Pass1 — **COMPLETE / PASS — 17/17 TEXT-COMPLETE**
- Part002 Pass1 unresolved holds — **0**
- Part002 Pass2A — **COMPLETE / PASS — 17/17 REVIEWED**
- Part002 Pass2A source-supported corrections — **16**
- Part002 Pass2A unresolved textual questions — **0**
- Part002 Pass2B — **COMPLETE / PASS — 17/17 REVIEWED**
- Part002 Pass2B cadence — **9 pages per iteration**
- Part002 Pass2B source-text / lexical / spacing / punctuation corrections — **5**
- Part002 Pass2B historical-glyph corrections — **0**
- Part002 Pass2B unresolved lexical/historical-glyph questions — **0**
- Part002 Pass3 — **COMPLETE / PASS — 17/17 REVIEWED**
- Part002 Pass3 source-text corrections — **0**
- Part002 Pass3 structural metadata corrections — **0**
- Part002 Pass3 unresolved visual / structural questions — **0**
- Part002 Part audit — **PASS / COMPLETE**
- Part002 audit canonical coverage — **17/17; 0 missing / 0 duplicate**
- Part002 audit supplied-Part blockers — **0**
- Part002 final metadata/status synchronization — **PASS / CLOSED**
- Part002 Tamil status — **17/17 verified / 0 needs-review**
- Part002 visual fidelity — **17/17 verified / 0 needs-review**
- Part002 documentation synchronization — **PASS / COMPLETE**
- Part002 Tamil archival-ready — **PASS / CLOSED**
- Part002 assembled Tamil — **PASS / CLOSED — 4/4 VERIFIED**
- Part002 English planning/setup — **COMPLETE / PASS**
- Part002 English E7–E10 — **SOURCE-CHECKED / COMPLETE — 4/4**
- Part002 glossary reconciliation — **RECONCILED / PASS**
- Part002 English editorial review — **PASS / CLOSED**
- Part002 bilingual review — **PASS / CLOSED**
- Part002 release/readiness — **PASS / CLOSED**
- Part002 release-ready synchronization — **PASS / CLOSED**
- Part002 final closure — **PASS / CLOSED / FROZEN**
- outgoing 34→35 witness — **GENUINE CONTINUATION / AUDITED**
- Part003 source — **REGISTERED / scans35–52 / AUTHORIZED**
- Part003 canonical records — **18/18 / scans35–52**
- Part003 Pass1 — **COMPLETE / PASS — 18/18 TEXT-COMPLETE**
- Part003 Pass2A — **COMPLETE / PASS — 18/18 REVIEWED**
- Part003 Pass2A corrections — **5**
- Part003 Pass2A unresolved textual questions — **0**
- Part003 Pass2B — **COMPLETE / PASS — 18/18 REVIEWED**
- Part003 Pass2B Batch 1 — **COMPLETE / PASS — scans35–43 / local1–9**
- Part003 Pass2B Batch 2 — **COMPLETE / PASS — scans44–52 / local10–18**
- Part003 Pass2B corrections — **3**
- Part003 Pass2B historical-glyph corrections — **0**
- Part003 Pass2B unresolved lexical / historical-glyph questions — **0**
- Part003 Pass3 — **COMPLETE / PASS — 18/18 REVIEWED**
- Part003 Pass3 source-text corrections — **0**
- Part003 Pass3 structural metadata corrections — **0**
- Part003 Pass3 unresolved visual / structural questions — **0**
- Part003 Part audit — **PASS / COMPLETE**
- Part003 audit canonical coverage — **18/18 / scans35–52 / local1–18**
- Part003 audit missing / duplicate records — **0 / 0**
- Part003 audit supplied-Part blockers — **0**
- Part003 final metadata/status synchronization — **PASS / CLOSED**
- Part003 Tamil status — **18/18 verified / 0 needs-review**
- Part003 visual fidelity — **18/18 verified / 0 needs-review**
- Part003 status exceptions — **0**
- Part003 documentation synchronization — **PASS / COMPLETE**
- Part003 Tamil archival-ready — **PASS / CLOSED**
- Part003 assembled Tamil — **PASS / CLOSED — 2/2 VERIFIED**
- Part003 assembled Tamil coverage — **18/18 physical scans / 17/17 publication-text pages + blank scan44 provenance**
- Part003 assembled Tamil validation blockers — **0**
- Part003 English translation planning/setup — **COMPLETE / PASS**
- Part003 English E11–E12 — **SOURCE-CHECKED / COMPLETE — 2/2**
- Part003 glossary reconciliation — **RECONCILED / PASS**
- Part003 English editorial review — **PASS / CLOSED**
- Part003 bilingual review — **PASS / CLOSED**
- Part003 release/readiness — **PASS / CLOSED**
- Part003 release-ready synchronization — **PASS / CLOSED**
- Part003 final closure — **PASS / CLOSED / FROZEN**
- Part003 Pass1 Batch 1 — **COMPLETE / scans35–44 / local1–10**
- Part003 Pass1 Batch 2 — **COMPLETE / scans45–52 / local11–18**
- Part003 Pass1 unresolved holds — **0**
- Part004 source — **REGISTERED / scans53–68 / AUTHORIZED**
- Part004 canonical records — **16/16 / scans53–68**
- Part004 Pass1 — **COMPLETE / PASS — 16/16 TEXT-COMPLETE**
- Part004 Pass1 unresolved holds — **0**
- Part004 Pass2A — **COMPLETE / PASS — 16/16 REVIEWED**
- Part004 Pass2A source-supported corrections — **4**
- Part004 Pass2A unresolved textual questions — **0**
- Part004 Pass2B — **COMPLETE / PASS — 16/16 REVIEWED**
- Part004 Pass2B Batch 1 — **COMPLETE / PASS — scans53–61 / local1–9**
- Part004 Pass2B Batch 2 — **COMPLETE / PASS — scans62–68 / local10–16**
- Part004 Pass2B corrections — **1**
- Part004 Pass2B historical-glyph corrections — **0**
- Part004 Pass2B unresolved lexical / historical-glyph questions — **0**
- Part004 Pass3 — **COMPLETE / PASS — 16/16 REVIEWED**
- Part004 Pass3 source-text corrections — **0**
- Part004 Pass3 structural metadata corrections — **0**
- Part004 Pass3 unresolved visual / structural questions — **0**
- Part004 Part audit — **PASS / COMPLETE — 16/16 canonical / 0 missing / 0 duplicate / 0 supplied-Part blockers**
- Part004 audit unresolved blockers — **0**
- Part004 final metadata/status synchronization — **PASS / CLOSED**
- Part004 Tamil status — **16/16 verified / 0 needs-review**
- Part004 visual fidelity — **16/16 verified / 0 needs-review**
- Part004 documentation synchronization — **PASS / COMPLETE**
- Part004 Tamil archival-ready — **PASS / CLOSED**
- Part004 assembled Tamil — **PASS / CLOSED — 3/3 VERIFIED**
- Part004 assembled Tamil coverage — **16/16 physical scans / 14/14 publication-text pages + blank scans56 and 66 provenance**
- Part004 assembled Tamil validation blockers — **0**
- Part004 English translation planning/setup — **COMPLETE / PASS**
- Part004 English E13–E15 — **SOURCE-CHECKED / COMPLETE — 3/3**
- Part004 glossary reconciliation — **RECONCILED / PASS**
- Part004 English editorial review — **PASS / CLOSED / 2 corrections**
- Part004 bilingual review — **PASS / CLOSED — 3/3**
- Part004 release/readiness — **PASS / CLOSED**
- Part004 release-ready synchronization — **PASS / CLOSED**
- Part004 final closure — **PASS / CLOSED / FROZEN**
- Part004 unresolved English/release blockers — **0**
- incoming 52→53 — **GENUINE CONTINUATION / AUDITED**
- outgoing 68→69 — **GENUINE CONTINUATION / AUDITED**
- Part005 source — **REGISTERED / scans69–85 / AUTHORIZED**
- Part005 intake + incoming boundary setup — **PASS / COMPLETE**
- Part005 canonical records — **17/17 — scans69–85**
- Part005 Pass1 — **COMPLETE / PASS — 17/17 TEXT-COMPLETE**
- Part005 Pass1 Batch 1 — **COMPLETE / PASS — scans69–78 / local1–10**
- Part005 Pass1 Batch 2 — **COMPLETE / PASS — scans79–85 / local11–17**
- Part005 unresolved Pass1 holds — **0**
- Part005 Pass2A cadence — **9 physical pages per iteration; only final remainder may contain fewer**
- Part005 Pass2A — **COMPLETE / PASS — 17/17 REVIEWED**
- Part005 Pass2A Batch 1 — **COMPLETE / PASS — scans69–77 / local1–9**
- Part005 Pass2A Batch 2 — **COMPLETE / PASS — scans78–85 / local10–17**
- Part005 Pass2A corrections — **4 / 0 unresolved**
- Part005 Pass2B cadence — **9 pages per iteration; final remainder may contain fewer**
- Part005 Pass2B — **COMPLETE / PASS — 17/17 REVIEWED**
- Part005 Pass2B Batch 1 — **COMPLETE / PASS — scans69–77 / local1–9**
- Part005 Pass2B Batch 2 — **COMPLETE / PASS — scans78–85 / local10–17**
- Part005 Pass2B source-text/lexical/spacing/punctuation corrections — **0**
- Part005 Pass2B historical-glyph corrections — **0**
- Part005 Pass2B unresolved lexical/historical-glyph questions — **0**
- Part005 Pass3 — **COMPLETE / PASS — 17/17 REVIEWED**
- Part005 Pass3 source-text corrections — **0**
- Part005 Pass3 structural metadata corrections — **0**
- Part005 Pass3 unresolved visual/structural questions — **0**
- Part005 Part audit — **PASS / COMPLETE**
- Part005 audit unresolved blockers — **0**
- Part005 final metadata/status synchronization — **PASS / CLOSED**
- Part005 Tamil status — **17/17 verified / 0 needs-review**
- Part005 visual fidelity — **17/17 verified / 0 needs-review**
- Part005 unresolved status exceptions — **0**
- Part005 documentation synchronization — **COMPLETE / PASS**
- Part005 Tamil archival-ready — **PASS / CLOSED**
- Part005 assembled Tamil — **PASS / CLOSED — 2/2 VERIFIED**
- Part005 assembled Tamil validation blockers — **0**
- Part005 outgoing 85→86 — **PENDING Part006 adjacent witness / deferred external boundary evidence**
- Part005 unresolved intake/boundary blockers — **0**
- exact next gate — **Part005 English translation planning/setup**


## Part005 downstream English / release state

Part005 assembled Tamil remains **PASS / CLOSED — 2/2 VERIFIED**.

Downstream English/release gates:

- E16–E17 — **SOURCE-CHECKED / COMPLETE — 2/2**
- glossary reconciliation — **RECONCILED / PASS**
- English editorial review — **PASS / CLOSED**
- whole-Part bilingual review — **PASS / CLOSED — 2/2**
- release/readiness — **PASS / CLOSED**
- release-ready synchronization — **PASS / CLOSED**
- unresolved blockers — **0**
- Part006 leakage — **0**

Current frontier:

**Part005 final closure / freeze.**


## Part005 final frozen state

Part005 is **FINAL CLOSED / FROZEN**.

- assembled Tamil — **PASS / CLOSED — 2/2 VERIFIED**
- E16–E17 — **SOURCE-CHECKED / COMPLETE — 2/2**
- glossary reconciliation — **RECONCILED / PASS**
- editorial review — **PASS / CLOSED**
- bilingual review — **PASS / CLOSED — 2/2**
- release/readiness — **PASS / CLOSED**
- release-ready synchronization — **PASS / CLOSED**
- final closure — **PASS / CLOSED / FROZEN**
- unresolved blockers — **0**
- Part006 leakage — **0**

Part006 is **NOT SUPPLIED / NOT REGISTERED**.

Current frontier:

**Part006 source intake + 85→86 adjacent-boundary witness inspection/setup.**


## Part006 intake / boundary state

Part006 source is now **REGISTERED / AUTHORIZED**.

- physical extent — **17 pages / scans86–102**
- incoming **85→86 — GENUINE CONTINUATION / AUDITED**
- frozen Part005 body imported into Part006 — **0**
- Part006 body imported backward into frozen Part005 — **0**
- scan94 — blank separator page
- scan95 — illustrated Chapter 6 title `விறகுவெட்டி`
- outgoing **102→103 — PENDING Part007 adjacent witness / deferred external boundary evidence**
- unresolved intake/boundary blockers — **0**

## Part006 Pass1 cadence

- fixed cadence — **10 physical pages per iteration**
- Batch 1 — **scans86–95 / local1–10**
- Batch 2 — **scans96–102 / local11–17 — final 7-page remainder**

Current frontier:

**Part006 Pass1 Batch 1 — scans86–95 / local1–10.**


## Part006 Pass1 Batch1 progress

- Batch 1 — **COMPLETE / PASS / TEXT-COMPLETE**
- scans — **86–95**
- local pages — **1–10**
- canonical records — **10/17**
- text-bearing physical pages — **9/10**
- blank physical pages — **1/10**
- scan94 — blank separator
- scan95 — Chapter 6 title `விறகுவெட்டி`
- unresolved source-reading holds — **0**
- status / visual-fidelity promotions — **0**
- frozen Parts001–005 mutations — **0**

Pass1 remains open.

Current frontier:

**Part006 Pass1 Batch 2 — scans96–102 / local11–17 — final 7-page remainder.**


## Part006 Pass1 closure

Part006 Pass1 is **COMPLETE / PASS — 17/17 TEXT-COMPLETE**.

- Batch 1 — **scans86–95 / local1–10**
- Batch 2 — **scans96–102 / local11–17**
- canonical records — **17/17**
- text-bearing pages — **16/17**
- blank physical page — **scan94**
- Chapter 6 title — **scan95 / `விறகுவெட்டி`**
- source-supported Pass1 corrections — **1**
- unresolved Pass1 source-reading holds — **0**
- status / visual-fidelity promotions — **0**
- frozen Parts001–005 mutations — **0**
- outgoing 102→103 — **PENDING Part007 adjacent witness**

Pass2A is now unblocked.

Current frontier:

**Part006 Pass2A — scans86–102 / local1–17.**

## Part006 Pass2A closure

- Part006 Pass2A — **COMPLETE / PASS — 17/17 REVIEWED**
- source-supported corrections — **6**
- pages with corrections — **5**
- clean pages — **12**
- unresolved textual questions — **0**
- printed-page mapping corrections — **0**
- physical-boundary / continuation corrections — **0**
- status promotions — **0**
- all 17 Part006 records remain `status: "needs-review"` / `visual_fidelity: "needs-review"`
- outgoing 102→103 — **PENDING Part007 adjacent witness / deferred external boundary evidence**
- Part007 text inferred/imported — **0**
- frozen Parts001–005 canonical/body mutations — **0**
- durable control — `PART_006_PASS2A_PROGRESS.md`

Pass2B is unblocked but has **not** been started.

Current frontier:

**Part006 Pass2B Batch 1 — scans86–94 / local1–9.**

## Part006 Pass2B Batch1 progress

- Batch 1 — **COMPLETE / PASS — scans86–94 / local1–9**
- whole-Part Pass2B reviewed — **9/17**
- source-text / lexical / spacing / punctuation corrections — **4**
- historical-glyph / historical-orthography corrections — **1**
- total source-supported corrections — **5**
- pages with corrections — **3**
- clean pages — **6**
- unresolved lexical / historical-glyph questions — **0**
- status promotions — **0**
- all Part006 canonical records remain `status: "needs-review"` / `visual_fidelity: "needs-review"`
- outgoing 102→103 — **PENDING Part007 adjacent witness / deferred external boundary evidence**
- Part007 / scan103 text inferred or imported — **0**
- frozen Parts001–005 canonical/body mutations — **0**
- durable control — `PART_006_PASS2B_PROGRESS.md`

Pass2B remains open.

Current frontier:

**Part006 Pass2B Batch 2 — scans95–102 / local10–17 — final 8-page remainder.**

## Part006 Pass2B closure

- Part006 Pass2B — **COMPLETE / PASS — 17/17 REVIEWED**
- Batch 1 — **COMPLETE / PASS — scans86–94 / local1–9**
- Batch 2 — **COMPLETE / PASS — scans95–102 / local10–17**
- source-text / lexical / spacing / punctuation corrections — **5**
- historical-glyph / historical-orthography corrections — **1**
- total source-supported corrections — **6**
- pages with corrections — **4**
- clean pages — **13**
- unresolved lexical / historical-glyph questions — **0**
- status promotions — **0**
- all 17 Part006 records remain `status: "needs-review"` / `visual_fidelity: "needs-review"`
- outgoing 102→103 — **PENDING Part007 adjacent witness / deferred external boundary evidence**
- Part007 / scan103 text inferred or imported — **0**
- frozen Parts001–005 canonical/body mutations — **0**
- durable control — `PART_006_PASS2B_PROGRESS.md`

Pass3 is now unblocked but has **not** been started.

Current frontier:

**Part006 Pass3 — scans86–102 / local1–17.**

## Part006 Pass3 closure

- Part006 Pass3 — **COMPLETE / PASS — 17/17 REVIEWED**
- source-text corrections at Pass3 — **0**
- structural metadata corrections at Pass3 — **0**
- unresolved visual / structural questions — **0**
- status promotions — **0**
- page-type mapping — **CONFIRMED / 17/17**
- printed-page mapping — **CONFIRMED / 14 source-visible numerals + 3 null-page exceptions**
- scan94 blank separator — **CONFIRMED**
- scan95 illustrated Chapter 6 title `6 / விறகுவெட்டி` — **CONFIRMED**
- scan96 chapter-opening blank-upper-field structure — **CONFIRMED**
- running-header alternation — **CONFIRMED**
- internal continuations 87→88, 96→97 and 99→100 — **CONFIRMED**
- outgoing 102→103 — **PENDING Part007 adjacent witness / deferred external boundary evidence**
- Part007 / scan103 text inferred or imported — **0**
- frozen Parts001–005 canonical/body mutations — **0**
- durable control — `PART_006_PASS3_PROGRESS.md`

All 17 Part006 canonical records remain `status: "needs-review"` / `visual_fidelity: "needs-review"`.

Current frontier:

**Part006 Part audit.**

## Part006 Part-audit closure

- Part006 Part audit — **PASS / COMPLETE**
- canonical records — **17/17**
- global scan coverage — **continuous 86–102**
- local-page coverage — **continuous 1–17**
- missing / duplicate canonical records — **0 / 0**
- exact source filename consistency — **17/17**
- pagination mismatches — **0**
- page-type / section mismatches — **0**
- Pass1 / Pass2A / Pass2B / Pass3 evidence gaps — **0**
- unresolved supplied-Part blockers — **0**
- outgoing 102→103 — **PENDING Part007 adjacent witness / deferred external boundary evidence**
- Part007 / scan103 leakage — **0**
- frozen Parts001–005 canonical/body mutations — **0**
- status promotions during audit — **0**
- durable control — `PART_006_AUDIT.md`

All 17 Part006 records remain `status: "needs-review"` / `visual_fidelity: "needs-review"`.

Current frontier:

**Part006 final metadata/status synchronization.**

## Part006 documentation synchronization

- Part006 documentation synchronization — **PASS / COMPLETE**
- source intake + incoming-boundary setup — **PASS / COMPLETE**
- Pass1 — **COMPLETE / PASS — 17/17**
- Pass2A — **COMPLETE / PASS — 17/17**
- Pass2B — **COMPLETE / PASS — 17/17**
- Pass3 — **COMPLETE / PASS — 17/17**
- Part audit — **PASS / COMPLETE**
- final metadata/status synchronization — **PASS / CLOSED**
- Tamil textual status — **17/17 verified / 0 needs-review**
- visual fidelity — **17/17 verified / 0 needs-review**
- unresolved status exceptions — **0**
- unresolved Tamil / lexical / historical-glyph / visual / structural blockers — **0**
- documentation-sync canonical page changes — **0**
- incoming 85→86 — **GENUINE CONTINUATION / AUDITED**
- outgoing 102→103 — **PENDING Part007 adjacent witness / deferred external boundary evidence**
- Part007 / scan103 leakage — **0**
- frozen Parts001–005 canonical/body mutations — **0**
- durable control — `PART_006_DOCUMENTATION_SYNC.md`
- Tamil archival-ready checkpoint — **NEXT GATE**

Current frontier:

**Part006 Tamil archival-ready checkpoint.**

Do not construct assembled Tamil until the Tamil archival-ready checkpoint closes.

## Part006 Tamil archival-ready closure

- Part006 Tamil archival-ready checkpoint — **PASS / CLOSED**
- canonical Part006 records — **17/17 verified**
- Tamil textual status — **17/17 verified / 0 needs-review**
- visual fidelity — **17/17 verified / 0 needs-review**
- unresolved status exceptions — **0**
- unresolved Tamil / lexical / historical-glyph / visual / structural / documentation blockers — **0**
- unresolved supplied-Part boundary blockers — **0**
- incoming 85→86 — **GENUINE CONTINUATION / AUDITED**
- outgoing 102→103 — **PENDING Part007 adjacent witness / deferred external boundary evidence**
- Part007 / scan103 leakage — **0**
- assembled Part006 section files introduced before archival-ready closure — **0**
- English Part006 section files introduced before archival-ready closure — **0**
- frozen Parts001–005 canonical/body mutations — **0**
- durable control — `PART_006_TAMIL_ARCHIVAL_READY.md`

Current frontier:

**Part006 assembled Tamil construction + audit.**

Canonical `pages/` remains authoritative. Do not begin English until assembled Tamil closes.

## Part006 assembled Tamil closure

- Part006 Tamil archival-ready — **PASS / CLOSED**
- Part006 assembled Tamil — **PASS / CLOSED — 2/2 VERIFIED**
- assembled section 17 — **Chapter 5 continuation / scans86–94**
- assembled section 18 — **Chapter 6 `விறகுவெட்டி` / scans95–102**
- physical scan coverage — **17/17 / scans86–102**
- publication-text coverage — **16/16 + blank scan94 provenance**
- missing / duplicate coverage — **0 / 0**
- unsupported Tamil insertion — **0**
- audit-note leakage — **0**
- canonical page mutations caused by assembly — **0**
- Part005 body duplication — **0**
- Part007 / scan103 leakage — **0**
- durable control — `PART_006_ASSEMBLED_TAMIL_VALIDATION.md`

Current frontier:

**Part006 English translation planning/setup.**

Do not alter verified canonical or assembled Tamil during English planning.

## Part006 release-ready synchronization closure

- release/readiness — **PASS / CLOSED**
- release-ready synchronization — **PASS / CLOSED**
- canonical Tamil — **17/17 verified**
- visual fidelity — **17/17 verified**
- assembled Tamil — **PASS / CLOSED — 2/2 VERIFIED**
- E18–E19 source-check — **SOURCE-CHECKED / COMPLETE — 2/2**
- glossary reconciliation — **RECONCILED / PASS**
- English editorial review — **PASS / CLOSED**
- whole-Part bilingual review — **PASS / CLOSED — 2/2 PAIRS**
- structural parity — **159/159 total; 145/145 rendered; 14/14 provenance**
- unresolved release/readiness blockers — **0**
- unresolved release-ready synchronization blockers — **0**
- canonical page changes during synchronization — **0**
- assembled Tamil body changes during synchronization — **0**
- maintained Part006 English body changes during synchronization — **0**
- frozen Parts001–005 English changes — **0**
- incoming 85→86 — **GENUINE CONTINUATION / AUDITED**
- outgoing 102→103 — **PENDING Part007 adjacent witness / deferred external boundary evidence**
- Part007 / scan103 leakage — **0**
- active Git PDF paths — **0**
- durable control — `PART_006_RELEASE_READY_SYNC.md`

Current frontier:

**Part006 final closure / freeze.**

## Part006 final closure / freeze

- Part006 final closure — **PASS / CLOSED / FROZEN**
- canonical Tamil — **17/17 verified**
- visual fidelity — **17/17 verified**
- assembled Tamil — **PASS / CLOSED — 2/2 VERIFIED**
- E18–E19 source-check — **SOURCE-CHECKED / COMPLETE — 2/2**
- glossary reconciliation — **RECONCILED / PASS**
- English editorial review — **PASS / CLOSED**
- whole-Part bilingual review — **PASS / CLOSED — 2/2 PAIRS**
- release/readiness — **PASS / CLOSED**
- release-ready synchronization — **PASS / CLOSED**
- final unresolved blockers — **0**
- canonical page changes caused by final closure — **0**
- assembled Tamil body changes caused by final closure — **0**
- maintained Part006 English body changes caused by final closure — **0**
- frozen Parts001–005 changes — **0**
- incoming 85→86 — **GENUINE CONTINUATION / AUDITED**
- outgoing 102→103 — **PENDING Part007 adjacent witness / deferred external boundary evidence**
- Part007 source — **NOT SUPPLIED / NOT REGISTERED**
- Part007 / scan103 leakage — **0**
- active Git PDF paths — **0**
- durable control — `PART_006_FINAL_CLOSURE.md`

Current frontier:

**Part007 source intake + 102→103 adjacent-boundary witness inspection/setup when the Part007 source is supplied.**

Do not infer scan103 or begin Part007 canonical transcription without the supplied source.

## Part007 intake / boundary state

Part007 source is now **REGISTERED / AUTHORIZED**.

- physical extent — **16 pages / scans103–118**
- incoming **102→103 — GENUINE CONTINUATION / AUDITED**
- frozen Part006 body imported into Part007 — **0**
- Part007 body imported backward into frozen Part006 — **0**
- scans103–104 — Chapter 6 continuation
- scan105 — illustrated Chapter 7 title `7 / தத்தளித்த தாமரை`
- scan106 — Chapter 7 opening page
- scans107–117 — Chapter 7 narrative
- scan118 — blank physical page
- outgoing **118→119 — PENDING Part008 adjacent witness / deferred external boundary evidence**
- unresolved intake/boundary blockers — **0**

## Part007 Pass1 cadence

- fixed cadence — **10 physical pages per iteration**
- Batch 1 — **scans103–112 / local1–10**
- Batch 2 — **scans113–118 / local11–16 — final 6-page remainder**

Current frontier:

**Part007 Pass1 Batch 1 — scans103–112 / local1–10.**

## Part007 Pass1 Batch1 progress

- Batch1 — **COMPLETE / PASS / TEXT-COMPLETE — scans103–112 / local1–10**
- canonical Part007 records — **10/16**
- whole-Part Pass1 — **10/16**
- unresolved Pass1 source-reading holds — **0**
- status promotions — **0**
- visual-fidelity promotions — **0**
- frozen Parts001–006 canonical/body mutations — **0**
- scan112→113 — **physical sentence continuation witnessed**
- scan113 body imported into Batch1 — **0**
- outgoing 118→119 — **PENDING Part008 adjacent witness / deferred external boundary evidence**
- Part008 / scan119 text inferred — **0**
- durable control — `PART_007_PASS1_PROGRESS.md`

Current frontier:

**Part007 Pass1 Batch 2 — scans113–118 / local11–16 — final 6-page remainder.**

## Part007 Pass1 closure

- Pass1 Batch1 — **COMPLETE / PASS / TEXT-COMPLETE — scans103–112 / local1–10**
- Pass1 Batch2 — **COMPLETE / PASS / TEXT-COMPLETE — scans113–118 / local11–16**
- whole-Part Pass1 — **COMPLETE / PASS — 16/16 TEXT-COMPLETE**
- canonical Part007 records — **16/16**
- text-bearing physical pages — **15/16**
- blank physical pages — **1/16 — scan118**
- unresolved Pass1 source-reading holds — **0**
- status promotions — **0**
- visual-fidelity promotions — **0**
- all Part007 records remain `status: "needs-review"` / `visual_fidelity: "needs-review"`
- frozen Parts001–006 canonical/body mutations — **0**
- scan116→117 continuation — **CONFIRMED**
- outgoing 118→119 — **PENDING Part008 adjacent witness / deferred external boundary evidence**
- Part008 / scan119 text inferred — **0**
- durable control — `PART_007_PASS1_PROGRESS.md`

Current frontier:

**Part007 Pass2A — scans103–118 / local1–16.**

## Part007 Pass2A closure

- result — **COMPLETE / PASS — 16/16 REVIEWED**
- source-supported corrections — **9**
- pages with corrections — **8**
- clean pages — **8**
- unresolved textual questions — **0**
- printed-page mapping corrections — **0**
- page-type / section corrections — **0**
- page-boundary / continuation corrections — **0**
- status promotions — **0**
- visual-fidelity promotions — **0**
- all 16 records remain `status: "needs-review"` / `visual_fidelity: "needs-review"`
- frozen Parts001–006 canonical/body mutations — **0**
- outgoing 118→119 — **PENDING Part008 adjacent witness / deferred external boundary evidence**
- Part008 / scan119 text inferred — **0**
- durable control — `PART_007_PASS2A_PROGRESS.md`

Current frontier:

**Part007 Pass2B Batch 1 — scans103–111 / local1–9.**


## Part007 closed verification + documentation state

- Part007 Pass1 — **COMPLETE / PASS — 16/16**
- Part007 Pass2A — **COMPLETE / PASS — 16/16 / 9 corrections / 0 unresolved**
- Part007 Pass2B — **COMPLETE / PASS — 16/16 / 0 corrections / 0 unresolved**
- Part007 Pass3 — **COMPLETE / PASS — 16/16 / 0 text / 0 structural corrections**
- Part007 Part audit — **PASS / COMPLETE**
- Part007 final metadata/status synchronization — **PASS / CLOSED**
- Part007 Tamil textual status — **16/16 verified / 0 needs-review**
- Part007 visual fidelity — **16/16 verified / 0 needs-review**
- Part007 documentation synchronization — **PASS / COMPLETE**
- documentation-sync canonical page changes — **0**
- incoming 102→103 — **GENUINE CONTINUATION / AUDITED**
- outgoing 118→119 — **PENDING Part008 adjacent witness / deferred external boundary evidence**
- Part008 / scan119 leakage — **0**
- durable control — `PART_007_DOCUMENTATION_SYNC.md`

Current frontier:

**Part007 Tamil archival-ready checkpoint.**

Canonical `pages/` remains authoritative. Do not construct assembled Tamil until the Tamil archival-ready checkpoint closes.
