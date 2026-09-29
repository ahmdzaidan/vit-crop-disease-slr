# Supplementary Materials

**How Are Vision Transformers Transforming Crop Disease Detection? A Systematic Literature Review**

Ahmad Zaidan Al-Anshory, Muhammad Aqil Firas, Ayla Chava, Agnia Klara Sari, Muhammad Rafli Alfansyah, Daniel Juniro Aslacris Situmorang, Mohamad Khoirun Najib, Mirza Farhan Azhari, Aulia Rizki Firdawanti

School of Data Science, Mathematics, and Informatics, IPB University, Bogor, Indonesia

---

## Overview

This repository contains the supplementary materials accompanying the systematic literature review (SLR) of Vision Transformer (ViT)-based crop disease detection. The review follows the PRISMA 2020 guidelines and analyzes 259 peer-reviewed studies retrieved from Scopus, covering ViT architectures, benchmark datasets, publication and geographical trends, and the major challenges and future research directions in this field.

## Contents

| File | Description |
|---|---|
| `data_extraction.csv` | Full data extraction sheet for all 259 included studies (author/year, ViT architecture, DL model(s) used, dataset(s), country/region, challenges and research gaps) |
| `prisma_checklist.pdf` | Completed PRISMA 2020 checklist |
| `figures/Figure S1_ml_dl_categories.png` | Full-resolution figure: Distribution of ML/DL umbrella categories used alongside ViTs (referenced but not reproduced in full in the manuscript due to page limits) |
| `figures/fig3_vit_architecture_full.png` | Full-resolution, unabridged breakdown of all Vision Transformer architecture variants identified during data extraction (Fig. 3 in the manuscript shows the harmonized/grouped version) |

## Data Extraction Fields

Each row in `data_extraction.csv` corresponds to one included study and contains the following fields, as described in Table IV of the manuscript:

1. Publication information (authors, title, publication year)
2. Vision Transformer architecture (ViT variant, e.g., ViT, Swin Transformer, DeiT, MobileViT, PVT, CvT, BEiT, Hybrid)
3. Deep learning model(s) used (baseline, comparison, or hybrid models)
4. Dataset information (dataset name, crop type, number of disease classes)
5. Country/Region (field site location, where reported)
6. Challenges and research gaps identified by the authors

## Methodology Summary

- **Database:** Scopus
- **Search string:** `TITLE-ABS-KEY(("Vision Transformer" OR ViT OR "Swin Transformer" OR DeiT) AND ("plant disease classification" OR "plant disease detection" OR "crop disease detection"))`
- **Records identified:** 333
- **Records screened:** 306
- **Studies included:** 259
- **Reporting guideline:** PRISMA 2020

Full details of the screening and eligibility process are provided in the manuscript (Section II) and in `prisma_checklist.pdf`.

## Contact

For questions regarding this dataset, contact ahmdzaidan@apps.ipb.ac.id
