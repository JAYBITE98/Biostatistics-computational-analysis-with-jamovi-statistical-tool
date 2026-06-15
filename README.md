# Biostatistics-computational-analysis-with-jamovi-statistical-tool
My Biostatistics work using jamovi for analyses”
# BIS601 Biostatistics – Final Assignment: Levothyroxine Strategies in Primary Hypothyroidism

**Student:** Folorunso Julius Falana  
**Student number:** 20254585  
**Course:** BIS601 Biostatistics  
**Assignment date:** June 2026  

## Overview

This repository contains my complete statistical analysis for the final assignment of BIS601. The study investigates three treatment strategies for primary hypothyroidism:

- **Arm A:** Fixed‑dose levothyroxine  
- **Arm B:** Weight‑based levothyroxine  
- **Arm C:** Levothyroxine + liothyronine  

165 participants were randomised equally (n=55 per arm) and followed up at baseline (T0), 3 months (T3), 6 months (T6), and 12 months (T12).

## Contents

| File | Description |
|------|-------------|
| `20254585_Folorunso_Falana_workbook_Answers.docx` | Completed workbook with all hypothesis tests, assumption checks, result tables, and interpretations. |
| `BIS601_hypothyroidism_data.omv` | Jamovi project file containing the original dataset (unique to me) and all analyses performed. |
| `BIS601_hypothyroidism_data.csv` | Plain‑text backup of the data (same as `.omv`). |
| `README.md` | This file. |

## Research questions answered

Thirteen hypothesis tests are performed, covering:

- Association between sex and palpitations (chi‑square)  
- Atrial fibrillation episodes across arms A vs C (Fisher’s exact)  
- Change in TSH across four visits (Friedman test)  
- Association of medication adherence with treatment arm (chi‑square)  
- Clinical complications across arms (Fisher’s exact)  
- TSH at month 12 across three arms (Kruskal‑Wallis)  
- Baseline total cholesterol by sex (independent t‑test)  
- Change in resting heart rate from T0 to T12 (paired t‑test)  
- Free T4 at month 12 across three arms (one‑way ANOVA)  
- Baseline anti‑TPO antibody by sex (Mann‑Whitney U)  
- Change in creatine kinase from T0 to T12 (Wilcoxon signed‑rank)  
- Change in proportion with TSH above target (McNemar’s test)  
- Change in free T4 across four visits (Friedman test)  

All assumption checks (normality, homogeneity of variances, expected cell counts) are reported, and appropriate parametric or non‑parametric tests are justified.

## Reproducing the analysis

1. Install [jamovi](https://www.jamovi.org/) (version 2.6 or later).  
2. Open `BIS601_hypothyroidism_data.omv` directly in jamovi.  
3. Navigate to the *Analyses* tab – all 13 analyses are saved in the project.  
4. To re‑run a test, click on it in the *Results* panel, or re‑create it from the jamovi menu using the variable names in the codebook (see appendix of the workbook).  

Alternatively, import `BIS601_hypothyroidism_data.csv` (File → Import → CSV) and set variable types according to the codebook in the workbook appendix.

## Academic integrity note

This analysis is my own individual work. The dataset was issued uniquely to me and is traceable. I can explain every assumption check, test choice, and interpretation if asked. The `.omv` file records the actual analyses I performed in jamovi.

## License

This repository is for educational submission purposes. Please do not redistribute the dataset or use it for any other study without permission.

## Contact

For questions about this analysis, you can reach me via my university email (20254585@student.university.edu – example only).
