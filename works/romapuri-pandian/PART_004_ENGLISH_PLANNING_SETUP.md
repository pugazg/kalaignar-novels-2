# ரோமாபுரிப் பாண்டியன் — Part004 English Translation Planning / Setup

Work: `ரோமாபுரிப் பாண்டியன்`  
Repository: `pugazg/kalaignar-novels-2`  
Branch: `main`

## Result

**PART004 ENGLISH TRANSLATION PLANNING / SETUP — COMPLETE / PASS**

This gate prepares the Part004 English workspace only. It does **not** draft or source-check E13, E14 or E15, and it does not reopen frozen Parts001–003 English or any closed Tamil layer.

## Preconditions

Part004 Tamil prerequisites were closed before this gate:

- canonical Tamil — **16/16 verified**
- visual fidelity — **16/16 verified**
- documentation synchronization — **PASS / COMPLETE**
- Tamil archival-ready — **PASS / CLOSED**
- assembled Tamil — **PASS / CLOSED — 3/3 VERIFIED**
- assembled physical coverage — **16/16 / scans53–68**
- publication-text coverage — **14/14**
- blank scans56 and 66 — **represented by provenance only**
- missing / duplicate assembled coverage — **0 / 0**
- unsupported Tamil insertion — **0**
- canonical page mutations caused by assembly — **0**
- Part005 leakage — **0**
- unresolved Tamil / lexical / historical-glyph / visual / structural blockers — **0**

Parts001–003 remain:

**FINAL CLOSED / FROZEN**

## Planning baseline

Live-main checkpoint before Part004 English planning:

`4009051e583970acc17080807a48d0baa387664a`

English-control checkpoint after planning updates:

`560093bbad12b4945ed8f628b17fdaf3c73c6f91`

Direct comparison confirms the planning activity changed only:

- `translations/en/TRANSLATION_PLAN.md`
- `translations/en/PROGRESS.md`
- `translations/en/GLOSSARY.md`
- `translations/en/sections/README.md`

and changed:

- canonical `pages/` files — **0**
- assembled Tamil `sections/` content files — **0**
- Parts001–003 English section files — **0**
- E13 English draft files — **0**
- E14 English draft files — **0**
- E15 English draft files — **0**
- Part005 files — **0**

## Reserved Part004 English batches

The next non-colliding sequence after closed Part003 E11–E12 is:

| Batch | Verified Tamil input | Scans | Planned English file | State |
|---|---|---:|---|---|
| **E13** | `sections/12-chapter-02-muthunagai-part004-continuation.md` | 53–56 | `translations/en/sections/12-chapter-02-muthunagai-part004-continuation.md` | **RESERVED / NEXT** |
| **E14** | `sections/13-chapter-03-maravar-maanam.md` | 57–66 | `translations/en/sections/13-chapter-03-the-warriors-honour.md` | **RESERVED** |
| **E15** | `sections/14-chapter-04-pulavar-magal-purappattaal.md` | 67–68 | `translations/en/sections/14-chapter-04-the-poets-daughter-sets-out.md` | **RESERVED** |

Batch discipline:

**E13 → E14 → E15**

E13 must become **SOURCE-CHECKED / COMPLETE** before E14 begins; E14 must close before E15 begins.

A draft alone does not close a batch.

## Authority

Part004 English authority remains:

1. verified canonical Tamil `pages/`
2. verified assembled Tamil `sections/`
3. project-created English `translations/en/`

English cannot authorize a Tamil correction.

If an English source-check finds a possible Tamil defect, record it separately and do not modify the frozen verified Tamil layer unless an explicit source-fidelity reopening is approved.

## Structural and boundary locks

Incoming:

- **52→53 — GENUINE CONTINUATION / AUDITED**
- Part003 E12 remains frozen
- E13 translates only the verified Part004 Chapter 2 continuation unit
- E13 must not alter or backfill Part003 English

Verified assembled Tamil structure is authoritative:

- scan53→54 — same-sentence continuation retained
- scan56 — blank physical separator represented by provenance only
- scan57 — illustrated Chapter 3 title page `மறவர் மானம்`
- scan61→62 — same-sentence continuation retained
- scan64→65 — same-sentence continuation retained
- scan66 — blank physical separator represented by provenance only
- scan67 — illustrated Chapter 4 title page `புலவர் மகள் புறப்பட்டாள்`

Outgoing:

- scan68 ends on a complete narrative sentence
- **68→69 — PENDING Part005 adjacent witness / deferred external boundary evidence**
- Part005 is not supplied / registered
- E15 must not infer, translate or import scan69 wording

## Glossary setup

Locked project forms carry forward where the same Tamil form recurs.

Part004 planning adds or activates:

- `முத்துநகை` → **Muthunagai**
- `செழியன்` → **Sezhiyan**
- `காரிக்கண்ணனார்` → **Karikannanar**
- `இருங்கோவேள்` → **Irungovel**
- `வில்லவன்` → **Villavan**
- `செந்தலையார்` → **Senthalaiyar**
- `வேளிர்குடி` → **Velir clan / Velir people**, context-sensitive
- `மறவர் மானம்` → **The Warrior's Honour**
- `புலவர் மகள் புறப்பட்டாள்` → **The Poet's Daughter Sets Out**
- `சாவுருக்குப் போகும் வழி` → **Road to Death**, preserving the source-visible sign function

Planning glossary holds — **0**.

Additional local wording may be settled during each batch source-check without changing Tamil.

## Planning integrity

- canonical Tamil changes caused by planning — **0**
- assembled Tamil changes caused by planning — **0**
- Parts001–003 English section changes caused by planning — **0**
- E13/E14/E15 draft files created in planning — **0**
- Part005 leakage — **0**
- unresolved planning holds — **0**

## Gate decision

**PART004 ENGLISH TRANSLATION PLANNING / SETUP — COMPLETE / PASS**

## Exact next activity

**E13 — draft + source-check Part004 Chapter 2 continuation / scans53–56.**

Do not begin E14 until E13 is **SOURCE-CHECKED / COMPLETE**.


## Post-planning control synchronization verification

Planning baseline:

`4009051e583970acc17080807a48d0baa387664a`

Post-planning synchronized checkpoint before this record refresh:

`5dfcd65cad8d0c42b771e36e275ef8390a0c346c`

Direct comparison confirms:

- canonical `pages/` files changed — **0**
- assembled Tamil content files changed — **0**
- English section draft files created — **0**
- Parts001–003 English section files changed — **0**
- Part005 files introduced — **0**
- changed files are English planning/control and lifecycle/navigation records only — **PASS**

The synchronized controls agree on:

- Part004 English planning/setup — **COMPLETE / PASS**
- reserved batches — **E13–E15**
- drafted/source-checked Part004 English units — **0/3**
- unresolved planning holds — **0**
- exact next gate — **E13 draft + source-check / scans53–56**

Therefore this planning gate caused no canonical Tamil, assembled Tamil, existing English-body, or Part005 drift.


## Post-planning E13 closure

The first reserved Part004 English batch has since closed:

- E13 — **SOURCE-CHECKED / COMPLETE**
- verified Tamil input — `sections/12-chapter-02-muthunagai-part004-continuation.md`
- English file — `translations/en/sections/12-chapter-02-muthunagai-part004-continuation.md`
- scans — **53–56**
- total Tamil / English blocks — **21 / 21**
- rendered Tamil / English blocks — **18 / 18**
- omitted / duplicated source blocks — **0 / 0**
- unresolved E13 source-check holds — **0**
- canonical Tamil edits caused by E13 — **0**
- assembled Tamil edits caused by E13 — **0**
- Parts001–003 English edits caused by E13 — **0**
- Part005 leakage — **0**
- durable source-check — `translations/en/E13_SOURCE_CHECK.md`

Current Part004 English state:

- E13 — **SOURCE-CHECKED / COMPLETE**
- E14 — **RESERVED / NEXT**
- E15 — **RESERVED**
- completed/source-checked — **1/3**

Current frontier:

**E14 — draft + source-check Part004 Chapter 3 `மறவர் மானம்` / scans57–66.**
