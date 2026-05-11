---
title: "The Metastatic Cascade"
type: concept
tags: [metastasis, invasion, intravasation, extravasation, colonization, dormancy, CTC, premetastatic-niche]
created: 2026-04-26
updated: 2026-04-29
sources: [hanahan-2026-hallmarks-cancer, canellas-socias-2022-emp1-hrcs, heinlein-2026-mapk-wnt-metastasis]
---

# The Metastatic Cascade

## Definition
The metastatic cascade is the multistep pathway by which cancer cells disseminate from a primary tumor and colonize distant organs to form secondary tumors (metastases). It is the primary driver of cancer mortality, including in CRC where ~50% of patients develop metastases. The cascade involves sequential steps of adaptation and survival, each representing a distinct bottleneck.

## Steps of the Cascade

### 1. Local invasion
- Cancer cells acquire invasive phenotypes (EMP, matrix remodeling)
- ECM degradation by matrix metalloproteinases (MMPs)
- Basement membrane breach
- Migration through stroma

### 2. Intravasation
- Entry into tumor blood or lymphatic vessels
- Requires mesenchymal phenotype features (see [[Epithelial-Mesenchymal Plasticity]])
- Facilitated by leaky tumor angiogenic vasculature (VEGFA-dependent)
- TAMs assist: "TMEM" doorways (tumor microenvironment of metastasis)

### 3. Survival in circulation (as CTCs)
- Most CTCs die; survival is the exception
- Mechanisms: anoikis resistance, platelet coating (immune camouflage), CTC clustering
- CTC clusters have higher metastatic efficiency than single CTCs; partial epithelial phenotype retained

### 4. Extravasation
- Arrest in target organ microvessels
- Cancer cell-vessel wall interactions (selectins, integrins)
- Active extravasation vs. mechanical trapping

### 5. Colonization (dormancy vs. outgrowth)
- Disseminated tumor cells (DTCs) may remain **dormant** for years to decades
- Dormancy maintained by: immune surveillance, failure to induce angiogenesis, paracrine growth suppression, metabolic insufficiency
- Outgrowth requires: niche support, immune evasion, angiogenesis induction, metabolic adaptation
- MET (mesenchymal → epithelial) may be required for proliferative outgrowth

### Premetastatic Niche
An early step: primary tumors secrete factors into circulation that reprogram distant tissue vasculature and immune cells, creating a permissive microenvironment before cancer cells arrive. Key mediators include tumor-derived exosomes, cytokines, and growth factors.

## Cellular Identity of the Metastasis-Initiating Population in CRC

A key open question — *which cell type seeds metastases?* — has been directly addressed for CRC:

- **[[EMP1]]-high HRCs (High-Relapse Cells)** are the metastasis-initiating population. They express the EpiHR signature (99-gene epithelial poor-prognosis set), populate invasion fronts and tumour buds, and exclusively populate liver micrometastases immediately after dissemination (Cañellas-Socias et al. 2022).
- **HRCs are distinct from LGR5+ cancer stem cells**: mutually exclusive UMAP distributions; HRCs lack the WNT/ISC transcriptional program.
- The **transcriptional identity** of HRCs is a **MAPK-high, WNT-low** state driven by AP-1 TFs (BATF, ATF3, FRA1, JUNB, FOS — downstream MAPK effectors) — identified by Heinlein et al. (2026) as the upstream regulator the Cañellas-Socias paper could not determine.
- **Stage-specific cellular roles** (Cañellas-Socias 2022):
  - Seeding/dissemination: HRCs (EMP1-high) — ablation before surgery prevents relapse
  - Micrometastasis initiation: HRCs occupy the apex of the cellular hierarchy
  - Outgrowth/macrometastasis: LGR5+ cells take over as the dominant cell type; HRCs give rise to LGR5+ progeny over time
- **LGR5+ cells are dispensable for dissemination** but required for outgrowth — ablating LGR5+ cells in the primary tumour does not prevent metastatic relapse, but does halt outgrowth after direct intrasplenic inoculation.
- This resolves a prior apparent contradiction: de Sousa e Melo et al. (2017) showed LGR5+ cells needed for metastasis using intrasplenic injection (a colonization/outgrowth assay); Cañellas-Socias shows HRCs needed at the *seeding* step from the primary tumour.

### Cluster-based dissemination
HRCs upregulate plakoglobin (Jup/Dsc2), enabling CTC cluster formation — analogous to breast cancer, where clusters have higher metastatic efficiency than single CTCs.

## CRC-Specific Metastatic Patterns

### Liver metastasis (most common; ~50–70% of mCRC)
- Portal venous drainage from colon → liver is the anatomical route
- Hepatic stellate cells (activated → CAF-like) form the metastatic niche
- KRAS/BRAF mutations, SMAD4 loss associated with higher liver metastatic risk
- Vascular co-option (no angiogenesis) is a key mechanism of liver colonization in CRC
- Surgical resection of liver mets is the only potentially curative approach in selected patients

### Lung metastasis (second most common)
- More common in rectal cancer (systemic venous drainage bypasses portal circulation)
- Generally better prognosis than liver mets when resectable

### Peritoneal metastasis
- Transcoelomic spread; shed cells implant on peritoneal surfaces
- SMAD4 loss (CRC) specifically associated with peritoneal spread
- MSS (microsatellite stable) predominates; immunotherapy largely ineffective
- Treated with HIPEC + CRS in selected patients; limited systemic options

### Lymph node metastasis
- N-stage is key prognostic determinant; drives adjuvant chemotherapy decisions
- Locoregional spread preceding hematogenous dissemination

## Genetics of Metastasis
A key finding from Hanahan 2026: **there are no universal "metastasis-specific" driver genes** analogous to oncogenes in primary tumorigenesis. Instead:
- Metastatic mutations are typically found in the primary tumor (truncal or within ITH)
- New CIN (somatic copy-number alterations, whole genome doubling) occurs en route to metastasis
- TP53 mutations are enriched in metastases vs. primary tumors — linked to genome instability
- Non-genetic mechanisms (EMP, metabolic plasticity, epigenetic reprogramming) are major drivers

> **Implication for CRC:** This means targeting metastatic CRC with precision genomic approaches alone is insufficient; the plasticity mechanisms that enable colonization are largely non-mutational.

## Open Questions
- What determines organ tropism in CRC? Why does colon cancer preferentially go to liver vs. peritoneum?
- What signals in the liver microenvironment enable EMP1+ HRCs to initiate colonization?
- What awakens dormant DTCs after years?
- How does the premetastatic niche differ between liver, lung, and peritoneum in CRC?
- What triggers the HRC → LGR5+ transition during metastatic outgrowth?
- Can the CIN that drives metastasis be therapeutically targeted?

## References
- [[hanahan-2026-hallmarks-cancer]] (framework)
- [[canellas-socias-2022-emp1-hrcs]] (HRC identity; stage-specific cellular roles; neoadjuvant immunotherapy window)
- [[heinlein-2026-mapk-wnt-metastasis]] (MAPK-high/WNT-low as transcriptional identity of metastasis-initiating cells; KRAS^G12D inhibition reverts state; patient prognostic data)
