# tcga-pathology-truncation-study

Investigating whether truncating cancer pathology reports to 512 tokens hurts classification accuracy.

## Project
Reproducing and extending Kefeli & Tatonetti (2024) on BRCA, LUAD, and PRAD cancer types using three input strategies:
1. First-512 truncation (ClinicalBERT baseline)
2. Head-to-tail truncation (ClinicalBERT)
3. Full document (Clinical-BigBird)

## Dataset
TCGA pathology reports 9,523 reports across 32 cancer types.  
Source: https://github.com/tatonetti-lab/tcga-path-reports

## Course
CSE 676 Deep Learning, University at Buffalo