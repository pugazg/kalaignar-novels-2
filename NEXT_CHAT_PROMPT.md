# NEXT CHAT PROMPT — ரோமாபுரிப் பாண்டியன் / Part002 E7 draft + source-check

Continue directly in `pugazg/kalaignar-novels-2`, branch `main`, active work `works/romapuri-pandian/`. **LIVE MAIN IS AUTHORITATIVE.**

Read the live controls before making changes. If this prompt conflicts with live `main`, live `main` wins.

## Read first

1. `HANDOVER.md`
2. `works/romapuri-pandian/README.md`
3. `works/romapuri-pandian/PART_002_ENGLISH_PLANNING_SETUP.md`
4. `works/romapuri-pandian/PART_002_ASSEMBLED_TAMIL_VALIDATION.md`
5. `works/romapuri-pandian/sections/06-ananthanarayanan-paarattu-urai-part002-continuation.md`
6. `works/romapuri-pandian/translations/en/TRANSLATION_PLAN.md`
7. `works/romapuri-pandian/translations/en/GLOSSARY.md`
8. `works/romapuri-pandian/translations/en/PROGRESS.md`
9. `works/romapuri-pandian/translations/en/sections/README.md`

## Durable state

### Part001

Part001 / scans **1–17** is **FINAL CLOSED / FROZEN**.

- Tamil canonical — **17/17 verified**
- assembled Tamil — **PASS / CLOSED — 6/6 VERIFIED**
- English E1–E6 — **SOURCE-CHECKED / COMPLETE**
- glossary/editorial/bilingual/release gates — **PASS / CLOSED**
- final closure — **PASS / CLOSED / FROZEN**

Do not reopen Part001 for stylistic polishing.

### Part002 Tamil

Source: `TVA_BOK_0065553_ரோமாபுரிப்_பாண்டியன்_part_002_pages_18-34.pdf`

- scans — **18–34 / 17 pages**
- SHA-256 — `0be5e57ed61405a39b18276db7184652ded8d401a18114caa3c9c039917a7dc0`
- canonical Tamil — **17/17 verified**
- visual fidelity — **17/17 verified**
- Part audit — **PASS / COMPLETE**
- Tamil archival-ready — **PASS / CLOSED**
- assembled Tamil — **PASS / CLOSED — 4/4 VERIFIED**
- Tamil unresolved blockers — **0**
- Part003 leakage — **0**

### Part002 English planning/setup

**COMPLETE / PASS**

Reserved batches:

| Batch | Tamil input | Scans | Planned English file | State |
|---|---|---:|---|---|
| **E7** | `sections/06-ananthanarayanan-paarattu-urai-part002-continuation.md` | 18 | `translations/en/sections/06-ananthanarayanan-appreciation-address-part002-continuation.md` | **RESERVED / NEXT** |
| **E8** | `sections/07-kaviyarasu-kannadasan-urai.md` | 19–22 | `translations/en/sections/07-kaviyarasu-kannadasan-address.md` | **RESERVED** |
| **E9** | `sections/08-arimugam.md` | 23–28 | `translations/en/sections/08-introduction.md` | **RESERVED** |
| **E10** | `sections/09-chapter-01-karikaar-chozhanum-peruvazhuthi-pandiyanum.md` | 29–34 | `translations/en/sections/09-chapter-01-karikala-cholan-and-peruvazhuthi-pandiyan.md` | **RESERVED** |

Current English count:

- Part002 drafted — **0/4**
- Part002 source-checked — **0/4**

## Boundary locks

Incoming:

- **17→18 = GENUINE CONTINUATION / AUDITED**
- Part001 E6 deliberately remains incomplete and frozen.
- E7 translates only the verified Part002 scan18 unit.
- Do not alter or backfill Part001 English.

Outgoing:

- scan34 ends at `குதிரைகள்`
- **34→35 = PENDING Part003 adjacent witness**
- do not infer or import scan35 / Part003 text
- later E10 must remain visibly incomplete at that boundary

## Authority and translation rules

Authority order:

1. verified canonical Tamil `pages/`
2. verified assembled Tamil `sections/`
3. project-created English `translations/en/`

For E7:

- translate only from the verified scan18 assembled Tamil unit;
- preserve source voice, attribution, rhetorical structure, paragraphing and punctuation force where meaningful;
- use locked glossary choices;
- do not fact-correct or normalize source claims inside translation prose;
- do not use published/web translations for quoted matter;
- do not modify canonical or assembled Tamil;
- record any genuine ambiguity as a hold rather than guessing.

Relevant locked forms include:

- `அனந்தநாராயணன்` → **Ananthanarayanan**
- `ஷேக்ஸ்பியர்` → **Shakespeare**
- `கிளியோபாட்ரா` / `கிளியோபாத்ரா` → **Cleopatra**
- `அந்தோணி` → **Antony**
- `செயங்கொண்டான்` → **Seyankondan**

## Exact next activity

**E7 — draft + source-check scan18 / `06-ananthanarayanan-paarattu-urai-part002-continuation.md`.**

Create the planned English section file:

`works/romapuri-pandian/translations/en/sections/06-ananthanarayanan-appreciation-address-part002-continuation.md`

Then perform a direct source-check against the verified Tamil unit and create a durable E7 source-check record following the Part001 pattern.

E7 closes only when:

- Tamil coverage — **complete**
- omissions — **0**
- unsupported additions — **0**
- glossary/source-sensitive names — **checked**
- Part001 English mutation — **0**
- canonical Tamil mutation — **0**
- assembled Tamil mutation — **0**
- Part003 leakage — **0**
- unresolved E7 holds — **0**

Do **not** begin E8 until E7 is **SOURCE-CHECKED / COMPLETE**.
