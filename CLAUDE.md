# CRC Metastasis Wiki — Schema & Workflow

## Domain
This wiki covers research on **metastasis of colorectal cancer (CRC)**, including:
- Molecular mechanisms of metastatic spread (EMT, invasion, intravasation, colonization)
- Organ-specific metastasis (liver, lung, peritoneum, lymph nodes)
- Driver mutations and their roles in metastatic progression (KRAS, BRAF, TP53, APC, SMAD4, PIK3CA, etc.)
- Tumor microenvironment (TME) and immune evasion
- Circulating tumor cells (CTCs) and cell-free DNA (cfDNA)
- Clonal evolution and heterogeneity
- Therapeutic approaches: chemotherapy, targeted therapy, immunotherapy, surgery
- Clinical staging, prognosis, and biomarkers
- Key model systems: patient-derived organoids, mouse models, cell lines

## Directory Structure

```
crc_llm_wiki/
├── CLAUDE.md           ← this file (schema & instructions)
├── raw/                ← immutable source documents (you add, LLM reads only)
│   └── assets/         ← downloaded images referenced by raw sources
├── wiki/               ← LLM-maintained knowledge base
│   ├── index.md        ← master catalog of all wiki pages
│   ├── log.md          ← append-only chronological event log
│   ├── overview.md     ← high-level synthesis of the field
│   ├── entities/       ← genes, proteins, pathways, cell types, drugs, cohorts, authors
│   ├── concepts/       ← mechanisms, theories, experimental paradigms
│   ├── sources/        ← one summary page per ingested source
│   └── analyses/       ← outputs of queries: comparisons, tables, figures, deep dives
```

## Page Conventions

### Frontmatter (YAML)
Every wiki page should begin with:
```yaml
---
title: "Page Title"
type: entity | concept | source | analysis | overview
tags: [list, of, relevant, tags]
created: YYYY-MM-DD
updated: YYYY-MM-DD
sources: [source-slug-1, source-slug-2]   # which raw sources support this page
---
```

### Wikilinks
Use `[[Page Name]]` for internal cross-references. Always link to the canonical page name. When mentioning an entity or concept that has (or should have) its own page, link it.

### Entity pages (`wiki/entities/`)
Covers: genes/proteins (KRAS, BRAF, SMAD4...), pathways (WNT, TGF-β, MAPK...), cell types (cancer-associated fibroblasts, Tregs...), drugs (oxaliplatin, bevacizumab, pembrolizumab...), clinical cohorts, model systems.

Structure:
```
## Overview
## Role in CRC Metastasis
## Mechanism
## Clinical Relevance / Biomarker Use
## Therapeutic Targeting (if applicable)
## Key Findings / Evidence
## Open Questions
## References
```

### Concept pages (`wiki/concepts/`)
Covers: mechanisms (EMT, anoikis resistance, metabolic reprogramming...), paradigms (clonal evolution, cancer stem cells...), experimental approaches (organoid culture, liver metastasis mouse model...).

Structure:
```
## Definition
## Relevance to CRC Metastasis
## Key Evidence
## Debates / Contradictions
## Open Questions
## References
```

### Source pages (`wiki/sources/`)
One page per ingested paper/article/document. Filename: `author-year-keyword.md` (e.g., `fang-2023-kras-liver.md`).

Structure:
```
## Citation
## Summary (3–5 sentences)
## Key Findings
## Methods
## Key Entities / Concepts (linked)
## Contradictions / Tensions with existing wiki content
## Gaps / Open Questions raised
## Figures of Note
```

### Analysis pages (`wiki/analyses/`)
Outputs of queries that are worth keeping. E.g., a comparison table of metastatic organotropism mechanisms, a summary of all KRAS-targeting strategies in the wiki.

## Workflows

### Ingest a new source
1. User drops source into `raw/` and says "ingest [filename]"
2. Read the source in full
3. Discuss key takeaways with the user (brief)
4. Write a source summary page in `wiki/sources/`
5. Update `wiki/index.md` with the new source entry
6. Update or create relevant entity pages in `wiki/entities/`
7. Update or create relevant concept pages in `wiki/concepts/`
8. Update `wiki/overview.md` if the source meaningfully shifts the synthesis
9. Append an entry to `wiki/log.md`: `## [YYYY-MM-DD] ingest | Author Year — Title`
10. Report: which pages were created/updated, any contradictions found

When a source contradicts an existing claim: flag it explicitly in both the source page and the relevant entity/concept page under a "Contradictions" section.

### Answer a query
1. Read `wiki/index.md` to identify relevant pages
2. Read the relevant pages
3. Synthesize an answer with citations to wiki pages (and through them, to raw sources)
4. Ask the user: "Should I file this as an analysis page?" If yes, write it to `wiki/analyses/`
5. Append a log entry: `## [YYYY-MM-DD] query | Question summary`

### Lint the wiki
Periodically check for:
- Contradictions between pages (flag with `> ⚠️ Contradiction:` blockquote)
- Stale claims superseded by newer sources
- Orphan pages (no inbound links from other pages)
- Important entities/concepts mentioned but lacking their own page
- Missing cross-references between related pages
- Data gaps that could be filled with a web search
- Append: `## [YYYY-MM-DD] lint | Summary of issues found`

## Tagging Vocabulary
Use consistent tags across pages. Core tags for this domain:
- **Metastasis site**: `liver-mets`, `lung-mets`, `peritoneal-mets`, `lymph-node-mets`
- **Mechanism**: `EMT`, `invasion`, `intravasation`, `extravasation`, `colonization`, `immune-evasion`, `angiogenesis`, `anoikis-resistance`
- **Molecular**: `mutation`, `driver-gene`, `signaling-pathway`, `epigenetics`, `transcription-factor`, `non-coding-RNA`
- **Cell biology**: `cancer-stem-cell`, `ctc`, `tumor-microenvironment`, `caf`, `macrophage`, `T-cell`
- **Clinical**: `biomarker`, `prognosis`, `staging`, `treatment-response`, `resistance`
- **Therapy**: `chemotherapy`, `targeted-therapy`, `immunotherapy`, `surgery`, `combination`
- **Model system**: `organoid`, `mouse-model`, `cell-line`, `patient-data`, `single-cell`
- **Evidence level**: `high-evidence`, `preliminary`, `contested`

## Naming Conventions
- Entity pages: PascalCase for gene/protein names as used in literature (e.g., `KRAS.md`, `SMAD4.md`, `TGF-beta-signaling.md`)
- Concept pages: kebab-case descriptive name (e.g., `epithelial-mesenchymal-transition.md`, `clonal-evolution.md`)
- Source pages: `lastname-year-keyword.md` (e.g., `tauriello-2018-tgfb-immunoevasion.md`)
- Analysis pages: descriptive kebab-case (e.g., `kras-targeting-strategies-comparison.md`)

## Index Format (`wiki/index.md`)
Organized by category. Each entry: `- [[Page Name]] — one-line summary (N sources)`

## Log Format (`wiki/log.md`)
Each entry starts with: `## [YYYY-MM-DD] <type> | <title>`
Types: `ingest`, `query`, `lint`, `update`
