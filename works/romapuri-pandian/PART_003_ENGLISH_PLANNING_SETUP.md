# ரோமாபுரிப் பாண்டியன் — Part003 English Translation Planning / Setup

Work: `ரோமாபுரிப் பாண்டியன்`  
Repository: `pugazg/kalaignar-novels-2`  
Branch: `main`

## Result

**PART003 ENGLISH TRANSLATION PLANNING / SETUP — COMPLETE / PASS**

This gate prepares the Part003 English workspace only. It does **not** draft or source-check E11 or E12, and it does not reopen frozen Parts001–002 English or any closed Tamil layer.

## Preconditions

Part003 Tamil prerequisites were closed before this gate:

- canonical Tamil — **18/18 verified**
- visual fidelity — **18/18 verified**
- documentation synchronization — **PASS / COMPLETE**
- Tamil archival-ready — **PASS / CLOSED**
- assembled Tamil — **PASS / CLOSED — 2/2 VERIFIED**
- assembled physical coverage — **18/18 / scans35–52**
- missing / duplicate assembled coverage — **0 / 0**
- unsupported Tamil insertion — **0**
- canonical page mutations caused by assembly — **0**
- Part004 leakage — **0**
- unresolved Tamil / lexical / historical-glyph / visual / structural blockers — **0**

Parts001–002 remain:

**FINAL CLOSED / FROZEN**

## Planning baseline

Live-main checkpoint before Part003 English planning:

`daa15f85300d366dfa8f5113ea524770de1d5192`

English-control checkpoint after planning updates:

`2eec3d94344862dcc3a7f88f5dbc27099c3eacbd`

Direct comparison confirms the planning activity changed only:

- `translations/en/TRANSLATION_PLAN.md`
- `translations/en/PROGRESS.md`
- `translations/en/GLOSSARY.md`
- `translations/en/sections/README.md`

and changed:

- canonical `pages/` files — **0**
- assembled Tamil `sections/` content files — **0**
- Part001/Part002 English section files — **0**
- E11 English draft files — **0**
- E12 English draft files — **0**
- Part004 files — **0**

## Reserved Part003 English batches

The next non-colliding sequence after closed Part002 E7–E10 is:

| Batch | Verified Tamil input | Scans | Planned English file | State |
|---|---|---:|---|---|
| **E11** | `sections/10-chapter-01-karikaar-chozhanum-peruvazhuthi-pandiyanum-part003-continuation.md` | 35–44 | `translations/en/sections/10-chapter-01-karikala-cholan-and-peruvazhuthi-pandiyan-part003-continuation.md` | **RESERVED / NEXT** |
| **E12** | `sections/11-chapter-02-muthunagai.md` | 45–52 | `translations/en/sections/11-chapter-02-muthunagai.md` | **RESERVED** |

Batch discipline:

**E11 → E12**

E11 must become **SOURCE-CHECKED / COMPLETE** before E12 begins.

A draft alone does not close a batch.

## Authority

Part003 English authority remains:

1. verified canonical Tamil `pages/`
2. verified assembled Tamil `sections/`
3. project-created English `translations/en/`

English cannot authorize a Tamil correction.

If an English source-check finds a possible Tamil defect, record it separately and do not modify the frozen verified Tamil layer unless an explicit source-fidelity reopening is approved.

## Structural and boundary locks

Incoming:

- **34→35 — GENUINE CONTINUATION / AUDITED**
- Part002 E10 remains frozen and visibly incomplete
- E11 translates only the verified Part003 Chapter 1 continuation unit
- E11 must not alter or backfill Part002 English

Verified assembled Tamil structure is authoritative:

- scan38→39 — `ஒப்பிடுவதற்கரிய`
- scan41→42 — direct-speech continuation
- scan44 — blank physical separator represented by provenance only
- scan45 — illustrated Chapter 2 title page
- scan47→48 — `மறைத்து வைக்கப்பட்டிருப்பதை`
- scan49→50 — `இந்த ஆபத்து வந்திருக்காதல்லவா?`

Outgoing:

- scan52 ends on a complete narrative sentence
- **52→53 — PENDING Part004 adjacent witness / deferred external boundary evidence**
- Part004 is not supplied / registered
- E12 must not infer, translate or import scan53 wording

## Glossary setup

Locked project forms carry forward where the same Tamil form recurs.

Part003 planning adds or activates:

- `வில்லவன்` → **Villavan**
- `செழியன்` → **Sezhiyan**
- `கரிகால்வளவன்` / `கரிகாலன்` → **Karikala Valavan / Karikalan**, context-sensitive
- `பெருவழுதி` / `பெருவழுதிப் பாண்டியன்` → **Peruvazhuthi / Peruvazhuthi Pandiyan**
- `காரிக்கண்ணனார்` → **Karikannanar**
- `இருங்கோவேள்` → **Irungovel**
- `முத்துநகை` → **Muthunagai**
- `சிவனடியார்கள்` → **devotees of Siva / Siva devotees**, settle locally by syntax
- `அன்பே சிவம்` → **Love is Siva**
- `பண்பே சைவம்` → **Virtue is Saivism**
- `புலிநக மாலை` → **tiger-claw necklace**

Quoted/displayed verse must be translated only from verified project Tamil, not from remembered, published, or web English versions.

No source-sensitive Tamil form is normalized in the Tamil layer by this planning activity.

Additional terms may be added only when encountered and source-checked during E11/E12.

## Planning integrity

- canonical Tamil edits caused by planning — **0**
- assembled Tamil edits caused by planning — **0**
- Part001 English section edits — **0**
- Part002 English section edits — **0**
- E11 drafts created — **0**
- E12 drafts created — **0**
- Part004 leakage — **0**
- unresolved planning holds — **0**

## Gate result

**PART003 ENGLISH TRANSLATION PLANNING / SETUP — COMPLETE / PASS**

## Exact next activity

**E11 — draft + source-check Part003 Chapter 1 continuation / scans35–44.**

Create the E11 English section from the verified assembled Tamil input, preserve source voice and structural provenance, source-check it against the verified Tamil authority, and create the durable E11 source-check record.

Do not begin E12 until E11 is **SOURCE-CHECKED / COMPLETE**.
