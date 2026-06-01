# Wolfgang Rush — Indian Company Law Drafting

**MCPB Desktop Extension** for Indian advocates using Claude Desktop App. Local-execution. Zero data collection.

> *Also available as a Claude Code Plugin:* *[github.com/Wolfgangrush/indian-company-drafting](https://github.com/Wolfgangrush/indian-company-drafting)*

## What this connector does

NCLT (Sections 241-242 oppression, 230-232 schemes, 66 reduction, 252 revival, 213/214 investigation, 245 class action) + NCLAT (421 + IBC 61) + IBC Section 7/9/10 applications.

## Case types

- `nclt-section-241-242-petition` — NCLT oppression and mismanagement petition under Sections 241-242 Companies Act 2013
- `nclt-scheme-of-arrangement` — NCLT scheme of arrangement / amalgamation under Sections 230-232
- `nclt-section-66-reduction-of-capital` — NCLT capital reduction petition under Section 66
- `nclt-section-252-revival-struck-off-company` — NCLT revival of struck-off company under Section 252
- `nclt-section-213-investigation` — NCLT investigation petition under Section 213 / 214
- `nclt-section-245-class-action` — NCLT class action under Section 245
- `nclat-appeal-section-421` — NCLAT appeal under Section 421 Companies Act
- `nclat-appeal-section-61-ibc` — NCLAT appeal under Section 61 IBC
- `ibc-section-9-operational-creditor-application` — IBC Section 9 operational creditor application
- `ibc-section-10-corporate-applicant` — IBC Section 10 corporate applicant initiation

## Install

1. Claude Desktop App → **Settings → Extensions → Install Extension**
2. Select `wolfgang-indian-company-drafting.mcpb`
3. Enable

## System requirements

Claude Desktop App ≥ 0.10.0 · Python ≥ 3.10 · `pandoc` for .docx · `pdftotext` for PDF case-files (optional)

## Privacy

Zero data collection. Three-layer privacy firewall. Canonical policy: **<https://wolfgangrush.github.io/privacy/>**


## ⚠️ AI verification disclaimer · 🔒 Pseudonymisation procedure

> **⚠️ AI can make mistakes — please verify the information before filing.**
> Every draft produced by this connector is a STARTING POINT. The Verifier
> agent runs an anti-hallucination firewall and the Overseer agent runs an
> opposing-counsel review, but neither replaces an advocate's independent
> verification of statutory references, citation accuracy, factual fidelity,
> and Registry-formatting compliance with the user's High Court / forum.
> The advocate filing the pleading remains responsible for the contents.
>
> **🔒 Protected by pseudonymisation procedure.** The Reader agent applies a
> domain-specific privacy firewall as the first step of the pipeline — party
> names, addresses, identifying numbers (FIR / CR / Crime / Suit / Diary /
> SLP / lower-court case numbers), PAN / Aadhaar references, financial
> figures, witness names, and statutory-notice references are substituted
> with structural placeholders BEFORE any downstream agent sees the facts.
> The Drafter, Verifier, Refiner, and Overseer agents process placeholders
> only. Real values are re-substituted at the final docx render step on the
> user's local machine. No real identifying data leaves the case folder.

## License

MIT.

## Publisher

**Rushikesh R. Mahajan**, Advocate, Bombay HC Nagpur, publishing as **Wolfgang Rush**. advrushikeshravindramahajan@gmail.com

## Source

<https://github.com/Wolfgangrush/indian-company-drafting-mcpb>

## Sample cases

See `SAMPLE-CASES/`.
