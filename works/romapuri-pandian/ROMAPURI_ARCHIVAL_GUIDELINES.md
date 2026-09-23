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
- Part004 reserved English batches — **E13–E15**
- Part004 E13 — **SOURCE-CHECKED / COMPLETE**
- Part004 English drafted/source-checked — **1/3**
- Part004 unresolved English source-check holds — **0**
- Part004 unresolved English planning holds — **0**
- incoming 52→53 — **GENUINE CONTINUATION / AUDITED**
- outgoing 68→69 — **PENDING Part005 adjacent witness / deferred external boundary evidence**
- exact next gate — **E14 draft + source-check / scans57–66**
