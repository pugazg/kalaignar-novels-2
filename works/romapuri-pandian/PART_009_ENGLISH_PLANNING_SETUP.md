# ரோமாபுரிப் பாண்டியன் — Part009 English Translation Planning / Setup

Work: `ரோமாபுரிப் பாண்டியன்`  
Repository: `pugazg/kalaignar-novels-2`  
Branch: `main`

## Result

**PART009 ENGLISH TRANSLATION PLANNING / SETUP — COMPLETE / PASS**

This gate prepares the Part009 English workspace only. It does **not** draft or source-check E24 or E25, and it does not reopen frozen Parts001–008 English or any closed Tamil layer.

## Preconditions

Part009 Tamil prerequisites are closed:

- canonical Tamil — **16/16 verified**
- visual fidelity — **16/16 verified**
- Part audit — **PASS / COMPLETE**
- final metadata/status synchronization — **PASS / CLOSED**
- documentation synchronization — **PASS / COMPLETE**
- Tamil archival-ready — **PASS / CLOSED**
- assembled Tamil — **PASS / CLOSED — 2/2 VERIFIED**
- assembled physical coverage — **16/16 / scans135–150**
- publication-text / displayed-title coverage — **15/15 + blank scan142 provenance**
- missing / duplicate assembled coverage — **0 / 0**
- unsupported Tamil insertion — **0**
- canonical page mutations caused by assembly — **0**
- frozen Part008 body duplication — **0**
- Part010 leakage — **0**
- unresolved Tamil / lexical / historical-glyph / visual / structural / documentation / assembly blockers — **0**

Parts001–008 remain:

**FINAL CLOSED / FROZEN**

## Planning baseline

Live-main checkpoint before Part009 English planning:

`b71734154a6e7cae4482b8acb84cbaad336bc43b`

Verified maintained Tamil inputs:

1. `sections/23-chapter-09-peruntheviyin-maruththuvar-part009-continuation.md` — scans135–142
2. `sections/24-chapter-10-erimalaimeethu-suriyakanthi.md` — scans143–150

The maintained English sequence is closed through **E23**.

At planning start:

- Part009 English section files — **0/2**
- E24 / E25 source-check records — **0**
- Part009 English planning control — **not yet present**

## Reserved Part009 English batches

The next non-colliding sequence after frozen Part008 E22–E23 is:

| Batch | Verified Tamil input | Scans | Planned English file | State |
|---|---|---:|---|---|
| **E24** | `sections/23-chapter-09-peruntheviyin-maruththuvar-part009-continuation.md` | 135–142 | `translations/en/sections/23-chapter-09-perunthevis-physician-part009-continuation.md` | **RESERVED / NEXT** |
| **E25** | `sections/24-chapter-10-erimalaimeethu-suriyakanthi.md` | 143–150 | `translations/en/sections/24-chapter-10-sunflower-on-a-volcano.md` | **RESERVED** |

Batch discipline:

**E24 → E25**

E24 must become **SOURCE-CHECKED / COMPLETE** before E25 begins.

A draft alone does not close a batch. Each batch requires a durable source-check record.

## Working English chapter titles

Planning carries forward the frozen Chapter 9 English title and reserves a working Chapter 10 title:

- `பெருந்தேவியின் மருத்துவர்` → **Perunthevi's Physician**
- `எரிமலைமீது சூரியகாந்தி` → **Sunflower on a Volcano**

The Chapter 10 title is a project working title, chosen to preserve the central source metaphor directly. Literary fit may be reviewed during E25 source-check without changing verified Tamil.

## Authority

Part009 English authority remains:

1. verified canonical Tamil `pages/`
2. verified assembled Tamil `sections/`
3. project-created English `translations/en/`

English cannot authorize a Tamil correction.

If English source-checking suggests a possible Tamil defect, record it separately and do not modify the verified Tamil layer unless an explicit source-fidelity reopening is approved.

Do not use outside published/web English versions to fill, normalize, identify or reconcile the translation. Translate only from the verified project Tamil and source-visible structure already locked in the project.

## Structural and boundary locks

Incoming:

- **134→135 — GENUINE CONTINUATION / AUDITED**
- frozen Part008 E23 remains unchanged
- E24 begins with scan135 continuation text only
- E24 must not backfill, revise, copy or extend frozen Part008 E23 English body

Verified Part009 assembled structure is authoritative.

### E24 / Chapter 9 continuation

- scans135–141 — Chapter 9 `பெருந்தேவியின் மருத்துவர்` continuation
- scan142 — genuine blank physical separator represented by provenance only
- source-faithful internal physical joins include:
  - 135→136
  - 136→137
  - 138→139
  - 140→141
- no English body text is rendered for scan142
- the incoming 134→135 boundary is retained as non-rendering provenance only

### E25 / Chapter 10

- scan143 — illustrated Chapter 10 title `10 / எரிமலைமீது சூரியகாந்தி`
- scan144 — Chapter 10 narrative opening
- scans145–150 — Chapter 10 continuation
- source-faithful internal joins include:
  - 146→147
  - 147→148
- scan144→145 is a same-scene continuation, not a split sentence
- outgoing **150→151 — PENDING Part010 adjacent witness / deferred external boundary evidence**
- E25 must not infer, translate or import scan151 / Part010 wording

The pending outgoing witness is external to Part009 and is not an English-planning blocker.

## Glossary setup

Locked project forms carry forward where the same Tamil form recurs:

- `முத்துநகை` → **Muthunagai**
- `முத்து` → **Muthu** when used as Muthunagai's assumed name
- `இருங்கோவேள்` → **Irungovel**
- `தாமரை` → **Thamarai** when used as the character's personal name
- `செழியன்` → **Sezhiyan**
- `கரிகாலன்` → **Karikalan**
- `கரிகால் பெருவளத்தான்` → **Karikala Peruvalathan**
- `கரிகாற் சோழன்` / `கரிகால் சோழன்` → **Karikala Cholan**, by verified local source form
- `பெருவழுதி` / `பெருவழுதிப் பாண்டியன்` → **Peruvazhuthi / Peruvazhuthi Pandiyan**, by local syntax
- `பெருந்தேவி` → **Perunthevi**
- `வேளிர்குடி` → **Velir clan / Velir people**, chosen by local syntax
- `மருத்துவர்` → **physician / doctor**, chosen by local syntax; Chapter 9 title remains **Physician**
- `ஓலை` / `ஓலைச்சுவடி` → **palm leaf / palm-leaf manuscript**, chosen by local syntax
- `மரமாளிகை` → **wooden palace** where the established narrative sense is active
- `சூரியகாந்தி` → **sunflower**
- `எரிமலை` → **volcano**
- `எரிமலைமீது சூரியகாந்தி` → **Sunflower on a Volcano** as the working Chapter 10 title

Source-sensitive safeguards:

- do not normalize verified Tamil merely because English renders it naturally;
- preserve dialogue paragraphing, quoted speech, displayed title structure and source-boundary provenance;
- preserve the open Chapter 9 continuation across the frozen Part008/Part009 boundary without rewriting E23;
- scan142 has provenance only and no English body text;
- preserve scan146→147 and scan147→148 joins without adding source meaning;
- preserve the Chapter 10 metaphor consistently between title and narrative context;
- do not import remembered, published or web English versions;
- locally ambiguous expressions may be settled conservatively during E24/E25 source-check from verified Tamil context;
- outgoing 150→151 remains external and Part010 wording must not be inferred.

Part009 planning glossary holds — **0**.

## Planning integrity

- canonical Tamil changes caused by planning — **0**
- assembled Tamil changes caused by planning — **0**
- Parts001–008 English section changes caused by planning — **0**
- E24 English draft file created in planning — **0**
- E25 English draft file created in planning — **0**
- E24 source-check record created in planning — **0**
- E25 source-check record created in planning — **0**
- Part010 leakage — **0**
- unresolved planning holds — **0**

## Gate decision

**PART009 ENGLISH TRANSLATION PLANNING / SETUP — COMPLETE / PASS**

## Exact next activity

**E24 — draft + source-check Part009 Chapter 9 `பெருந்தேவியின் மருத்துவர்` continuation / scans135–142.**

Create E24 only from the verified assembled Tamil input, preserve incoming-boundary provenance and blank scan142 provenance, source-check it against the verified Tamil authority, and create the durable E24 source-check record.

Do not begin E25 until E24 is **SOURCE-CHECKED / COMPLETE**.


## Post-planning synchronization verification

Pre-planning checkpoint:

`b71734154a6e7cae4482b8acb84cbaad336bc43b`

Post-planning synchronized checkpoint before this verification record:

`a641dec8705db20339499b33a5014c4ffab5dd39`

Direct repository comparison confirms:

- total commits — **1**
- changed files — **15**
- canonical `pages/` changes — **0**
- assembled Part009 Tamil section-body changes — **0**
- E24 English body file created — **0**
- E25 English body file created — **0**
- E24 / E25 source-check records created — **0 / 0**
- frozen Parts001–008 English-body changes — **0**
- Part010 / scan151 content introduced — **0**
- durable Part009 English planning control — **present**
- reserved sequence — **E24 → E25**
- E24 state — **RESERVED / NEXT**
- E25 state — **RESERVED**
- next-chat frontier — **E24 draft + source-check**

Therefore English planning introduced no canonical Tamil, assembled Tamil, frozen English-body, premature Part009 English-body, or Part010 drift.
