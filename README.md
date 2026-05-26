# EGFR-MutSentry

> **A Precision Oncology Framework for Structural Atlas of EGFR Mutations in NSCLC**

[![Website](https://img.shields.io/badge/Website-Live-brightgreen?style=flat-square&logo=google-chrome)](http://danbioinfo.tech/egfr-mutsentry/)
[![License](https://img.shields.io/badge/License-Academic%20Use-blue?style=flat-square)](http://danbioinfo.tech/egfr-mutsentry/citation)
[![Manuscript](https://img.shields.io/badge/Manuscript-Under%20Review-orange?style=flat-square)](http://danbioinfo.tech/egfr-mutsentry/citation)
[![Mutants](https://img.shields.io/badge/EGFR%20Mutants-2%2C540-navy?style=flat-square)]()

---

## 🌐 Online Platform

**➡️ [http://egfr-mutsentry.com/](http://egfr-mutsentry.com/)**

---

## Overview

**EGFR-MutSentry** is an online precision oncology platform providing instant, structure-based insights and personalized TKI (tyrosine kinase inhibitor) recommendations for **2,540 EGFR mutants** in non-small cell lung cancer (NSCLC).

For each input mutation, it:
- Parses structural features and reveals mechanisms of aberrant activation
- Classifies the mutation into one of three mechanism-defined functional classes
- Outputs a ranked TKI affinity list across six first-, second-, and third-generation inhibitors
- Screens high-affinity FDA-approved drug candidates for resistant mutants

EGFR-MutSentry bridges structural biology and clinical decision-making, empowering oncologists and researchers with precise, actionable insights for targeted therapy.

---

## Key Features

### 🔬 Structure-Based Classification

Mutations are classified into three mechanism-defined classes with distinct therapeutic implications:

| Class | Description | Count |
|-------|-------------|-------|
| **Monomer-Activated** | Activate EGFR kinase as a monomer, driving autophosphorylation independently of dimerization | 1,298 |
| **Dimerization-Dependent** | Require receptor dimerization for kinase activation via asymmetric kinase-domain interactions | 605 |
| **Non-Activating** | Do not directly trigger kinase activation; may modulate drug binding or protein stability | 637 |

### 💊 Personalized TKI Recommendation

Molecular docking-based binding affinity (ΔG) ranking across **6 EGFR-TKIs** spanning three generations:

| Generation | Drugs |
|------------|-------|
| 1st Generation | Erlotinib, Gefitinib |
| 2nd Generation | Afatinib, Dacomitinib |
| 3rd Generation | Osimertinib, Lazertinib |

> **Key finding:** Second-generation TKIs offer the broadest coverage — they are the optimal choice for **72.6%** of activating mutants, followed by third-generation (22.8%) and first-generation (4.7%).

### 🛡️ Pan-TKI Resistance & Drug Repurposing

For **8 pan-TKI low-affinity mutants** (all compound mutations carrying resistance sites such as T790M, C797S, L718Q), where all six standard TKIs fail, EGFR-MutSentry performs structure-guided virtual screening against ~2,986 FDA-approved drugs to nominate repurposed therapeutic candidates.

---

## Database at a Glance

| Metric | Value |
|--------|-------|
| Total EGFR Mutants | **2,540** |
| Functional Classes | **3** |
| TKIs Profiled | **6** |
| Structural AI Tools | **3** (AlphaFold2, AlphaFold3, AlphaMissense) |
| Pan-TKI Resistant Mutants | **8** |

---

## Website Structure

| Page | Description |
|------|-------------|
| [**Home**](http://danbioinfo.tech/egfr-mutsentry/) | Platform overview, system diagram, and key features |
| [**Database**](http://danbioinfo.tech/egfr-mutsentry/database) | Browse, search, and filter all 2,540 EGFR mutants with TKI binding affinities |
| [**Statistics**](http://danbioinfo.tech/egfr-mutsentry/statistics) | Interactive charts: mutation class distribution, TKI landscape, drug-generation advantage, pan-TKI resistance profiles |
| [**Citation**](http://danbioinfo.tech/egfr-mutsentry/citation) | Citation formats (Plain Text / BibTeX / RIS), acknowledgment template |

---

## Methods

EGFR-MutSentry integrates three state-of-the-art AI structural tools:

- **AlphaFold2** — High-accuracy monomeric EGFR structure prediction
- **AlphaFold3** — Dimeric EGFR structure prediction for dimerization-dependent mutants
- **AlphaMissense** — Pathogenicity scoring for variant classification

Key structural domains analyzed: **αC-helix**, **activation loop (A-loop)**, **DFG motif**

---

## Citation

If you use EGFR-MutSentry in your research, please cite:

> Li, P., Wang, D., Liu, M. et al. *Navigating EGFR mutant diversity via conformational atlas to predict TKI responses and alternative inhibitors.* Manuscript submitted to *npj Precision Oncology* (2026).

You may also include in your Methods/Acknowledgments section:

> *"We used EGFR-MutSentry (Li et al., 2026) to obtain structural classification and TKI binding affinity predictions for EGFR mutants analyzed in this study."*

---

## License

EGFR-MutSentry is provided for **academic and research use only**. Commercial usage requires explicit permission from the authors.

---

## Contact

**Tianjin Medical University · Yang Lab**

📧 dan_wang@tmu.edu.cn

---

*This manuscript is currently under peer review. Citation details will be updated upon official publication.*
