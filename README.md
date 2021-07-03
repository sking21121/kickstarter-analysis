# Kickstarting with Excel

## Overview of Project
Louise wants to know how different campaigns fared in relation to their launch dates and their funding goals. My purpose is to submit a written report based on my analysis and the visualizations I create.
### Purpose
My purpose is to use the Kickstarter dataset and develop pivot tables and charts to help Louise analyse campaign outcomes
based on their launch dates and their funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The table from the Theater Outcomes by Launch Date sheet will provide successful, failed, and canceled plays by the month for all years. The months of May, june  and July have the highest successful launch dates. The successful trend goes down toward the Fall and Winter months. The months of November and December have failed totals that are almost equal to successful totals. And January has the most canceled plays of any month.
### Analysis of Outcomes Based on Goals
From the table Outcomes Based on Goals the highest percentage of successful projects were under $1000 and the next successful percentage was under $1000 to $5000. And the latter group also had the most in total projects. The range from $35000 to $45000 also had a high success rate but only had 9 total projects. The highest percentage of failed projects wer in the $45000 and over $50000 range but this only accouted for 17 total projects. No projects were cancelled.
### Challenges and Difficulties Encountered
To make the Pivot table for Theater Outcomes Based on Launch Date i created a pivot table with Outcomes in columns and Date Created Conversion in Rows. Count of Outcomes as the Values. And for filters i used Parent category and Years. To make the Column labels present like the example I needed to sort column labels in descending order and only click the successful, failed and canceled, not selecting live. I then sorted Parent category by theater. To make chart I selected Stacked Line with Markers from the Recommended Charts. Not much difficulty in this assignment.
For the Outcomes Based on Goals I used CountIFs to fill in the columns for Number Successful, Failed, and Canceled. Example =COUNTIFS(Kickstarter!D:D, ">=5000",Kickstarter!F:F,"successful", Kickstarter!D:D, "<=9999", Kickstarter!R:R,"plays"). Total projects is just the Sum of the three previous columns in same row. To get the Percentage Successful, Failed, and Canceled, I just divide (Number Successful, Failed, Canceled)/Total Projects. Example =B2/E2. Then Format cell to Percentage and 2 decimal places. The only difficulty I had was by first attempt I used E:E(pledged amount) and not goal, and so my numbers were off. I realised i needed to use goal and got numbers correct. 
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
I would request you start the launch dates in May or June based on successful outcomes. I would not start any plays in December or January based on failed or cancelled outcomes.
- What can you conclude about the Outcomes based on Goals?
I would request keeping any new plays in the $10,000 and under range based on success rates. 
- What are some limitations of this dataset?
We know when the plays were successful or failed, but we don't know the type of plays that were successful or failed. So a category of the type of play (comedy, drama, thriller, action) would allow us to know which type was successful or failed. We could be more specific on our recommendations.
- What are some other possible tables and/or graphs that we could create?
A Box Plot could be used to point out any outliers or skewed data. 
