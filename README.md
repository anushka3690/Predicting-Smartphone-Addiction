# Smartphone Addiction Prediction

## Project objective

Explore whether behavioral and lifestyle information can help predict smartphone-addiction outcomes. The notebook combines exploratory analysis with feature engineering and a supervised classification workflow.

## Analysis and modeling

The notebook derives behavioral measures such as estimated weekly screen time, non-productive time, notifications per app open, screen time relative to study or sleep, and phone-checking intensity. It uses a stratified train/test split, a preprocessing/model pipeline, and probability predictions evaluated with ROC-AUC.

These are exploratory model features, not evidence that any single behavior causes addiction. No benchmark score is stated here; review the notebook outputs for the experiment details.

## Data and files

- `notebook/model1.ipynb` — exploratory analysis, feature engineering, and modeling
- The notebook expects `../data/train.csv` and `../data/test.csv`; these input files are not included in the repository.

## Reproduce the analysis

Place the permitted competition data in a `data/` directory at the repository root, then open the notebook in Jupyter and run its cells in order. Install the notebook's Python dependencies in your environment before execution.