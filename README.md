EDA for Feature Selection in Dynamic Ride-Sharing Pricing Model

In this project, I conducted an Exploratory Data Analysis (EDA) to perform feature selection to understand the factors influencing the historical cost of ride-sharing services. The dataset included 1,000 records with various attributes influencing ride costs, such as the number of riders and drivers, location category, customer loyalty status, past rides, average ratings, time of booking, vehicle type, expected ride duration, and the historical cost of the ride. The aim was to identify the most relevant features that significantly impact ride costs, aiding in the development of more accurate predictive models in the future.

Process:

1. Data Familiarization: We began by understanding the dataset, identifying each feature, its type (numerical or categorical), and the target variable, "Historical_Cost_of_Ride."

2. Data Quality Check: We checked for missing values and verified the correctness of data types. The dataset did not contain any missing values, and the data types were appropriate for each feature.

3. Univariate Analysis:

* Analyzed the distribution of numerical features using histograms and descriptive statistics.
* Evaluated categorical features using count plots.

4. Bivariate Analysis:

* Explored the relationship between numerical features and the target variable using scatter plots.
* Assessed the impact of categorical features on ride costs using box plots.

Key Insights:

1. Numerical Features:

* Expected_Ride_Duration showed a clear relationship with ride cost, indicating longer rides generally cost more.
* Other numerical features (Number_of_Riders, Number_of_Drivers, Number_of_Past_Rides, Average_Ratings) did not exhibit strong linear relationships with the ride cost but might still contribute valuable information in non-linear combinations or interactions.

2. Categorical Features:

* Location_Category demonstrated significant cost variance, with urban areas typically having higher ride costs.
* Customer_Loyalty_Status influenced ride costs, potentially through loyalty discounts or premium pricing for higher status.
* Time_of_Booking affected ride costs, reflecting varying demand throughout the day.
* Vehicle_Type had a substantial impact on ride costs, with premium vehicles costing more than economy options.

Conclusion:

The EDA process identified key features influencing ride costs, providing valuable insights for feature selection in predictive modeling. Expected_Ride_Duration, Location_Category, Customer_Loyalty_Status, Time_of_Booking, and Vehicle_Type emerged as the most critical features. Other numerical features, while not showing strong linear relationships, may still offer predictive power through advanced modeling techniques.

This comprehensive EDA underscores the importance of thorough data exploration and feature selection in building accurate and robust predictive models, ultimately aiding in dynamic pricing strategies for ride-sharing services.
