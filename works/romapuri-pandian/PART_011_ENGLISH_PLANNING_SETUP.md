# ரோமாபுரிப் பாண்டியன் — Part011 English Translation Planning / Setup

Work: `ரோமாபுரிப் பாண்டியன்`  
Repository: `pugazg/kalaignar-novels-2`  
Branch: `main`

## Result

**PART011 ENGLISH TRANSLATION PLANNING / SETUP — COMPLETE / PASS**

This gate prepares the Part011 English workspace only. It does **not** draft or source-check E28, E29 or E30, and it does not reopen frozen Parts001–010 English or any closed Tamil layer.

## Preconditions

Part011 Tamil prerequisites are closed:

- canonical Tamil — **16/16 verified**
- visual fidelity — **16/16 verified**
- Part audit — **PASS / COMPLETE**
- final metadata/status synchronization — **PASS / CLOSED**
- documentation synchronization — **PASS / COMPLETE**
- Tamil archival-ready — **PASS / CLOSED**
- assembled Tamil — **PASS / CLOSED — 3/3 VERIFIED**
- assembled physical coverage — **16/16 / scans168–183**
- publication-text / displayed-title coverage — **16/16**
- missing / duplicate assembled coverage — **0 / 0**
- deterministic canonical reconstruction — **3/3 EXACT / PASS**
- unsupported Tamil insertion — **0**
- canonical page mutations caused by assembly — **0**
- frozen Part010 body duplication — **0**
- Part012 leakage — **0**
- unresolved Tamil / lexical / historical-glyph / visual / structural / documentation / assembly blockers — **0**

Parts001–010 remain:

**FINAL CLOSED / FROZEN**

## Planning baseline

Live-main checkpoint before Part011 English planning:

`e252efe7694abe874d905a74302595a5fabc061b`

Verified maintained Tamil inputs:

1. `sections/27-chapter-11-olai-kai-maariyathu-part011-continuation.md` — scan168
2. `sections/28-chapter-12-mannasai.md` — scans169–180
3. `sections/29-chapter-13-nedumaran-thadumaatram.md` — scans181–183

The maintained English sequence is closed through **E27 / section26 / Part010**.

At planning start:

- Part011 English section files — **0/3**
- E28 / E29 / E30 source-check records — **0**
- Part011 English planning control — **not yet present**

## Reserved Part011 English batches

The next non-colliding sequence after frozen Part010 E26–E27 is:

| Batch | Verified Tamil input | Scans | Planned English file | State |
|---|---|---:|---|---|
| **E28** | `sections/27-chapter-11-olai-kai-maariyathu-part011-continuation.md` | 168 | `translations/en/sections/27-chapter-11-the-palm-leaf-changes-hands-part011-continuation.md` | **RESERVED / NEXT** |
| **E29** | `sections/28-chapter-12-mannasai.md` | 169–180 | `translations/en/sections/28-chapter-12-hunger-for-land.md` | **RESERVED** |
| **E30** | `sections/29-chapter-13-nedumaran-thadumaatram.md` | 181–183 | `translations/en/sections/29-chapter-13-nedumaran-wavers.md` | **RESERVED** |

Batch discipline:

**E28 → E29 → E30**

E28 must become **SOURCE-CHECKED / COMPLETE** before E29 begins. E29 must become **SOURCE-CHECKED / COMPLETE** before E30 begins.

A draft alone does not close a batch. Each batch requires a durable source-check record.

## Working English chapter titles

Planning carries forward the already established Chapter 11 English title and reserves working project renderings for Chapters 12 and 13:

- `ஓலை கை மாறியது` → **The Palm Leaf Changes Hands**
- `மண்ணாசை` → **Hunger for Land** — **working project title**
- `நெடுமாறன் தடுமாற்றம்` → **Nedumaran Wavers** — **working project title**

The Chapter 11 title is already established by frozen Part010 E27 and must carry forward unchanged for E28.

The Chapter 12 and Chapter 13 English titles are planning-stage project renderings derived from the verified Tamil titles and existing local title style; they are **not** claims of an external/published English title. Literary fit may be reviewed during E29/E30 source-check without changing verified Tamil.

## Authority

Part011 English authority remains:

1. verified canonical Tamil `pages/`
2. verified assembled Tamil `sections/`
3. project-created English `translations/en/`

English cannot authorize a Tamil correction.

If English source-checking suggests a possible Tamil defect, record it separately and do not modify the verified Tamil layer unless an explicit source-fidelity reopening is approved.

Do not use outside published/web English versions to fill, normalize, identify or reconcile the translation. Translate only from the verified project Tamil and source-visible structure already locked in the project.

## Structural and boundary locks

Incoming:

- **167→168 — GENUINE CONTINUATION / AUDITED**
- frozen Part010 E27 remains unchanged
- E28 begins with scan168 continuation text only
- E28 must not backfill, revise, copy or extend frozen Part010 E27 English body

Verified Part011 assembled structure is authoritative.

### E28 / Chapter 11 continuation

- scan168 — terminal Chapter 11 `ஓலை கை மாறியது` continuation / close
- source input contains only scan168 body plus non-rendering boundary provenance
- incoming 167→168 boundary remains provenance only
- Chapter 11 title remains **The Palm Leaf Changes Hands**
- do not duplicate frozen scan167 / E27 body

### E29 / Chapter 12

- scan169 — illustrated Chapter 12 title `12 / மண்ணாசை`
- scan170 — Chapter 12 narrative opening
- scans171–180 — Chapter 12 continuation / close
- source-faithful physical joins include:
  - 172→173
  - 173→174
  - 175→176
  - 176→177
  - 177→178 physical split word
  - 178→179
- scan177→178 source fragments `உறுதியளித்` + `திருந்தேன்.` are already represented in assembled Tamil with an inline non-rendering boundary comment; English must preserve the semantic continuity without inventing a second sentence or extra meaning

### E30 / Chapter 13

- scan181 — illustrated Chapter 13 title `13 / நெடுமாறன் தடுமாற்றம்`
- scan182 — Chapter 13 narrative opening
- scan183 — Chapter 13 continuation
- 182→183 physical continuation remains source-faithful
- outgoing **183→184 — PENDING Part012 adjacent witness / deferred external boundary evidence**
- E30 must not infer, translate or import scan184 / Part012 wording

The pending outgoing witness is external to Part011 and is not an English-planning blocker.

## Glossary / naming setup

Locked project forms carry forward where the same Tamil form recurs:

- `முத்துநகை` → **Muthunagai**
- `முத்து` → **Muthu** when used as Muthunagai's assumed name
- `இருங்கோவேள்` → **Irungovel**
- `தாமரை` → **Thamarai** when used as the character's personal name
- `செழியன்` → **Sezhiyan**
- `கரிகாலன்` → **Karikalan**
- `பெருவழுதி` / `பெருவழுதிப் பாண்டியன்` → **Peruvazhuthi / Peruvazhuthi Pandiyan**, by local syntax
- `வீரபாண்டி` → **Veerapandi**
- `கொடுங்கோல்` → **Kodungol**
- `நெடுமாறன்` → **Nedumaran**
- `வேளிர்குடி` → **Velir clan / Velir people**, chosen by local syntax
- `ஓலை` → **palm leaf** in ordinary message/document context
- `முத்திரை மோதிரம்` → **seal ring**
- `அமைச்சர்` → **minister**
- `ஒற்றன்` → **spy**
- `படையெடுப்பு` → **invasion / campaign**, chosen by local syntax
- `மரமாளிகை` → **wooden palace**
- `ஓலை கை மாறியது` → **The Palm Leaf Changes Hands**
- `மண்ணாசை` → **Hunger for Land** as the planning-stage Chapter 12 title
- `நெடுமாறன் தடுமாற்றம்` → **Nedumaran Wavers** as the planning-stage Chapter 13 title

Source-sensitive safeguards:

- do not normalize verified Tamil merely because English renders it naturally;
- preserve dialogue paragraphing, quoted speech, displayed-title structure and source-boundary provenance;
- preserve the open Chapter 11 continuation across the frozen Part010/Part011 boundary without rewriting E27;
- preserve scan177→178 as one physical split-word continuation rather than inventing punctuation;
- preserve the pending 183→184 boundary without importing Part012;
- do not import remembered, published or web English versions;
- locally ambiguous expressions may be settled conservatively during E28/E29/E30 source-check from verified Tamil context;
- Chapter 12/13 planning titles remain working project titles until their source-check gates close.

Part011 planning glossary holds — **0**.

## Planning integrity

- canonical Tamil changes caused by planning — **0**
- assembled Tamil changes caused by planning — **0**
- Parts001–010 English section changes caused by planning — **0**
- E28 English draft file created in planning — **0**
- E29 English draft file created in planning — **0**
- E30 English draft file created in planning — **0**
- E28 source-check record created in planning — **0**
- E29 source-check record created in planning — **0**
- E30 source-check record created in planning — **0**
- Part012 leakage — **0**
- unresolved planning holds — **0**

## Gate decision

**PART011 ENGLISH TRANSLATION PLANNING / SETUP — COMPLETE / PASS**

## Exact next activity

**E28 — draft + source-check Part011 Chapter 11 `ஓலை கை மாறியது` continuation / scan168.**

Create E28 only from the verified assembled Tamil input, preserve incoming 167→168 provenance without frozen E27 backfill, source-check it against the verified Tamil authority, and create the durable E28 source-check record.

Do not begin E29 until E28 is **SOURCE-CHECKED / COMPLETE**.


## Post-planning synchronization verification

Pre-planning checkpoint:

`e252efe7694abe874d905a74302595a5fabc061b`

Post-planning synchronized checkpoint before this verification record:

`9fecded8a20a09919811004cb3e99403eb64f58b`

Direct repository comparison confirms:

- total commits — **1**
- changed files — **15**
- canonical `pages/` changes — **0**
- assembled Part011 Tamil section-body changes — **0**
- E28 English body file created — **0**
- E29 English body file created — **0**
- E30 English body file created — **0**
- E28 / E29 / E30 source-check records created — **0 / 0 / 0**
- frozen Parts001–010 English-body changes — **0**
- Part012 / scan184 content introduced — **0**
- durable Part011 English planning control — **present**
- reserved sequence — **E28 → E29 → E30**
- E28 state — **RESERVED / NEXT**
- E29 state — **RESERVED**
- E30 state — **RESERVED**
- Chapter 11 title — **The Palm Leaf Changes Hands**
- Chapter 12 working title — **Hunger for Land**
- Chapter 13 working title — **Nedumaran Wavers**
- next-chat frontier — **E28 draft + source-check**

Therefore English planning introduced no canonical Tamil, assembled Tamil, frozen English-body, premature Part011 English-body, or Part012 drift.
