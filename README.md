# Wirless Broadband Market Size Calculation
## Methodology
Used the following datasets:<br />
1. Mobile broadband subscriptions per 100 people by country<br />
2. Price of broadband subscription by country<br />
3. Average speed of internet by country<br />
4. Total population by country<br />
To calculate the total revenue generated by broadband, multiplied the total number of users by the price of each subscription<br />
To caclulate the median pricing per MBps, I divided the price of broadband by the average speed of internet for each country and found the median price/MBps. 

## Regression
To differentiate between groups of countries and their associated MBps pricing, created a regression model with HDI (Human Development Index). Decided to omit other variables for now. Log shifted the MBps pricing and took out obvious outliers (states in the middle of civil war, states with beyond $1000 MBps cost)
