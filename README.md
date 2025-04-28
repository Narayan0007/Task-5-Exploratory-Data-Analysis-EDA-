# Task-5-Exploratory-Data-Analysis-EDA-


# Titanic Dataset EDA  
**Exploratory Analysis of Survival Patterns**

## Overview  
Performed comprehensive data exploration on the Titanic passenger dataset to identify key survival factors. Analyzed 891 passenger records with 14 features including class, age, fare, and gender.

## Key Steps  
✔️ **Data Cleaning**: Handled missing values in `age` (mean imputation) and `embark_town` (record removal). Dropped `deck` column (70%+ missing).  
📊 **Visual Analysis**: Created histograms, boxplots, heatmaps, and survival comparison charts.  
🔗 **Correlation Study**: Identified strong links between survival and class/fare, with gender as a critical factor.  
📝 **Insights**: Found first-class passengers had 2.6x higher survival rate than third-class, and female survival rate (75%) dwarfed male (20%).

## Tools Used  
`Python` | `Pandas` | `Seaborn` | `Matplotlib` | `Jupyter Notebook`

## How to Reproduce  
1. `pip install pandas seaborn matplotlib jupyter`  
2. Run the provided Jupyter notebook cells sequentially  
3. Visualizations will generate automatically

## Key Findings  
- **Class Privilege**: Upper-class survival advantage  
- **Gender Priority**: "Women first" policy clearly visible  
- **Fare Impact**: Higher-paying passengers survived more  
- **Age Paradox**: No linear correlation but notable child survival patterns

*Full analysis available in PDF report and Jupyter notebook.*
