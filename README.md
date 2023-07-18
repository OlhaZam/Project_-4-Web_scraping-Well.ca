# Project #4 

### Web scraping of sales and offers from Well.ca (an online health and beauty store).

The dataset was created using web mining techniques, which involved scraping the Well.ca website to gather information about the products in 
the sale category. The dataset includes the product name, original price, and new price for each item.

The goal of this analysis is to gain insights into the pricing strategies and promotional offers of Well.ca. 
By examining the prevalence of different discount ranges, we can understand which discount ranges are most frequently proposed by the store. 
This information can be valuable for both the store and customers in making informed purchasing decisions and understanding market 
trends in the health and beauty industry.

<img width="1152" alt="Project_Preview" src="https://github.com/OlhaZam/Project_-4-Web_scraping-Well.ca/assets/137802329/bb6cf763-a117-45ad-a29a-8daf549726e4">


#### Data analysis workflow:


##### Data Collection
Gathering the relevant data from Wel.ca website by HTML research analysis and identifying specific promotional section of the wesite.
Finding and collecting all sales categories and all products in these categories.

  
##### Data Cleaning 
In our case some of the products are placed in the sales section but they don't actually has a discount. In these cases we still want to analyse this items and to pursue consistensy and accuracy I took the available price for this item and collected it as previous and as new price at the same time.


##### Data Exploration 
Exploring and examining the dataset to understand its structure, variables, and patterns. 


##### Data Transformation 
Performing necessary transformations on the data, such as feature engineering, normalization, or scaling, to prepare it for analysis. This step aims to enhance the data quality and facilitate further analysis.


##### Data Analysis 
Applying various analytical techniques and calculations to derive insights for data visualizations. 
Calculate the discount percentage for the every item and sorting them from the highest discount to the lowest.


##### Interpretation and Visualization
Interpreting the analysis results and presenting them in a meaningful way using visualizations by histogram chart and donut plot. This step helps to effectively communicate the findings and make data-driven decisions.

##### Conclusion
Summarizing the analysis findings, drawing conclusions, and providing gained insights. 
