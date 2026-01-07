# Final Report of Capstone Project on Analyzing Bike Sharing Demand

Presentation Link: https://github.com/vasavi0417/Veerla_Data606/blob/main/docs/Bike%20Share%20Insights%20690%20CapStone%20Project.pptx

Youtube Link: https://youtu.be/B5-Oq2zgQ5E

### Introduction:

**Bike Share**: The system that allows individuals to rent bikes for short trips on a pay-per-use basis.

Factors Influencing Bike Share Demand:

**Urbanization**: The demand for bike share is higher in densely populated areas with shorter distances between destinations.

**Weather Conditions**: Seasonal variations affect the demand for bike share, with better weather leading to increased usage.

**Infrastructure**: Availability of bike lanes, bike parking facilities, and safe cycling routes positively impact demand.

**Time**: Bike share experiences spikes in demand during work starting and closing hours.

**Public Awareness**: Effective marketing and public awareness campaigns can boost usage.


### Issue of Interest:
The issue of interest for this project is analyzing bike sharing demand in the context of ride-hailing apps such as Uber and Ola. Bike-sharing systems have become increasingly popular in urban areas as a sustainable mode of transportation, and this trend aligns with the goals of ride-hailing companies to provide convenient and eco-friendly travel options to their users.

### Importance:
Analyzing bike-sharing demand is important for several reasons. Firstly, it can aid urban planners and policymakers in designing efficient transportation networks. Secondly, bike-sharing companies can use this analysis to optimize fleet management, station placement, and pricing strategies. Lastly, studying bike-sharing demand patterns can provide insights into commuting habits, environmental impact, and public health.




### Data Sources:
To analyze bike sharing demand, I am using data from the Kaggle data source and the size of the data is nearly 1Gb and 17380 rows with 12 features.



[This is a link to Train data](https://github.com/harshitssj4/Kaggle-Bike-Sharing-Demand/blob/master/train.csv)

[This is a link to Test data](https://github.com/harshitssj4/Kaggle-Bike-Sharing-Demand/blob/master/test.csv)


### Data Analysis of Bike share Demand:

The boxplot with meaningful information is the Hour of the day because it shows the busiest hours are 7AM-8AM and 5 PM-6 PM, which means the users mainly rent bikes to ride to work/school and to return back home at the end of the day. Based on boxplots 4 and 5 (Working Day and Holiday), we see most outliers are in working days. The result makes sense when looking at holidays since all outliers are for non-holiday days. The last boxplot demonstrates the obvious common sense that most users rent bikes when the weather is Clear and Cloudy (1 and 2), and almost no users when is heavy raining or snowing (3).



![image](https://github.com/vasavi0417/Veerla_Data606/assets/42056699/de6940d8-bca3-42a4-b9fc-566dc836a2e5)






Bike sharing demand vary across different times of the day, days of the week, and seasons

![image](https://github.com/vasavi0417/Veerla_Data606/assets/42056699/3230bb12-0755-4007-9e2b-2c1e7bc5f7f3)




## Techniques/Models:
1.I have used Correlation matrix for feature selection.

2.Removed the outliers from the selected features and target variable.

3.The variables/measures that were used in the analysis datetime,season,holiday,workingday,weather,temp,atemp,humidity,windspeed,casual,registered,count.

4.Trained the model with different ML algorithms like Linear Regression model, Random Forest Regressor model, Gradient Boosting Regressor model and Extreme Gradient Boost Regressor method.

5 Extreme Gradient Boost model(XG Boost) has the least RMSE which is 0.08 (Root Mean Squared Logarithmic Error) we have chosen that one for our prediction and the accuracy for that is 97.1 %

## Conclusion:

1.As we embrace the transformative power of Machine Learning for demand prediction, businesses can unlock new possibilities for operational efficiency and customer satisfaction.

2.As cities strive to create cleaner, healthier, and more accessible environments, bike-share systems offer a remarkable solution.


