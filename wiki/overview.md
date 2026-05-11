---
title: "Overview — CRC Metastasis"
type: overview
tags: [overview, metastasis, colorectal-cancer]
created: 2026-04-26
updated: 2026-04-29
sources: [hanahan-2026-hallmarks-cancer, canellas-socias-2022-emp1-hrcs, heinlein-2026-mapk-wnt-metastasis, riedl-2026-kras-inhibitors-review]
---

# Overview: Metastasis of Colorectal Cancer

*This page is a living synthesis. It is updated with every ingest and should always reflect the current state of the wiki's understanding.*

---

## The Disease

Colorectal cancer (CRC) is the third most common cancer worldwide and the second leading cause of cancer-related death. Approximately 20–25% of patients present with synchronous metastases at diagnosis, and an additional 25–30% of initially localized patients will develop metastatic disease. Five-year survival for metastatic CRC (mCRC) remains below 15%, making metastatic progression the dominant driver of CRC mortality.

---

## Preferred Metastatic Sites

CRC metastasizes in a strongly organ-tropic pattern:
- **Liver** — most common (~50–70% of mCRC patients); receives portal venous drainage from the colon; the primary site for surgical resection with curative intent
- **Lung** — second most common; more frequent in rectal cancer due to systemic venous drainage
- **Peritoneum** — associated with poor prognosis; microsatellite-stable (MSS) tumors predominate; limited systemic treatment options
- **Lymph nodes** — locoregional spread; key staging determinant

---

## Molecular Landscape

Key driver alterations in mCRC:
| Gene | Frequency | Role |
|------|-----------|------|
| APC | ~80% | WNT pathway gatekeeper; initiating mutation |
| KRAS/NRAS | ~50% | RAS-MAPK activation; anti-EGFR resistance |
| BRAF V600E | ~10% | Poor prognosis; MAPK activation; MSI-associated |
| TP53 | ~60% | Genomic instability |
| SMAD4 | ~20% | TGF-β signaling loss; associated with peritoneal/liver mets |
| PIK3CA | ~15–20% | PI3K-AKT-mTOR activation |

Microsatellite instability (MSI-H) occurs in ~5% of mCRC and defines a subgroup with exceptional response to immune checkpoint blockade (pembrolizumab). The remaining ~95% are MSS and largely immunotherapy-refractory.

---

## The Metastatic Cascade

The current model involves sequential steps:
1. **Local invasion** — EMT, matrix remodeling, basement membrane breach
2. **Intravasation** — entry into blood or lymphatic vessels; CTC formation
3. **Survival in circulation** — anoikis resistance, immune evasion, CTC clusters
4. **Extravasation** — arrest in target organ vasculature, extravasation
5. **Colonization** — niche establishment, dormancy vs. outgrowth, organ-specific adaptation

### The metastasis-initiating cell state: HRCs
A pivotal recent finding (Cañellas-Socias et al. 2022) identifies **[[EMP1]]-high High-Relapse Cells (HRCs)** as the cellular origin of CRC metastatic recurrence. HRCs are a distinct epithelial cell state — enriched at invasion fronts, tumour buds, and stroma-contacting clusters — defined by the 99-gene EpiHR signature. They are not LGR5+ cancer stem cells (mutually exclusive distributions). Key points:
- ~30–40% of CRC patients undergoing curative resection develop metastatic relapse; HRCs are the residual cells responsible
- Micrometastases are HRC-dominated; LGR5+ cells take over as metastases grow
- Ablating EMP1+ cells before surgery prevents relapse; ablating LGR5+ cells does not
- CAFs induce the HRC state; KRAS mutations correlate with higher HRC abundance
- Neoadjuvant anti-PD1 + anti-CTLA4 exploits a window of T-cell susceptibility in early micrometastases to prevent relapse in MSS CRC mouse models

### The MAPK-high/WNT-low axis: upstream regulator of the HRC state
Heinlein et al. (2026) identified the transcriptional program governing HRC identity: a **MAPK-high, WNT-low** cell state driven by AP-1 TFs (downstream KRAS/MAPK) and associated with chromosomal amplification of MAPK pathway genes. Key implications:
- MAPK signaling drives EMP1 expression via AP-1 chromatin remodeling; WNT suppression enforces the HRC/non-stem identity
- Metastatic CRC cells selected by serial in vivo passaging are MAPK-high/WNT-low; KRAS^G12D inhibition (MRTX1133) reverts this state and reduces liver/lung metastases
- High MAPK + low WNT gene signature is prognostic in patients (AVANT HR 1.67; CALGB HR 2.29) — better than KRAS mutation status alone
- Adaptive WNT reactivation upon KRAS inhibition suggests combined MAPK + WNT targeting may be needed

---

## Current Treatment Landscape

- **Chemotherapy backbone**: FOLFOX, FOLFIRI, FOLFOXIRI
- **Biologics**: bevacizumab (anti-VEGF), cetuximab/panitumumab (anti-EGFR; RAS/BRAF WT only), ramucirumab, ziv-aflibercept
- **Targeted**: BRAF V600E — encorafenib + cetuximab; **KRAS G12C — sotorasib + panitumumab (FDA approved, Codebreak 300)**; adagrasib + cetuximab (accelerated approval)
- **Immunotherapy**: pembrolizumab (MSI-H/dMMR only, 1st line)
- **Surgery**: liver resection in selected patients; HIPEC for peritoneal disease
- **Emerging KRAS^G12D targeting**: KRAS^G12D is the most prevalent KRAS mutation in CRC (~12.6%). Zoldonrasib (ORR 61% NSCLC, 30% PDAC), GFH375 (ORR 58% NSCLC, 41% PDAC), and ASP3082 (PROTAC, ORR 38%) are in Phase 1/2 trials. Anti-EGFR combinations likely needed given EGFR-driven adaptive resistance in CRC.
- **YAP/TEAD co-inhibition + KRAS**: preclinical synergy; may prevent adaptive resistance to KRAS inhibitors via SHOC2/PP1c-YAP bypass pathway

---

## Open Questions

- What transcription factor(s) maintain the HRC/EMP1-high state?
- What liver microenvironmental signals permit HRC colonization?
- What triggers the HRC → LGR5+ transition during metastatic outgrowth?
- Can EMP1 surface expression be exploited for targeted therapy (ADC, CAR-T)?
- Can neoadjuvant immunotherapy be combined with HRC-targeting for synergistic MSS CRC prevention?
- Why do some patients with EMP1-high primary tumours never relapse?

---

## Key Tensions in the Field

- **LGR5+ cells and metastasis**: De Sousa e Melo (2017) showed LGR5+ cells necessary for liver metastasis; Cañellas-Socias (2022) shows LGR5+ cells dispensable for dissemination but required for outgrowth. Reconciled by stage specificity. Heinlein (2026) adds mechanistic explanation: LGR5+ cells require WNT-high/MAPK-low state; metastatic dissemination requires the inverse.
- **YAP and the HRC state**: YAP activity is elevated in MAPK-high metastatic cells (Heinlein 2026), yet YAP knockdown does not affect EMP1/HRC state (Cañellas-Socias 2022). Reconciled: MAPK → YAP and MAPK → EMP1 are parallel, not sequential; YAP is co-elevated but not causally upstream of EMP1 specifically.
- **EMT in CRC**: Canonical EMT TFs (ZEB1/2, SNAI1/2) are not upregulated in HRCs; instead, a partial EMT module (Lama2, Itga2, Plaur) and AP-1 TFs (MAPK effectors) define invasive capacity while retaining epithelial identity.
- **Prognostic markers in CRC**: KRAS mutation status alone is insufficient (Heinlein 2026); combined MAPK + WNT activity score is significantly more prognostic across two patient cohorts.
