# ML-Data-Cleaning-and-Feature-Selection
Assignment-1

Abstract

The market sales data analysis revolves around customer-specific details encompassing demographics such as age, income, and shopping behavior, including factors like spending amounts and website visits. The central objective is to determine whether a customer will respond positively to a marketing campaign. This analytical journey begins with comprehensive data exploration techniques, including correlation heatmaps, boxplots, and Q-Q plots, which unveil relationships, outliers, and data distribution patterns. Subsequently, a logistic regression model is meticulously constructed for predicting customer responses. However, it becomes evident that not all columns hold significant importance in predicting the dependent variable.

To address data gaps caused by missing values, a variety of imputation methods are rigorously evaluated. These methods include mean imputation, which replaces missing values with the feature's mean, median imputation that uses the median of observed data, and regression imputation, where missing values are predicted based on related features and data patterns.

This comprehensive approach ensures that the model is equipped to handle real-world data complexities, and the selection of the most effective imputation strategy is paramount to maintaining data integrity. Ultimately, this process empowers businesses to make informed marketing decisions, leveraging insights from customer data analysis to optimize campaign strategies and maximize positive responses.

## About Dataset - Marketing Campaign

**Context**

A response model can provide a significant boost to the efficiency of a marketing campaign by increasing responses or reducing expenses. The objective is to predict who will respond to an offer for a product or service

**Content**

1. AcceptedCmp1 - 1 if customer accepted the offer in the 1st campaign, 0 otherwise
2. AcceptedCmp2 - 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
3. AcceptedCmp3 - 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
4. AcceptedCmp4 - 1 if customer accepted the offer in the 4th campaign, 0 otherwise
5. AcceptedCmp5 - 1 if customer accepted the offer in the 5th campaign, 0 otherwise
6. Response (target) - 1 if customer accepted the offer in the last campaign, 0 otherwise
7. Complain - 1 if customer complained in the last 2 years
8. DtCustomer - date of customer’s enrolment with the company
9. Education - customer’s level of education
10. Marital - customer’s marital status
11. Kidhome - number of small children in customer’s household
12. Teenhome - number of teenagers in customer’s household
13. Income - customer’s yearly household income
14. MntFishProducts - amount spent on fish products in the last 2 years
15. MntMeatProducts - amount spent on meat products in the last 2 years
16. MntFruits - amount spent on fruits products in the last 2 years
17. MntSweetProducts - amount spent on sweet products in the last 2 years
18. MntWines - amount spent on wine products in the last 2 years
19. MntGoldProds - amount spent on gold products in the last 2 years
20. NumDealsPurchases - number of purchases made with discount
21. NumCatalogPurchases - number of purchases made using catalogue
22. NumStorePurchases - number of purchases made directly in stores
23. NumWebPurchases - number of purchases made through company’s web site
24. NumWebVisitsMonth - number of visits to company’s web site in the last month
25. Recency - number of days since the last purchase

This dataset is rich with information relevant to customer behavior and responses to marketing campaigns. It appears suitable for building predictive models to understand which factors influence customer responses to different campaigns and, ultimately, to optimize future marketing strategies. The target variable "Response" can be used to train and evaluate predictive models, while the other variables offer valuable features for analysis and modeling. Data preprocessing and statistical analysis can provide insights into customer behavior patterns and campaign effectiveness.
