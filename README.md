# Stock Portfolio Optimization

## Table of Contents
1. [Introduction/Overview](#introductionoverview)
2. [Objective](#objective)
3. [Methodology/Approach](#methodologyapproach)
4. [Installation/Requirements](#installationrequirements)
5. [File Descriptions](#file-descriptions)
6. [Data Collection and Sources](#data-collection-and-sources)
7. [Usage/How to Run](#usagehow-to-run)
8. [Results/Conclusions](#resultsconclusions)
9. [Contributors/Team](#contributorsteam)
10. [License](#license)

## Introduction/Overview
This project focuses on optimizing a stock portfolio to closely track the NASDAQ-100 index using Integer Programming. The approach involves selecting stocks and optimizing their weights with Gurobi to minimize tracking error.

## Objective
To create a stock portfolio that mimics the NASDAQ-100 index, balancing tracking accuracy and portfolio simplicity.

## Methodology/Approach
- **Stock Selection and Weight Optimization**: Picking stocks and calculating optimal weights.
- **Mixed Integer Program**: An alternative method without pre-selecting stocks.
- **Data Preprocessing**: Using 2019 and 2020 datasets.
- **Performance Evaluation**: Assessing portfolio performance with different stock counts.
- **Recommendations & Comparisons**: Evaluating various portfolio construction methods.

## Installation/Requirements
- [Python](https://www.python.org/downloads/)
- [Jupyter Notebook](https://jupyter.org/install)
- [Gurobi Optimizer](https://www.gurobi.com/downloads/) - Requires Gurobi license

## File Descriptions
- **`Stock-Portfolio-Optimization.ipynb`**: This Jupyter Notebook contains Python code for improving and analyzing stock portfolios.
- **`Stock-Portfolio-Optimization.pdf`**: A comprehensive report explaining the methodologies, analytical processes, and valuable insights pertaining to stock portfolio optimization.

## Data Collection and Sources

**Datasets Overview:**  
This project uses two CSV files located in the Data folder. These files contain stock data from the NASDAQ-100 for the years 2019 and 2020. The datasets are:

- `stocks2019.csv`
- `stocks2020.csv`

**File Structure:**  
- The first column lists the date.
- The second column shows the index price (NDX).
- Columns 3-102 represent the prices of individual stocks.

## Usage/How to Run
Utilize the `Stock-Portfolio-Optimization.ipynb` to assess and optimize your stock portfolio. Ensure your data adheres to the structure mentioned above, or make slight modifications to suit your dataset's structure. Simply substitute your data and execute the code. If your data's structure diverges significantly from the original, additional code adjustments may be necessary.

## Results/Conclusions
The project showcases effective index fund construction techniques, highlighting the balance between tracking accuracy and portfolio complexity. Optimal results were obtained with a balanced stock number, considering both in-sample and out-of-sample performance and practical portfolio management aspects.

## Contributors/Team
- Manideep Telukuntla
- Krittika Deshwal
- Milind Bhatia
- Chih-En Ko

## License
Licensed under [MIT License](https://github.com/ManideepTelukuntla/InvestigateTMDBMovieData/blob/master/LICENSE)
