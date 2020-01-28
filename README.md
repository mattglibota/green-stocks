# Module 2 Challenge - Green Stocks

The VBA code for the challenge is located in the **AllStocksAnalysis** subroutine. It contains the updated array functionality to reduce the looping through the entire data set more than once. The subroutine named was updated on 1/27/2020 because of Grader feedback.

The key is to increase the *tickerIndex* when the *endingPrice* is stored. This indicates the ticker is about to change.

After gathering the metrics, looping through the array of tickers to pull output parameters is much more efficient than looping through the whole dataset 12 times.

### Challenge
