# Stock Portfolio Optimization

<div align="center">
  <img src="https://github.com/ManideepTelukuntla/Stock-Portfolio-Optimization/blob/main/Images/Stock-Portfolio-Optimization.svg" width="800" height="600" alt="Stock Portfolio Optimization">
  <br>
  <p>Image by <a href="https://www.freepik.com/free-vector/gradient-stock-market-concept_19931742.htm#query=stock%20portfolio%20illustration&position=21&from_view=search&track=ais&uuid=116d69f3-c705-4bb1-a54d-4b4268f4bd90">Freepik</a></p>
</div>


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

## 1. Introduction/Overview
This project focuses on optimizing a stock portfolio to closely track the NASDAQ-100 index using Integer Programming. The approach involves selecting stocks and optimizing their weights with Gurobi to minimize tracking error.

## 2. Objective
To create a stock portfolio that mimics the NASDAQ-100 index, balancing tracking accuracy and portfolio simplicity.

## 3. Methodology/Approach
- **Stock Selection and Weight Optimization**: Picking stocks and calculating optimal weights.
- **Mixed Integer Program**: An alternative method without pre-selecting stocks.
- **Data Preprocessing**: Using 2019 and 2020 datasets.
- **Performance Evaluation**: Assessing portfolio performance with different stock counts.
- **Recommendations & Comparisons**: Evaluating various portfolio construction methods.

## 4. Installation/Requirements
- [Python](https://www.python.org/downloads/)
- [Jupyter Notebook](https://jupyter.org/install)
- [Gurobi Optimizer](https://www.gurobi.com/downloads/) - Requires Gurobi license

## 5. File Descriptions
- **`Stock-Portfolio-Optimization.ipynb`**: This Jupyter Notebook contains Python code for improving and analyzing stock portfolios.
- **`Stock-Portfolio-Optimization.pdf`**: A comprehensive report explaining the methodologies, analytical processes, and valuable insights pertaining to stock portfolio optimization.
- **`Data`**: Folder with datasets used in this project.
- **`Images`**: Folder with images pertaining to this project.

## 6. Data Collection and Sources

**Datasets Overview:**  
This project uses two CSV files located in the Data folder. These files contain stock data from the NASDAQ-100 for the years 2019 and 2020. The datasets are:

- `stocks2019.csv`
- `stocks2020.csv`

**File Structure:**  
- The first column lists the date.
- The second column shows the index price (NDX).
- Columns 3-102 represent the prices of individual stocks.

## 7. Usage/How to Run
Utilize the `Stock-Portfolio-Optimization.ipynb` to assess and optimize your stock portfolio. Ensure your data adheres to the structure mentioned above, or make slight modifications to suit your dataset's structure. Simply substitute your data and execute the code. If your data's structure diverges significantly from the original, additional code adjustments may be necessary.

## 8. Results/Conclusions
The project showcases effective index fund construction techniques, highlighting the balance between tracking accuracy and portfolio complexity. Optimal results were obtained with a balanced stock number, considering both in-sample and out-of-sample performance and practical portfolio management aspects.

## 9. Contributors/Team
- Manideep Telukuntla
- Krittika Deshwal
- Milind Bhatia
- Chih-En Ko

## 10. License
Licensed under [MIT License](https://github.com/ManideepTelukuntla/InvestigateTMDBMovieData/blob/master/LICENSE)
