# Citation Integrity in Frontier Language Models

**Author:** Anubhav Sapkota  
**Affiliation:** GrayTell Labs  
**Date:** September 18, 2026  
**License:** Apache 2.0

---

## Overview

This repository contains the paper, data, prompts, and scoring rubric for an empirical evaluation of **citation accuracy in three frontier language models** — Claude Sonnet 5 Medium, ChatGPT 5.6 Terra, and DeepSeek V4.1 Flash — under research-agent conditions.

Each model was asked five research questions across three domains (AI/ML, biology/medicine, physics) and **forced to provide formal academic citations** in a strict format. Every citation was then manually verified against Google Scholar, PubMed, DOI resolution, and publisher websites.

## Key Findings

| Metric | Count | Percentage |
|--------|-------|------------|
| Total citations evaluated | 45 | 100% |
| **Real & Accurate** | 32 | **71%** |
| **Real but Distorted** | 12 | **27%** |
| **Fully Fabricated** | 1 | **2%** |

**The dominant failure mode is author misattribution, not fabrication.**

Models frequently produced citations with a correct DOI, correct title, and correct journal — but attributed to the wrong authors. This error type is dangerous because it survives superficial verification (DOI resolution confirms the paper exists; a researcher may not check the authors).

### Per-Model Accuracy

| Model | Accurate | Distorted | Fabricated | Accuracy Rate |
|-------|----------|-----------|------------|---------------|
| Claude Sonnet 5 Medium | 12 | 3 | 0 | **80%** |
| ChatGPT 5.6 Terra | 11 | 3 | 1 | **73%** |
| DeepSeek V4.1 Flash | 9 | 6 | 0 | **60%** |

Claude was the most accurate. ChatGPT produced the only fabrication. DeepSeek had the highest distortion rate (40%), almost all through wrong author attribution.

**Note on statistical significance:** With n=15 per model, 95% confidence intervals overlap. These per-model differences should not be interpreted as statistically significant. See the Threats to Validity section in the paper for details.

## Benchmark

<p align="center">
  <img src="/benchmark.png" alt="Citation Integrity Benchmark" width="100%">
</p>

## Why This Matters

Research agents — including the ones we are building at GrayTell — currently rely on **DOI resolution** or **title matching** to verify citations. This study shows that is not enough.

A citation can be:
- ✅ Real (DOI resolves)
- ✅ Correct title (search finds it)
- ❌ Credited to the wrong authors

This is the gap research agents must close.

## Repository Structure
citation-integrity-llm/
├── README.md ← you are here
├── CITATION.cff ← citation metadata
├── LICENSE ← Apache 2.0
├── benchmark.png ← benchmark chart
├── citation_integrity_llm.md ← the full paper
├── citations_scored.csv ← all 45 citations with verification labels
├── raw_responses.md ← full unedited model responses
└── strict_citation_prompt.txt ← the exact prompt use

## The Paper

📄 **[Read the full paper →](citation_integrity_llm)**

Full title: *Citation Integrity in Frontier Language Models: Author Misattribution and Fabrication in Research-Agent Conditions*

## The Data

- **[`citations_scored.csv`](citations_scored.csv)** — every citation produced by every model, with its verified label (`Real & Accurate`, `Real but Distorted`, `Fully Fabricated`) and notes on the specific error.
- **[`raw_responses.md`](raw_responses.md)** — the complete, unedited responses from Claude Sonnet 5 Medium, ChatGPT 5.6 Terra, and DeepSeek V4.1 Flash for Q3–Q5, including their `References` sections.

## The Prompt

- **[`strict_citation_prompt.txt`](strict_citation_prompt.txt)** — the exact prompt used to force formal citations, plus the verification protocol and scoring rubric.

## Reproducing This Work

1. Copy the prompt from `strict_citation_prompt.txt`
2. Run it on each model with the same questions (listed in the prompt file)
3. Extract every citation the model produces
4. Verify each one manually:
   - Search exact title on Google Scholar
   - Search authors + year + keywords
   - Resolve DOI (https://doi.org/[DOI])
   - Check the publisher website
5. Label each citation as:
   - **Real & Accurate** — all fields correct
   - **Real but Distorted** — paper exists, at least one field wrong
   - **Fully Fabricated** — no evidence the paper exists
6. Compare your results to `citations_scored.csv`

## Method Summary

| Element | Detail |
|---------|--------|
| Models tested | Claude Sonnet 5 Medium, ChatGPT 5.6 Terra, DeepSeek V4.1 Flash |
| Access method | Web interface |
| Date of collection | September 2026 |
| Questions | 5 (2 pilot + 3 core) |
| Core questions | CRISPR & sickle cell, gut microbiome & neurodegeneration, high-Tc superconductivity |
| Total citations | 45 (15 per model) |
| Verification | Google Scholar, PubMed, DOI, publisher sites |
| Scoring | Manual, per-citation, by a single reviewer |

## Limitations

- **Small sample size.** 45 citations (15 per model) is enough to identify patterns, but not to estimate population-level rates. 95% confidence intervals overlap between models.
- **Single run per prompt.** Models were not re-run for consistency.
- **Single reviewer.** All verification was performed by one person. No inter-annotator agreement was calculated.
- **No prompt ablation.** A single strict prompt was used; results may differ under other prompting conditions.
- **Unspecified temperature.** Model temperature settings were not recorded.
- **Limited domains.** Three domains tested; results may differ elsewhere.
- **Manual verification.** Some obscure papers may have been missed.

See the paper's Threats to Validity section for full discussion.

## Citation

If you use this work, please cite:

```bibtex
@misc{sapkota2026citation,
  author       = {Sapkota, Anubhav},
  title        = {Citation Integrity in Frontier Language Models:
                  Author Misattribution and Fabrication in
                  Research-Agent Conditions},
  year         = {2026},
  publisher    = {GrayTell Labs},
  howpublished = {\url{https://github.com/graytell/citation-integrity-llm}},
  note         = {Version 1.0.0}
}
GitHub will also generate APA, BibTeX, and RIS formats automatically via the "Cite this repository" button (powered by CITATION.cff).

Contact
Anubhav Sapkota
Founder, GrayTell Labs
sapkotaanubhav91@gmail.com
X: @GrayTell_Org

License
This work is licensed under the Apache License 2.0.
