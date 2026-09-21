# English Translation Plan — ரோமாபுரிப் பாண்டியன் / Part001

Status: **PLANNING / SETUP — COMPLETE / PASS**

This is the control plan for the project-created English translation of **Part001 only**.

## Authority hierarchy

1. `works/romapuri-pandian/pages/` — canonical audited Tamil; controlling authority.
2. `works/romapuri-pandian/sections/` — **PASS / CLOSED** assembled Tamil reading layer.
3. `works/romapuri-pandian/translations/en/` — derived project-created English only.

If English conflicts with canonical Tamil, Tamil governs.

English work must never silently correct, regularize, modernize, fact-correct or rewrite the Tamil source layer.

## Translation objective

Produce readable English that remains reversible to the verified Part001 Tamil evidence.

Preserve:

- speaker and narrator agency;
- chronology and knowledge state;
- rhetorical questions, repetition, exclamations, irony and emphatic phrasing;
- paragraph and displayed-text structure where meaningful;
- source-visible section structure;
- source-specific names, titles, offices and place names;
- historical, literary and political framing as presented by the source;
- quoted verse only from the verified project Tamil;
- source-visible English already printed in bibliographic matter;
- the open Part001 ending at scan17.

Do not add explanatory history, biography, politics, literary criticism or factual reconciliation inside translation prose unless the Tamil source supplies it.

## Verified Tamil inputs

Part001 assembled Tamil contains **6 verified section files**:

1. `../../sections/00-front-matter.md` — scans1–4
2. `../../sections/01-moondram-pathippin-munnurai.md` — scan5
3. `../../sections/02-kaanikkai.md` — scans6–7
4. `../../sections/03-pathippurai.md` — scan8
5. `../../sections/04-devaneyap-paavanar-thalaimai-urai.md` — scans9–11
6. `../../sections/05-ananthanarayanan-paarattu-urai.md` — scans12–17

Scan2 is copy-specific donation-label material and is not rendered in the maintained assembled publication-reading layer. No separate English translation unit is created for that copy-specific label.

## Reserved Part001 English units

| Batch | Tamil input | Planned English file | Scans | Planning state |
|---|---|---|---:|---|
| **E1** | `../../sections/00-front-matter.md` | `sections/00-front-matter.md` | 1–4 | **RESERVED / NEXT** |
| **E2** | `../../sections/01-moondram-pathippin-munnurai.md` | `sections/01-preface-to-the-third-edition.md` | 5 | **RESERVED** |
| **E3** | `../../sections/02-kaanikkai.md` | `sections/02-dedication.md` | 6–7 | **RESERVED** |
| **E4** | `../../sections/03-pathippurai.md` | `sections/03-publishers-note.md` | 8 | **RESERVED** |
| **E5** | `../../sections/04-devaneyap-paavanar-thalaimai-urai.md` | `sections/04-devaneya-pavanar-presidential-address.md` | 9–11 | **RESERVED** |
| **E6** | `../../sections/05-ananthanarayanan-paarattu-urai.md` | `sections/05-ananthanarayanan-appreciation-address.md` | 12–17 | **RESERVED** |

Batch discipline:

**E1 closes draft + source-check before E2 begins; E2 before E3; E3 before E4; E4 before E5; E5 before E6.**

No batch may be marked complete merely because a draft exists.

## Names, titles and source variants

The glossary uses conservative source-facing project romanizations.

Initial locked handling includes:

- `ரோமாபுரிப் பாண்டியன்` → **Romapuri Pandiyan**
- `கலைஞர் மு. கருணாநிதி` → **Kalaignar M. Karunanidhi**
- `தேவநேயப் பாவாணர்` → **Devaneya Pavanar**
- `அனந்த நாராயணன்` / `அனந்தநாராயணன்` → **Ananthanarayanan** unless source spacing must be represented in a quoted bibliographic form
- `கவியரசு கண்ணதாசன்` → **Kaviyarasu Kannadasan**
- source-visible work titles and literary names are handled in `GLOSSARY.md`

Do not normalize a source-sensitive Tamil form merely because an external spelling is more familiar.

## Section-title handling

Working English section labels:

- `மூன்றாம் பதிப்பின் முன்னுரை` → **Preface to the Third Edition**
- `காணிக்கை` → **Dedication**
- `பதிப்புரை` → **Publisher's Note**
- `தேவநேயப் பாவாணர் தலைமை உரை` → **Devaneya Pavanar's Presidential Address**
- `அனந்தநாராயணன் பாராட்டு உரை` → **Ananthanarayanan's Appreciation Address**

These are project English labels. Tamil section metadata remains authoritative.

## Quotations and verse

Translate only from verified project Tamil.

Rules:

- preserve meaningful lineation;
- preserve quotation boundaries;
- do not import published, remembered or web English versions;
- if a quoted literary line is difficult or ambiguous, translate conservatively from the canonical Tamil and record any unresolved hold;
- source claims within speeches remain source-attributed speech, not project assertions.

This rule applies especially to the Tirukkural quotations and the Kalinkattupparani verse in the speeches.

## Source-visible English

Where the source itself already prints English bibliographic or quoted wording, preserve that source-visible English rather than re-translating it through Tamil.

Examples include bibliographic matter on scan4 and the quoted English proverb on scan12.

## Political / historical source framing

Part001 contains historical and political statements inside authorial front matter and speeches.

English must:

- translate those statements as source voice;
- preserve attribution and rhetorical force;
- not insert external verification, endorsement or correction into translation prose;
- not silently modernize offices, party labels or political descriptions.

## Cross-page and Part-boundary rules

Verified internal joins remain represented naturally in English without losing provenance.

Special internal join:
- scans12→13: canonical Tamil `வந்திருக்கின்` + `றன.` = assembled `வந்திருக்கின்றன.`

Permanent outgoing Part001 rule:
- scan17 ends `ஜராத் என்ற அவளது பணிப்பெண்ணும் அது`;
- **17→18 = GENUINE CONTINUATION / AUDITED**;
- scan18 belongs to Part002;
- no scan18 wording may be translated or inferred in Part001;
- E6 must end visibly incomplete in English.

## Source-check requirements per batch

Each E-batch closes only after checking:

1. complete sentence/paragraph coverage against its Tamil section;
2. names/titles against `GLOSSARY.md`;
3. quotation and verse structure;
4. source-sensitive historical/political framing;
5. no added explanation;
6. no omitted Tamil meaning;
7. no Part002 leakage;
8. canonical/assembled Tamil mutations caused by English work = **0**.

A durable `E#_SOURCE_CHECK.md` record is created when each batch closes.

## Post-drafting sequence

After E6 closes:

1. whole-Part glossary reconciliation;
2. English editorial review;
3. whole-Part bilingual review against verified Tamil;
4. release/readiness report;
5. release-ready synchronization;
6. no-post-release textual-drift verification;
7. Part001 final closure / freeze.

## Exact next activity

**E1 — draft + source-check `00-front-matter.md` / scans1–4.**

Do not begin E2 until E1 is **SOURCE-CHECKED / COMPLETE**. Do not begin Part002 transcription.
