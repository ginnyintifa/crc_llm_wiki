---
title: "Cañellas-Socias 2022 — Metastatic recurrence in CRC arises from residual EMP1+ cells"
type: source
tags: [liver-mets, lung-mets, invasion, intravasation, colonization, immune-evasion, cancer-stem-cell, ctc, tumor-microenvironment, caf, T-cell, EMT, mutation, driver-gene, biomarker, prognosis, immunotherapy, mouse-model, organoid, single-cell, high-evidence]
created: 2026-04-28
updated: 2026-04-28
sources: [canellas-socias-2022-emp1-hrcs]
---

# Cañellas-Socias 2022 — Metastatic recurrence in CRC arises from residual EMP1+ cells

## Citation
Cañellas-Socias A, Cortina C, Hernando-Momblona X, et al. "Metastatic recurrence in colorectal cancer arises from residual EMP1+ cells." *Nature* 611, 603–613 (2022). https://doi.org/10.1038/s41586-022-05402-9. Corresponding author: Eduard Batlle (IRB Barcelona).

## Summary
This paper identifies **high-relapse cells (HRCs)** — a specific tumour epithelial cell state marked by [[EMP1]] (Epithelial Membrane Protein 1) — as the cellular origin of CRC metastatic recurrence. By mining scRNA-seq data from large patient cohorts, the authors found that 99 epithelial-specific genes (the EpiHR signature) independently predict relapse. HRCs are distinct from [[LGR5]]+ cancer stem cells; they populate invasion fronts, tumour buds, and liver micrometastases, and give rise to LGR5+ progeny during outgrowth. Genetic ablation of EMP1high cells before surgery prevented metastatic relapse, while LGR5+ cell ablation did not affect dissemination. Neoadjuvant anti-PD1 + anti-CTLA4 immunotherapy exploited a window of T-cell susceptibility in early micrometastases and prevented relapse in MSS CRC mouse models.

## Key Findings

### 1. The EpiHR signature and HRC identity
- From 2,530 poor-prognosis genes in a meta-cohort of 1,830 CRC patients, 99 were epithelial-tumour-cell-specific (EpiHR). These independently predict relapse (HR = 2.26 per +1 SD, P = 1.2×10⁻⁷), even after controlling for TME-HR genes.
- EpiHR+ cells (HRCs) are present in 18/27 tumours at variable proportions (1.4–98.1%). They associate with right-sided CRC and AJCC stages III–IV.
- HRC gene set is enriched for: hypoxia, cell–cell adhesion, ECM, actin cytoskeleton, cell migration; includes DDR1, integrins α2/α3/β4, PLAUR.
- HRCs are **distinct from LGR5+ stem-like cells** — mutually exclusive UMAP distributions; confirmed in both human (SMC, KUL cohorts) and mouse (AKTP) CRCs.

### 2. EMP1 marks HRCs at invasion fronts and micrometastases
- [[EMP1]], encoding a tight junction component, is the top HRC marker gene with the highest overlap with EpiHR in both human and mouse CRC.
- EMP1–TOMhigh cells are strongly enriched at **invasion fronts, tumour buds, and stroma-contacting clusters** in primary CRCs; also found near blood vessels (haematogenous dissemination route).
- Liver **micrometastases are entirely EMP1high/LGR5low**; LGR5 expression is progressively gained during outgrowth while EMP1–TOM decreases — antithetic pattern across metastatic progression.
- EMP1high cells retain epithelial markers (EPCAM, E-cadherin); canonical EMT transcription factors are not upregulated. Instead, HRCs express a **partial EMT module** (Lama3, Lamc2, Itga2, Plaur) and junctional complex genes (Pcdh1, Dsc2, Clnd4, Jup/plakoglobin).
- Basal-like pancreatic cancer signature marks both human and mouse HRCs; KRT17 marks EMP1high invasion fronts.

### 3. HRC dynamics across the metastatic cascade (scRNA-seq + CellRank)
- AKTP mouse model: caecal organoid implantation → primary CRC → surgical resection → metastatic relapse (predominantly liver; also lung, peritoneum, mesenteric lymph nodes).
- Smart-seq2 scRNA-seq of 900 cells across primary, micro-, small, and macrometastases revealed six clusters (proliferative, LGR5+ Ki67+/−, differentiated KRT20+, HRCs KRT20+/KRT20−).
- **Micrometastases are HRC-dominated**: undifferentiated (KRT20−) HRCs occupy the apex of the cellular hierarchy; they give rise to LGR5+ and proliferative progeny. This is reversed in macrometastases where LGR5+ cells lead the hierarchy.
- Primary CRCs show a mixed hierarchy: proliferative LGR5− cells → LGR5+ or HRCs.

### 4. EMP1high cells are causally required for metastatic relapse
- CRISPR knock-in of inducible caspase-9 into the Emp1 locus (Emp1-iCasp9-tdTomato) enables cell-specific ablation with AP20187 (DIM).
- DIM treatment during primary tumour growth but ceased before surgery: **only 5/22 mice relapsed** vs 26/33 controls (P < 0.001). Primary tumour growth unaffected.
- DIM started 1 week *after* surgery: no effect — 9/9 mice relapsed. DIM after intrasplenic inoculation (bypassing primary tumour/seeding): no effect on liver metastasis burden.
- Conclusion: EMP1high HRCs are required during the *seeding phase* (dissemination from primary tumour), but dispensable once metastatic colonization is complete.
- Equivalent protection in AKP and AKPS (SMAD4-mutant) models; 20-fold reduction in lung metastasis burden from rectal EMP1 ablation.
- **LGR5+ cell ablation (DTR model)** did NOT prevent metastatic relapse from primary CRC, but DID halt metastasis after direct intrasplenic injection → LGR5+ cells required for outgrowth but dispensable for dissemination and initial colonization.

### 5. Determinants of HRC state
- **KRAS mutations** strongly correlate with EpiHR expression (TCGA COAD). CRISPR-derived organoids (CTOs) confirm KrasG12D genotypes upregulate EpiHR and coreHRC.
- **CAF co-culture** increases EMP1-TOM+ cell proportion 6-fold in vitro; CAF abundance correlates with HRC proportion in patient scRNA-seq data (Pearson correlation). CAFs surround EMP1high invasion fronts in vivo.
- **YAP does NOT drive the HRC state**: YAP knockdown (shRNA or dominant-negative TEAD) did not alter Emp1, Lamc2, or EMP1high cell numbers. HRCs show minimal overlap with YAP_22 or fetal intestinal progenitor signatures. Chemotherapy (FOLFIRI) upregulates YAP/fetal program but not the HRC state.

### 6. Neoadjuvant immunotherapy window
- Liver micrometastases are initially T-cell infiltrated (high CD3+ density); as they grow, T cells are progressively excluded to the periphery while CAFs (α-SMA+, POSTN+) and macrophages (CD68+) are recruited.
- Undifferentiated HRCs in micrometastases upregulate interferon-α and interferon-γ response genes, and express high PD-L1 (Cd274) and IDO1, suggesting active immune suppression but residual vulnerability.
- **Neoadjuvant** anti-PD1 + anti-CTLA4 (before surgery): increased CD8+ T cells in primary CRC; prevented relapse in 7/9 treated mice vs 4/17 controls. Primary tumour growth not cured.
- Neoadjuvant anti-PD1 monotherapy: equivalent results.
- **Late immunotherapy** (2 weeks post-surgery): no effect on metastatic outgrowth → consistent with clinical failure of ICI in MSS mCRC.

## Methods
- **scRNA-seq**: 10x Genomics (mouse primary tumours), Smart-seq2 (longitudinal metastasis profiling), CellRank pseudotime analysis
- **Human cohorts**: SMC (Samsung Medical Center, n=27 CRCs, scRNA-seq) and KUL (Katholieke Universiteit Leuven) for scRNA-seq; meta-cohort of 1,830 patients for prognosis analysis
- **Mouse models**: AKTP MTOs (Apc, Kras, Tgfbr2, Trp53 mutations) implanted into caecum apex of C57BL/6 mice — novel surgical modification enabling complete primary resection; also AKP and AKPS models
- **Genetic reporters/ablation**: CRISPR knock-in of Emp1-iCasp9-tdTomato, Lgr5-DTR-eGFP, Lgr5-iCT, and dual-labelled lines
- **Imaging**: Light-sheet 3D fluorescence, bioluminescence (eGFP-luciferase), confocal, NanoZoomer scanning
- **Multiplex IF**: Immune (LY6G, CD4, CD8, CD68, FOXP3) and stromal (CD34, CD146, α-SMA, POSTN) panels on Vectra Polaris
- **RNA-seq/microarray**: CTO genotype comparison, MTO co-culture with fibroblasts, chemotherapy response

## Key Entities / Concepts (linked)
- [[EMP1]] — HRC marker gene; tight junction component; tracks metastasis-initiating cells
- [[LGR5]] — cancer stem cell marker; dispensable for seeding, required for outgrowth
- [[KRAS]] — KRAS mutations drive HRC/EpiHR state; coreHRC upregulated in KrasG12D organoids
- [[SMAD4]] — HRC-driven relapse confirmed in AKPS model (SMAD4-mutant CRC)
- [[CAFs]] — induce HRC state; correlate with HRC abundance; surround invasion fronts
- [[Epithelial-Mesenchymal Plasticity (EMP)]] — HRCs represent partial EMT, not full EMT; retain epithelial identity; partial EMT module (Lama3, Lamc2, Itga2, Plaur)
- [[The Metastatic Cascade]] — HRCs are the metastasis-initiating population; LGR5+ cells take over during outgrowth; cluster extravasation (Jup/plakoglobin) proposed
- [[Tumor Microenvironment (TME)]] — micrometastatic TME initially T-cell rich but progressively immune-excluded; CAF/macrophage co-evolution with metastatic outgrowth; neoadjuvant window

## Contradictions / Tensions with Existing Wiki Content

> ⚠️ **Tension with prior LGR5+ CSC model**: de Sousa e Melo et al. (2017, ref. 3 in paper) showed LGR5+ cells are dispensable for primary CRC growth but *necessary* for liver metastasis formation. This paper shows LGR5+ cells are dispensable for *dissemination and initial colonization* but required for *outgrowth*. These are reconcilable: the de Sousa study used direct intrasplenic inoculation (bypassing dissemination), so both findings are stage-specific and not contradictory — they capture different bottlenecks.

> ⚠️ **YAP and metastasis**: Some prior work linked YAP activity to CRC metastasis (Heinz et al. 2022, Cancer Res.; ref. 28) and to cancer cell plasticity. This paper rigorously shows YAP does NOT control the HRC transcriptional state. YAP may be relevant at other stages (outgrowth) but not to HRC identity.

> ⚠️ **EMP (partial EMT) vs. canonical EMT**: Existing EMP concept page notes canonical EMT TFs (ZEB1/2, SNAI1/2, TWIST) as regulators. HRCs do not upregulate these. Instead, HRC invasion is mediated by a partial EMT program (Lama3, Lamc2, Itga2, Plaur) and junctional complexes, consistent with the EMP concept but adding mechanistic granularity.

## Gaps / Open Questions Raised
- What signals within the liver microenvironment enable EMP1high HRCs to initiate colonization?
- What maintains the HRC state vs. differentiation to LGR5+ cells? Transcription factor identity?
- Can EMP1 itself be targeted therapeutically (it is a surface-accessible protein)?
- Why do some patients never develop metastatic relapse despite having EMP1high cells in the primary tumour?
- What determines whether micrometastases remain dormant vs. progress to overt metastasis?
- Can neoadjuvant immunotherapy be combined with HRC-targeting to achieve synergistic prevention of relapse in MSS CRC?

## Figures of Note
- **Fig. 1**: EpiHR signature identification; Kaplan–Meier relapse-free survival; UMAP showing HRC vs. LGR5+ distributions in human CRCs; HRC enrichment in stages III–IV
- **Fig. 2**: Mouse model schematic; scRNA-seq UMAP of 900 cells across metastatic progression; CellRank vector fields showing hierarchy inversion (HRCs at apex in micrometastases → LGR5+ in macrometastases)
- **Fig. 3**: EMP1–TOM marking invasion fronts and tumour buds; antithetic EMP1/LGR5 pattern across metastasis size; KRAS mutation correlation with EpiHR; CAF co-culture induction of EMP1high cells
- **Fig. 4**: EMP1high ablation prevents relapse (26/33 → 5/22); LGR5+ ablation does not prevent relapse but blocks outgrowth after intrasplenic inoculation
- **Fig. 5**: Micrometastases T-cell infiltrated → immune excluded during growth; PD-L1 expression on HRCs; neoadjuvant ICI prevents relapse (2/9 vs 13/17 relapse); late ICI ineffective
