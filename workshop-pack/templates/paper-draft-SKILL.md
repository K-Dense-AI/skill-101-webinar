---
name: paper-draft
description: Expand a paper abstract or short study summary into a structured IMRAD draft — Introduction, Methods, Results, Discussion — written in full paragraphs, staying strictly grounded in the abstract and inserting placeholders for anything that needs a real source or measurement instead of inventing it. Use when the user pastes an abstract or asks to expand, draft, flesh out, or write a paper, manuscript, or report from an abstract or summary.
---

# Paper Draft

## When to use
When the user pastes an abstract or short study summary and asks to "expand", "draft", "flesh out", or "write" a paper, manuscript, or report from it.

## Output format (ALWAYS use exactly this)
Write in full, flowing paragraphs — never bullet points inside a section. Use these four headers:

## Introduction
2–3 paragraphs: background and why it matters, the gap, and the study's aim/contribution (all drawn from the abstract).

## Methods
1–2 paragraphs, past tense: the approach, datasets, and procedures named in the abstract.

## Results
1–2 paragraphs, past tense: the findings reported in the abstract, keeping every number and statistic exactly.

## Discussion
2 paragraphs: interpretation, relation to prior work, limitations, and next steps.

End with:

**Gaps to fill** — a short bulleted list of every placeholder you inserted.

## Rules
- Expand ONLY what the abstract supports. Never invent specific numbers, statistics, p-values, sample sizes, citations, or method details that are not in the abstract.
- Where a real manuscript would cite a source, insert `[citation needed]`. Where a specific value or method detail is missing, insert `[TODO: add detail]`. Do not fabricate them.
- Keep every quantitative result from the abstract exact (numbers, units, confidence intervals, n).
- Neutral, formal academic register; define abbreviations at first use.
- Do not overstate findings beyond what the abstract claims.

## Example
Input: "We built a model to flag mislabeled cells in scRNA-seq data. On 5 datasets it cut labeling errors by 30% versus the standard pipeline."

Output:
## Introduction
Single-cell RNA sequencing has become central to resolving cellular heterogeneity, yet mislabeled cells remain a persistent source of error in downstream analysis [citation needed]. Existing pipelines struggle to flag these errors reliably [citation needed]. Here we present a model that identifies mislabeled cells to improve label quality.
## Methods
The model was evaluated on five datasets [TODO: add dataset names and sizes] and compared against the standard labeling pipeline [TODO: name the baseline pipeline].
## Results
Across the five datasets, the method reduced labeling errors by 30% relative to the standard pipeline.
## Discussion
These results suggest that automated error flagging can meaningfully improve label quality in scRNA-seq workflows. Limitations include [TODO: add limitations]; future work should test generalization to additional tissues [citation needed].

**Gaps to fill**
- Citations for background claims and the baseline comparison
- Dataset names and sizes
- Name of the baseline pipeline
- Stated limitations
