# Election Analysis

## Overview of Project

The purpose of this project was to refactor and build code in VBA to run analysis on stock information from 2017 and 2018. This information could then be used to influence decisions on which stocks to invest in. Code was built throughout the assessment for this dataset and then refactored to see if it could become more efficient.   

## Results

### Stock Results
This analysis showed that 2017 was a much better performing year for the provided stocks, with eleven of the twelve stocks showing positive returns. The following year showed a much different outcome, with only two of the twelve stocks with a positive return. TERPs was the only stock with a negative return for both years the analysis was done. 

![2017 stock performance](https://user-images.githubusercontent.com/104689576/169200061-124be86f-ec21-4679-8b4c-84419ff609cb.png)
![2018 stock performance](https://user-images.githubusercontent.com/104689576/169200040-c5b93b76-8782-446c-ba67-b89b4d7998ca.png)


### Script Differences
The original script was performed using a nested loop to run through the ticker array, and for each ticker calculating the volume, starting prices, and ending prices before moving on to the next ticker to perform the same analysis. The refactored code had a similar structure, but instead of using a nested loop, it made arrays of the volumes, starting prices, and ending prices, and used an index of the tickers to run through the data. 
By changing the structure of the code and the way the data was reviewed, the refactored code was able to decrease the time it took to perform the analysis. 

Original Times and Script:
![Original_2017](https://user-images.githubusercontent.com/104689576/169200121-58fd69a7-0cf7-4c28-b0b1-a1e2c2c55fcb.png)
![Original_2018](https://user-images.githubusercontent.com/104689576/169200135-efec4f9c-2960-4de4-9df4-13ec1da37f0b.png)
![Original_Code](https://user-images.githubusercontent.com/104689576/169200205-8779babc-0b95-43b0-bea8-1a574226927b.png)


Refactored Times:
![VBA_Challenge_2017](https://user-images.githubusercontent.com/104689576/169200223-5c1a4a2e-dd8a-44a6-b1f7-4d803fd7d49e.png)
![VBA_Challege_2018](https://user-images.githubusercontent.com/104689576/169200233-75f26df6-f103-4aeb-8774-b4efa4850d5c.png)
![Refactored Code](https://user-images.githubusercontent.com/104689576/169200244-c9fc97e2-2663-4e58-9b45-063902d3747b.png)

## Summary

In conclusion, refactoring code can drastically cut down the amount of calculation and loops done through a dataset, subsequently reducing the amount of time and energy needed to retrieve the intended results. This can allow for more data to be analyzed and improve efficiency of operations, particularly with large, complex data sets. However, refactoring code can take a large amount of time and energy as well, so the benefits must be weighed with the cost. It can be disadvantageous to spend the time to refactor code to improve efficiency if it does not drastically improve the results, such as in cases where the dataset might not be that large. For this dataset, it might not have been worth the time spent to refactor the code and improve the time it took to run from nine tenths of a second to one and a half tenths of second. 

