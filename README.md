#### Table of Contents

1. [Installation](#Installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#Instructions)
5. [Licensing, Authors, and Acknowledgements](#licensing)

# Installation<a name="Installation"></a>
libraries needed by this project are provided by the Anaconda distribution of Python. Packages include numpy, pandas, matplotlib, seaborn, ast,sklearn and scipy The code should run with no issues using Python versions 3.*. 

# Project Motivation<a name="motivation"></a>
This project identify segments of the population that form the core customer base for a mail-order sales company in Germany. These segments can then be used to direct marketing campaigns towards audiences that will have the highest expected rate of returns. The data has been provided by Bertelsmann Arvato Analytics.

# File Descriptions<a name="files"></a>
1. Data folder contain data needed in this project
- Udacity_AZDIAS_Subset.csv: Demographics data for the general population of Germany; 891211 persons (rows) x 85 features (columns).
- Udacity_CUSTOMERS_Subset.csv: Demographics data for customers of a mail-order company; 191652 persons (rows) x 85 features (columns).
- Data_Dictionary.md: Detailed information file about the features in the provided datasets.
- AZDIAS_Feature_Summary.csv: Summary of feature attributes for demographics data; 85 features (rows) x 4 columns
2. Identify_Customer_Segments notebook record detail of the project.
3. img folder contain result screenshots.

# Result<a name="results"></a>
customer are clusted into 9 clusters and by comparing distribution cluster 4 are most over represented by target company.
![Screenshot 1](https://github.com/haataa/Identify_Customer_Segments/blob/master/img/WX20190623-215423%402x.png)

# Licensing, Authors, Acknowledgements<a name="licensing"></a>
This project was completed as part of the Udacity Data Scientist Nanodegree. 
