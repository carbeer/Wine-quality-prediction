# Wine quality prediction
The goal of this work is to **predict the quality of red wine** by using parameters such as the pH value, or the density of the wine. This shall make it possible to **presort the wines** so that not every substandard wine must be tasted by expensive expert sommeliers.

### Implementation
We used RapidMiner with the Weka extension for our implementation. The following methods have been tested:
1. Linear Regression: NAE = 0.746 +/- 0.038
2. Regression Tree: NAE = 0.745 +/- 0.041
3. Neural Net: NAE = 0.862 +/- 0.149
4. **Model Tree: NAE = 0.743 +/- 0.035**

### Data source
We used the following data set: P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis.
Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009. It can be accessed here: https://archive.ics.uci.edu/ml/datasets/Wine+Quality

