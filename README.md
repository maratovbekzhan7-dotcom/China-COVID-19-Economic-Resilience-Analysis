# Economic Resilience Index (ERI): China During COVID-19


Click [here](README.md) to see the Chinese document.  

## Overview

This project introduces the **Economic Resilience Index (ERI)**, designed to measure how resilient different Chinese provinces were during the COVID-19 period. The index combines several standardized economic indicators into a single composite score, allowing regional comparison and temporal analysis.

The main goal of the project is to:

* Quantitatively assess regional economic resilience
* Compare provinces based on their ability to withstand economic shocks
* Visualize spatial and statistical patterns clearly and intuitively

---

## Methodology

### 1. Data Preparation

Raw provincial-level economic indicators were collected and cleaned. Each indicator reflects an aspect of economic stability or recovery capacity during the pandemic period.

### 2. Standardization (Z-score)

To make indicators comparable, each variable was standardized using the **Z-score** method:

> Z = (x − μ) / σ

This removes scale effects and allows aggregation across different units.

### 3. Index Construction

The standardized indicators were aggregated into a single composite index:

* Higher ERI values → stronger economic resilience
* Lower ERI values → weaker economic resilience

### 4. Trend and Distribution Analysis

Statistical analysis was applied to:

* Observe the overall distribution of ERI values
* Identify outliers and regional patterns
* Analyze trends across provinces

---

## Visualizations

### 🗺️ ERI Map (Provincial Level)

The map visualizes the spatial distribution of economic resilience across China during COVID-19.


<img src="Economic_Resilience-China/data/visuals/maps/map_eri-covid.png" width="600">


* Darker colors indicate higher resilience
* Lighter colors indicate lower resilience

---

### 📊 ERI Distribution and Trends

These charts illustrate the statistical behavior of the index.

#### ERI Distribution


<img src="Economic_Resilience-China/data/visuals/plots/plot-2.png" width="600">


---

## Key Findings

* Economically diversified provinces tend to show higher resilience
* Less-developed or structurally dependent regions were more vulnerable
* Some western regions display unexpected stability, suggesting non-obvious resilience factors

---

## Technologies Used

* Python
* Pandas & NumPy
* Matplotlib
* GeoPandas
* Jupyter Notebook

---

## Purpose of the Project

This project is primarily academic and analytical. It demonstrates:

* Applied economic analysis
* Data processing and standardization techniques
* Clear and interpretable data visualization

It can be extended for comparative studies, policy analysis, or further econometric modeling.

---

## Notes

All visualizations are generated programmatically. Paths in this README assume the default project structure shown above.
