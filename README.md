# A Little Study on the Marshall–Olkin Generalized Exponential Distribution

This repository contains the full LaTeX thesis project for:

**“A Little Study on the Marshall–Olkin Generalized Exponential Distribution via EM Algorithm, Simulation, and Data Analysis.”**

It includes mathematical foundations, derivations, EM algorithm estimation, simulation experiments, and real data analysis based on the 2015 paper by Ristić & Kundu.

---

## Project Structure

```text
moge_thesis/
├── main.tex                     # Main LaTeX file (compiles the whole thesis)
├── references.bib               # BibTeX references
├── preamble/
│   └── packages.tex             # Packages and custom commands
├── frontmatter/
│   ├── titlepage.tex            # Title page with logo & author info
│   ├── abstract.tex             
│   └── acknowledgements.tex
├── chapters/
│   ├── chapter1_introduction.tex
│   ├── chapter2_distributions.tex
│   ├── chapter3_model_description.tex
│   ├── chapter4_methodology_em_overview.tex
│   ├── chapter5_parameter_estimation.tex
│   ├── chapter6_simulation_study.tex
│   ├── chapter7_data_analysis.tex
│   └── chapter8_conclusion.tex
├── figures/                     # Plots, diagrams, TTT plots, hazard curves
├── data/                        # Datasets used for analysis
└── code/                        
    ├── moge_em_algorithm.py     # EM Algorithm implementation
    ├── moge_simulation.py       # Simulation study
    └── moge_data_analysis.py    # Real data model fitting
```

--- 

## Chapters Overview

### Chapter 1: Introduction

Motivation, real-life examples, story-driven explanation of lifetime modelling.

### Chapter 2: Distributions

Exponential → GE → Marshall–Olkin → MOGE.

### Chapter 3: Model Description

Full CDF & PDF derivation for the MOGE model.

### Chapter 4: EM Methodology

Conceptual EM algorithm explanation.

### Chapter 5: Parameter Estimation

MLE + full EM derivation.

### Chapter 6: Simulation Study

Bias, MSE, boxplots, convergence checks.

### Chapter 7: Real Data Analysis

Model comparison:
- MOGE
- GE
- Weibull
- Gamma

### Chapter 8: Conclusion

Findings, limitations, future scope.

---

## Purpose of This Repository

To provide a clean, reproducible, well-organized thesis workflow that includes:

- Full LaTeX code
- Mathematical derivations
- Python implementations
- Simulation results
- Data analysis scripts
- Figures & plots
- Everything needed to build and replicate the complete research project

---

## Contributors

- Devanshi Rhea Aucharaz
- Naima Dzhunushova
- Ridhi Jain
- Makhabat Zhyrgalbekova

**Supervisor:** Dr. Suchismita Das

--- 

## Source Materials Used

- Ristić & Kundu (2015) — Marshall–Olkin Generalized Exponential Distribution  

Note: Original papers are not included in this repository due to copyright restrictions.
