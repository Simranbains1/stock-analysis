# stock-analysis

## Overview of Project
This project aims to analyze the entire stock market so our client Steve can provide a report for his parents. We started with an analysis of a dozen stocks in 2017 and 2018 that was created through VBA. We then refactored the data to run through the entirety of the 2017 and 2018 stocks provided. We also checked if the refactored code ran faster than the previous code. 

## Results
### Data
At the beginning of the project, we are presented with the stock information for twelve stocks, including information on ticker value, stock issue date, opening/closing/adjusted closing price, highest/lowest price, and volume of the stock. We used VBA coding to pull information on the total daily volume and return of each stock.

The data below shows the total daily volume for 2017 and 2018. We can easily see which stocks are doing well and which stocks shouldn't be invested in. 

![VBA_Challenge_2017_data_.png](https://github.com/Simranbains1/stock-analysis/blob/main/Resources/VBA_Challenge_2017_data_.png)

![VBA_Challenge_2018_data.png](https://github.com/Simranbains1/stock-analysis/blob/main/Resources/VBA_Challenge_2018_data.png)

Initially, we ran through the information for the stock DQ. The code below shows how the sheets were looped through to pull the relvant information.

[Resources/Initial Code.png](https://github.com/Simranbains1/stock-analysis/blob/422041ec4f9aac4334538c8a37d2aaa7f01475b5/Resources/Initial%20Code.png)

We can see above that the code specifies the ticker DQ, so our refactoring included running through all of the stocks provided. The following code details how we looped through the data for each of the stock options. 

[Resources/Updated Code.png](https://github.com/Simranbains1/stock-analysis/blob/47ee705c3afb21aa36603c0a73685570e27189c1/Resources/Updated%20Code.png)

### Analysis
Once the code had been refactored, we wanted to check if the execution time improved. Looking below, we can see that the refactored code runs faster for both the 2017 and 2018 analyses. 

![VBA_Challenge_2017.png](https://github.com/Simranbains1/stock-analysis/blob/main/Resources/VBA_Challenge_2017.png)
![VBA_Challenge_2018.png](https://github.com/Simranbains1/stock-analysis/blob/main/Resources/VBA_Challenge_2018.png)


### Analysis


Using images and examples of your code, compare the stock performance between 2017 and 2018, as well as the execution times of the original script and the refactored script.



## Summary
In a summary statement, address the following questions.
What are the advantages or disadvantages of refactoring code?
How do these pros and cons apply to refactoring the original VBA script? (There is a detailed statement on the advantages and disadvantages of the original and refactored VBA script)


