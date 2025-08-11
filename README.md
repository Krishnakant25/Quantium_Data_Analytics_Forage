Forage Quantium Data Analytics Virtual Experience Program
Project Overview
This project is a detailed data analysis of chip purchases at supermarkets. The primary goal was to analyze customer purchasing behaviors and evaluate the performance of stores undergoing a new layout trial. The insights gained from this analysis will help the client understand customer preferences and determine the success of the store layout trial.

Dependencies:

Language: Python 3.8

Packages: pandas, matplotlib, mlxtend, datetime, sklearn, scipy

Task 1: Data Preparation and Customer Analytics
Objective
To prepare and clean the provided transaction and customer data, and then analyze customer purchasing behaviors based on different demographic segments.

Key Activities
Data Cleaning:

Converted the date column from integer to datetime format.

Removed non-chip products (salsas) and identified and handled outliers in the data.

Customer Segmentation Analysis:

Analyzed total sales and purchase frequencies across different customer segments, including LIFESTAGE and MEMBER_TYPE.

Conducted a deep dive into the Mainstream Young Singles/Couples segment to understand their specific preferences for chip brands and packet sizes.

Insights
Top Contributing Segments: The three highest-contributing segments to total sales are: 1. Budget Older Families, 2. Mainstream Young Singles/Couples, and 3. Mainstream Retirees.

Purchase Behavior:

Budget Older Families purchased the largest average number of chip packets per customer.

Mainstream Young Singles/Couples have the largest population among all segments.

Chip Preferences:

Across most segments, Kettles chips and 175g packets are the most frequently purchased.

The Mainstream Young Singles/Couples segment showed distinct preferences, being 28% more likely to purchase Tyrrells chips and 32% more likely to buy 270g packets (Twisties chips) compared to other segments.

Task 2: Experimentation and Uplift Testing
Objective
To evaluate the success of the new store layout trial in three stores (77, 86, and 88) during the trial period of February to April 2019.

Key Activities
Control Store Selection:

Used total sales and the number of customers as key metrics to find suitable control stores.

Generated a combined score for each potential control store by calculating Pearson correlations and magnitude distances to the trial stores. The store with the highest score was selected as the control.

Hypothesis Testing:

Conducted hypothesis testing to determine if the performance differences between the trial and control stores were statistically significant. The 95% control threshold was used to assess significance.

Insights
Trial and Control Store Pairs:

Store 77 was paired with Control Store 233.

Store 86 was paired with Control Store 155.

Store 88 was paired with Control Store 40.

Trial Performance:

Store 77: Saw a statistically significant increase in total sales during March and April. The number of customers also showed a significant increase in at least two months.

Store 86: Experienced a statistically significant increase in total sales during March and also saw a significant increase in the number of customers in at least two months.

Store 88: The trial did not result in a significant change in performance for this store.

Task 3: Analytics and Commercial Application
Objective
To synthesize the findings from Tasks 1 and 2 and create a commercial report for the client, highlighting key insights and a final recommendation.

Key Activities
Report Creation: Developed a professional PowerPoint presentation based on the Pyramid Principle to clearly communicate the project's key findings.

Final Recommendation: Provided a data-driven recommendation on the success of the store trial, supported by the analytical evidence from the previous tasks.
