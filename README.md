 Marketing-Campaigns-Performance-Analysis-Python-
We will be analysing the performance of 2 marketing campaigns to evalue the effectiveness of campaigns
Problem Statement 
As a marketing agency, our primary objective is to maximize the return on investment (ROI)for our clients' advertising campaigns
We have conducted two ad campaigns, one on Facebook and the other on AdWords and we need to determine which platform yields better results in terms of clicks, conversions, and overall cost-effectiveness.
By identifying the most effective platform, we can allocate our resources more efficiently and optimize our advertising strategies to deliver better outcomes for our clients.

Resarch Question
Which ad platform is more effective in terms of conversions, clicks, and overall cost-effectiveness?

Data OverView 
Date 
Facebook Ad Campaign 
Facebook Ad Views 
Facebook Ad Clicks 
Facebook Ad Conversions 
Cost per Facebook Ad 
Facebook Click-Through Rate (CTR) 
Facebook Conversion Rate 
Facebook Cost per Click (CPC) 

AdWords Ad Campaign 
AdWords Ad Views 
AdWords Ad Clicks 
AdWords Ad Conversions 
Cost per AdWords Ad 
AdWords Click-Through Rate (CTR) 
AdWords Conversion Rate 
AdWords Cost per Click (CPC) 

The dataset comprises a collection of data comparing the performance of two separate ad campaigns conducted throughout the year 2019.
Specifically, the data covers a Facebook Ad campaign and an AdWords Ad campaign. For each day of the year 2019, 
there is a corresponding row in the dataset, resulting in a total of 365 lines of campaign data to analyze. 
The dataset includes various performance metrics for each ad campaign, providing insights into their effectiveness and efficiency over time.

Methodology 
![image](https://github.com/user-attachments/assets/a6aa4696-7423-4ecd-9a8b-d139a47f3d89)

Comparing Campaigns performance

![image](https://github.com/user-attachments/assets/24c82dc7-99bf-4c35-97f0-260d2d0ef951)
![image](https://github.com/user-attachments/assets/ae74f590-cf63-4771-90e9-6ed0f6a18100)
![image](https://github.com/user-attachments/assets/8a57ab65-7e89-48c7-b010-94c97bcba97f)
All the histogram are showing somewhat symmetrical shape. This symmetrical shape suggests that the number of clicks and conversions is relatively evenly distributed.
In other words, there are not many clicks or conversions that are outliers on either the high or low end.


Daily Ad-Campaign Conversion Frequency 
![image](https://github.com/user-attachments/assets/1e95ca8b-b055-48ad-9f56-26e31f9e5cee)
The data suggests Facebook had more frequent higher conversion days than AdWords, which either had very low conversion rates (less than 6) or moderate ones (6 - 10).
There is a significant variance in the number of high-conversion days between two different campaigns.
The absence of any days with conversions between 10 - 15 and more than 15 in AdWords indicates a need to review what strategies were changed or what external factors could have influenced these numbers.

Relation Between Conversion & Clicks - Facebook
![image](https://github.com/user-attachments/assets/816c2537-48c9-4896-a8c2-1d844a0f55a2)

A correlation coefficient of 0.87 indicates a strong positive linear relationship between clicks on Facebook ads and sales.
This suggests that as the number of clicks on Facebook ads increases, sales tend to increase as well.
This strong correlation suggests that Facebook ads are highly effective in driving sales, as a large portion of the variation in sales can be explained by the variation in clicks on Facebook ads.
The strong correlation between clicks on Facebook ads and sales suggests that Facebook advertising is highly effective in driving sales for the business. 
Increasing investment in Facebook ads or optimizing their performance could potentially lead to even higher sales.

Relation Between Conversion & Clicks - Adwords
![image](https://github.com/user-attachments/assets/32cf7c64-89c3-48b4-be64-478d8f87be7b)

A correlation coefficient of 0.45 indicates a moderate positive linear relationship between clicks on AdWords ads and sales. 
While there is still a positive relationship, it is not as strong as with Facebook ads.
The moderate correlation between clicks on AdWords ads and sales indicates that while AdWords advertising does contribute to sales, its effectiveness may be influenced by other factors.
Further analysis is needed to identify these factors and optimize AdWords campaigns accordingly.

Relation Between Conversion & Clicks
![image](https://github.com/user-attachments/assets/9dc9e6f1-c79f-4dd9-b722-b9938dde6fbe)
![image](https://github.com/user-attachments/assets/0df71b8c-6ff8-4379-abd8-83ce6238970a)

Correlation Analysis Overview
Facebook Ads:
Correlation Coefficient: 0.87
Relationship: Strong positive correlation with sales.
Implication: Higher clicks lead to significantly higher sales.
Recommendation: Increase investment or optimize Facebook ads to boost sales.
AdWords Ads:
Correlation Coefficient: 0.45
Relationship: Moderate positive correlation with sales.
Implication: Positive impact on sales but less strong than Facebook ads.
Recommendation: Analyze and optimize AdWords campaigns for improved results.


Hypothesis Testing
Hypothesis: Advertising on Facebook will result in a greater number of conversions compared to advertising on AdWords.
Null Hypothesis (H0): There is no difference in the number of conversions between Facebook and AdWords, or the number of conversions from AdWords is greater than or equal to those from Facebook.
Alternate Hypothesis (H1): The number of conversions from Facebook is greater than the number of conversions from AdWords.

The mean number of conversions from Facebook ads (11.74) is substantially higher than the mean number of conversions from AdWords ads (5.98). 
This suggests that, on average, Facebook advertising is more effective in generating conversions compared to AdWords advertising.
The T statistic (32.88) is a measure of the difference between the means of the two groups relative to the variation within the groups.
A larger T statistic indicates a greater difference between the means of the two groups.
The p-value (9.35e-134) is extremely small, indicating strong evidence against the null hypothesis.
The results strongly support the alternate hypothesis, indicating that the number of conversions from Facebook advertising is indeed greater than the number of conversions from AdWords advertising.
Facebook advertising appears to be a more effective channel for generating conversions compared to AdWords advertising, based on the sample data analyzed.
Given the significant difference in conversion rates between Facebook and AdWords, consider reallocating resources towards Facebook advertising efforts. 
This could involve increasing ad spend, expanding targeting efforts, or experimenting with different ad formats to capitalize on the platform's effectiveness in driving conversions.


Analyzing Facebook Campaign metrics over time
![image](https://github.com/user-attachments/assets/9f0e92d9-d377-441f-9cff-5dc3ee755f59)

Across the weekdays over a year, the total number of conversions remains relatively consistent, indicating a consistent level of engagement throughout the week. 
However, Mondays and Tuesdays consistently exhibit the highest conversion rates compared to other days, suggesting that the beginning of the workweek sees heightened user engagement or responsiveness to marketing efforts

![image](https://github.com/user-attachments/assets/6f55bb88-f0b7-406d-ae7a-0c50ad6a2c20)
Examining the monthly trend in conversions reveals an overall upward trajectory, indicating a general increase in conversions over time. 
However, certain months stand out with variations in conversion rates. February, April, May, June, August, and November experience a decline in conversions compared to neighboring months.
These periods of decreased conversion rates could be influenced by factors such as seasonal fluctuations, changes in consumer behavior, or adjustments in marketing strategies.

![image](https://github.com/user-attachments/assets/5efec3ee-fdbe-4705-ba95-2f316d1686da)
The CPC trend over the 12-month period shows some fluctuations but overall maintains a relatively stable range.
May and November have the lowest CPC values, indicating potentially more cost-effective advertising or higher conversion rates during these periods.
February has the highest CPC value, suggesting that advertising costs may be relatively higher during this month compared to others.
Lower CPC values in certain months (e.g., May and November) could indicate periods of higher advertising effectiveness or more favorable market conditions.
Consider allocating more advertising budget to months with historically lower CPC values (e.g., May and November) to maximize ROI.


Regression Analysis 
![image](https://github.com/user-attachments/assets/acee6060-9d16-42d1-8d72-85e49d248799)
The model has a reasonably good predictive power, with an R2 score of 76.35%. This suggests that it can effectively predict Facebook ad conversions based on the number of Facebook ad clicks.
With the insights provided by the Linear Regression model, businesses can make informed decisions about resource allocation, budget planning, and campaign optimization.
For instance, knowing the expected number of Facebook ad conversions based on a certain number of Facebook ad clicks can help in setting realistic campaign goals, optimizing ad spend, and assessing the ROI of Facebook advertising efforts.













