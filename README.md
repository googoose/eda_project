# EDA Project  - AIPM course

Welcome to the EDA project of week 5 in the AIPM course.

## Short description of the problem
1.	Through EDA/statistical analysis I will present at least 3 insights regarding the overall data, one of them  geographical.
2. I will present at least 3 recommendations for my client Erin Robinson. She invests in poor neighborhoods, does buying & selling, wants mainly to have her costs back and make a little profit. She is a socially responsible woman. 
3. Recommendations will include
* where to best invest for making a profit (geographically) (even if small).
* emerging areas - still quite cheap but with growing prices
* what time of the year is best to buy and sell, directed at her area of interest (poor neighborhoods)
* looking at price per sqft values to identify if the areas are really cheap. 
4. Assumptions and information from Erin to better specify her search : 
* "poor" areas means that it is within the 10% cheapest houses in the county
5. Hypothesis
* The lowest-priced houses (bottom 10%) in the entire region are concentrated in a few of all the ZIP codes, indicating highly localized investment zones.
* The Price-per-SqFt growth rate year-over-year in the target neighborhoods will exceed the city average Price-per-SqFt growth rate over the next years based on the available history.
* Within poor areas, the houses are generally smaller, thus also contributing to a lower mean price
* Summer time is a good time to buy since most people think about vacation. January seems to be good to sell, since people had time over Christmas to investigate the market.
* The average House SqFt in target neighborhoods is significantly smaller than the city average, suggesting the low price is partially driven by unit size, not just location risk.


## Description of the contents of the repository 
* <b>EDA.jpynb</b> contains the Jupyter Notebook with the code I've written for this project and comments explaining it. 
* <b>1_Fetching_the_data_eda.ipynb</b> contains the Jupyter Notebook with the code to get the house data from the SQL data base 

* README.md this file that describes the contents of the repository. This file is the source of information for navigating through the repository.

* <b>202510_EDA_Project_insights.pptx</b> (and EDA_Project_insights.ppt) is a short presentation giving a high-level overview of my methodology and recommendations for my client Erin. 

* cleanup.py - a Python script for processing and cleaning my data, using functions and docstrings. 

