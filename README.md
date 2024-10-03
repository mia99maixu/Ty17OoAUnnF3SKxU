# Happy Customer

### Background:

We are one of the fastest growing startups in the logistics and delivery domain. We work with several partners and make on-demand delivery to our customers. During the COVID-19 pandemic, we are facing several different challenges and everyday we are trying to address these challenges. We thrive on making our customers happy. As a growing startup, with a global expansion strategy we know that we need to make our customers happy and the only way to do that is to measure how happy each customer is. If we can predict what makes our customers happy or unhappy, we can then take necessary actions.

### Data Description:

- Y = target attribute (Y) with values indicating 0 (unhappy) and 1 (happy) customers
- X1 = order was delivered on time
- X2 = contents of my order was as I expected
- X3 = I ordered everything I wanted to order
- X4 = I paid a good price for my order
- X5 = I am satisfied with my courier
- X6 = the app makes ordering easy for me

### Methodology:

1. Exploratory Data Analysis(EDA). Analysis of the features by visualizing the features in catplots, and finding any relations or trends considering multiple features.
2.  Running Basic Algorithms, Logistic Regression model, and evaluation. Where the accuracy did not satisfy the standard matrix. Important Features Extraction. Plot the feature's importance.
3. Feature Engineering and Data Cleaning, removing lower-importance features.
4. Run alternative algorithms, and train the models eg. CatBoost, XGBoost, LightGBM, and Decision Tree. Cross Validation.
5. Evaluate the model again and achieve the goal.
   
### Conclusion:

This is a binary prediction by feature selection project. After discarding the two features X2 and X4, the model had improved the accuracy but not that much. The accuracy between 0.62-0.65 indicates moderate overall performance. A precision between 0.54-0.57 suggests that the model has a relatively high rate of false positives, meaning that nearly half of the positive predictions are incorrect. A recall between 0.64-0.73 indicates that the model is better at identifying actual positives, with a lower rate of false negatives. The F1-score between 0.58-0.64 indicates a balance between precision and recall, but it is somewhat closer to recall, given the higher recall value. According to a comparable smaller dataset, when trained the model may encounter the under-sampling issue, which can result in lower accuracy. To avoid this limitation, can try either over the sample size or collect more data points.
