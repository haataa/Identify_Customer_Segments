#### Table of Contents

1. [Project Motivation](#motivation)
2. [Installation](#Installation)
3. [File Descriptions](#files)
4. [Results](#Instructions)
5. [Licensing, Authors, and Acknowledgements](#licensing)

# Project Motivation<a name="motivation"></a>
This project identify segments of the population that form the core customer base for a mail-order sales company in Germany. These segments can then be used to direct marketing campaigns towards audiences that will have the highest expected rate of returns. The data has been provided by Bertelsmann Arvato Analytics.

# Installation<a name="Installation"></a>
libraries needed by this project are provided by the Anaconda distribution of Python. Packages include numpy, pandas, matplotlib, seaborn, ast,sklearn and scipy The code should run with no issues using Python versions 3.*. 

# File Descriptions<a name="files"></a>
1. Data folder contain data needed in this project
- Udacity_AZDIAS_Subset.csv: Demographics data for the general population of Germany; 891211 persons (rows) x 85 features (columns).
- Udacity_CUSTOMERS_Subset.csv: Demographics data for customers of a mail-order company; 191652 persons (rows) x 85 features (columns).
- Data_Dictionary.md: Detailed information file about the features in the provided datasets.
- AZDIAS_Feature_Summary.csv: Summary of feature attributes for demographics data; 85 features (rows) x 4 columns
2. Identify_Customer_Segments notebook record detail of the project.
3. img folder contain result screenshots.

# Result<a name="results"></a>
Blog post of the project can be found in [medium](https://medium.com/@haataa/how-can-we-identify-customer-segments-using-cluster-method-94a58ddba772?postPublishedType=repub)

Customer are clusted into 10 clusters according to cluster numbers - SSE plot. ![Screenshot 4](https://github.com/haataa/Identify_Customer_Segments/blob/master/img/20190701160146.png)

Cluster distribution is very different between the general population and company customers. ![Screenshot 1](https://github.com/haataa/Identify_Customer_Segments/blob/master/img/20190701154329.png)

 To see the difference of each cluster I draw another graph. ![Screenshot 2](https://github.com/haataa/Identify_Customer_Segments/blob/master/img/20190701154357.png)
 
 
To have a visual of our cluster, I plot cluster distribution with two important features: GREEN_AVANTGARDE and FINANZ_MINIMALIST. ![Screenshot 3](https://github.com/haataa/Identify_Customer_Segments/blob/master/img/20190701154414.png)

# Licensing, Authors, Acknowledgements<a name="licensing"></a>
This project was completed as part of the Udacity Data Scientist Nanodegree. 
