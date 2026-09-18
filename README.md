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

