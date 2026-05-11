---
title: "Epithelial-Mesenchymal Plasticity (EMP)"
type: concept
tags: [EMT, EMP, metastasis, invasion, plasticity, CTCs, liver-mets, peritoneal-mets]
created: 2026-04-26
updated: 2026-04-29
sources: [hanahan-2026-hallmarks-cancer, canellas-socias-2022-emp1-hrcs, heinlein-2026-mapk-wnt-metastasis, riedl-2026-kras-inhibitors-review]
---

# Epithelial-Mesenchymal Plasticity (EMP)

## Definition
Epithelial-mesenchymal plasticity (EMP) is the acquired capability of cancer cells to dynamically switch between epithelial and mesenchymal phenotypic states. This subsumes and refines the older concept of the epithelial-mesenchymal transition (EMT). Unlike the discrete, irreversible EMT that occurs during normal embryogenesis, cancer cells typically exhibit **hybrid EMT states** — simultaneously maintaining both epithelial and mesenchymal characteristics to varying degrees, often dynamically.

The reverse process (mesenchymal → epithelial, MET) also occurs and is relevant to metastatic colonization.

## Relevance to CRC Metastasis

EMP is central to CRC metastatic spread:

1. **Local invasion** — partial EMP enables cancer cells to detach from the epithelial layer, breach the basement membrane, and invade stroma
2. **Intravasation** — mesenchymal features facilitate entry into blood/lymphatic vessels
3. **CTC survival** — hybrid EMT states are enriched in CTCs; CTC clusters (partly epithelial) have higher metastatic efficiency than fully mesenchymal single CTCs
4. **Colonization** — MET (mesenchymal → epithelial re-transition) is required for outgrowth at distant sites (liver, lung, peritoneum)
5. **Therapy resistance** — EMP states correlate with drug resistance, stemness, and immune evasion

## Mechanism

EMP is regulated at multiple levels:

| Level | Examples |
|-------|---------|
| Transcription factors | ZEB1/2, SNAI1/2, TWIST1/2 (mesenchymal inducers); CDH1/E-cadherin (epithelial marker) |
| Signaling pathways | TGF-β (canonical EMT inducer), WNT, Notch, Hedgehog, EGF, HGF |
| Epigenetic | DNA methylation, histone modifications, chromatin remodeling |
| microRNAs | miR-200 family (suppress ZEB; maintain epithelial); miR-34 (suppress SNAI) |
| TME signals | CAF-secreted TGF-β; TAM-secreted EGF; hypoxia via HIF-1α |

Cancer cells do not make a complete, irreversible switch. Instead they occupy a spectrum of hybrid states, with phenotypic plasticity (the hallmark) enabling dynamic movement along this spectrum in response to microenvironmental cues.

## Key Evidence

### HRCs as the CRC partial-EMT cell state
- Cañellas-Socias et al. (2022) identified **High-Relapse Cells (HRCs)** — marked by [[EMP1]] — as the tumour cell population in CRC that embodies partial EMT. HRCs are enriched at invasion fronts and tumour buds, retain full epithelial markers (EPCAM+, E-cadherin+), and do *not* upregulate canonical EMT transcription factors (ZEB1/2, SNAI1/2, TWIST).
- Instead, HRCs express a **partial EMT module**: Lama3, Lamc2, Itga2, Plaur — genes associated with basement membrane invasion and extravasation.
- HRCs also upregulate junctional complex genes: Pcdh1, Dsc2, Clnd4, Jup (plakoglobin) — enabling cluster-based CTC formation (higher metastatic efficiency).
- HRCs are transcriptionally related to basal-like pancreatic cancer and tumour budding cells (KRT17, LAMC2).

### MAPK-high/WNT-low as the transcriptional driver of the HRC/partial-EMT state
- Heinlein et al. (2026) identified the upstream driver of the HRC/EMP1 state: **MAPK pathway activation** via AP-1 TFs (BATF, ATF3, FRA1, JUNB, FOS) directly remodels chromatin at the *Emp1* locus and the broader invasion gene network.
- The MAPK-high state simultaneously suppresses WNT/LGR5 stem programs — explaining the HRC/LGR5+ mutual exclusivity observed in Cañellas-Socias 2022.
- KRAS^G12D inhibition rapidly (3 d) reduces EMP1 expression and reverts the metastatic/partial-EMT transcriptional state, validating MAPK as the governing pathway.

### Other evidence (from Hanahan 2026 framework)
- Hybrid EMT states, not fully mesenchymal cells, have the highest metastatic efficiency in experimental models
- Single-cell transcriptomics of CRC liver metastases reveals heterogeneous EMP states
- SMAD4 loss in CRC (associated with poor prognosis) is linked to TGF-β signaling dysregulation and EMP
- CTC clusters in CRC patients are associated with worse prognosis than single CTCs

## EMP as resistance to KRAS inhibition
Riedl et al. (2026) explicitly identifies EMT as a validated non-genetic resistance mechanism to KRAS^G12C inhibitors:
- Tumor cells under KRAS inhibition pressure can acquire mesenchymal motility and invasiveness via ZEB1, SNAI1/2, TWIST upregulation
- This represents a form of KRAS dependency escape: cells reduce reliance on KRAS signaling by shifting transcriptional programs
- Histologic transformation (related process) also reported: adenocarcinoma → squamous cell carcinoma in NSCLC under KRAS^G12C inhibitor pressure
- This connects directly to the HRC/EMP1 findings: HRCs represent the pre-existing partial-EMT state that enables initial dissemination, while full EMT induction during KRAS inhibition may represent acquired resistance in the metastatic setting

## Debates / Contradictions
- The utility of E-cadherin as an EMT marker is debated — partial loss may be sufficient for invasion without complete EMP
- Whether MET is required for metastatic colonization or whether hybrid states can colonize directly is unresolved in CRC; HRC-to-LGR5 transition during metastatic outgrowth (Cañellas-Socias 2022) supports a de facto MET as metastases grow
- The role of EMP in CRC brain metastasis (rare) vs. liver/peritoneal (common) may differ substantially

## Distinction from Classical EMT
| Classical EMT | EMP (current view) |
|--------------|-------------------|
| Discrete, irreversible transition | Continuous spectrum of hybrid states |
| Epithelial OR mesenchymal | BOTH epithelial AND mesenchymal traits co-present |
| Developmental context (embryogenesis) | Cancer context (dynamic, reversible) |
| Complete loss of E-cadherin | Often partial E-cadherin loss |

## Open Questions
- What transcription factor(s) maintain the HRC/partial-EMT state? (Not YAP, not canonical EMT TFs — identity unknown)
- How does CAF-secreted signalling mechanistically induce EMP1 expression and the HRC state?
- Can EMP states be therapeutically targeted without disrupting normal wound healing?
- Does KRAS mutational status alter EMP dynamics in CRC? (Evidence: KrasG12D CTOs upregulate HRC/EpiHR program)
- What maintains the HRC vs. LGR5+ boundary — is it reversible, and what triggers the switch during outgrowth?

## References
- [[hanahan-2026-hallmarks-cancer]] (framework)
- [[canellas-socias-2022-emp1-hrcs]] (HRC partial-EMT state in CRC; EMP1 as marker)
- [[heinlein-2026-mapk-wnt-metastasis]] (MAPK/AP-1 as upstream driver of HRC/EMP1 partial-EMT state; KRAS inhibition reverts)
