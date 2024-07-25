# House-Sales-in-King-County-USA
 Data Analyst working at a Real Estate Investment Trust. The Trust would like to start investing in Residential real estate.

Insights Gained:
1.	Data Overview and Preparation:
o	The dataset comprised of 21,613 house sales records with features such as number of bedrooms, bathrooms, living area square footage, and more.
o	Missing values were minimal and handled appropriately, while categorical features like 'waterfront' and 'view' were encoded for analysis.
2.	Exploratory Data Analysis:
o	Higher square footage and better grades of houses correlated strongly with higher prices.
o	Houses with waterfront views tended to have significantly higher prices, with noticeable outliers.
3.	Feature Engineering and Selection:
o	A second-order polynomial transformation was applied to capture non-linear relationships, significantly improving model performance.
o	Features like 'sqft_living', 'grade', and 'lat' were identified as the most influential in predicting house prices.
4.	Modeling and Evaluation:
o	Ridge Regression was used with a regularization parameter of 0.1 to prevent overfitting.
o	The model's R² score on the test data was 0.83, indicating that the model explains 83% of the variability in house prices.
5.	Key Insights:
o	Square footage and house grade are critical factors in determining house prices.
o	Polynomial features captured complex relationships, enhancing the model's predictive power.
o	Waterfront properties, while rare, significantly boost house prices.
6.	Limitations and Future Work:
o	The analysis was limited by the available features; additional factors like proximity to amenities and crime rates could provide more insights.
o	Future work could involve more advanced models, such as gradient boosting or deep learning, to capture even more complex patterns.
