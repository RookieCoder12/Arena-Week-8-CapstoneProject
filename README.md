# DevArena-Week-7

## Overview
This project analyzes transactional retail data to uncover insights into sales performance across regions and time periods. The workflow includes data cleaning, exploratory data analysis (EDA), and statistical testing.

Using Python libraries such as Pandas, Matplotlib, and Statsmodels, the project examines sales trends, regional distribution, and seasonal patterns. A Two-Way ANOVA is applied to evaluate whether differences in sales across regions and quarters are statistically significant.

The project combines data preprocessing, visualization, and statistical analysis to support data-driven decision-making.

## Files
- data/
    - `cleaned_data.xlsx` - <b>Excel file</b> that contaons the raw data.
    - `raw_data.xlsx` - <b>Excel file</b> that contains the data after all the preprocessing and feature engineering has been done.

- notebooks/
    - `1_data_cleaning.ipynb` - <b>Python Notebook</b> that contains the preprocessing and feature engineering processes done on the data.
    - `2_eda.ipynb` - <b>Python Notebook</b> that contains the exploratory data analysis done on the data.
    - `3_analysis.ipynb` - <b>Python Notebook</b> that contaoins the statistical analysis done on the data.

- presentations/

- reports/

- `README.md` - This file.

- `requirements.txt` - Consist of <b>Python libraries</b> required for this project.

## Getting Started

### Prerequisites
Ensure you have Python 3.x installed on your system.

### Cloning Repository
Cloning the repository:
```zsh
git clone https://github.com/RookieCoder12/Arena-Week-8-CapstoneProject.git     
```

### Installation
Install the required dependencies:
```zsh
pip install -r requirements.txt
```

### Running the Project

#### Running the Python Notebook
1. Run jupyter notebook:
```zsh
jupyter notebook
```
2. Open ```1_data_cleaning.ipynb```, Open ```2_eda.ipynb```, Open ```3_analysis.ipynb```.

## Structure     
In this project, a structured data analysis workflow was implemented using Python to analyze transactional retail data and extract meaningful business insights.<br>

During the preprocessing phase, the dataset was cleaned and prepared by handling missing values, correcting data types, and creating additional features such as Month, Quarter, and Time of Day to support analysis.<br>

The analysis begins with Exploratory Data Analysis (EDA), where sales trends across regions, time periods, and transaction characteristics were examined to understand overall patterns in the data.<br>

Further analysis includes aggregation and pivot-based analysis, where region-wise and quarter-wise sales distributions were computed to enable comparative evaluation of performance.<br>

Statistical analysis was performed using Two-Way ANOVA to evaluate whether differences in sales across regions and quarters are statistically significant, along with examining interaction effects between these factors.<br>

Visualization plays a key role in the project, with bar charts, stacked graphs, and trend plots used to represent sales distributions and patterns clearly, improving interpretability.<br>

Overall, this project integrates data preprocessing, exploratory analysis, statistical modeling, and visualization to provide a comprehensive understanding of sales behavior and support data-driven decision-making.