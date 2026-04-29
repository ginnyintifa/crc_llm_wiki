# Wiki Log

Append-only chronological record of all wiki activity.
Format: `## [YYYY-MM-DD] <type> | <description>`
Parse last 5 entries: `grep "^## \[" wiki/log.md | tail -5`

---

## [2026-04-29] query | How does the EMP1 paper advance the Hanahan hallmarks framework?

Filed as analysis: wiki/analyses/emp1-paper-advances-on-hallmarks-framework.md. Covers hallmarks 7 and 9, CAF TME class, immune evasion/co-targeting, and KRAS→plasticity link.

## [2026-04-29] ingest | Cañellas-Socias et al. 2022 — Metastatic recurrence in CRC arises from residual EMP1+ cells

Source page: wiki/sources/canellas-socias-2022-emp1-hrcs.md (complete). Entity created: wiki/entities/EMP1.md. Updated: wiki/concepts/epithelial-mesenchymal-plasticity.md (HRC partial-EMT section added), wiki/concepts/metastatic-cascade.md (HRC as metastasis-initiating population; stage-specific LGR5 vs HRC roles), wiki/overview.md (HRC synthesis; Open Questions; Key Tensions populated), wiki/index.md (source and EMP1 entity added; concept source counts updated). No contradictions with existing wiki — LGR5/metastasis tension explicitly reconciled by stage specificity. Key new tension flagged: YAP does not drive HRC state.

## [2026-04-27] update | Index completed; overview sources field corrected

Updated `wiki/index.md` to catalog all existing pages: 1 source (hanahan-2026-hallmarks-cancer), 4 concept pages (Cancer Hallmarks Framework, Epithelial-Mesenchymal Plasticity, Metastatic Cascade, Tumor Microenvironment). Added stub placeholders for anticipated entity pages (KRAS, TP53, APC, SMAD4, CAFs, TAMs, etc.). Fixed `overview.md` sources frontmatter (was empty; now references hanahan-2026-hallmarks-cancer).

## [2026-04-26] init | Wiki initialized for CRC metastasis research

Directory structure created. CLAUDE.md schema written. Empty index and overview stubs in place. Ready for first ingest.
