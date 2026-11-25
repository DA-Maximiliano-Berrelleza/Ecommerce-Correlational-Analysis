# NovaRetail+ | Customer Behavior Correlation Analysis

[Español](README.md) | English

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DA-Maximiliano-Berrelleza/Ecommerce-Correlational-Analysis/blob/main/Ecommerce_Correlational_Analysis.ipynb)

## Objective

Identify which customer behaviors are most strongly associated with annual revenue generated for NovaRetail+, providing evidence to support the Growth and Retention team.

This is an exploratory, correlational analysis. It does not establish causation.

## Data

The dataset contains **15,000 records and 12 columns** covering customer characteristics, activity, advertising, satisfaction, membership, churn, device, region, and revenue generated.

The primary metric is `ingreso_anual` (annual revenue).

This project was completed as part of TripleTen's data analytics training program.

## Analysis workflow

1. Load and explore the dataset.
2. Prepare the data and document assumptions.
3. Visualize relationships using a heatmap and scatterplots.
4. Calculate Pearson and Spearman correlations, point-biserial correlation, and Cramér's V.
5. Interpret findings and business implications.
6. Document limitations and next steps.

## Repository files

| File | Contents |
|---|---|
| `Ecommerce_Correlational_Analysis.ipynb` | Code, visualizations, results, and analysis report. |
| `novaretail_comportamiento_clientes_2024.csv` | Dataset used in the project. |
| `README.md` | Project description and execution instructions in Spanish. |
| `README.en.md` | Project description and execution instructions in English. |

## Tools

Python, pandas, NumPy, Seaborn, Matplotlib, and SciPy. The notebook was run in Google Colab.

## Reproduce the analysis in Google Colab

1. Download `novaretail_comportamiento_clientes_2024.csv` from this repository.
2. Click the **Open in Colab** button at the top of this README.
3. In Colab's **Files** panel, upload the CSV.
4. Confirm that its path is:
   `/content/novaretail_comportamiento_clientes_2024.csv`.
5. Run the cells in order, from the imports through the final calculation.

The notebook includes saved outputs, so the analysis can be reviewed without running it. To recalculate the results, upload the CSV to the Colab session.
