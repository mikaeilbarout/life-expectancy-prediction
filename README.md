Life Expectancy Prediction
Linear Regression Project

A machine learning project that predicts life expectancy across
156 countries using health, economic, and social indicators.

-----

## PROJECT OVERVIEW

Life expectancy is one of the most important indicators of a
country’s overall well-being. This project explores the key
factors that influence how long people live, using data from
the World Health Organization (WHO) spanning 2000 to 2015.

-----

## REPOSITORY STRUCTURE

life-expectancy-prediction/
|
|– data/
|   └– Life_Expectancy_Data.csv
|
|– notebook/
|   └– Life_Expectancy.ipynb
|
|– images/
|
|– README.md
|– requirements.txt
└– .gitignore

-----

## DATASET INFO

Source      : World Health Organization (WHO)
Rows        : 2,461
Columns     : 23
Countries   : 156
Time Period : 2000 to 2015

Key Features:

- Life_expectancy                 –> Target variable (years)
- Adult_Mortality                 –> Mortality rate per 1000
- infant_deaths                   –> Infant deaths per 1000
- Alcohol                         –> Litres per capita
- GDP                             –> GDP per capita (USD)
- Schooling                       –> Avg years of schooling
- BMI                             –> Average BMI
- HIV/AIDS                        –> Deaths per 1000 births
- Income_composition_of_resources –> Human Dev. Index (0-1)
- Status                          –> Developed / Developing
- Continent                       –> Geographic continent

-----

## PROJECT WORKFLOW

1. Data Loading & Exploration
- Loaded dataset with Pandas
- Explored data types, shape, basic statistics
- Visualized country distribution by continent
1. Exploratory Data Analysis (EDA)
- Scatter plots: Life Expectancy vs Schooling
- Correlation heatmap across all features
- Missing value analysis
1. Data Preprocessing
- Replaced Unknown values with NaN
- Filled missing values using mean imputation
- One-Hot Encoding for Status and Continent
1. Modeling
- Train/Test Split: 70% / 30%
- Model: LinearRegression (scikit-learn)
- Evaluated with Actual vs Predicted scatter plot
- Residual distribution plot

-----

## TECH STACK

- Python 3.8+
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Jupyter Notebook

-----

## HOW TO RUN

1. Clone the repository:
   git clone https://github.com/mikaeilbarout/life-expectancy-prediction.git
   cd life-expectancy-prediction
1. Install dependencies:
   pip install -r requirements.txt
1. Launch Jupyter Notebook:
   jupyter notebook notebook/Life_Expectancy.ipynb

-----

## AUTHOR

Your Name
GitHub   : https://github.com/mikaeilbarout
LinkedIn : https://www.linkedin.com/in/mikaeil-baroutchi/
