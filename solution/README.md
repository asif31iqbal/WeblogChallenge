# Summary of my approach

The details of the solution with embedded notes are given in the [solution.ipynb](https://github.com/asif31iqbal/WeblogChallenge/blob/master/solution/solution.ipynb) notebook.

Here is a brief summary:

## Part 1

1. For sessionizing, I used an idle time based approach. Whenever idle time is over and a new request comes in, that is considered a new session. I used a simple heuristic that I came up with to determine how long the idle time should be, described in detail in the notebook.

2. The computations for questions 2, 3 and 4 are based on the sessionization.

## Part 2

1. For predicting next minutes load, I tried several approaches - Weighted Moving Average, Exponential Moving Average, Linear Regression and LSTM. LSTM seems to give the best results, I compared the MAE and R2 scores.
2. I made my best interpretation and did it accordingly. Would be happy to discuss.
3. Same goes here.
