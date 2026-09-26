# ரோமாபுரிப் பாண்டியன் — Part007 English Translation Planning / Setup

Work: `ரோமாபுரிப் பாண்டியன்`  
Repository: `pugazg/kalaignar-novels-2`  
Branch: `main`

## Result

**PART007 ENGLISH TRANSLATION PLANNING / SETUP — COMPLETE / PASS**

This gate prepares the Part007 English workspace only. It does **not** draft or source-check E20 or E21, and it does not reopen frozen Parts001–006 English or any closed Tamil layer.

## Preconditions

Part007 Tamil prerequisites are closed:

- canonical Tamil — **16/16 verified**
- visual fidelity — **16/16 verified**
- Part audit — **PASS / COMPLETE**
- final metadata/status synchronization — **PASS / CLOSED**
- documentation synchronization — **PASS / COMPLETE**
- Tamil archival-ready — **PASS / CLOSED**
- assembled Tamil — **PASS / CLOSED — 2/2 VERIFIED**
- assembled physical coverage — **16/16 / scans103–118**
- publication-text coverage — **15/15 + blank scan118 provenance**
- missing / duplicate assembled coverage — **0 / 0**
- unsupported Tamil insertion — **0**
- canonical page mutations caused by assembly — **0**
- Part006 body duplication — **0**
- Part008 leakage — **0**
- unresolved Tamil / lexical / historical-glyph / visual / structural / documentation blockers — **0**

Parts001–006 remain:

**FINAL CLOSED / FROZEN**

## Planning baseline

Live-main checkpoint before Part007 English planning:

`f80ba9bd1d82f00c111b6d80358ff20d783c7a3d`

The verified maintained Tamil inputs are:

1. `sections/19-chapter-06-viragu-vetti-part007-continuation.md` — scans103–104
2. `sections/20-chapter-07-thathalitha-thamarai.md` — scans105–118

The existing English batch sequence is closed through **E19**. No E20/E21 English section files or source-check records exist at planning start.

## Reserved Part007 English batches

The next non-colliding sequence after frozen Part006 E18–E19 is:

| Batch | Verified Tamil input | Scans | Planned English file | State |
|---|---|---:|---|---|
| **E20** | `sections/19-chapter-06-viragu-vetti-part007-continuation.md` | 103–104 | `translations/en/sections/19-chapter-06-the-woodcutter-part007-continuation.md` | **RESERVED / NEXT** |
| **E21** | `sections/20-chapter-07-thathalitha-thamarai.md` | 105–118 | `translations/en/sections/20-chapter-07-the-floundering-lotus.md` | **RESERVED** |

Batch discipline:

**E20 → E21**

E20 must become **SOURCE-CHECKED / COMPLETE** before E21 begins.

A draft alone does not close a batch. Each batch requires a durable source-check record.

## Authority

Part007 English authority remains:

1. verified canonical Tamil `pages/`
2. verified assembled Tamil `sections/`
3. project-created English `translations/en/`

English cannot authorize a Tamil correction.

If an English source-check finds a possible Tamil defect, record it separately and do not modify the verified Tamil layer unless an explicit source-fidelity reopening is approved.

Do not use outside published/web English versions to fill, normalize, identify, or reconcile the translation. Translate only from the verified project Tamil and source-visible material.

## Structural and boundary locks

Incoming:

- **102→103 — GENUINE CONTINUATION / AUDITED**
- frozen Part006 E19 remains unchanged
- E20 translates only the verified Part007 Chapter 6 continuation unit
- E20 must not backfill, revise, or extend Part006 English

Verified Part007 assembled structure is authoritative:

- scans103–104 — Chapter 6 `விறகுவெட்டி` continuation / close
- scan105 — illustrated Chapter 7 title `7. தத்தளித்த தாமரை`
- scan106 — Chapter 7 narrative opening
- scans107–117 — Chapter 7 continuation
- scan112→113 — same-sentence physical continuation preserved
- scan116→117 — same-sentence physical continuation preserved
- scan118 — fully blank physical terminal page represented by provenance only; it has no English body text

Outgoing:

- **118→119 — PENDING Part008 adjacent witness / deferred external boundary evidence**
- E21 must not infer, translate, or import scan119 / Part008 wording

The pending outgoing witness is external to Part007 and is not an English-planning blocker.

## Glossary setup

Locked project forms carry forward where the same Tamil form recurs.

Part007 planning activates or adds:

- `விறகுவெட்டி` → **The Woodcutter** for the Chapter 6 title
- `விறகு வெட்டி` → **woodcutter** when used as an occupation/common noun
- `தத்தளித்த தாமரை` → **The Floundering Lotus** as the working Chapter 7 English title
- `தாமரை` → **Thamarai** when it is the character's personal name
- `முத்துநகை` → **Muthunagai**
- `முத்து` → **Muthu** when used as Muthunagai's assumed name
- `செழியன்` → **Sezhiyan**
- `கரிகாலன்` → **Karikalan**
- `கரிகாற் சோழன்` / `கரிகால் சோழன்` → **Karikala Cholan**, by verified local source form
- `கரிகால் பெருவளத்தான்` → **Karikala Peruvalathan**
- `இருங்கோவேள்` → **Irungovel**
- `பெருந்தேவி` → **Perunthevi**
- `யவனக் கிழவர்` / `யவனக்கிழவர்` → **Yavana elder**
- `வேளிர்குடி` → **Velir clan / Velir people**, chosen by local syntax
- `ஜுவாலை` → translate by local sense as **flame / blaze** rather than normalize the Tamil source
- `மெளனம்` → translate by meaning as **silence**, while preserving the verified Tamil historical orthography in the Tamil layer

For the Chapter 7 title, **The Floundering Lotus** preserves the literal lotus image while `தாமரை` in personal-name contexts remains **Thamarai**. The title handling may be checked for literary fit during E21 source-check without changing verified Tamil.

Source-sensitive safeguards for Part007:

- do not normalize verified Tamil forms merely because English renders them naturally;
- preserve dialogue paragraphing, displayed wording and source-boundary provenance;
- preserve scan112→113 and scan116→117 joins without adding source meaning;
- scan118 has provenance only and no English body text;
- do not import published, remembered or web English versions;
- new locally ambiguous expressions may be settled conservatively during E20/E21 source-check from the verified Tamil context;
- incoming 102→103 must not cause E20 to backfill frozen Part006 E19;
- outgoing 118→119 remains external and Part008 wording must not be inferred.

Part007 planning glossary holds — **0**.

## Planning integrity

- canonical Tamil changes caused by planning — **0**
- assembled Tamil changes caused by planning — **0**
- Parts001–006 English section changes caused by planning — **0**
- E20 English draft files created in planning — **0**
- E21 English draft files created in planning — **0**
- E20 source-check record created in planning — **0**
- E21 source-check record created in planning — **0**
- Part008 leakage — **0**
- unresolved planning holds — **0**

## Gate decision

**PART007 ENGLISH TRANSLATION PLANNING / SETUP — COMPLETE / PASS**

## Exact next activity

**E20 — draft + source-check Part007 Chapter 6 `விறகுவெட்டி` continuation / scans103–104.**

Create the E20 English section only from the verified assembled Tamil input, preserve source voice and incoming-boundary provenance, source-check it against the verified Tamil authority, and create the durable E20 source-check record.

Do not begin E21 until E20 is **SOURCE-CHECKED / COMPLETE**.


## E20 source-check closure

- E20 — **SOURCE-CHECKED / COMPLETE**
- verified Tamil input — `sections/19-chapter-06-viragu-vetti-part007-continuation.md`
- English file — `translations/en/sections/19-chapter-06-the-woodcutter-part007-continuation.md`
- scans — **103–104**
- Tamil / English total blocks — **14 / 14**
- Tamil / English rendered blocks — **12 / 12**
- standalone provenance comments — **2 / 2**
- incoming-boundary comments retained — **1 / 1**
- source-boundary comments retained — **1 / 1**
- omitted / duplicated source blocks — **0 / 0**
- source-check corrections — **3**
- unresolved E20 source-check holds — **0**
- canonical Tamil edits caused by E20 — **0**
- assembled Tamil edits caused by E20 — **0**
- frozen Parts001–006 English edits — **0**
- E21 English draft created during E20 — **0**
- Part008 leakage — **0**
- durable source-check — `translations/en/E20_SOURCE_CHECK.md`

Current Part007 English state:

- E20 — **SOURCE-CHECKED / COMPLETE**
- E21 — **RESERVED / NEXT**
- completed/source-checked — **1/2**

Current frontier:

**E21 — draft + source-check Part007 Chapter 7 `தத்தளித்த தாமரை` / scans105–118.**
