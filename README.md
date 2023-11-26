# Hypothesis Testing - District Literacy Rates in Uttar Pradesh and Maharashtra

## Objective
The objective of this project is to conduct a hypothesis test to determine whether the difference between the mean district literacy rates in two of the largest states in India by population, Uttar Pradesh (UP) and Maharashtra (MH), is statistically significant or due to chance.

## Business Context
The Department of Education tasked with investigating the mean district literacy rates in UP and MH. Due to resource constraints, 20 randomly districts are chosen in each state. The goal is to understand if the observed difference in mean district literacy rates is statistically significant. If there is a statistically significant difference in mean district literacy rates, the state with the lower literacy rate will receive funding to improve literacy. 

## Steps

1. **Data Collection and Preprocessing:** Loaded data from 'Literacy Data 2011.csv', removed leading/trailing spaces, and extracted districts of UP and MH.

2. **Exploratory Data Analysis:** Visualized the literacy rates in districts of UP and MH using bar plots.

3. **Sampling:** Randomly sampled 20 districts from each state and calculated the mean literacy rates for each sample.

4. **Hypothesis Testing:** Conducted an independent two-sample t-test to compare the mean literacy rates. The null hypothesis is that there is no significant difference.

5. **Results and Visualization:** Visualized the difference in mean literacy rates and provided a summary report.

## Files

- `Hypothesis_Testing_Notebook.ipynb`: Jupyter notebook containing the analysis.
- `Literacy Data 2011.csv`: Dataset used for the analysis.

## Packages utilized 

1. Pandas
2. SciPy
3. Matplotlib and Seaborn


