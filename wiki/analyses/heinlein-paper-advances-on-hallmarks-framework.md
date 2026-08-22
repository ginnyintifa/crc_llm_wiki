---
title: "How the Heinlein MAPK/WNT paper advances the Hanahan hallmarks framework"
type: analysis
tags: [driver-gene, mutation, signaling-pathway, EMT, invasion, colonization, liver-mets, lung-mets, biomarker, prognosis, targeted-therapy]
created: 2026-08-22
updated: 2026-08-22
sources: [heinlein-2026-mapk-wnt-metastasis, hanahan-2026-hallmarks-cancer]
---

# How the Heinlein MAPK/WNT paper advances the Hanahan hallmarks framework

**Query:** Does Heinlein et al. (2026) advance any specific points made in the Hanahan (2026) hallmarks review?

**Short answer:** Yes — Heinlein takes several things Hanahan states as *general principles* (CIN-driven hallmark acquisition, non-genetic metastasis-driving cell states, KRAS's multi-hallmark reach) and gives them a causally validated, single-node mechanistic account in CRC. It also surfaces a genuine complication to Hanahan's "hallmark co-targeting" rationale.

---

## Hallmark 1 (Sustaining proliferative signaling) + Enabling characteristic 1 (Loss of genomic integrity)

Hanahan cites [[KRAS]] as the canonical CRC hallmark-1 driver and separately lists CIN as an enabling characteristic, but treats them as parallel, largely independent bullet points. The Heinlein paper mechanistically links them: serial in vivo passaging of AKPS organoids shows metastatic potential increases via **stepwise chromosomal amplification** of MAPK pathway genes (Kras, Braf, Raf1, Sos1, several MAPK isoforms on chromosomes 6, 15, 17) — not new point mutations (WES found only 12–30 additional somatic mutations per passage, none known CRC drivers). CIN directly dials up hallmark-1 signaling dosage rather than merely co-occurring with it; AK^Q61R (a more catalytically active KRAS allele) produced an even higher metastatic frequency than AK^G12D, confirming pathway *activity level* — not mutation identity — as the operative variable.

## Hallmark 7 (Unlocking phenotypic plasticity)

Hanahan describes hybrid EMP/dedifferentiation states abstractly, without naming a regulatory circuit. Heinlein's ATAC-seq + BETA integrative analysis identifies the actual molecular toggle: **AP-1 transcription factors (BATF, ATF3, FRA1, JUNB, FOS)** open chromatin at metastatic-state loci — including [[EMP1]] — while TCF/LEF (WNT-associated) sites close in the same cells. The switch is pharmacologically reversible: KRAS^G12D inhibition (MRTX1133) flips cells from an RSC-like (regenerative stem cell) back to a CBC-like (crypt base columnar) state, reactivating [[LGR5]]/WNT targets. This is a named, druggable circuit for a hallmark Hanahan leaves conceptual.

## Hallmark 9 (Activating invasion and metastasis)

Hanahan's specific claim is that no universal metastasis-driver genes exist, and that CIN and EMP are the real engines of the metastatic cascade. Heinlein is close to a direct experimental proof of this exact claim: metastatic capacity in an isogenic model increased purely through CNA accumulation and a transcriptional state change (MAPK-high/WNT-low), with whole-exome sequencing explicitly ruling out new driver mutations as the cause. See also [[The Metastatic Cascade]].

## Cross-hallmark coupling — advances (and complicates) the co-targeting rationale

Hanahan's hallmark co-targeting logic assumes hallmarks are mechanistically independent enough that hitting several at once forecloses compensatory escape routes. Heinlein shows a case that cuts the other way: a **single upstream node** (KRAS^G12D / MAPK activity) simultaneously governs hallmark 7 (plasticity), hallmark 9 (metastasis), and touches hallmark 8 (evading immune destruction — MRTX1133 treatment also restored MHC-I expression, which had been suppressed in the metastatic P5 state). Adding a TEAD/YAP inhibitor on top of KRAS inhibition added no further effect on MAPK or WNT targets. So rather than validating "combine independent targets to block resistance," this is evidence that some hallmarks are *not* mechanistically independent in CRC — they are coupled downstream of one lesion — meaning monotherapy at the right node can achieve what looks like co-targeting for free. This is a genuine nuance/tension with Hanahan's framework, not just an instantiation of it.

## Operationalizing the "KRAS associates with all 9 hallmarks" claim

Hanahan states KRAS associates broadly with all 9 hallmarks and that hallmark burden generally tracks CRC prognosis, without a quantitative instrument. Heinlein converts this into a validated clinical tool: a MAPK-high/WNT-low **pathway-activity signature** predicts overall survival in two independent phase 3 RCT cohorts (AVANT: HR 1.673, P=3.66×10⁻⁵; CALGB: HR 2.292, P=0.009) — and notably, **KRAS mutation status alone did not significantly predict survival** in the AVANT cohort. This is both an advance and a mild correction: genotype-based hallmark attribution (KRAS-mutant = hallmark 1 active) is insufficient on its own; downstream pathway *activity* state is what carries the prognostic signal.

---

## Summary table

| Hanahan point | Status in hallmarks paper | Advance from Heinlein paper |
|---------------|---------------------------|------------------------------|
| CIN is an enabling characteristic; KRAS drives hallmark 1 | Stated as parallel principles | CIN (chromosomal amplification of MAPK genes) shown to directly *cause* hallmark-1 pathway dosage increase, without new mutations |
| Hybrid EMP/plasticity states drive hallmarks | Stated as principle, no circuit named | AP-1 TF network identified as the reversible chromatin-level toggle between MAPK-high (metastatic) and WNT-high (stem) states |
| No universal metastasis genes; CIN + EMP drive invasion/metastasis | Stated as principle | Directly demonstrated in an isogenic serial-passaging CRC model — metastatic gain from CNA + transcriptional state alone |
| Hallmark co-targeting overcomes resistance via independent mechanisms | Proposed as general therapeutic rationale | Complicated: single-node KRAS/MAPK inhibition alone reverted plasticity, metastasis, and an immune-evasion phenotype (MHC-I) — hallmarks behaved as coupled, not independent, in this system |
| KRAS associates broadly with all 9 hallmarks; prognosis tracks hallmark burden | Broad qualitative claim | Quantitative MAPK+WNT activity signature validated as prognostic in two independent cohorts; KRAS mutation status alone was insufficient |

## References
- [[heinlein-2026-mapk-wnt-metastasis]]
- [[hanahan-2026-hallmarks-cancer]]
