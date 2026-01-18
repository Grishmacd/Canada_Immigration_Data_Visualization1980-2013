# Canada Immigration Data Visualization (1980–2013)

This notebook analyzes and visualizes **immigration to Canada from 1980 to 2013** using a country-wise dataset. The focus is on creating multiple plots to compare immigration trends across years and countries.

---

## Problem Statement

Given a dataset containing immigration details to Canada (1980–2013), the goal is to:
- Understand yearly immigration trends
- Compare immigration patterns between multiple countries
- Create clear visualizations using different chart types

---

## Selection of Data

**Dataset Type Used:** Structured tabular dataset  
- Rows: Countries  
- Columns: Years (1980 to 2013)  
- Values: Immigration counts per year

---

## Collection of Data

The dataset is uploaded in Google Colab using:
- `from google.colab import files`
- `files.upload()`

Then it is loaded and processed using **pandas**.

---

## Visualizations Created

### 1) Area Plot (Multiple Countries)
Compares immigration trends over time for:
- India
- China
- Philippines
- Pakistan
- France
- Bangladesh

### 2) Bar Chart (1980–2013)
Shows immigration values across years using a bar plot format.

### 3) Boxplot (India: 1980–2013)
Displays the distribution of India’s immigration values across the full year range.

### 4) Area Chart (India vs France)
Direct comparison of immigration trends between India and France (1980–2013).

### 5) Pie Chart (India Total)
Represents India’s total immigration across 1980–2013 as a pie-style visualization.

### 6) Scatter + Histogram (2013 Values)
Uses 2013 values for selected countries:
- Fiji
- Singapore
And visualizes them using scatter and histogram-style plots.

---

## Main Libraries Used (and why)

1. `pandas`  
   - Loads the dataset, filters country/year data, and prepares values for plotting.

2. Plotting Libraries  
   - Used to generate area plots, bar charts, boxplots, pie charts, scatter plots, and histograms.

---

## Output

- Multiple charts showing immigration trends and comparisons
- Country-focused view (example: India over 1980–2013)
- Comparison plots across multiple countries and years

---

## Developer
Grishma C.D
