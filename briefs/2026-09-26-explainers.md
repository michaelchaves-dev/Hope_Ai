# Explainer schema retrofit — 2026-09-26

News-only schema add. Not medical advice. No disease cross-off claims. Not a new approvals scout.

## What changed

- `README.md` — added **Product explainer fields** (treat / mechanism / origin if sourced / label-level AEs / one-sentence clinical snapshot / cite).
- `ledger/INNOVATIONS.md` — every named product, device, and research-tool row now has one short **Explainer** paragraph after the headline.
- Standing daily routine updated the same day to require this block on new named products.

## Coverage

| Category | Count (approx.) | Notes |
| --- | --- | --- |
| Named products / devices / research tools with explainer | 57 | Evidence tag kept on headline |
| Process-news rows marked `N/A — process news` | 5 | AWG check, Moonshots check, Expedited IND Pilot, NIH RFI, CBER index |
| Origin note filled (sourced) | GLP-1 class only | Wegovy / Mounjaro / Zepbound / mouse semaglutide study — Gila monster exendin-4 → Byetta lineage (PubMed 21194543 / Eng et al. JBC 1992). All other rows: `origin not sourced this run.` |
| `label AEs not sourced this run` | ~29 | Used when DailyMed/label table was not re-parsed this pass; FDA press AE lists used when available |

## Rows with fuller AE + efficacy snapshots this pass (examples)

Cobenfy (EMERGENT PANSS), Wegovy (STEP 1), Zepbound (SURMOUNT-1), Casgevy (93.5% VOC-free), Leqembi (Clarity AD CDR-SB), Rezdiffra (MAESTRO-NASH), Atebrioz, Onswik, Lyrfigtu, Zanvastro, Journavx, Blujepa, Qfitlia, Brinsupri, Myqorzo, Winrevair, Hemgenix.

## Intentionally not invented

- No folklore origins outside the sourced GLP-1/Byetta lineage.
- No disease cured/crossed-off language.
- Thin 2025 Modeyso/Forzinity rows kept honest with `label AEs not sourced this run` pending deeper label parse.

## Permanent sources (see [`sources/PERMANENT.md`](../sources/PERMANENT.md))

Standing check path reused from daily brief item 10 / README. This schema-retrofit note does not re-fetch AWG or Moonshots; latest verified notes remain in `sources/PERMANENT.md` and daily brief item 10.

## Follow-up for later daily runs

Prefer DailyMed / Drugs@FDA label PDFs when FDA HTML is blocked; replace `label AEs not sourced` lines as labels are opened.
