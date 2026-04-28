## Forecasting Sales of Rossman Drugstores
### Unit: ADS1002 (Semester 2, 2024)

Objective:
- Historical sales data of 1,115 Rossmann stores was used to build a machine learning model, to forecast the sales up to four weeks in advance.
- Additionally, learn the predicting variables that are the most influential on Sales.

Main outcomes:
- Analysis of the top 20% stores in terms of sales, showed that `Promotion` and `Customers` had the greatest positive impact on sales,
- Time series analysis showed sales increasing during the weeks leading up to Christmas,
- A StackingRegressor (base models RandomForestRegressor, GradientBoostingRegressor, XGBRegressor) achieved testing R^2 score of 0.84 in predicting the subsequent four weeks of sales*. 

*Please view the Final Report (`ADS1002_FinalReport_Rossmann.pdf`) for the complete report, including the plots of predicted sales.
