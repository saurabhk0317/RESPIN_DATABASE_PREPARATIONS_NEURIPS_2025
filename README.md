_# RESPIN Database Preparations — NeurIPS 2025 (Datasets and Benchmarks Track)

This repository contains the Overleaf LaTeX source files, figures, and tables for the **RESPIN Database** paper submitted to **NeurIPS 2025 (Datasets and Benchmarks Track)**.  
The paper documents the design, development, and benchmarking of the **RESPIN corpus** — a large-scale, dialect-rich speech dataset for Indian languages, jointly developed at SPIRE Lab, IISc Bangalore.

---

## 📘 Overview

The RESPIN corpus aims to enable robust and dialect-aware **Automatic Speech Recognition (ASR)** and **Dialect Identification (DID)** for Indian languages.  
This NeurIPS 2025 submission presents:
- Dataset composition and statistics across 9 Indian languages and 38 dialects  
- Recording and annotation pipeline with quality control stages  
- Domain coverage (Agriculture and Finance)  
- Benchmark results using multiple ASR and DID baselines  
- Multimodal extensions integrating speech and text modalities  

This repository mirrors the complete Overleaf project used for preparing the camera-ready draft and supplementary appendix.

---

## 📁 Repository Structure
Styles/
├── figures/                 
│   └── *                     # Figures used in the main paper
│
├── figures_appendix/         
│   └── *                     # Figures used in the supplementary appendix
│
├── tables/                   
│   └── *                     # Tables for dataset statistics and benchmark results
│
├── RESPIN_DATABASE_PREPARATIONS_NEURIPS_2025.pdf        
│                             # Main draft (pre-final version)
│
├── RESPIN_DATABASE_PREPARATIONS_NEURIPS_2025_FINAL.pdf  
│                             # Final camera-ready version
│
├── RESPIN_NEURIPS_final_draft.tex                       
│                             # LaTeX source file for the main paper
│
├── additional_appendices.tex                            
│                             # Supplementary appendix with extended results and details
│
├── neurips_2025.pdf                                    
│                             # NeurIPS 2025 style guide (PDF)
│
├── neurips_2025.sty                                    
│                             # Official NeurIPS 2025 LaTeX style file
│
├── respin_database.tex                                 
│                             # Core LaTeX file integrating all sections and figures
│
└── respin_references.bib                               
                              # Bibliography file containing all references cited in the paper

📄 Description of Key Components

figures/ — Contains all plots and schematic diagrams used in the main paper.

figures_appendix/ — Includes supplementary visualizations for the appendix (dataset breakdowns, model comparisons, etc.).

tables/ — Contains LaTeX tables summarizing dataset statistics, benchmarks, and model comparisons.

RESPIN_DATABASE_PREPARATIONS_NEURIPS_2025_FINAL.pdf — Final compiled camera-ready version of the paper.

RESPIN_NEURIPS_final_draft.tex — Main LaTeX source for the paper (entry point for compilation).

additional_appendices.tex — Appendix and supplementary content, typically included after the main text.

respin_database.tex — Core LaTeX file that integrates all sections, figures, and tables.

respin_references.bib — BibTeX file containing all citations used across the paper.

neurips_2025.sty / neurips_2025.pdf — Official NeurIPS 2025 Datasets and Benchmarks style files for formatting and submission compliance.

---

## 🧩 Components

### 1. **Paper and Appendix**
- `RESPIN_NEURIPS_final_draft.tex`: Main text of the NeurIPS 2025 submission  
- `additional_appendices.tex`: Contains extended tables and analyses included in the supplementary appendix

### 2. **Figures and Tables**
- `figures/` and `figures_appendix/`: Contain visualizations of dataset statistics, language coverage, and model performance
- `tables/`: Includes language-wise and dialect-wise statistics, benchmark results, and dataset distribution summaries

### 3. **Bibliography and Styles**
- `respin_references.bib`: Contains all references cited in the paper
- `neurips_2025.sty`: Official NeurIPS LaTeX style file for Datasets and Benchmarks submissions

---

## 🧪 Related Work

The RESPIN Database builds upon the team's prior work on:
- **MADASR** and **MADASR2.0** multilingual ASR challenges  
- **Dialect identification methods** combining SSL-Conformer and RoBERTa text encoders  
- **Multimodal fusion architectures** for joint ASR–DID training in Indian languages  

For details, refer to the Interspeech 2025 paper:  
> *Jointly Improving Dialect Identification and ASR in Indian Languages using Multimodal Feature Fusion*  
> and the ICASSP 2025 paper:  
> *Improving Dialect Identification in Indian Languages Using Multimodal Features from Dialect-Informed ASR*.

---

## 🏗️ Development Notes

This repository was originally synced from **Overleaf**, and retains its directory structure and compilation settings.  
To build locally:

```bash
pdflatex RESPIN_NEURIPS_final_draft.tex
bibtex RESPIN_NEURIPS_final_draft
pdflatex RESPIN_NEURIPS_final_draft.tex
pdflatex RESPIN_NEURIPS_final_draft.tex

🧠 Citation

If you use the RESPIN corpus or refer to this paper, please cite:

@inproceedings{saurabh2025respin,
  title     = {RESPIN-S1.0: A Large-Scale Dialect-Rich Speech Corpus for Indian Languages},
  author    = {Saurabh Kumar and et al.},
  booktitle = {NeurIPS Datasets and Benchmarks Track},
  year      = {2025}
}

👥 Acknowledgements

This work was carried out at SPIRE Lab, Indian Institute of Science (IISc) Bangalore
as part of ongoing efforts to advance speech recognition and dialect modeling for Indian languages.
We thank the ARTPARK initiative for support and collaboration on multilingual data collection and curation.

📄 License

All LaTeX source files and supplementary materials in this repository are provided for academic and research use only.
Please contact the authors for dataset licensing details or redistribution permissions.
_
