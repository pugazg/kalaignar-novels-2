# NEXT CHAT PROMPT — ரோமாபுரிப் பாண்டியன் / Part002 English translation planning/setup

Continue directly in `pugazg/kalaignar-novels-2`, branch `main`, active work `works/romapuri-pandian/`. **LIVE MAIN IS AUTHORITATIVE.**

Do not rely on this handoff over live repository state if they differ. Read the current control files first and continue only from the actual live frontier.

## Read first

1. `HANDOVER.md`
2. `works/romapuri-pandian/README.md`
3. `works/romapuri-pandian/ROMAPURI_ARCHIVAL_GUIDELINES.md`
4. `works/romapuri-pandian/PART_002_TAMIL_ARCHIVAL_READY.md`
5. `works/romapuri-pandian/PART_002_ASSEMBLED_TAMIL_VALIDATION.md`
6. `works/romapuri-pandian/sections/README.md`
7. `works/romapuri-pandian/translations/en/TRANSLATION_PLAN.md`
8. `works/romapuri-pandian/translations/en/GLOSSARY.md`
9. `works/romapuri-pandian/translations/en/PROGRESS.md`
10. `works/romapuri-pandian/translations/en/sections/README.md`

## Durable release state

### Part001

Part001 / scans **1–17** is **FINAL CLOSED / FROZEN**.

- canonical Tamil — **17/17 verified**
- visual fidelity — **17/17 verified**
- Tamil archival-ready — **PASS / CLOSED**
- assembled Tamil — **PASS / CLOSED — 6/6 VERIFIED**
- English E1–E6 — **SOURCE-CHECKED / COMPLETE**
- glossary reconciliation — **RECONCILED / PASS**
- editorial review — **PASS / CLOSED**
- bilingual review — **PASS / CLOSED**
- release/readiness — **PASS / CLOSED**
- release-ready synchronization — **PASS / CLOSED**
- final closure — **PASS / CLOSED / FROZEN**

Do not reopen Part001 for stylistic polishing.

### Part002

Controlling source:

`TVA_BOK_0065553_ரோமாபுரிப்_பாண்டியன்_part_002_pages_18-34.pdf`

Source identity:

- local pages — **17**
- global scans — **18–34**
- SHA-256 — `0be5e57ed61405a39b18276db7184652ded8d401a18114caa3c9c039917a7dc0`

Closed Tamil state:

- canonical records — **17/17**
- Pass1 — **COMPLETE / PASS — 17/17**
- Pass2A — **COMPLETE / PASS — 17/17 / 16 corrections / 0 unresolved**
- Pass2B — **COMPLETE / PASS — 17/17 / 5 corrections / 0 historical-glyph corrections / 0 unresolved**
- Pass3 — **COMPLETE / PASS — 17/17 / 0 text corrections / 0 structural corrections / 0 unresolved**
- Part audit — **PASS / COMPLETE**
- final metadata/status synchronization — **PASS / CLOSED**
- canonical Tamil — **17/17 verified / 0 needs-review**
- visual fidelity — **17/17 verified / 0 needs-review**
- documentation synchronization — **PASS / COMPLETE**
- Tamil archival-ready — **PASS / CLOSED**
- assembled Tamil — **PASS / CLOSED — 4/4 VERIFIED**
- Part003 leakage — **0**

## Verified Part002 assembled Tamil units

The maintained Part002 reading layer is:

1. `sections/06-ananthanarayanan-paarattu-urai-part002-continuation.md` — scan **18**
2. `sections/07-kaviyarasu-kannadasan-urai.md` — scans **19–22**
3. `sections/08-arimugam.md` — scans **23–28**
4. `sections/09-chapter-01-karikaar-chozhanum-peruvazhuthi-pandiyanum.md` — scans **29–34**

Assembly validation is **PASS / CLOSED** with:

- represented physical scans — **17/17**
- omitted publication-text pages — **0**
- duplicate publication-text pages — **0**
- unsupported Tamil insertion — **0**
- audit-note leakage — **0**
- canonical page mutations caused by assembly — **0**
- Part003 leakage — **0**

Verified split-word joins in the assembled layer:

- scan25→26 — `கொண்டா` + `னாம்.` → **`கொண்டானாம்.`**
- scan33→34 — `முத்` + `தாரத்தையெடுத்து` → **`முத்தாரத்தையெடுத்து`**

Do not reinterpret these joins.

## Boundary locks

Incoming:

- **17→18 — GENUINE CONTINUATION / AUDITED**
- Part001 English remains frozen and deliberately ends incomplete.
- Part002 English may translate scan18 from its own verified assembled Tamil unit, but must not alter or backfill Part001 English.

Outgoing:

- scan34 ends at **`குதிரைகள்`**
- **34→35 — PENDING Part003 adjacent witness**
- Part003 is not yet supplied / registered
- do not infer, reconstruct or translate scan35
- Part002 English Chapter 1 unit must remain visibly incomplete at this boundary

## English authority and translation rules

Authority order remains:

1. canonical Tamil `pages/`
2. verified assembled Tamil `sections/`
3. project-created English `translations/en/`

Part002 English must be derived from the verified assembled Tamil layer.

Do not:

- alter canonical or assembled Tamil;
- silently modernize source wording;
- fact-correct historical/political/literary claims inside translation prose;
- import published or web translations of quoted material;
- normalize source-sensitive names merely from external familiarity;
- import Part003 content.

Preserve source voice, attribution, rhetoric, chronology, paragraph structure, quotation boundaries and source-sensitive variants.

Part001 glossary decisions remain valid where the same source forms recur. Extend the glossary only for genuinely new Part002 names, titles, places, offices, literary terms or source-sensitive forms.

## Exact next activity — Part002 English translation planning/setup

Perform **planning/setup only** before drafting the first Part002 English unit.

Extend the existing English controls rather than replacing the closed Part001 records.

Reserve the next non-colliding sequential batches after E1–E6:

| Batch | Verified Tamil input | Scans | Planned English unit |
|---|---|---:|---|
| **E7** | `../../sections/06-ananthanarayanan-paarattu-urai-part002-continuation.md` | 18 | Part002 continuation of Ananthanarayanan address |
| **E8** | `../../sections/07-kaviyarasu-kannadasan-urai.md` | 19–22 | Kannadasan address |
| **E9** | `../../sections/08-arimugam.md` | 23–28 | Introduction |
| **E10** | `../../sections/09-chapter-01-karikaar-chozhanum-peruvazhuthi-pandiyanum.md` | 29–34 | Chapter 1 opening |

During this setup:

- extend `translations/en/TRANSLATION_PLAN.md` for Part002 while retaining Part001 frozen history;
- extend `translations/en/GLOSSARY.md` with Part002-only terms as needed;
- extend `translations/en/PROGRESS.md`;
- extend `translations/en/sections/README.md` with E7–E10 reservations;
- define planned English filenames without colliding with Part001 files;
- keep E7 as the first draft/source-check batch after planning closes;
- record canonical Tamil changes caused by planning = **0**;
- record assembled Tamil changes caused by planning = **0**;
- record Part003 leakage = **0**.

Do **not** draft E7 in the planning/setup activity unless the live workflow explicitly shows planning/setup already closed.

## Expected next frontier after planning/setup

If planning/setup passes cleanly:

**E7 — draft + source-check the verified scan18 Part002 continuation unit.**

Batch discipline should remain sequential:

**E7 closes SOURCE-CHECKED / COMPLETE before E8 begins; E8 before E9; E9 before E10.**

After E10 closes, continue the established Part workflow:

glossary reconciliation → editorial review → bilingual review → release/readiness → release-ready synchronization → final Part002 closure/freeze.

Only after Part002 final closure may Part003 canonical transcription begin.
