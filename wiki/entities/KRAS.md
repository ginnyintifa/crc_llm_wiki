---
title: "KRAS"
type: entity
tags: [driver-gene, mutation, signaling-pathway, biomarker, targeted-therapy, prognosis, resistance, high-evidence]
created: 2026-05-10
updated: 2026-05-11
sources: [heinlein-2026-mapk-wnt-metastasis, canellas-socias-2022-emp1-hrcs, hanahan-2026-hallmarks-cancer, riedl-2026-kras-inhibitors-review]
---

# KRAS

## Overview
KRAS (Kirsten RAS) is the most frequently mutated oncogene in CRC, mutated in ~45–50% of cases. It encodes a small GTPase that cycles between inactive (GDP-bound) and active (GTP-bound) states, driving the MAPK (RAS-RAF-MEK-ERK) and PI3K-AKT pathways. In CRC, KRAS mutations (predominantly G12D, G12V, G13D) render the protein constitutively active. Beyond its role in primary tumour growth, KRAS mutation is now established as a driver of the **MAPK-high, WNT-low** transcriptional state that enables metastatic dissemination.

## Role in CRC Metastasis
KRAS mutation has multiple roles at different stages of CRC progression:

- **Primary tumour initiation**: Activating mutations in KRAS cooperate with APC loss (WNT activation) to drive tumour growth; LGR5+ ISCs are the cell of origin
- **Metastatic cell state induction**: KRAS^G12D drives MAPK pathway activity, suppresses WNT/LGR5 programs, and upregulates the metastatic transcriptional program including [[EMP1]] — the HRC marker (Heinlein 2026)
- **EpiHR/HRC signature correlation**: KRAS-activating mutations correlate with higher EpiHR expression in TCGA COAD; CRISPR CTO experiments confirm KrasG12D genotypes upregulate coreHRC and EpiHR programs (Cañellas-Socias 2022)
- **Dose-dependent effect**: KRAS^Q61R (higher GDP→GTP exchange rate → more active RAS) is more metastatic than KRAS^G12D in the same AKPS background — metastatic potential scales with MAPK activity level

## Mechanism: MAPK-high/WNT-low axis
The mechanistic link between KRAS mutation and metastasis operates through a **MAPK–WNT reciprocal antagonism**:

1. Activating KRAS → MAPK cascade (RAF → MEK → ERK) → AP-1 TF activation (BATF, ATF3, FRA1, JUNB, FOS)
2. AP-1 TFs remodel chromatin at invasion/dissemination gene loci, including *Emp1*
3. Simultaneously, MAPK activation suppresses WNT-driven transcription: TCF/LEF-associated chromatin closes; Lgr5, Smoc2, Nkd1, Wif1 downregulated
4. Net result: MAPK-high, WNT-low cell state with upregulated EMP1 = metastasis-initiating HRC identity

This inverse MAPK–WNT relationship is consistent with normal intestinal homeostasis where MAPK and WNT balance intestinal function, and aligns with observations that EGFR inhibition reduces YAP-driven transcription in residual tumor cells (Lupo et al. 2020).

Chromosomal amplification of MAPK pathway genes (Kras, Braf, Raf1, Sos1, Mapk11/12/13/14, Map3k4 on chromosomes 6, 15, 17) — rather than new point mutations — can further amplify this state during in vivo selection for metastatic competence.

## Clinical Relevance / Biomarker Use
- **Anti-EGFR resistance**: KRAS mutations predict non-response to cetuximab/panitumumab (anti-EGFR); RAS/BRAF WT required for benefit
- **Prognostic limitation**: KRAS mutation status alone is **insufficient** as a prognostic marker for survival — KRAS mutation alone did not significantly correlate with overall survival in the AVANT cohort (Heinlein 2026), likely because MAPK activation can arise via BRAF mutation or gene amplification
- **Combined MAPK+WNT activity score**: Significantly more prognostic than KRAS mutation status; high MAPK + low WNT predicts shorter OS (HR 1.67–2.29 across two cohorts)

## Therapeutic Targeting

### Drug classes (Riedl 2026)
Three classes of (K)RAS inhibitors, trading specificity vs. coverage:

| Class | Coverage | Examples | Tolerability |
|-------|---------|---------|-------------|
| Mutant-selective | Single KRAS mutant (G12C or G12D) | Sotorasib, adagrasib, divarasib (G12C); MRTX1133, zoldonrasib, GFH375 (G12D) | Best |
| Isoform-selective (pan-KRAS) | Multiple KRAS mutants + WT-KRAS; spare NRAS/HRAS | BI-2865, BI-3706674 | Intermediate |
| Pan-RAS | All KRAS/NRAS/HRAS mutant + WT | Daraxonrasib (RMC-6236), ERAS-0015 | Least favorable |

### KRAS^G12C inhibitors — CRC-specific clinical data
CRC is a distinct case: single-agent KRAS^G12C ORR (~9–23%) is roughly half that of NSCLC (~32–56%), driven by EGFR-mediated adaptive RAS/MAPK reactivation. Anti-EGFR combination approximately doubles ORR.

**FDA-approved in CRC:** Sotorasib + panitumumab (Codebreak 300, Ph3): ORR 30.2%, mPFS 5.6 months vs. 2.0 months SOC — approved for chemotherapy-refractory mCRC.

**Other combinations in CRC:**
- Adagrasib + cetuximab: ORR 34%, mPFS 6.9 months, mOS 15.9 months
- Divarasib + cetuximab: ORR 62.5% (highest reported to date for KRAS^G12C + anti-EGFR)
- Olomorasib + cetuximab: ORR 43%
- Next-gen agents (glecirasib, IBI351, garsorasib) show higher single-agent ORRs in NSCLC (~47–56%); CRC combinations ongoing

### KRAS^G12D inhibitors (most relevant for CRC)
KRAS^G12D is the most prevalent KRAS mutation in CRC (~12.6%). First-generation KRAS^G12C inhibitors do not cover G12D. Emerging agents:
- **MRTX1133** (Mirati): preclinical proof-of-concept; reduces metastatic burden in AKPS mouse models; Phase 1 clinical trial terminated
- **Zoldonrasib (RMC-9805)**: CYPA tricomplex ON-state; NSCLC ORR 61%, PDAC ORR 30% (Ph1/2)
- **GFH375 (VS-7375)**: ON/OFF-state noncovalent; NSCLC ORR 58%, PDAC ORR 41% (Ph1/2)
- **ASP3082**: PROTAC; ORR 38% in Ph1; active in KRAS-amplified models
- Multiple others in Phase 1: HRS-4642, INCB161734, LY3962673, AZD0022, TSN1611

### Combination strategies
- **KRAS + anti-EGFR** (in CRC): validated; sotorasib + panitumumab FDA approved; multiple Phase 3 trials ongoing
- **KRAS + ICI**: adagrasib + pembrolizumab (KRYSTAL-7): ORR 61%, mPFS 27.7 months in PD-L1 >50% NSCLC — primarily relevant for MSS CRC if extended
- **KRAS + YAP/TEAD inhibition**: synergistic preclinically (KRAS inhibition → YAP nuclear translocation → TEAD-mediated bypass transcription); combination blocks resistance
- **Pan-RAS + mutant-selective**: daraxonrasib + elironrasib/zoldonrasib trials ongoing — potent ON-state from pan-RAS + sustained OFF-state from mutant-selective

### Resistance mechanisms
**Primary (10–30%):** KEAP1 loss (strongest predictor, particularly NSCLC); preexisting RAS co-mutations; TP53/PIK3CA in CRC/PDAC

**Acquired genetic (~60% at progression):**
- On-target: KRAS amplification; secondary KRAS mutations (G12D, G13D, Q61H in *trans*); switch II pocket mutations (R68, M72, H95, Y96)
- Off-target: RTK amplification/mutation/fusion (EGFR dominant in CRC; ERBB2, FGFR, c-MET); BRAF/MAP2K1 mutations; NRAS/HRAS bypass

**Non-genetic (~25%):**
- Adaptive RTK/RAS reactivation: negative feedback relief → EGFR/HER2/FGFR upregulation → WT RAS activation (bypasses mutant KRAS inhibition)
- **YAP/TAZ/TEAD**: KRAS inhibition → Scribble membrane displacement → SHOC2/PP1c complex → YAP nuclear translocation → TEAD-mediated gene program (MRAS); combination with pan-TEAD inhibitor synergistic
- **EMT**: ZEB1/SNAI1/2/TWIST-driven; loss of KRAS dependency; increasingly recognized clinically
- Histologic transformation (NSCLC: adenocarcinoma → squamous/mucinous)

## Key Findings / Evidence
| Finding | Model | Source |
|---------|-------|--------|
| KRAS^G12D drives MAPK-high/EMP1-high metastatic cell state | AKPS organoid passaging model | [[heinlein-2026-mapk-wnt-metastasis]] |
| KRAS^Q61R more metastatic than KRAS^G12D | AK mouse model | [[heinlein-2026-mapk-wnt-metastasis]] |
| MRTX1133 reduces Emp1/Dusp4 expression in vivo; upregulates Smoc2/Lgr5 | AKPS P5 mouse | [[heinlein-2026-mapk-wnt-metastasis]] |
| MRTX1133 significantly reduces liver and lung metastases | AKPS P5 mouse | [[heinlein-2026-mapk-wnt-metastasis]] |
| KrasG12D CTOs upregulate coreHRC and EpiHR programs | CRISPR CTO panel | [[canellas-socias-2022-emp1-hrcs]] |
| KRAS mutations correlate with higher EpiHR expression in TCGA COAD | Patient data | [[canellas-socias-2022-emp1-hrcs]] |
| KRAS mutated in ~50% CRC; associates with all 9 cancer hallmarks | Review | [[hanahan-2026-hallmarks-cancer]] |

## Open Questions
- What determines whether KRAS mutation alone is sufficient for HRC/MAPK-high state, or whether chromosomal amplification of additional MAPK genes is needed?
- Can combined KRAS + WNT inhibition overcome adaptive WNT reactivation after KRAS^G12D inhibition?
- Does KRAS^G12D inhibition affect the immune TME sufficiently to synergize with ICI in mCRC?
- What accounts for site-specific differences in MAPK/WNT activity between liver and lung metastases?

## References
- [[heinlein-2026-mapk-wnt-metastasis]]
- [[canellas-socias-2022-emp1-hrcs]]
- [[hanahan-2026-hallmarks-cancer]]
