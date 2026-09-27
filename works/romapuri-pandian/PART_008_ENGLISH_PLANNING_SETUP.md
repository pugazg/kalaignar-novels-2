# ரோமாபுரிப் பாண்டியன் — Part008 English Translation Planning / Setup

Work: `ரோமாபுரிப் பாண்டியன்`  
Repository: `pugazg/kalaignar-novels-2`  
Branch: `main`

## Result

**PART008 ENGLISH TRANSLATION PLANNING / SETUP — COMPLETE / PASS**

This gate prepares the Part008 English workspace only. It does **not** draft or source-check E22 or E23, and it does not reopen frozen Parts001–007 English or any closed Tamil layer.

## Preconditions

Part008 Tamil prerequisites are closed:

- canonical Tamil — **16/16 verified**
- visual fidelity — **16/16 verified**
- Part audit — **PASS / COMPLETE**
- final metadata/status synchronization — **PASS / CLOSED**
- documentation synchronization — **PASS / COMPLETE**
- Tamil archival-ready — **PASS / CLOSED**
- assembled Tamil — **PASS / CLOSED — 2/2 VERIFIED**
- assembled physical coverage — **16/16 / scans119–134**
- publication-text / displayed-title coverage — **15/15 + blank scan132 provenance**
- missing / duplicate assembled coverage — **0 / 0**
- unsupported Tamil insertion — **0**
- canonical page mutations caused by assembly — **0**
- Part007 body duplication — **0**
- Part009 leakage — **0**
- unresolved Tamil / lexical / historical-glyph / visual / structural / documentation / assembly blockers — **0**

Parts001–007 remain:

**FINAL CLOSED / FROZEN**

## Planning baseline

Live-main checkpoint before Part008 English planning:

`3de88c47e44b9615784b10986bf76c179bbf51cf`

Verified maintained Tamil inputs:

1. `sections/21-chapter-08-vedam-kalaindhathu.md` — scans119–132
2. `sections/22-chapter-09-peruntheviyin-maruththuvar.md` — scans133–134

The maintained English batch sequence is closed through **E21**.

At planning start:

- Part008 English section files — **0/2**
- E22 / E23 source-check records — **0**
- Part008 English planning control — **not yet present**

## Reserved Part008 English batches

The next non-colliding sequence after frozen Part007 E20–E21 is:

| Batch | Verified Tamil input | Scans | Planned English file | State |
|---|---|---:|---|---|
| **E22** | `sections/21-chapter-08-vedam-kalaindhathu.md` | 119–132 | `translations/en/sections/21-chapter-08-the-disguise-falls-away.md` | **RESERVED / NEXT** |
| **E23** | `sections/22-chapter-09-peruntheviyin-maruththuvar.md` | 133–134 | `translations/en/sections/22-chapter-09-perunthevis-physician.md` | **RESERVED** |

Batch discipline:

**E22 → E23**

E22 must become **SOURCE-CHECKED / COMPLETE** before E23 begins.

A draft alone does not close a batch. Each batch requires a durable source-check record.

## Working English chapter titles

Planning reserves these working titles:

- `வேடம் கலைந்தது!` → **The Disguise Falls Away!**
- `பெருந்தேவியின் மருத்துவர்` → **Perunthevi's Physician**

These are project English working titles. Their literary fit may be reviewed during the corresponding source-check without changing verified Tamil.

## Authority

Part008 English authority remains:

1. verified canonical Tamil `pages/`
2. verified assembled Tamil `sections/`
3. project-created English `translations/en/`

English cannot authorize a Tamil correction.

If English source-checking suggests a possible Tamil defect, record it separately and do not modify the verified Tamil layer unless an explicit source-fidelity reopening is approved.

Do not use outside published/web English versions to fill, normalize, identify or reconcile the translation. Translate only from the verified project Tamil and source-visible material.

## Structural and boundary locks

Incoming:

- **118→119 — CHAPTER TRANSITION / AUDITED**
- frozen Part007 E21 remains unchanged
- E22 begins with the Chapter 8 displayed title and must not backfill or revise Part007 English

Verified Part008 assembled structure is authoritative:

### E22 / Chapter 8

- scan119 — illustrated Chapter 8 title `8 / வேடம் கலைந்தது!`
- scan120 — Chapter 8 narrative opening
- scans121–131 — Chapter 8 continuation / printed119–129
- scan132 — genuine blank physical separator represented by provenance only
- physical joins preserved:
  - 120→121
  - 124→125
  - 127→128
- E22 must retain source-boundary provenance without adding source meaning

### E23 / Chapter 9

- scan133 — illustrated Chapter 9 title `9 / பெருந்தேவியின் மருத்துவர்`
- scan134 — Chapter 9 narrative opening
- supplied Part008 ends mid-dialogue at:
  `...யாருக்கும் ஜாடையாகக் கூடத் தெரியக்கூடாது;`
- outgoing **134→135 — PENDING Part009 adjacent witness / deferred external boundary evidence**
- E23 must not infer, translate or import scan135 / Part009 wording

The pending outgoing witness is external to Part008 and is not an English-planning blocker.

## Glossary setup

Locked project forms carry forward where the same Tamil form recurs.

Part008 planning carries forward:

- `முத்துநகை` → **Muthunagai**
- `முத்து` → **Muthu** when used as Muthunagai's assumed name
- `இருங்கோவேள்` → **Irungovel**
- `தாமரை` → **Thamarai** when used as the character's personal name
- `செழியன்` → **Sezhiyan**
- `கரிகாலன்` → **Karikalan**
- `கரிகாற் சோழன்` / `கரிகால் சோழன்` → **Karikala Cholan**, by verified local source form
- `பெருவழுதி` / `பெருவழுதிப் பாண்டியன்` / `பெருவழுதிப் பாண்டியர்` → **Peruvazhuthi / Peruvazhuthi Pandiyan**, by local syntax and form
- `பெருந்தேவி` → **Perunthevi**
- `வேளிர்குடி` → **Velir clan / Velir people**, chosen by local syntax
- `விறகுவெட்டி` → **The Woodcutter** when it is the Chapter 6 title
- `விறகு வெட்டி` / `விறகுவெட்டி` in common-noun context → **woodcutter**
- `பச்சிலை` → **medicinal leaf** where the medical/plant sense is active
- `ஓலை` / `ஓலைச்சுருள்` → **palm-leaf / palm-leaf scroll**, according to local syntax
- `ஒற்றர்` → **spy / intelligence agent**, chosen by local narrative syntax
- `வீரபாண்டி` → **Veerapandi**
- `மருத்துவர்` → **physician / doctor**, chosen by local syntax; Chapter 9 title uses **Physician**

New Part008 title locks for drafting:

- `வேடம் கலைந்தது!` → **The Disguise Falls Away!**
- `பெருந்தேவியின் மருத்துவர்` → **Perunthevi's Physician**

Source-sensitive safeguards:

- do not normalize verified Tamil merely because English renders it naturally;
- preserve dialogue paragraphing and embedded palm-leaf-letter structure;
- preserve scan120→121, 124→125 and 127→128 joins without adding meaning;
- scan132 has provenance only and no English body text;
- preserve Chapter 9's supplied mid-dialogue ending without completion;
- do not import remembered, published or web English versions;
- locally ambiguous expressions may be settled conservatively during E22/E23 source-check from verified Tamil context;
- incoming 118→119 must not cause E22 to revise frozen Part007 E21;
- outgoing 134→135 remains external and Part009 wording must not be inferred.

Part008 planning glossary holds — **0**.

## Planning integrity

- canonical Tamil changes caused by planning — **0**
- assembled Tamil changes caused by planning — **0**
- Parts001–007 English section changes caused by planning — **0**
- E22 English draft files created in planning — **0**
- E23 English draft files created in planning — **0**
- E22 source-check record created in planning — **0**
- E23 source-check record created in planning — **0**
- Part009 leakage — **0**
- unresolved planning holds — **0**

## Gate decision

**PART008 ENGLISH TRANSLATION PLANNING / SETUP — COMPLETE / PASS**

## Exact next activity

**E22 — draft + source-check Part008 Chapter 8 `வேடம் கலைந்தது!` / scans119–132.**

Create the E22 English section only from the verified assembled Tamil input, preserve chapter-title/displayed-text structure, source-boundary provenance and blank scan132 provenance, source-check it against the verified Tamil authority, and create the durable E22 source-check record.

Do not begin E23 until E22 is **SOURCE-CHECKED / COMPLETE**.


## Post-planning synchronization verification

Pre-planning checkpoint:

`3de88c47e44b9615784b10986bf76c179bbf51cf`

Post-planning synchronized checkpoint before this verification record:

`8a86af23fa024b00f2ca80e3e59e934c5ccc1d82`

Direct repository comparison confirms:

- total commits — **15**
- changed files — **15**
- canonical `pages/` changes — **0**
- assembled Part008 Tamil section changes — **0**
- Part008 English body files created — **0**
- E22 / E23 source-check records created — **0**
- frozen Parts001–007 English-body changes — **0**
- Part009 / scan135 repository paths — **0**
- durable Part008 English planning control — **present**

The synchronized controls agree on:

- Part008 assembled Tamil — **PASS / CLOSED — 2/2 VERIFIED**
- reserved English sequence — **E22 → E23**
- E22 — **RESERVED / NEXT**
- E23 — **RESERVED**
- planned English drafts — **0/2**
- source-checked English batches — **0/2**
- unresolved planning holds — **0**
- exact next activity — **E22 draft + source-check**

Therefore English planning introduced no canonical Tamil, assembled Tamil, frozen English-body, Part009, or premature E22/E23 draft drift.


## E22 source-check closure

- E22 — **SOURCE-CHECKED / COMPLETE**
- verified Tamil input — `sections/21-chapter-08-vedam-kalaindhathu.md`
- English file — `translations/en/sections/21-chapter-08-the-disguise-falls-away.md`
- scans — **119–132**
- working title — **The Disguise Falls Away!**
- Tamil / English total blocks — **135 / 135**
- Tamil / English rendered blocks — **124 / 124**
- standalone provenance comments — **11 / 11**
- total provenance/comment occurrences — **14 / 14**
- source-boundary occurrences retained — **13 / 13**
- incoming-boundary comment retained — **1 / 1**
- blank scan132 provenance retained — **1 / 1**
- omitted / duplicated source blocks — **0 / 0**
- source-check corrections — **14**
- unresolved E22 source-check holds — **0**
- canonical Tamil edits caused by E22 — **0**
- assembled Tamil edits caused by E22 — **0**
- frozen Parts001–007 English edits — **0**
- E23 English draft created during E22 — **0**
- E23 source-check record created during E22 — **0**
- Part009 leakage — **0**
- durable source-check — `translations/en/E22_SOURCE_CHECK.md`

Current Part008 English state:

- E22 — **SOURCE-CHECKED / COMPLETE**
- E23 — **RESERVED / NEXT**
- completed/source-checked — **1/2**

Current frontier:

**E23 — draft + source-check Part008 Chapter 9 `பெருந்தேவியின் மருத்துவர்` / scans133–134.**
