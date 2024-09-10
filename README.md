# Urban Air Quality and Health Impact Analysis

This project analyzes urban air quality data and its health impacts using Python for data cleaning, exploratory data analysis (EDA), and visualizations. It focuses on the correlation between temperature, humidity, and various health metrics across multiple cities.

## Dataset
- **Source:** [Urban Air Quality and Health Impact Dataset](link_to_dataset)
- **Description:** The dataset includes daily temperature, humidity, air quality, and health risk scores for several cities.

## Project Overview
1. **Data Cleaning:** Missing values in `preciptype`, `snowdepth`, and `Condition_Code` were imputed using mode and median values.
2. **Exploratory Data Analysis (EDA):**
   - Correlation matrix to identify relationships between variables.
   - Visualizations (boxplots, scatter plots) for `Health_Risk_Score` across cities and seasons.
3. **Key Insights:**
   - Higher temperatures tend to correlate with increased health risk scores.
   - Certain cities, like Houston and Dallas, show a higher median health risk.

## Tools and Techniques
- **Python Libraries:** pandas, seaborn, matplotlib
- **Statistical Methods:** Correlation analysis
- **Visualizations:** Boxplots, scatter plots, heatmaps

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/Smolbitties/Urban-Air-Quality.git
