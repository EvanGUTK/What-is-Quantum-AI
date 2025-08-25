# What‑is‑Quantum‑AI
> A rigorous, **theoretical** map of Quantum ⨯ AI: concepts, claims, caveats, and small simulator demos.

![hero](figures/hero.png)

**TL;DR**
- This repo is a **theory‑first** exploration of how quantum computing (QC) may intersect with machine learning (ML/AI).
- Everything here is **simulator‑based and non‑hardware‑validated** unless explicitly stated.
- Goals: (1) explain the space precisely, (2) provide small runnable sketches on CPU, (3) document open questions honestly.

---

## Table of Contents
- [Scope & Philosophy](#scope--philosophy)
- [Quickstart](#quickstart)
- [Project Layout](#project-layout)
- [Quantum 101 (tiny primer)](#quantum-101-tiny-primer)
- [ML 101 (tiny primer)](#ml-101-tiny-primer)
- [Hybrid Patterns (VQE, QAOA, QNN, Kernels)](#hybrid-patterns-vqe-qaoa-qnn-kernels)
- [Data Encoding & Ansatz Design](#data-encoding--ansatz-design)
- [Trainability, Barren Plateaus & Mitigation](#trainability-barren-plateaus--mitigation)
- [Error & Noise: Mitigation vs. Correction](#error--noise-mitigation-vs-correction)
- [Benchmarks & Baselines](#benchmarks--baselines)
- [Worked Mini‑Demos (Simulators)](#worked-mini-demos-simulators)
- [Ethics, Safety & Hype Control](#ethics-safety--hype-control)
- [Roadmap & Open Questions](#roadmap--open-questions)
- [How to Contribute](#how-to-contribute)
- [Cite This Work](#cite-this-work)
- [License](#license)

---

## Scope & Philosophy
**What this is**
- A structured, **claim‑traceable** reference for Quantum AI ideas.  
- A set of **small, CPU‑friendly demos** to make definitions concrete.

**What this is not**
- Not an endorsement that any given quantum approach **beats** classical methods today.  
- Not hardware results. **Assume simulators only** unless clearly labeled otherwise.

**Design principles**
1. **Explain first, code second.** Theory sections lead; demos follow.
2. **No cherry‑picking.** Always compare to strong **classical baselines** sized to the task.
3. **Reproducibility.** Fixed seeds, documented environments, small datasets for quick runs.
4. **Transparency.** Explicitly separate **assumptions, hypotheses, and evidence**.

---

## Quickstart
> CPU‑only, Python 3.10+ recommended.

**Option A: Conda**
```bash
git clone https://github.com/<you>/What-is-Quantum-AI.git
cd What-is-Quantum-AI
conda env create -f environment/conda-env.yml
conda activate whatisqai
python -m pip install -e .
