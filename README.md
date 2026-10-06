# Hope_Ai

Public, news-only ledger of medical and science innovation.

This repo tracks real progress with sources and evidence tags. It does **not** claim that any disease is cured or "crossed off." It is **not** medical advice.

## How to read evidence tags

| Tag | Meaning |
| --- | --- |
| `approved` | Regulator-approved product or indication (e.g. FDA label change) |
| `late-trial` | Late-stage / pivotal clinical evidence (Phase 3 or equivalent published results) |
| `early` | Early research, Phase 1/2, preclinical, or exploratory |
| `device` | Medical device / implant / BCI pathway (designation, trial, or clearance) |
| `news` | Policy, process, pipeline, or secondary reporting worth tracking |

## Product explainer fields

Every named medicine, biologic, gene therapy, implant, or notable candidate row in [`ledger/INNOVATIONS.md`](ledger/INNOVATIONS.md) includes **one short paragraph** after the headline covering, in order:

1. **What it treats** — disease or condition
2. **Active ingredient or mechanism** — generic name + class
3. **Origin note** — only when sourced (example pattern: GLP-1 class ← Gila monster exendin-4 / Byetta lineage). If unknown, write exactly `origin not sourced this run.` Never invent folklore.
4. **Reported side effects** — label-level common and serious only (not a scare list). If the label is unreachable, write `label AEs not sourced this run.`
5. **Clinical-result snapshot** — one sentence: trial name or approval basis + main efficacy number if published
6. **Cite** — label, FDA page, or paper (URL on the following line is fine)

Keep the evidence tag on the headline. Pure process/news rows (IND pilots, RFIs, check-log items, indexes) get: `Explainer: N/A — process news.` Research tools without a marketed product still get a short what-it-is paragraph from the paper. Do not invent origins or side effects. Keep each explainer to one short paragraph so the ledger stays readable.

## Layout

- [`ledger/INNOVATIONS.md`](ledger/INNOVATIONS.md) — running list, newest first
- [`sources/PERMANENT.md`](sources/PERMANENT.md) — Alex Wissner-Gross Innermost Loop + Moonshots check log
- [`briefs/YYYY-MM-DD.md`](briefs/) — daily scout notes
- [`briefs/weekly/YYYY-Www.md`](briefs/weekly/) — Sunday public hope brief

## Cadence

- Daily scout → commit brief + update ledger (08:07 ET); new named products must include the explainer paragraph
- Sunday public brief in-repo (09:07 ET)
- No social posts unless the owner names another forum

Owner: [michaelchaves-dev](https://github.com/michaelchaves-dev)

<!-- SAS-IP-FOOTER-v1 -->
---
**Subtract Architect Studios™**  
Copyright © 2026 Michael F. Chaves. All rights reserved in original Subtract Architect Studios materials except as expressly licensed. See [IP_NOTICE.md](./IP_NOTICE.md). Existing open-source and third-party licenses remain controlling for materials they cover.
