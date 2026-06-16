# Northeastern University Research Funding Analysis

Exploratory data analysis of externally funded research grants at Northeastern University from 1995 to 2026.

## Goal
Build a picture of who is funded at Northeastern, how much, by whom, and on what topics, and how that has changed over time.

## Data
Four internal datasets:
- `faculty-list-2025.xlsx` current faculty roster (2,232 people)
- `grants-with-copi.xlsx` primary grant file, 2,670 unique grants, $2.15B total
- `grants-with-abstract.xlsx` grant titles and abstracts (8,075 rows)
- `ri_matches_grants_2026.xlsx` alternate grant export, used for cross-validation


## Notebooks
- `01_northeastern_funding_basic_QC.ipynb` — data loading, cleaning, null audit, and exploratory analysis
- `02_funding_analysis.ipynb` — funding concentration, college and agency breakdowns, co-PI structure, gap analysis
- `03_topic_modeling.ipynb` — text cleaning and topic modeling with LDA, NMF, and BERTopic on grant abstracts
- `04_topic_validation.ipynb` — topic coherence scoring, assignment confidence, logistic regression classifier, UMAP visualization, within-topic analysis


## Status
Data cleaning and quality check complete. Funding analysis complete. Topic modeling complete. Topic validation and college-topic analysis complete.