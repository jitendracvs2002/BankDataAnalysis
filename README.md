# BankDataAnalysis
A visual data analysis of Bank Marketing Data taken from the UCI ML repository: https://archive.ics.uci.edu/ml/citation_policy.html

DATA ANALYSIS USING VISUALIZATION IN BANKING
The data used for this project is Bank Marketing Data Set from the UCI ML repository: https://archive.ics.uci.edu/ml/citation_policy.html

During the work, the task of a preliminary analysis of a positive response (term deposit) to direct calls from the bank is solved. In essence, the task is the matter of bank scoring, i.e. according to the characteristics of clients (potential clients), their behavior is predicted (loan default, a wish to open a deposit, etc.).

The aim of this project is to find the following :

What are the most useful Python libraries for visual analysis?
How to build interactive plots?
How to visualize single features?
How to do a visual analysis for the feature interaction?
How to provide a comprehensive visual analysis for numerical and categorical features?
Libraries used :

Matplotlib
Seaborn
Plotly

CONCLUSIONS AND INTERPRETATIONS
There are neither any data missing, nor explicit outliers that should be cut. But we can omit housing, loan and day_of_week features in the next steps.

The euribor3m and nr.employed features strongly correlate with emp.var.rate.

Employment Variation Rate is a quarterly indicator, euribor3m - euribor 3 month rate is a day indicator, and nr.employed - number of employees is a quarterly indicator.

The correlation of the employment change with the number of employed issues itself is obvious, but its correlation with EURIBOR (Euro Interbank Offered Rate, the European interbank offer rate) is interesting.

This indicator is based on the average interbank interest rates in Eurozone. It also has a positive effect since the higher the interest rate is, the more willingly customers will spend their money on financial tools.

Therefore, if banks want to improve their lead generation, what they should do is to improve the quality of phone conversations and run their campaigns when interest rates are high and the macroeconomic environment is stable.
