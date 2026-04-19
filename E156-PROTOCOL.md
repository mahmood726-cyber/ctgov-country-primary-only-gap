# E156 Protocol — `ctgov-country-primary-only-gap`

This repository is the source code and dashboard backing an E156 micro-paper on the [E156 Student Board](https://mahmood726-cyber.github.io/e156/students.html).

---

## `[207]` CT.gov Country Primary-Only Gap

**Type:** methods  |  ESTIMAND: Primary-only-gap stock among older studies missing the primary outcome description field while retaining the detailed description field  
**Data:** 249,507 eligible older closed interventional studies with primary-only-gap stock and rate summaries

### 156-word body

Which country-linked CT.gov portfolios most often leave older study pages without the primary outcome description while keeping the broader detailed-description field? We analysed 249,507 eligible older closed interventional studies from the March 29, 2026 full-registry snapshot and exploded country links. We defined a primary-only gap as missing primary outcome description with detailed description still present, then ranked country-linked portfolios with at least 500 linked studies. The United States led the country-linked primary-only-gap stock table at 13,662 studies, followed by Canada at 2,381, France at 2,233, and Germany at 1,629. Iran had the highest large-country primary-only-gap rate at 18.4 percent, while India reached 15.1 percent and Canada 13.8 percent. Country-linked primary-only gaps show where the endpoint sentence disappears even though the broader study narrative remains visible in older registry records. Country-linked rows are non-exclusive because multinational studies can contribute to more than one national portfolio in registry link tables. They reflect registry link geography rather than jurisdiction.

### Submission metadata

```
Corresponding author: Mahmood Ahmad <mahmood.ahmad2@nhs.net>
ORCID: 0000-0001-9107-3704
Affiliation: Tahir Heart Institute, Rabwah, Pakistan

Links:
  Code:      https://github.com/mahmood726-cyber/ctgov-country-primary-only-gap
  Protocol:  https://github.com/mahmood726-cyber/ctgov-country-primary-only-gap/blob/main/E156-PROTOCOL.md
  Dashboard: https://mahmood726-cyber.github.io/ctgov-country-primary-only-gap/

References (topic pack: CT.gov / ClinicalTrials.gov audit):
  1. Zarin DA, Tse T, Williams RJ, Rajakannan T. 2017. Update on trial registration 11 years after the ICMJE policy was established. N Engl J Med. 376(4):383-391. doi:10.1056/NEJMsr1601330
  2. Anderson ML, Chiswell K, Peterson ED, Tasneem A, Topping J, Califf RM. 2015. Compliance with results reporting at ClinicalTrials.gov. N Engl J Med. 372(11):1031-1039. doi:10.1056/NEJMsa1409364

Data availability: No patient-level data used. Analysis derived exclusively
  from publicly available aggregate records. All source identifiers are in
  the protocol document linked above.

Ethics: Not required. Study uses only publicly available aggregate data; no
  human participants; no patient-identifiable information; no individual-
  participant data. No institutional review board approval sought or required
  under standard research-ethics guidelines for secondary methodological
  research on published literature.

Funding: None.

Competing interests: MA serves on the editorial board of Synthēsis (the
  target journal); MA had no role in editorial decisions on this
  manuscript, which was handled by an independent editor of the journal.

Author contributions (CRediT):
  [STUDENT REWRITER, first author] — Writing – original draft, Writing –
    review & editing, Validation.
  [SUPERVISING FACULTY, last/senior author] — Supervision, Validation,
    Writing – review & editing.
  Mahmood Ahmad (middle author, NOT first or last) — Conceptualization,
    Methodology, Software, Data curation, Formal analysis, Resources.

AI disclosure: Computational tooling (including AI-assisted coding via
  Claude Code [Anthropic]) was used to develop analysis scripts and assist
  with data extraction. The final manuscript was human-written, reviewed,
  and approved by the author; the submitted text is not AI-generated. All
  quantitative claims were verified against source data; cross-validation
  was performed where applicable. The author retains full responsibility for
  the final content.

Preprint: Not preprinted.

Reporting checklist: PRISMA 2020 (methods-paper variant — reports on review corpus).

Target journal: ◆ Synthēsis (https://www.synthesis-medicine.org/index.php/journal)
  Section: Methods Note — submit the 156-word E156 body verbatim as the main text.
  The journal caps main text at ≤400 words; E156's 156-word, 7-sentence
  contract sits well inside that ceiling. Do NOT pad to 400 — the
  micro-paper length is the point of the format.

Manuscript license: CC-BY-4.0.
Code license: MIT.

SUBMITTED: [ ]
```


---

_Auto-generated from the workbook by `C:/E156/scripts/create_missing_protocols.py`. If something is wrong, edit `rewrite-workbook.txt` and re-run the script — it will overwrite this file via the GitHub API._