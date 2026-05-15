# Supplementary Code for TITLE

This repository contains the supplementary code used for the bioinformatic and imaging analyses described in the manuscript:

**TITLE**  
DOI: **XXX**

The study investigates chromatin organization, accelerated aging, transcriptomic alterations, and nuclear morphology in schizophrenia.

## Repository Contents

This repository includes code for:

- Analysis of chromatin architecture and age-related changes in schizophrenia using our original multi-omics dataset (available in the NCBI Gene Expression Omnibus (GEO) under accession numbers **GSE330387** and **GSE330768**).
- Construction of transcriptomic aging clocks based on Elastic Net regression using publicly available schizophrenia transcriptomic data from the PsychENCODE Consortium (DOI: 10.15154/1g4m-dy13).
- Calculation of a custom transcriptomic aging metric, **Age Score**, based on previously published datasets (DOI: 10.1186/s13059-019-1747-7 and DOI: 10.7554/eLife.92393).
- Quantitative microscopy analysis of neuronal nuclei and assessment of nuclear size differences in schizophrenia using our imaging dataset, available on Zenodo (DOI: 10.5281/zenodo.20098460).

---

## Repository Structure

### `TranscriptomicClocks/`

Code for constructing transcriptomic aging clocks using Elastic Net regression.

**Data source:**
- PsychENCODE Consortium (DOI: 10.15154/1g4m-dy13)

---

### `AgeScore/`

Code for calculating the custom transcriptomic **Age Score**, a metric for estimating biological aging based on age-associated gene expression changes.

**Data sources:**
- Mendizabal et al., 2019 (DOI: 10.1186/s13059-019-1747-7)
- Zhu et al., 2024 (DOI: 10.7554/eLife.92393)

---

### `NucleiMicroscopy/`

Scripts for microscopy image processing and quantitative analysis of nuclear morphology.

**Data source:**
- Zenodo dataset (DOI: 10.5281/zenodo.20098460)

---

### `ChromatinAnalysis/`

Code for analyzing chromatin organization and aging-related chromatin alterations in schizophrenia.

**Data source:**
- GEO accessions: **GSE330768**, **GSE229816**, **GSE291967**

---

## Requirements

The code is primarily written in:
- Python
- R
- Bash

Dependencies are specified within individual scripts and notebooks.

---

## Citation

If you use this code or the associated datasets, please cite:

**TITLE**  
DOI: **XXX**

---

## Contact

For questions regarding the code or datasets, please contact the corresponding authors listed in the manuscript.