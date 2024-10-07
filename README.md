# Exploring Movie Budgets vs Box Office Revenue (100 Days of Python)

This repository contains a Jupyter notebook analyzing the relationship between film production budgets and box office revenue. The data used in this analysis was scraped from [the-numbers.com](https://www.the-numbers.com/movie/budgets) on May 1st, 2018. This notebook is part of Angela Yu's **100 Days of Python** course.

## Contents

### Notebook Sections
1. **Introduction**: Overview of the project's goal - to analyze the correlation between movie production budgets and their box office performance.
2. **Data Exploration and Cleaning**: Cleaning the scraped data, handling NaN values, removing duplicate rows, and converting column data types for further analysis.
3. **Descriptive Statistics**: Calculation of metrics like average budget, worldwide gross revenue, and determining how many movies were profitable.
4. **Data Visualization with Seaborn**: Use bubble charts and regression plots to explore trends visually, including plotting movie releases over time and budget-to-revenue correlations.
5. **Linear Regression Analysis**: Predict the relationship between movie budget and box office revenue using scikit-learn.

## Requirements
- **Pandas**: For data manipulation and analysis.
- **Matplotlib** and **Seaborn**: For data visualization.
- **Scikit-learn**: To build a linear regression model.

You can install the required libraries with:
```sh
pip install pandas matplotlib seaborn scikit-learn
```

## Usage

1. Clone this repository:
```sh
git clone <repository_url>
```

2. Open the notebook in Jupyter:
```sh
jupyter notebook movie_budget_analysis.ipynb
```

3. Explore the notebook to understand the data analysis process, and run the cells to visualize relationships between production budgets and revenue.
   
## Data Source

- The data used for this analysis was sourced from the-numbers.com, providing movie budget and box office revenue details.

## Acknowledgments
- Angela Yu: The inspiration for this notebook came from 100 Days of Python, which is an engaging and educational course for those looking to advance their Python programming skills.
- The-Numbers.com: For providing the dataset used in this analysis.

## License
This project is licensed under the MIT License.
