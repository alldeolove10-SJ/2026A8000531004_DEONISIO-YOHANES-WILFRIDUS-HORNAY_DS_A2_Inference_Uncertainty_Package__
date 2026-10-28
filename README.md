# DS-A2: Inference and Uncertainty

## 1. Project Overview

This project is about statistical inference and uncertainty. It uses sample data to calculate statistical summaries, confidence intervals, and effect sizes.

The goal is to understand the results and see how uncertainty affects the interpretation of data.

## 2. Project Files

The repository contains the following files and folders:

- `data/` - Contains the sample dataset.
- `Results/` - Contains the analysis results, tables, and figures.
- `report/` - Contains the final report in Word and PDF formats.
- `DS_A2_Inference_Uncertainty.ipynb` - Notebook used for the analysis.
- `DS_A2_Inference_Uncertainty.executed.ipynb` - Notebook with executed results.
- `AI_USE_LOG.md` - Record of AI tool usage.
- `README.md` - Project information and instructions.

## 3. Dataset

The dataset is stored in `data/ds_a2_sample_data.csv`.

It is used for the statistical analysis and calculations in this project.

## 4. Analysis

The analysis includes the following steps:

1. Load and check the sample data.
2. Calculate basic statistical summaries.
3. Use bootstrap sampling to study the distribution of estimates.
4. Calculate confidence intervals.
5. Calculate Cohen's d to examine effect size.
6. Present the results using tables and figures.

## 5. Results

The `Results/` folder contains:

- `DS_A2_statistical_summary.csv` - Statistical summary of the data.
- `bootstrap_sampling_distribution.png` - Bootstrap sampling distribution.
- `cohens_d_table.png` - Cohen's d results.
- `confidence_interval_table.png` - Confidence interval results.
- `statistical_summary_table.png` - Summary statistics table.

## 6. How to Run

Install the required libraries:

```bash
pip install pandas numpy matplotlib scipy jupyter nbconvert
```

Open the notebook:

```bash
jupyter notebook DS_A2_Inference_Uncertainty.ipynb
```

Run the notebook cells in order to perform the analysis.

To execute the notebook from the terminal, use:

```bash
jupyter nbconvert --to notebook --execute DS_A2_Inference_Uncertainty.ipynb --output DS_A2_Inference_Uncertainty.executed.ipynb
```

## 7. Report

The `report/` folder contains the final project report in Word and PDF formats. It explains the statistical methods and presents the main results.

## 8. Conclusion

This project helped me understand statistical inference and how to measure uncertainty in sample data. The results show how statistical summaries, confidence intervals, bootstrap sampling, and effect sizes can be used to interpret data.
