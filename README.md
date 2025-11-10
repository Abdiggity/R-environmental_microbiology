# Microbial Community Analysis – Lyme Park (Environmental Microbiology)

This repository contains R code and a report analysing bacterial community composition along a 1.2 km freshwater stream in Lyme Park (UK).  
The aim is to explore how abiotic factors — particularly **pH** and **metal concentrations** — shape lotic microbial community structure and diversity.

The project demonstrates the full workflow of a microbial ecology analysis, from community diversity metrics to ordination and environmental correlation.

---

##  Project Overview

**Techniques used:**
- Alpha diversity (richness, Simpson index)
- Beta diversity (Bray–Curtis dissimilarity, NMDS)
- Environmental fitting (`envfit`, `anosim`)
- Community assembly modelling (Raup–Crick null model)
- Co-occurrence and correlation analysis
- Rank–abundance visualisation

**Software:** R (`vegan`, `BiodiversityR`)

---

##  Repository Structure

```text
.
├── README.md                     # project description and instructions
├── analysis.R                    # main R analysis script (clean, annotated)
├── report/
│   └── Environmental_Microbiology_Coursework.docx  # written report
└── figures/                      # optional: generated NMDS / ordination / rank-abundance plots
