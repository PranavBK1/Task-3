I worked on predicting house prices using a dataset with features like area, bedrooms, bathrooms, stories, etc.

First, I handled categorical data and checked feature correlations. Area, bathrooms, and stories showed the strongest relation to price.

I built simple linear regression models for each of these, but their accuracy wasn’t great.

Then, I created a multiple linear regression model using all features — it performed much better.

To improve results further, I removed outliers using the IQR method and retrained the model. This helped reduce error and improved accuracy.

Lastly, I visualized regression lines and error comparisons. Multiple regression with cleaned data gave the best results.

Takeaway: More features + clean data = better predictions.
