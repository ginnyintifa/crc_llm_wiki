# Wiki Log

Append-only chronological record of all wiki activity.
Format: `## [YYYY-MM-DD] <type> | <description>`
Parse last 5 entries: `grep "^## \[" wiki/log.md | tail -5`

---

## [2026-08-22] query | How does Heinlein 2026 add value to the Hanahan 2026 hallmarks review?

Analysis page created: wiki/analyses/heinlein-paper-advances-on-hallmarks-framework.md. Key points: CIN (chromosomal amplification of MAPK genes, not new mutations) shown to causally drive hallmark 1; AP-1 TF network identified as the reversible chromatin toggle underlying hallmark 7 (plasticity); direct demonstration of Hanahan's "no universal metastasis genes, CIN+EMP drive invasion" claim; complication flagged for hallmark co-targeting rationale — single-node KRAS/MAPK inhibition alone reverted plasticity, metastasis, and an immune-evasion phenotype (MHC-I), suggesting these hallmarks are coupled rather than independent in this system; MAPK+WNT activity signature validated as prognostic (AVANT, CALGB cohorts) where KRAS mutation status alone was not. Index updated.

## [2026-05-11] ingest | Riedl et al. 2026 — Emerging landscape of KRAS inhibitors in cancer treatment

Source page created: wiki/sources/riedl-2026-kras-inhibitors-review.md. Entity updated: wiki/entities/KRAS.md (therapeutic targeting section substantially rewritten: three drug classes, CRC clinical data, resistance mechanisms). Concept updated: wiki/concepts/epithelial-mesenchymal-plasticity.md (EMT as KRAS inhibitor resistance mechanism added). Overview updated: treatment landscape updated with sotorasib + panitumumab FDA approval, G12D agents, YAP co-inhibition. Index + log updated. Key tension resolved: YAP molecular mechanism after KRAS inhibition (Scribble → SHOC2/PP1c → YAP) now explains the Cañellas-Socias/Heinlein discrepancy. MRTX1133 Phase 1 termination noted.

## [2026-05-10] ingest | Heinlein et al. 2026 — A high-MAPK, low-WNT cell state drives metastatic dissemination in colorectal cancer

Source page created: wiki/sources/heinlein-2026-mapk-wnt-metastasis.md. Entity created: wiki/entities/KRAS.md. Entity updated: wiki/entities/EMP1.md (MAPK/AP-1 upstream regulation section added; evidence table expanded). Concept pages updated: epithelial-mesenchymal-plasticity.md (MAPK-high as driver of HRC partial-EMT), metastatic-cascade.md (MAPK-high/WNT-low transcriptional identity). Overview updated: MAPK-WNT axis section added; Key Tensions expanded (YAP reconciled, prognostic markers tension added). Index updated: source, KRAS entity, concept source counts. Key tension flagged: YAP elevated in MAPK-high cells (Heinlein) vs YAP KD does not affect EMP1 (Cañellas-Socias) — partially reconciled.

## [2026-04-29] query | How does the EMP1 paper advance the Hanahan hallmarks framework?

Filed as analysis: wiki/analyses/emp1-paper-advances-on-hallmarks-framework.md. Covers hallmarks 7 and 9, CAF TME class, immune evasion/co-targeting, and KRAS→plasticity link.

## [2026-04-29] ingest | Cañellas-Socias et al. 2022 — Metastatic recurrence in CRC arises from residual EMP1+ cells

Source page: wiki/sources/canellas-socias-2022-emp1-hrcs.md (complete). Entity created: wiki/entities/EMP1.md. Updated: wiki/concepts/epithelial-mesenchymal-plasticity.md (HRC partial-EMT section added), wiki/concepts/metastatic-cascade.md (HRC as metastasis-initiating population; stage-specific LGR5 vs HRC roles), wiki/overview.md (HRC synthesis; Open Questions; Key Tensions populated), wiki/index.md (source and EMP1 entity added; concept source counts updated). No contradictions with existing wiki — LGR5/metastasis tension explicitly reconciled by stage specificity. Key new tension flagged: YAP does not drive HRC state.

## [2026-04-27] update | Index completed; overview sources field corrected

Updated `wiki/index.md` to catalog all existing pages: 1 source (hanahan-2026-hallmarks-cancer), 4 concept pages (Cancer Hallmarks Framework, Epithelial-Mesenchymal Plasticity, Metastatic Cascade, Tumor Microenvironment). Added stub placeholders for anticipated entity pages (KRAS, TP53, APC, SMAD4, CAFs, TAMs, etc.). Fixed `overview.md` sources frontmatter (was empty; now references hanahan-2026-hallmarks-cancer).

## [2026-04-26] init | Wiki initialized for CRC metastasis research

Directory structure created. CLAUDE.md schema written. Empty index and overview stubs in place. Ready for first ingest.
