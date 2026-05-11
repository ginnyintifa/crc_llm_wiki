---
title: "Heinlein 2026 — A high-MAPK, low-WNT cell state drives metastatic dissemination in colorectal cancer"
type: source
tags: [liver-mets, lung-mets, invasion, colonization, EMT, mutation, driver-gene, signaling-pathway, biomarker, prognosis, targeted-therapy, mouse-model, organoid, single-cell, high-evidence]
created: 2026-05-10
updated: 2026-05-10
sources: [heinlein-2026-mapk-wnt-metastasis]
---

# Heinlein 2026 — A high-MAPK, low-WNT cell state drives metastatic dissemination in colorectal cancer

## Citation
Heinlein M, Li GX, Kljavin N, Moore AR, Biehs B, Tao L, Boumahdi S, Mohammadi F, Shi M, Liang Y, Koeppen H, Riggi N, Piskol R & de Sauvage FJ. "A high-MAPK, low-WNT cell state drives metastatic dissemination in colorectal cancer." *Nature Cancer* (2026). https://doi.org/10.1038/s43018-026-01155-w. Corresponding authors: Robert Piskol, Frederic J. de Sauvage (Genentech).

## Summary
This paper identifies a **MAPK-high, WNT-low transcriptional cell state** as the key driver of CRC metastatic dissemination, using a serial in vivo orthotopic passaging system that progressively selected for highly metastatic organoids (P5) from parental AKPS organoids (P0) in immunocompetent C57BL/6N mice. The enhanced metastatic potential of P5 cells arose from chromosomal amplifications in MAPK pathway genes — not new point mutations — leading to elevated AP-1 TF activity, upregulation of [[EMP1]], and suppression of WNT/LGR5 stem cell programs. Pharmacological inhibition of KRAS^G12D (MRTX1133) reverted the MAPK-high transcriptional state, reduced EMP1 expression, and significantly reduced liver and lung metastases. A MAPK-high/WNT-low gene signature correlated with shorter overall survival in two independent patient cohorts (AVANT and CALGB), validating clinical relevance. Together, the findings establish MAPK pathway activity as the upstream transcriptional regulator of the metastasis-initiating cell state in CRC, with WNT pathway suppression as its functional counterpart.

## Key Findings

### 1. Serial in vivo passaging model of mCRC
- AKPS organoids (Apc^−/−, Kras^G12D, Trp53^−/−, Smad4^−/−) implanted orthotopically into C57BL/6N mice; liver metastases isolated, expanded, and re-injected for 5 rounds (P0→P5).
- P5 organoids (notably m484) reliably produced macroscopic liver metastases in ~100% of mice and abundant lung metastases; P1 organoids rarely metastasized to liver in C57BL/6N mice.
- Enhanced metastatic potential not explained by increased proliferation or primary tumor size (equivalent at endpoint); attributed to improved **dissemination and/or colonization efficiency**.
- Immunocompetent setting: P5 showed increased metastasis in NSG mice too, but immune evasion partially contributed (T cell infiltration reduced, MHC-I downregulated, CXCL9/CXCL10 absent in P5 TME).

### 2. Chromosomal instability — not new point mutations — drives the metastatic state
- WES revealed only 12–30 additional somatic point mutations per passage vs. P0; no new known CRC oncogenic driver mutations identified.
- In contrast, **step-wise increase in chromosomal copy number alterations** (CNA) across passages.
- P5 organoids (m484): chromosomal amplifications at chromosomes **6, 15, and 17** encoding MAPK pathway genes: Kras, Braf, Raf1, Sos1, Mapk11, Mapk12, Mapk13, Mapk14, Map3k4, Map4k3, Myo, Ptk2, Tsc2, Hsf1 — all amplified.
- CNAs correlated positively with increased RNA expression of affected genes.
- AK^Q61R (higher GDP→GTP exchange rate than G12D → more active KRAS) showed even higher metastatic frequency than AK^G12D, confirming MAPK activity level is the key determinant.

### 3. MAPK-high, WNT-low transcriptional state
- P5 tumor epithelial cells (vs. P1): enriched pathways: DNA replication, cell cycle, EGF/EGFR signaling, focal adhesion, MAPK cascade; **depleted**: WNT signaling, type II IFN signaling, oxidative phosphorylation.
- WNT downstream target genes (Smoc2, Wif1, Nkd1, Lgr5, Axin2, Ascl2) significantly downregulated in P5; canonical WNT TF gene expression (Lgr5, Smoc2, Nkd1) confirmed by ISH.
- scRNA-seq of liver and lung metastases from NSG mice confirmed site-specific differences: liver metastases show higher Smoc2 (WNT) baseline; lung metastases more responsive to KRAS inhibition.
- This state is mutually exclusive with the WNT-high LGR5+ stem cell state (MAPK-high and LGR5+ cells occupy distinct transcriptional states — refs. 31–33 cited).

### 4. AP-1 chromatin remodeling drives EMP1 and the metastatic program
- ATAC-seq on sorted EpCAM+ tumor epithelial cells from P1 and P5 tumors:
  - P5-specific open chromatin motifs: **AP-1 family TFs** (BATF, ATF3, FRA1, JUNB, FOS — all downstream MAPK effectors) — strongest enrichment
  - P1-specific open chromatin motifs: TCF/LEF, CREB (WNT-associated)
- BETA integrative analysis of ATAC-seq + RNA-seq identified **[[EMP1]] as a top P5-specific MAPK target gene** with increased AP-1-associated chromatin accessibility at its locus.
- Smoc2 locus showed reduced chromatin accessibility at TCF-LEF binding sites in P5, confirming WNT program silencing.
- ENCODE ChIP-seq confirmed AP-1 TF binding at the EMP1 promoter in human cell lines — mechanistic link between MAPK/AP-1 and EMP1 upregulation.

### 5. KRAS^G12D inhibition reverts the metastatic transcriptional state
- MRTX1133 (KRAS^G12D-specific inhibitor) in P5-bearing mice:
  - 3 d treatment: significantly reduced Emp1 and Dusp4 (MAPK target) expression in colon tumors (ISH)
  - 14 d treatment: significantly reduced macroscopic liver metastases and lung metastases; EpCAM+ tumor epithelial cells reduced; MHCI expression increased
  - Shifted P5 transcriptional profile toward P1 along PC1 (which separates MAPK from WNT programs)
  - Upregulated WNT targets (Smoc2, Lgr5); downregulated MAPK targets (Spry2, Spred1/2, Etv1/4/6)
  - Reverted P5 from RSC-like (regenerative stem cell) to CBC-like (crypt base columnar) state
- TEAD inhibitor (GNE-7883, pan-TEAD inhibitor) alone had no additional effect on MAPK or WNT targets beyond KRAS inhibition → **WNT reactivation is primarily through MAPK suppression, not YAP/TEAD**.
- Late treatment (established liver metastases): reduced metastatic burden significantly; lung metastases showed greater sensitivity than liver metastases (site-specific WNT/MAPK baseline differences).

### 6. MAPK-high/WNT-low signature prognostic in patients
- AVANT cohort (n=826 RNA-seq, treatment-naïve CRC): high MAPK + low WNT patients had significantly shorter overall survival vs. low MAPK + high WNT (median OS 1.50 vs. 3.04 years; HR 1.673, P=3.66×10⁻⁵).
- CALGB cohort (n=572): confirmed (HR 2.292, P=0.009).
- KRAS mutation status alone did not significantly correlate with survival in the AVANT cohort — KRAS mutation is insufficient as a prognostic marker; **combined MAPK+WNT activity score provides better resolution**.

## Methods
- **Mouse model**: AKPS organoids (Apc, Kras^G12D, Trp53, Smad4) orthotopically injected into rectum of C57BL/6N mice; serial passaging via liver metastasis isolation; P5 m484 is the primary highly metastatic line
- **WES**: 50M paired-end 75-bp reads; somatic variant calling with GATK4; CNV analysis with Control-FREEC
- **Bulk RNA-seq**: sorted EpCAM+ tumor epithelial cells from in vivo tumors; edgeR + limma; GSEA
- **ATAC-seq**: sorted tumor epithelial cells from P1 and P5 in vivo tumors; motif enrichment with HOMER; direct target inference with BETA
- **scRNA-seq**: 10x Genomics, NSG mice, sorted RFP+ metastatic cells from liver and lung
- **Drug treatment**: MRTX1133 (30 mg/kg i.p. twice daily); GNE-7883 (pan-TEAD inhibitor); epigenetic inhibitor panel (EPZ004777, RG108, A-485, panobin ostat)
- **Patient cohorts**: AVANT (phase 3 RCT, bevacizumab + oxaliplatin chemotherapy) and CALGB (phase 3 RCT); MAPK signature = canonical downstream targets (SPRED1/2, ETS, SPRY2/4, ETV1/4/6, DUSP4/6); WNT signature = LGR5, AXIN2, ASCL2, SLC12A2, GKN33P, NKD1, WIF1, SMOC2

## Key Entities / Concepts (linked)
- [[EMP1]] — top MAPK target gene in metastatic cells; AP-1 TF binding at Emp1 promoter; KRAS inhibition reduces EMP1; this paper identifies MAPK/AP-1 as the upstream regulator of the HRC/EMP1 state
- [[KRAS]] — KRAS^G12D amplification drives MAPK-high state; KRAS^Q61R even more metastatic; MRTX1133 inhibition reverts metastatic state
- [[LGR5]] — WNT-driven stem cell program suppressed in MAPK-high metastatic cells; reactivated upon KRAS inhibition
- [[Epithelial-Mesenchymal Plasticity (EMP)]] — MAPK-high state drives the partial-EMT HRC identity via AP-1 chromatin remodeling at invasion/adhesion gene loci
- [[The Metastatic Cascade]] — MAPK-high state is the transcriptional program enabling dissemination; plasticity between MAPK-high (dissemination) and WNT-high (outgrowth) states

## Contradictions / Tensions with Existing Wiki Content

> ⚠️ **YAP activity in metastatic cells (tension with Cañellas-Socias 2022)**: This paper shows P5 metastatic cells express a YAP-dependent transcriptional signature, and KRAS^G12D inhibition reverses YAP-associated programs. However, Cañellas-Socias 2022 showed that YAP knockdown does NOT affect Emp1 expression or HRC abundance. These are partially reconcilable: MAPK signaling drives both EMP1 (via AP-1) and YAP activity, but YAP is likely not the direct regulator of EMP1 — consistent with the finding that TEAD inhibitor alone had no additional effect on MAPK/WNT targets beyond KRAS inhibition in this paper. YAP activity is co-elevated but not causally upstream of EMP1.

> ⚠️ **Mechanism upstream of EMP1/HRC state (advances Cañellas-Socias 2022)**: Cañellas-Socias 2022 identified EMP1 as a marker and showed CAFs induce the HRC state, but could not identify the governing transcription factor. This paper resolves it: AP-1 TFs (downstream of MAPK) regulate the Emp1 locus and the broader metastatic transcriptional program.

> ⚠️ **LGR5+ cell state and MAPK-WNT axis**: Cañellas-Socias 2022 notes HRCs are distinct from LGR5+ cells and mutually exclusive. This paper mechanistically explains the mutual exclusivity: MAPK activation suppresses WNT/LGR5 programs, and LGR5+ stem identity requires WNT-high (MAPK-low) conditions. KRAS inhibition reactivates LGR5, converting cells from RSC-like to CBC-like state.

## Gaps / Open Questions Raised
- What are the epigenetic mechanisms that lock in the MAPK-high/WNT-low state? (Epigenetic inhibitor panel in this paper had no effect — chromatin state is resistant to single-agent reprogramming)
- How does the liver microenvironment maintain higher WNT activity (Smoc2 elevation) in liver metastases vs. lung? What microenvironmental factor differences drive this?
- Can combined KRAS inhibition + WNT pathway inhibitors overcome the adaptive WNT reactivation and further reduce metastatic burden?
- Can MAPK + WNT activity scoring be implemented clinically as a prognostic biomarker?
- Does the MAPK-high state in human CRC primary tumours predict metastatic relapse similar to the EpiHR/EMP1-high signature?
- Does the MAPK-high/WNT-low state co-define HRCs, or is it a broader, overlapping but distinct population?

## Figures of Note
- **Fig. 1**: Model schematic; passaging tree; metastatic frequency increases across P0–P5 in C57BL/6N (immunocompetent)
- **Fig. 2**: CNA step-wise accumulation; MAPK/WNT pathway enrichment scores (P5 vs P1); AK^Q61R vs AK^G12D metastatic frequency comparison
- **Fig. 3**: MAPK pathway gene amplifications on chromosomes 6, 15, 17; Dusp4/Smoc2 ISH; AK^G12D vs AK^Q61R metastatic potential
- **Fig. 4**: ATAC-seq motif enrichment (AP-1 in P5; TCF/LEF in P1); BETA regulatory network; Emp1 locus chromatin accessibility; MRTX1133 reverts MAPK-high state
- **Fig. 5**: KRAS^G12D inhibition (early and late treatment) reduces liver/lung metastases; Emp1/Dusp4 downregulation; Smoc2 upregulation; PCA showing transcriptional reversion
- **Fig. 6**: MAPK-high/WNT-low prognostic in AVANT (HR 1.673) and CALGB (HR 2.292) cohorts
