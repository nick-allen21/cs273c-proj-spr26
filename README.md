# cs273c-proj-spr26

CS273C Course Project — Report 3 notebook (Stage 6b).

Reproduction of **Figure 1c** from Wu et al. (2025), *Nature Medicine*,
"Individual variations in glycemic responses to carbohydrates and underlying
metabolic physiology" (doi:10.1038/s41591-025-03719-2).

The notebook recreates the per-meal postprandial glucose response — AUC above
baseline and time-to-peak across seven standardized 50 g carbohydrate meals —
confirming the paper's headline result that rice produces the highest glucose AUC.

## Contents
- `Nick_Juan_Jessica_Research_Paper_Reproduction_Project.ipynb` — the reproduction notebook (Stages 0–5).
- `source_data/` — Figure source-data spreadsheets from the paper (`fig1.xlsx` holds the Fig 1c sheets).

## Running it
The notebook is self-contained. A setup cell fetches `fig1.xlsx` from this repo at
runtime, so a top-to-bottom **Restart Kernel → Run All** reproduces the figure on any
machine with internet.

LLM cells use Stanford Data Ocean's `%%sdo_llm` magic; on other platforms, supply your
own API key and run the prompt cells to regenerate the results.

Team: Nick Allen, Juan, Jessica.
