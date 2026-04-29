---
title: "EMP1 (Epithelial Membrane Protein 1)"
type: entity
tags: [biomarker, invasion, intravasation, colonization, liver-mets, lung-mets, EMT, cancer-stem-cell, high-evidence]
created: 2026-04-28
updated: 2026-04-28
sources: [canellas-socias-2022-emp1-hrcs]
---

# EMP1 (Epithelial Membrane Protein 1)

## Overview
EMP1 (encoded by *EMP1* in human, *Emp1* in mouse) is a tetraspan membrane protein and component of epithelial tight junctions. In the context of CRC metastasis, EMP1 is the defining marker of **High-Relapse Cells (HRCs)** — the tumour epithelial cell state responsible for metastatic dissemination and initial colonisation of distant organs. Its discovery as the top hit from the EpiHR prognostic gene signature makes it a candidate biomarker and potential therapeutic target.

## Role in CRC Metastasis
EMP1high cells represent the **metastasis-initiating population** in CRC:
- Enriched at invasion fronts, tumour buds, and stroma-contacting clusters in primary CRCs
- Exclusively populate liver micrometastases immediately after dissemination
- Give rise to LGR5+ stem-like cells and proliferative cell progeny during metastatic outgrowth
- Expression decreases as metastases grow (inverse relationship with LGR5 gain)
- EMP1high cells near blood vessels in primary CRCs suggest a haematogenous/lymphatic dissemination route

## Mechanism
EMP1 is a component of **tight junctions** (established by Durgan et al. 2015 and Bangsow et al. 2008). In the HRC context:

- HRCs retain full epithelial identity (EPCAM+, E-cadherin+, EMP1+) — no canonical EMT
- Instead, HRCs express a **partial EMT module**: Lama3, Lamc2, Itga2, Plaur (associated with invasion, extravasation)
- Multiple junctional complex proteins co-upregulated in coreHRC: Pcdh1, Dsc2, Clnd4, Jup (plakoglobin)
- Plakoglobin (Jup) enables CTC cluster formation and confers enhanced metastatic ability (analogous to breast cancer)
- HRCs share transcriptional identity with basal-like pancreatic cancer cells and tumour budding cells (KRT17, LAMC2)

The EMP1high state is distinct from:
- LGR5+ cancer stem cells (mutually exclusive; HRCs lack WNT/ISC signature)
- Classical EMT (no upregulation of ZEB1/2, SNAI1/2, TWIST)
- YAP-driven fetal intestinal progenitor state (only 3/22 YAP core genes overlap; YAP KD does not affect Emp1)

## Clinical Relevance / Biomarker Use
- The **EpiHR signature** (99 epithelial-specific poor-prognosis genes including EMP1) independently predicts CRC relapse: HR = 2.26 per +1 SD, P = 1.2×10⁻⁷
- EpiHR is prognostic within each CMS (consensus molecular subtype), stratifying patients into high vs. low risk across subtypes
- EpiHR associates with right-sided CRC and AJCC stages III–IV
- LAMC2 expression (a coreHRC gene) correlates with EMP1 mRNA in CRC patient samples; LAMC2 is a known tumour budding marker
- EMP1 mRNA detectable by RNAscope FISH in human CRC tissue; elevated at invasion fronts (LGR5 marks cores)

## Therapeutic Targeting
Direct targeting of EMP1 has not been validated clinically, but proof-of-concept in mouse models:
- Genetic ablation of EMP1high cells (iCasp9 system) before surgery prevents metastatic relapse in AKTP, AKP, and AKPS models
- EMP1 is a surface-accessible protein (tetraspan membrane component) — potential target for antibody-drug conjugates or CAR-T if tumour-selective expression validated
- Indirect: neoadjuvant immunotherapy exploits the T-cell vulnerability of EMP1high micrometastases

## Key Findings / Evidence
| Finding | Model | Source |
|---------|-------|--------|
| EMP1 top marker of HRC/EpiHR signature | Human scRNA-seq (SMC, KUL) + AKTP mouse | [[canellas-socias-2022-emp1-hrcs]] |
| EMP1high cells exclusively populate liver micrometastases | AKTP mouse (iCT reporter) | [[canellas-socias-2022-emp1-hrcs]] |
| Ablation of EMP1high before surgery prevents relapse (5/22 vs 26/33) | AKTP mouse | [[canellas-socias-2022-emp1-hrcs]] |
| CAF co-culture induces 6-fold increase in EMP1high cells | AKTP MTOs in vitro | [[canellas-socias-2022-emp1-hrcs]] |
| KRAS mutations correlate with EpiHR/EMP1 expression | TCGA COAD + CRISPR CTOs | [[canellas-socias-2022-emp1-hrcs]] |
| EMP1 marks invasion fronts in human CRC (RNAscope FISH) | Patient tissue | [[canellas-socias-2022-emp1-hrcs]] |

## Open Questions
- What transcription factor(s) drive the EMP1high/HRC state? (Not YAP, not canonical EMT TFs)
- Is EMP1 itself functionally required, or is it a passive marker?
- How does the CAF-HRC interaction mechanistically work (paracrine signals)?
- Can EMP1 surface expression be exploited for targeted delivery in CRC?
- Does EMP1 expression in the primary tumour predict response to neoadjuvant immunotherapy?

## References
- [[canellas-socias-2022-emp1-hrcs]]
