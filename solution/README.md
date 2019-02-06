# Summary of my approach

The details of the solution with embedded notes are given in the **solution.ipynb** notebook.

Here is a brief summary:

## Part 1

1. For sessionizing, I used an idle time based approach. Whenever idle time is over and a new request comes in, that is considered a new session.

2. The subsequent computations are based on the sessionization,

## Part 2

1. For predicting next minutes load, I tried several approaches - Weighted Moving Average, Exponential Moving Average, Linear Regression and LSTM. LSTM seems to give the best results.
2. I made my best interpretation and did it accordingly.
3. Same goes here.
