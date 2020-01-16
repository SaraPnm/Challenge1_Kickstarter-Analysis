# An Analysis of Kickstarter Campaigns
## Description:
Module 1 exercises and challenge are included in [Challenge 1_data-1-1-3-StarterBook.xlsx](https://github.com/SaraPnm/Challenge1_Kickstarter-Analysis.git/Challenge%201_data-1-1-3-StarterBook.xlsx)
### Challenge 1
The green sheets *"Outcomes Based on Launch Date"* and *"Outcomes Based on Goals"* contain the requested information in Challenge 1. This challenge investigates two (2) parameters that affect Crowdfunding campaign outcomes:
1. **Campaign Goals**
  - Figure 1A represents the campaign outcome percentages based on set goals ($) for subcategory “plays”. The overall trends in Figure 1A suggests that:
    *	There is a big gap between the successful and failed campaign percentages when the set goal is less than $5,000, or more than $45,000. The percentage of successful campaigns in higher when the set goal is less than $5,000. The percentage of successful campaigns in lower when the set goal is more than $45,000.
    * Between $5,000 and $50,000 goal, there is no specific trends between the outcome and goals.
    * There is no canceled campaign for “plays” subcategory.
    * It should be noted that the currency type was not the same for all the analyzed rows.
  
  ![Figure%201A](Challenge1-Figure%201A.png)

- Figure 1B represents the campaign outcome percentages based on set goals ($) when no filter on parent categories or subcategories is applied. The overall trends in Figure 1B suggests that:
  * The percentage of successful campaigns decreases as the goal increases.
  * The percentage of failed and canceled campaigns increases as the goals increases.
  * There is a big gap between the successful and failed campaign percentages when the set goal is less than $5,000, or more than $45,000.
  * It should be noted that the currency type was not the same for all the analyzed rows.
  
  ![Challenge1-Figure%201B](Challenge1-Figure%201B.png)

- The interpretations from Figure 1A and 1B suggest that the campaign set goal can highly affect the final outcomes. It seems more possible to have a successful outcome when the set goals are less.

2. **Campaign Launch Date**
- Figure 2 shows the campaign outcomes in each month for parent category “theater”. 
  * The number of successful campaigns varies among different months. “May” has the highest number of successful campaigns while “December” shows the lowest.
  * The failed and cancelled campaign trends seem steadier among different month compared to successful campaigns.
  * Overall, the number of successful campaigns in each month is higher than each of failed and canceled campaigns.
  
  ![Challenge1-Figure%202](Challenge1-Figure%202.png)
<br/>
<br/>
This dataset is a very good starting point for analysis about future crowdfunding campaigns. However, there are some limitations to it including but not limited to: sample size, lack of information about crowdfunding method and advertisement type, and lack of details on backers of each parent category/subcategory-which could let the analyzer know his/her audience better, and invest on the right people for his/her campaign goals.

<br/>
In my point of view, it may be beneficial to convert all the currencies to a reference currency before the analysis. Also, filtering the data based on country may lead to interesting results as the culture, industry, economy and etc is different for each country. Investigating the gap between the goal and pledged columns could also help the analyzer decide to what extent a campaign failed.
