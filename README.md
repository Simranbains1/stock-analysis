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

![Resources/Initial Code.png](https://github.com/Simranbains1/stock-analysis/blob/422041ec4f9aac4334538c8a37d2aaa7f01475b5/Resources/Initial%20Code.png)

We can see above that the code specifies the ticker DQ, so our refactoring included running through all of the stocks provided. The following code details how we looped through the data for each of the stock options. 

![Resources/Updated Code.png](https://github.com/Simranbains1/stock-analysis/blob/47ee705c3afb21aa36603c0a73685570e27189c1/Resources/Updated%20Code.png)

### Analysis
Once the code had been refactored, we wanted to check if the execution time improved. Looking below, we can see that the refactored code runs faster for both the 2017 and 2018 analyses. The refactored execution time is listed before the initial execution time. 

![VBA_Challenge_2017.png](https://github.com/Simranbains1/stock-analysis/blob/main/Resources/VBA_Challenge_2017.png)
![VBA_Challenge_2018.png](https://github.com/Simranbains1/stock-analysis/blob/main/Resources/VBA_Challenge_2018.png)

![VBA_Challene_2017_old.png](https://github.com/Simranbains1/stock-analysis/blob/main/Resources/VBA_Challene_2017_old.png)
![VBA_Challene_2018_old.png](https://github.com/Simranbains1/stock-analysis/blob/main/Resources/VBA_Challene_2018_old.png)

## Summary
In the project above, we see that there is a huge benefit to refactoring code. The code is now able to run through thousands of stocks in a short amount of time. However, refactoring is not always a plus. We will look at the advantages and disadvantages of refactoring in relation to the original VBA code below. 

### Disadvantages
If refactoring is not done correctly, it is possible to affect the outcomes that we are looking at. It is imperative that the data is refactored carefully to ensure that the functionality is not changed but streamlined. To ensure that the refactoring process did not affect the results, we have to carefully compare the two and ensure that the two codes are still pulling information the same way. 

### Advantages 
Refactoring is an essential part of coding. It is similar to dealin with household clutter. The original code is the cluttered home, everything is there but it's not clean or easy to follow. Refactoring takes the clutter and organizes everything into a code that is easy to understand, share, maintain, and add upon. Troubleshooting is also easier in a refactored code because we can more find errors more quickly in a structured code. 
