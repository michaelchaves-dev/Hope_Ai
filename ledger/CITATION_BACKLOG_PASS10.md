# Citation backlog pass 10 (primary FDA URLs — labels)

Reuse-before-invent checklist continuing [`CITATION_BACKLOG.md`](CITATION_BACKLOG.md) (draft PR #10), [`CITATION_BACKLOG_PASS2.md`](CITATION_BACKLOG_PASS2.md) (draft PR #11), [`CITATION_BACKLOG_PASS3.md`](CITATION_BACKLOG_PASS3.md) (draft PR #12), [`CITATION_BACKLOG_PASS4.md`](CITATION_BACKLOG_PASS4.md) (draft PR #13), [`CITATION_BACKLOG_PASS5.md`](CITATION_BACKLOG_PASS5.md) (draft PR #14), [`CITATION_BACKLOG_PASS6.md`](CITATION_BACKLOG_PASS6.md) (draft PR #15), [`CITATION_BACKLOG_PASS7.md`](CITATION_BACKLOG_PASS7.md) (draft PR #16), [`CITATION_BACKLOG_PASS8.md`](CITATION_BACKLOG_PASS8.md) (draft PR #17), and [`CITATION_BACKLOG_PASS9.md`](CITATION_BACKLOG_PASS9.md) (draft PR #18). Novel-drug **year-index** rows still on `main` that now have a verified product-specific FDA primary ready to swap into [`INNOVATIONS.md`](INNOVATIONS.md).

Frozen baseline on `main` @ `2547030`: `year_index_url_count` = **26**.

Open draft PRs #2 / #3 / #10 / #11 / #12 / #13 / #14 / #15 / #16 / #17 / #18 already cover other year-index → primary work; do not duplicate those rows here.

## Verified ready (this pass) — apply next after QBM+MF+BKT+Mounjaro+JKL+WDK+ZDB+SPQ+Imdelltra to beat toward 26 → 0

| Product | Current (year-index) | Verified primary |
| --- | --- | --- |
| Cabenuva (cabotegravir + rilpivirine) | `novel-drug-approvals-2021` | https://www.accessdata.fda.gov/drugsatfda_docs/label/2021/212888s000lbl.pdf |
| Vyvgart (efgartigimod alfa-fcab) | `novel-drug-approvals-2021` | https://www.accessdata.fda.gov/drugsatfda_docs/label/2021/761195s000lbl.pdf |
| Lumakras (sotorasib) | `novel-drug-approvals-2021` | https://www.accessdata.fda.gov/drugsatfda_docs/label/2021/214665s000lbl.pdf |
| Aduhelm (aducanumab-avwa) | `novel-drug-approvals-2021` | https://www.accessdata.fda.gov/drugsatfda_docs/label/2021/761178s000lbl.pdf |

Also update each row’s Explainer cite clause to match (original approval prescribing information / label).

## Notes

- Dedicated Drug Trials Snapshot HTML pages for these four were still not found live this pass (common `drug-trials-snapshots-*` slugs, `drug-approvals-and-databases/drug-trials-snapshot(s)-*`, and `development-approval-process-drugs/drug-trials-snapshots-*` variants). The 2021 Snapshots Summary Report (https://www.fda.gov/media/158482/download) mentions all four in aggregate demographics but is not a product-page primary. Per README cite guidance (“label, FDA page, or paper”) and prior backlog pattern (e.g. Myqorzo FDA news page in PR #10), original approval **prescribing information** PDFs on `accessdata.fda.gov` are verified as primary product pages that beat year-index.
- **Cabenuva** label (NDA 212888, Initial U.S. Approval 2021): complete long-acting injectable HIV-1 regimen for virologically suppressed adults; pivotal FLAIR + ATLAS (n=1,182 pooled); common AEs include injection site reactions, pyrexia, fatigue, headache, musculoskeletal pain, nausea, sleep disorders, dizziness, rash.
- **Vyvgart** label (BLA 761195, Initial U.S. Approval 2021): gMG in AChR-Ab+ adults; Study 1 MG-ADL responders 67.7% vs 29.7% placebo in first cycle; common AEs (≥10%) respiratory tract infection, headache, UTI.
- **Lumakras** label (NDA 214665, Initial U.S. Approval 2021): KRAS G12C NSCLC after prior systemic therapy (accelerated); CodeBreaK 100 ORR 36%, median DOR 10.0 months; common AEs (≥20%) diarrhea, musculoskeletal pain, nausea, fatigue, hepatotoxicity, cough.
- **Aduhelm** label (BLA 761178, Initial U.S. Approval 2021): Alzheimer’s (accelerated; amyloid plaque reduction); ARIA is the key imaging-related risk; commercial discontinuation is historical context only, not a cross-off claim.
- **Komzifti explainer correction (apply with PASS3 URL):** main still says “KMT2A-rearranged AML”; live Snapshot https://www.fda.gov/drugs/drug-trials-snapshots/drug-trials-snapshots-komzifti confirms **NPM1-mutated** relapsed/refractory AML (CR+CRh 21.4%). Fix headline/Explainer wording on ledger apply — not rewritten in this file-only PR.
- Do not invent Snapshot HTML URLs; prefer a live Snapshot page later if one reappears, but these labels are ready to apply now.
- Full ledger apply for prior backlogs remains deferred; Contents upload of `INNOVATIONS.md` is still the preferred path when available.
