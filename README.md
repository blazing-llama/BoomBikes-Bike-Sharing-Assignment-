# BoomBikes-Bike-Sharing-Assignment-
Built a multiple linear regression model for the prediction of demand for shared bikes.

Bike Sharing Case Study
Problem Statement:
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

Essentially the company wants :

To understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19, by creating a linear model.
To identify the variables affecting their revenues i.e. Which variables are significant in predicting the demand for shared bikes.
To know the accuracy of the model, i.e. How well those variables describe the bike demands
They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

Inferences:

Positive coefficients like temp, season_Summer indicate that an increase in these values will lead to an increase in the value of cnt. On the other hand, all the negative coefficients indicate that an increase in these values will lead to a decrease in the value of cnt. From the R-Squared and adj R-Squared value of both train and test dataset, we could conclude that the above variables can well explain more than 81% of bike demand.
Coefficients of the variables explain the factors affecting the bike demand. Based on the final model, the top three features contributing significantly towards explaining the demand are Temperature (0.438717), weathersit: Light Snow, Light Rain + Mist & Cloudy (-0.291749), and year (0.234455). Hence, it can be concluded that the variables temperature, season/weather situation, and month are significant in predicting the demand for shared bikes.

Final Recommendations for the Company:

The company should consider the months of Jan, Jul, Sep, Nov, Dec as they have higher demand compared to other months.
With an increase in temperature, the demand also increases. Therefore, the company should keep track of the weather conditions.
During the Winter season, the demand rises, and hence the company should be well prepared to meet the high demand.
The holiday season seems to be the least interesting time for biking. Therefore, the company could consider increasing motivation and marketing efforts during these times.
