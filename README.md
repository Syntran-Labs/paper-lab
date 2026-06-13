# 📄 Paper Lab

![Track](https://img.shields.io/badge/Syntran%20Labs-Paper%20Track-purple?style=flat-square)
![Purpose](https://img.shields.io/badge/Purpose-Paper%20Implementations-brightgreen?style=flat-square)
![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=flat-square&logo=python&logoColor=white)
![CI](https://img.shields.io/badge/CI-GitHub%20Actions-blue?style=flat-square&logo=githubactions&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active-success?style=flat-square)

**AI and ML research papers turned into working, reproducible implementations.**

*Every project takes a published paper and translates its core algorithms, experiments, and findings into clean, runnable code — with explanations that connect each implementation back to the paper.*

*Part of [Syntran Labs](https://github.com/Syntran-Labs)*

---

## ✨ What Is This?

**Paper Lab is a curated catalog of independent educational implementations of research papers from Syntran Labs.** Each implementation lives in its own standalone `paper-*` repository with its own README, notebooks, tests, and CI.

Each project is built around one question:

> **"What would it look like if the paper's key ideas were implemented from scratch, clearly, and verified to work?"**

That means every project in this collection aims to be:

| Quality | What It Means |
|---|---|
| 📖 **Paper-grounded** | Every class, function, and dataset maps back to a specific definition, algorithm, or section in the paper |
| 🔁 **Reproducible** | Key tables and figures from the paper are reproduced numerically and verified |
| 🪞 **Independent** | Not the official implementation — a clean, educational re-implementation with clear scope |
| ✅ **Tested** | Smoke-tests and CI confirm the implementation runs correctly |
| 🚫 **No copyright violations** | Paper PDFs are excluded; DOI references are provided in every repo |

---

## 📚 Published Implementations

Each project is a **standalone repository** with its own README, notebooks, tests, and GitHub Actions CI.

| Project | Paper | Year | Status | What It Reproduces |
|---|---|:---:|:---:|---|
| **[paper-rag-graph-4-datasets](https://github.com/Syntran-Labs/paper-rag-graph-4-datasets)** | Diamantini et al. — *A Graph RAG Approach to Enhance Explainability in Dataset Discovery* · [DOI](https://doi.org/10.1007/s41019-025-00313-x) | 2026 | ✅ Published | Two-layer KG model (BKG + SKG), source profiling, KG-enriched query generation (Algorithm 1), preference-oriented ranking & explainability (Algorithm 2), end-to-end pipeline demo, Tables 1–5 · Python · Jupyter · NumPy · pandas · matplotlib · pytest |

---

## 🧭 Implementation Philosophy

> **A paper implementation should make the reader understand the paper, not just run it.**

For that reason, every project in this collection goes beyond code:

```
Working implementations        Paper-grounded explanations      Reproduced tables & figures
Offline mock outputs           CI-validated smoke-tests         Clear scope: what is and isn't reproduced
```

And follows a consistent structure:

```text
paper-*/
├── README.md            ← what paper, what is reproduced, how to run
├── CITATION.cff         ← cite the implementation + the original paper
├── *.ipynb              ← notebooks (one per major pipeline stage)
├── gen_notebooks.py     ← source of truth; regenerates all notebooks
├── tests/               ← smoke-tests
└── .github/workflows/   ← CI
```

---

## 🔗 Key Links

- **[Syntran Labs](https://github.com/Syntran-Labs)** — The full portfolio
- **[learning-lab](https://github.com/Syntran-Labs/learning-lab)** — Educational engineering projects track
- **[systems-lab](https://github.com/Syntran-Labs/systems-lab)** — Production-oriented AI systems track

---

*Built at [Syntran Labs](https://github.com/Syntran-Labs) by Leonardo Sigales*

*Found an implementation useful? A ⭐ helps others find it too.*

**[Connect on LinkedIn →](https://www.linkedin.com/in/leonardo-sigales-58296619)**
