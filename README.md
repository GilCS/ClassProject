#About this Project#

in this project we analyzed restaurant data (file zomato.csv) in India, that contains information about restaurants, mainly their locations, menus, guests, cost of a meal for two, and rating.
our business question was pricing  - we classified restaurant variables in order to predict the cost of a dinner date.  This prediction should be helpful to identify restaurants that are over or under priced for restaurant owners and customers.

1.   **step 1:** cleaning the data - the dataset was text based, and contained several fields (like "url") that had no data gain. all fields were changed to numeric or categorical. the most important fields - cost and rate we normalized for better accuracy.
2. **step 2:** data visualization - we added visualizations to better understand data spread and correlation.
3.  **step 3:** using classification and prediction algorithms - we used 4 different algorithms, each with its own advantages, in order to get the best result.
random forest is a based on trees classification, that combines the classification made by multiple trees.
support vector machine is the most suitable algorithm that classifies data points in a multidimensional space.
the XGBoost algorithm is a high accuracy predictive model that has a high prediction accuracy rate.
4. **step 4:** assessing the outcomes, deciding which model to use for best results.
