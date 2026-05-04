# R Analysis Portfolio — Haruna Isola Aremu

Reproducible data analysis scripts and reports in R, covering germination
biology, statistical genetics, and data visualisation. Developed across
doctoral-level research and structured online coursework.

---

## Contents

### 1. Celosia argentea — Temperature Germination Profile (TGP)
**File:** `celosia_visualisation.R`
**Rendered report:** [View on GitHub Pages](https://haroon948.github.io/portfolio_1/)

Analysis of germination responses across 35 *Celosia argentea* accessions
tested along a 15–40°C temperature gradient. Conducted at Aarhus University,
Flakkebjerg Research Facility (February–April 2026).

Covers:
- Data wrangling and transformation with `tidyverse`
- Germination percentage, mean germination time (MGT), and germination
  index (GI) computed per accession and temperature
- `pmax()` for daily germination increments with negative-increment flooring
- NA-aware standard error denominators
- Multi-panel `ggplot2` visualisations with a consistent temperature
  colour palette across all figures (heatmap, bar charts, boxplots,
  violin plots, faceted trend curves)

**Key finding:** Optimal temperature for germination capacity is 35°C;
optimal temperature for germination speed is 30°C.

---

### 2. Segregation Distortion Analysis — FIT 678 Assignment
**File:** `week3-2_assignment.Rmd`
**Rendered report:** [View on GitHub Pages](https://haroon948.github.io/portfolio_1/week3-2-assignment.html)

Chi-square goodness-of-fit analysis of molecular marker segregation in
backcross (mouse) and F2 (maize) populations. Completed as part of
FIT 678: Genetic Data Analysis for Plant Breeding (Federal University
of Viçosa, Brazil — Prof. Guilherme da Silva Pereira).

Covers:
- Chi-square tests for 1:1 (backcross) and 1:2:1 (F2) Mendelian ratios
- Loop-based marker-wise testing across 14 mouse and 12 maize markers
- Bonferroni correction for multiple testing (family-wise error rate)
- Visualisation of sorted p-values against uncorrected and corrected
  significance thresholds
- Interpretive write-up integrated with code in R Markdown

---

## Note on Raw Data

Raw data files are not included in this repository. The *Celosia argentea*
dataset was collected as part of an ongoing research collaboration at
Aarhus University, Flakkebjerg Research Facility, and remains unpublished.
Sharing it publicly without institutional clearance would be inappropriate
at this stage. The FIT 678 datasets (mouse and maize marker data) are
course materials owned by the Federal University of Viçosa and are not
mine to distribute.

All scripts are written to be fully reproducible once compatible data
are supplied. Data loading lines are clearly marked in each script.

---

## Author

**Haruna Isola Aremu**
Plant Scientist | Computational Breeding & Data Analysis
MSc Plant Breeding and Genetics, Federal University of Technology Akure (FUTA)
BTech Crop Production and Soil Science, LAUTECH

[LinkedIn](https://www.linkedin.com/in/haruna-aremu/) | [GitHub](https://github.com/haroon948)
