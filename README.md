# BH-PCMLAI-Capstone-Assignment-20.1
This repository contains code for the required Capstone Assignment 20.1
<br>-Manali Parmar

Link to [the notebook](https://github.com/manali-parmar/BH-PCMLAI-Capstone-Assignment-20.1/blob/main/Capstone%20Assignment%2020.1.ipynb).

This project explores whether Machine Learning algorithms can identify different U.S. economic and financial market regimes using historical stock market and macroeconomic data.

I used Principal Component Analysis (PCA) to reduce the number of variables and K-Means clustering to group months with similar economic conditions. I then compared the identified clusters with major historical economic periods to understand how they relate to inflation, recessions, recoveries, and expansions.

The analysis uses a chronological training and test split to examine how clusters learned from earlier observations describe later economic conditions. The analysis is exploratory and does not evaluate forecasting.

This project used PCA and K-Means clustering to identify four economic and financial market regimes using historical U.S. data. The identified clusters show relationships with economic expansions, inflationary periods, recoveries, and recessions. Overall, the analysis demonstrates how unsupervised machine learning can help identify patterns in economic and financial market conditions. The results also show limitations. For example, most of 2022–23 is assigned to Cluster 1 (Stable Growth / Expansion) rather than Cluster 2 (High Inflation / Monetary Tightening). This suggests that the clusters capture combinations of economic conditions.
