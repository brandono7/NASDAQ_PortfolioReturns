# NASDAQ_PortfolioReturns
# Problem Statement
Can machine learning empirical asset pricing models that augment the portfolio strategies of NASDAQ-100 stocks outperform the benchmark NASDAQ-100 index (NDX)?

This Capstone Project serves to explore the effectiveness of the various models in predicting risk premiums and analyze the performance of a long-short portfolio based on the predicted risk premiums.

## Guide to my Github Repository 

To run the code, please either clone the repository using Git: 
``` 
git clone https://github.com/brandono7/NASDAQ_PortfolioReturns.git 
```
or download the repository as a zip file and extract it to a location of your choice.

Note that in the GitHub Repo, there is no data uploaded due to the large file sizes. Should you require the datasets, please refer to this Google Drive [link](https://drive.google.com/drive/folders/1fEUDRNV4UvK38lX7cTGfntw64MSoAKPW?usp=share_link) to download the files.

**Prerequisites**

Before running the project, make sure to install the following python libraries on your virtual environment via terminal / command prompt:
```
pip install -r requirements.txt
```

**Repository Structure**

1. **`src` folder**: Contains the essential Jupyter Notebooks used for data cleaning, analysis, model building - Ordinary Least Squares (OLS), Random Forest, LightGBM and Neural Networks as well as the Diebold-Mariano Test and portfolio performances. This folder also contains the $R^2$ results for each model, the actual and predicted risk_premiums for the Diebold-Mariano test for each model, and portfolio performances for each model in CSV files. 
2. **`data` folder (not uploaded to remote Github Repo)**: Contains the datasets that were used for this project. The datasets that were used were **cleaned_df_with_tickers.csv** for the stock level data, **DGS3MO.csv** for the risk free rate and **nasdaq_100_benchmark.csv**. The remaining datasets are the raw datasets. 

This project is an individual assignment for a NUS course - DSE4101: Capstone Project in Data Science and Economics I.

Author: Brandon

Special Thanks to Prof Liu Chunchun for her guidance. 

Last Updated: 11 Apr 2025