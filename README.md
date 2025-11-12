# RESPIN Database Preparations — NeurIPS 2025 (Datasets & Benchmarks Track)

This repository contains the Overleaf LaTeX source, figures, tables, and compiled PDFs for the RESPIN Database paper submitted to NeurIPS 2025 (Datasets & Benchmarks Track). The paper documents the design, development, and benchmarks for the RESPIN corpus — a large-scale, dialect-rich speech dataset for Indian languages developed at SPIRE Lab, IISc Bangalore.

---

## 📘 Overview

RESPIN is designed to enable robust, dialect-aware research in:

- Automatic Speech Recognition (ASR)
- Dialect Identification (DID)

This NeurIPS submission includes:
- Dataset composition and statistics across 9 Indian languages and 38 dialects
- Recording and annotation pipeline with quality-control stages
- Domain coverage (Agriculture and Finance)
- Benchmark results using multiple ASR and DID baselines
- Multimodal extensions integrating speech and text

The repository mirrors the Overleaf project used to prepare the camera-ready draft and supplementary appendix.

---

## 📁 Repository Structure

Top-level layout (representative):

```
Styles/
├── figures/                      # Figures used in the main paper
├── figures_appendix/             # Appendix figures
├── tables/                       # LaTeX tables for stats & benchmarks
├── RESPIN_DATABASE_PREPARATIONS_NEURIPS_2025.pdf
├── RESPIN_DATABASE_PREPARATIONS_NEURIPS_2025_FINAL.pdf
├── RESPIN_NEURIPS_final_draft.tex
├── additional_appendices.tex
├── neurips_2025.pdf
├── neurips_2025.sty
├── respin_database.tex
└── respin_references.bib
```

Brief descriptions:

- figures/ — plots and schematic diagrams used in the main paper.
- figures_appendix/ — supplementary visualizations for the appendix (dataset breakdowns, model comparisons).
- tables/ — LaTeX tables summarizing dataset statistics, benchmarks, and distribution summaries.
- RESPIN_DATABASE_PREPARATIONS_NEURIPS_2025_FINAL.pdf — final camera-ready PDF.
- RESPIN_NEURIPS_final_draft.tex — main LaTeX source (entry point for compilation).
- additional_appendices.tex — supplementary appendix with extended results.
- respin_database.tex — core LaTeX file assembling sections, figures, and tables.
- respin_references.bib — BibTeX bibliography used in the paper.
- neurips_2025.sty / neurips_2025.pdf — official NeurIPS style files and guide.

---

## 🧩 Components

### 1. Paper and Appendix
- RESPIN_NEURIPS_final_draft.tex: Main NeurIPS 2025 submission source.
- additional_appendices.tex: Extended tables and analyses for the supplementary appendix.

### 2. Figures and Tables
- figures/ and figures_appendix/: Visualizations of dataset statistics, language/dialect coverage, and model results.
- tables/: Language-wise and dialect-wise statistics, benchmark results, dataset distribution summaries.

### 3. Bibliography and Styles
- respin_references.bib: All references cited in the paper.
- neurips_2025.sty: Official NeurIPS LaTeX style file for Datasets and Benchmarks submissions.

---

## 🧪 Related Work

RESPIN builds on prior efforts by the team, including:
- MADASR and MADASR2.0 multilingual ASR challenges
- Dialect identification methods combining SSL-Conformer and RoBERTa text encoders
- Multimodal fusion architectures for joint ASR–DID training in Indian languages

See related publications:
- "Jointly Improving Dialect Identification and ASR in Indian Languages using Multimodal Feature Fusion" — Interspeech 2025
- "Improving Dialect Identification in Indian Languages Using Multimodal Features from Dialect-Informed ASR" — ICASSP 2025

---

## 🏗️ Development & Local Build

This repository was synced from Overleaf and retains the directory and compilation settings.

To compile the paper locally (example sequence):

```bash
pdflatex RESPIN_NEURIPS_final_draft.tex
bibtex RESPIN_NEURIPS_final_draft
pdflatex RESPIN_NEURIPS_final_draft.tex
pdflatex RESPIN_NEURIPS_final_draft.tex
```

Notes:
- Ensure neurips_2025.sty is available in the working directory or TEXINPUTS path.
- Run bibtex (or biber if using biblatex) as appropriate for your bibliography configuration.

---

## 🧠 Citation

If you use the RESPIN corpus or refer to this paper, please cite:

```bibtex
@inproceedings{
kumar2025respins,
title={{RESPIN}-S1.0: A read speech corpus of 10000+ hours in dialects of nine Indian Languages},
author={Saurabh Kumar and Abhayjeet Singh and DEEKSHITHA G and Amartyaveer and Jesuraj Bandekar and Savitha Murthy and Sumit Sharma and Sandhya Badiger and Sathvik Udupa and Amala Nagireddi and Srinivasa Raghavan K M and Rohan Saxena and Jai Nanavati and Raoul Nanavati and Janani Sridharan and Arjun Mehta and Ashish Khuraishi K S and Sai Praneeth Reddy Mora and Prashanthi Venkataramakrishnan and Gauri Date and Karthika P and Prasanta Kumar Ghosh},
booktitle={The Thirty-ninth Annual Conference on Neural Information Processing Systems Datasets and Benchmarks Track},
year={2025},
url={https://openreview.net/forum?id=qL8M2dOY4L}
}
```

---

## 👥 Acknowledgements

This work was carried out at SPIRE Lab, Indian Institute of Science (IISc) Bangalore. We thank the ARTPARK initiative for support and collaboration on multilingual data collection and curation.

---

## 📄 License & Data Use

All LaTeX source files and supplementary materials in this repository are provided for academic and research use only. Contact the authors for dataset licensing details or redistribution permissions.

---

If you need a trimmed version of this README (e.g., only build instructions, or a condensed repo tree), say which section to focus on.
