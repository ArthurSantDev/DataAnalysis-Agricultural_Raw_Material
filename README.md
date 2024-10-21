![Thumb](https://github.com/user-attachments/assets/b3c5eb11-f4b5-40c3-b3ae-614234eee2a3)

# Data Analysis - Agricultural Raw Material
This Python project performs the analysis and visualization of agricultural raw material price data using a dataset from Kaggle.

## Stack utilizada
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%2311557C.svg?style=for-the-badge&logo=Matplotlib&logoColor=white) ![Seaborn](https://img.shields.io/badge/seaborn-%234C7EAB.svg?style=for-the-badge&logo=seaborn&logoColor=white) [Kaggle](https://img.shields.io/badge/Kaggle-%2320BEFF.svg?style=for-the-badge&logo=Kaggle&logoColor=white) 

## Features
1 - **Data Loading and Cleaning:** The dataset is loaded from a CSV file. Percent values, commas, and other symbols are removed to ensure data consistency. Missing values (NaN) are handled by removing the rows with incomplete data.

2 - **Type Conversion:** The columns related to prices and percentage changes are converted to the float type to allow for precise numerical analysis.

3 - **Date Indexing:** The dates are formatted to the yyyy-mm-dd standard and set as the index, facilitating analysis over time.

4 - **Correlation Analysis:** Correlation matrices are generated to analyze the relationship between different raw material prices, with visualization through heatmaps.

5 - **Visualizations:** The project includes various graphs to explore the data:
- **Heatmap** of raw material price correlations.
- **Percentage Change Graphs** of prices over time.
- **Histograms** of the distribution of percentage changes.
- **Evolutionary Graphs** of prices over time.

6 - **Libraries Used:**
- **NumPy** for array manipulation and data handling..
- **Pandas** for dataframe manipulation.
- **Seaborn** and **Matplotlib** for graphical visualization.

## Installation
```bash
    pip install numpy
    pip install pandas
    pip install seaborn
    pip install matplotlib
    or
    pip install numpy pandas seaborn matplotlib
```

## Screenshots
![DA - Agricultural Raw Material](https://github.com/user-attachments/assets/34754124-ef0d-41db-965a-0b539a3e04b4)
