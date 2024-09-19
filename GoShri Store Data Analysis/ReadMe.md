# GoShri Sales analysis 
# GoShri 
GoShri is a premium clothing store offering a diverse range of men’s and women’s apparel, catering to various age groups. With a nationwide presence across India and products featured on major e-commerce platforms, GoShri delivers the latest fashion trends and high-quality garments right to customers' doorsteps.
# Introduction
The primary goal of this analysis is to examine Vrinda’s sales data for the year 2022, extracting key insights about the customer base and identifying opportunities to drive revenue growth in the coming year.
# Business objective
This analysis aims to answer the following key questions:
+ How does revenue contribution vary across different genders and age groups?
+ What insights can be drawn from the sales trendline?
+ Which sales channel contributes the most to overall revenue?
+ Which product categories are more popular by gender?
+ What is the sales distribution by month throughout the year?
+ What is the sales forecast for 2023 based on historical data?
+ How can sales strategies be optimized to target high-potential regions?
# Data Cleaning
The following steps were done clean the dataset.
+ The Gender column had inconsistent values like "Men","Women","M","W". So everything was formatted to standard values "Men","Women".
+ A new column was added based on age called Age category which differentiates people into "Young","Adults","Senior".
+ The quantity column has inconsistent values like 1,2,one,two. they were formatted to standard values as 1 & 2.
+ The Currency and Amount columns were merged together and formatted as currencies.
+ The ship-city and ship-state had inconsitent names so converted them using =LOWER() function to lower case for better consitency.
  
