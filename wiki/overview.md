---
title: "Overview — CRC Metastasis"
type: overview
tags: [overview, metastasis, colorectal-cancer]
created: 2026-04-26
updated: 2026-04-29
sources: [hanahan-2026-hallmarks-cancer, canellas-socias-2022-emp1-hrcs]
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

---

## Current Treatment Landscape

- **Chemotherapy backbone**: FOLFOX, FOLFIRI, FOLFOXIRI
- **Biologics**: bevacizumab (anti-VEGF), cetuximab/panitumumab (anti-EGFR; RAS/BRAF WT only), ramucirumab, ziv-aflibercept
- **Targeted**: BRAF V600E — encorafenib + cetuximab; KRAS G12C — sotorasib/adagrasib
- **Immunotherapy**: pembrolizumab (MSI-H/dMMR only, 1st line)
- **Surgery**: liver resection in selected patients; HIPEC for peritoneal disease
- **Emerging**: KRAS G12D targeting, SMAD4-directed approaches, combination immunotherapy strategies for MSS

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

- **LGR5+ cells and metastasis**: De Sousa e Melo (2017) showed LGR5+ cells necessary for liver metastasis; Cañellas-Socias (2022) shows LGR5+ cells dispensable for dissemination but required for outgrowth. Reconciled by stage specificity — different experimental models tested different bottlenecks.
- **YAP and plasticity**: YAP has been linked to CRC metastasis and cell plasticity, but rigorously shown *not* to control the HRC transcriptional state (Cañellas-Socias 2022). YAP may act at other stages.
- **EMT in CRC**: Canonical EMT TFs (ZEB1/2, SNAI1/2) are not upregulated in HRCs; instead, a partial EMT module (Lama2, Itga2, Plaur) defines invasive capacity while retaining epithelial identity.
