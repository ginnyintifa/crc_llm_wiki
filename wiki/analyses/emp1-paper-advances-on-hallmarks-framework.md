---
title: "How the EMP1 paper advances the Hanahan hallmarks framework"
type: analysis
tags: [EMT, invasion, colonization, tumor-microenvironment, caf, immune-evasion, immunotherapy, mutation, driver-gene, plasticity]
created: 2026-04-29
updated: 2026-04-29
sources: [canellas-socias-2022-emp1-hrcs, hanahan-2026-hallmarks-cancer]
---

# How the EMP1 paper advances the Hanahan hallmarks framework

**Query:** Does Cañellas-Socias et al. (2022) advance any specific points made in the Hanahan (2026) hallmarks review?

**Short answer:** Yes — the EMP1 paper takes three things Hanahan describes as *principles* (plasticity-driven metastasis, CAF–cancer crosstalk, and timed immune evasion) and instantiates all three in a single, causally validated CRC system. It also adds a specific KRAS–plasticity link that the hallmarks framework only gestures at.

---

## Hallmark 7 — Unlocking phenotypic plasticity

Hanahan describes hybrid EMP states as a key plasticity mechanism but does not identify the responsible cell population in any specific cancer. The EMP1 paper gives CRC concrete cellular resolution: **HRCs ([[EMP1]]-high) are the hybrid-EMT state**, defined not by canonical EMT transcription factors (ZEB1/2, SNAI1/2 — which Hanahan lists) but by a distinct partial-EMT module (Lama2, Lamc2, Itga2, Plaur) while retaining E-cadherin and EPCAM. This refines the hallmark from an abstract concept to a named, trackable, ablatable cell population.

## Hallmark 9 — Activating invasion and metastasis

Hanahan's key claim: *no universal metastasis-specific driver genes exist*; instead, non-genetic mechanisms like EMP and cell plasticity drive the cascade. The EMP1 paper is close to a direct experimental proof — metastatic relapse is driven not by a new mutation but by a **cell state** (EMP1-high HRCs). The paper also resolves an ambiguity the hallmarks framework leaves open — *which cells initiate vs. sustain metastases* — with a stage-specific answer:

| Stage | Dominant population | Causal evidence |
|-------|--------------------|-----------------| 
| Seeding from primary tumour | HRCs (EMP1-high) | Ablation before surgery prevents relapse |
| Micrometastasis initiation | HRCs at apex of cellular hierarchy | CellRank pseudotime (scRNA-seq) |
| Macrometastatic outgrowth | LGR5+ stem-like cells | LGR5 ablation halts outgrowth but not seeding |

## TME cell class 3 — CAFs

Hanahan describes CAFs as remodeling ECM and suppressing immunity but treats their role in inducing cancer cell plasticity states only abstractly. The EMP1 paper is specific:
- CAF co-culture induces a **6-fold increase in EMP1-high cells** in vitro
- α-SMA⁺ CAFs physically surround EMP1-high invasion fronts in vivo
- HRC abundance correlates with CAF abundance in patient scRNA-seq (Pearson correlation, SMC cohort)

This makes CAF-driven HRC induction a concrete mechanistic instantiation of the general CAF–cancer crosstalk principle.

## Hallmark 8 — Evading immune destruction + Hallmark co-targeting

Hanahan frames T cell exclusion and immunosuppressive TME as a hallmark, and proposes ICI + TME reprogramming as a future co-targeting strategy. The EMP1 paper adds **temporal resolution** absent from the framework:

- Micrometastases: T-cell infiltrated, PD-L1 high, interferon-response genes upregulated in HRCs — *vulnerable*
- As metastases grow: T cells excluded to periphery; CAFs (α-SMA⁺, POSTN⁺) and macrophages (CD68⁺) recruited — *resistant*

Consequence: neoadjuvant anti-PD1 + anti-CTLA4 (before surgery, targeting residual micrometastatic disease) prevents relapse (2/9 vs. 13/17 relapsed). The same regimen applied 2 weeks post-surgery fails completely. This is the most therapeutically actionable advance on Hanahan's co-targeting rationale in the entire paper — it shows that co-targeting works but only within a specific temporal window, a nuance the framework does not capture.

## KRAS → plasticity link

Hanahan associates KRAS with hallmark 1 (proliferative signaling) and broadly notes it associates with "all 9 hallmarks." The EMP1 paper adds a specific link Hanahan does not make: **KRAS mutations (particularly G12D) directly upregulate the HRC/EpiHR transcriptional program** (TCGA COAD analysis; confirmed in CRISPR-derived CTOs). This connects a canonical CRC driver mutation to the invasive cell state — a concrete example of Hanahan's claim that oncogenic mutations co-opt multiple hallmarks simultaneously.

---

## Summary table

| Hanahan point | Status in hallmarks paper | Advance from EMP1 paper |
|---------------|--------------------------|------------------------|
| Hybrid EMP states drive plasticity | Stated as principle | HRCs named, molecularly defined, causally tested |
| No universal metastasis genes; cell states matter | Stated as principle | Directly demonstrated in CRC relapse model |
| CAFs induce cancer cell plasticity | Implied | Shown mechanistically; quantified; correlated in patients |
| T cell exclusion enables immune evasion | Stated as principle | Temporal dynamics resolved; vulnerability window identified |
| ICI + TME co-targeting as future strategy | Proposed | Validated in MSS CRC — with timing constraint |
| KRAS associates with multiple hallmarks broadly | Broad claim | Specific KRAS → HRC/EpiHR link demonstrated |

## References
- [[canellas-socias-2022-emp1-hrcs]]
- [[hanahan-2026-hallmarks-cancer]]
