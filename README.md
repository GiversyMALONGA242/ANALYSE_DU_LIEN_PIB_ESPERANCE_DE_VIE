# Porfolio_Project

# Analysis of Economic Output and Life Expectancy (2000–2015)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Data%20Visualization-green)

## Executive Summary

This project explores the relationship between a nation's economic wealth (Gross Domestic Product - GDP) and the overall health of its population (Life Expectancy at Birth). Using longitudinal data from **2000 to 2015** across six representative countries (**Chile, China, Germany, Mexico, United States, and Zimbabwe**), the analysis evaluates whether higher economic output systematically translates to longer life expectancy.

---

## Research Questions

1. Has life expectancy increased over time in the six nations?
2. Has GDP increased over time in the six nations?
3. Is there a strong correlation between GDP and life expectancy?
4. What is the average life expectancy in these nations?
5. What is the overall distribution of life expectancy across the dataset?

---

## Data Sources

- **GDP Data:** World Bank national accounts data and OECD National Accounts data files (in USD).
- **Life Expectancy Data:** World Health Organization (WHO) Global Health Observatory records (Life expectancy at birth, in years).

Dataset file: `all_data.csv` (96 observations, 4 columns).

---
# Publication medium lien
https://medium.com/@giversymb/richesse-long%C3%A9vit%C3%A9-analyse-%C3%A9conom%C3%A9trique-et-visualisation-de-limpact-du-pib-sur-l-esp%C3%A9rance-de-f17fcc659332

## Project Structure

```bash
├── all_data.csv             # Raw dataset
├── life_expectancy_gdp.ipynb # Jupyter Notebook containing code, plots, and interpretations
├── README.md                # Project documentation
