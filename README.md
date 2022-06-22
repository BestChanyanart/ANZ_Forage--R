# ANZ_forage

ANZ Virtual Internship is an Internship program on a website Forage, please check out here (https://www.theforage.com/virtual-internships/prototype/ZLJCsrpkHo9pZBJNY/ANZ-Virtual-Internship). 
There are 5 tasks in the ANZ data program (2 Mandatory Tasks and 3 Optional Tasks). 

## Provided dataset 

A synthesised transaction dataset containing 3 months’ worth of transactions for 100 hypothetical customers. It contains purchases, recurring transactions, and salary transactions.
    
## 1. Exploratory Data Analysis 

Task requires 
- Load the transaction dataset into an analysis tool of your choice (Excel, R, SAS, Tableau, or similar)
    
- Start by doing some basic checks – are there any data issues? Does the data need to be cleaned?
    
- Gather some interesting overall insights about the data. For example -- what is the average transaction amount? How many transactions do customers make each month, on average?
    
- Segment the dataset by transaction date and time. Visualise transaction volume and spending over the course of an average day or week. Consider the effect of any outliers that may distort your analysis.

**Result:  https://htmlpreview.github.io/?https://github.com/BestChanyanart/ANZ_forage/blob/main/ANZ_Module_1_Exploratory-Data-Analysis.html**

## 2. Predictive Analysis 

Task requires 
      
- Explore correlations between annual salary and various customer attributes (e.g. age). These attributes could be those that are readily available in the data (e.g. age) or those that you construct or derive yourself (e.g. those relating to purchasing behaviour). Visualise any interesting correlations using a scatter plot.
      
- Build a simple regression model to predict the annual salary for each customer using the attributes you identified above

- How accurate is your model? Should ANZ use it to segment customers (for whom it does not have this data) into income brackets for reporting purposes?
      
- For a challenge: build a decision-tree based model to predict salary. Does it perform better? How would you accurately test the performance of this model?
      
**Result:  https://htmlpreview.github.io/?https://github.com/BestChanyanart/ANZ_forage/blob/main/ANZ_Module_2_Predictive-Analytics.html**

## 3. Exploring Big Data with PySpark (Optional Task) 

Task requires 

- To perform the following transformation steps using the synthetic transaction file by using PySpark DataFrame. Output the results to a local file.
Project only the records where 

    > Status=authorized AND card_present_flag=0
    > Split the long_lat and merchant_long_lat fields into long, lat and merch_long, merch_lat fields
    > Output the data as a CSV file

**Result: https://colab.research.google.com/github/BestChanyanart/ANZ_Forage--R/blob/main/ANZ_Module_3_Exploring_Big_Data_with_PySpark_.ipynb**
