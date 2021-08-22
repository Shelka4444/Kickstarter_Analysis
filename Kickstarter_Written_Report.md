# Kickstarting with Excel

## Overview of Project
This project is dedicated to uncovering hidden trends in kickstarter campaigns using data analysis tools in Excel.
### Purpose
The purpose of this project is to gain insights into the best time of year and kickstarter campaign strategies in order to successfully launch a campaign to fund a project of the client's choosing, ie. "plays" in this case.
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Upon examination of the data for "theater" for all the years available (2009-2017), it is apparent that most successful campaigns are launched in June. The data for failed campaigns hovers between 31% and 38% across the year aside from October and December which have 43% and 47% rates of failed campaigns, respectively. Canceled theater campaigns range from <1% up to 7%, with the highest number occurring in January.

![[Outcomes by Launch Date]](/Users/rachelkrasner/Desktop/UCB_Data_Analysis/Challenge 1 Kickstarter/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
The data for outcomes based on goals for "plays" is more nuanced than in the previous section. There is a higher rate of success rate for campaigns with a goal of less than $5,000 and also from $35,000 to $45,000, with overall success rates from 67% to 76%, respectively. However, the number of successful campaigns is far higher for the less than $5,000 category (529 plays) vs $35,000 to $45,000 (6 plays). The failure rate is a reflection of the success rate as evidenced in the graph presented below. Aside from goals in the range of $35,000 to $45,000, the overall trend of failed projects increases with the increasing goal amount. There were no canceled plays according to this data set.

![[Outcomes based on Goals]](/Users/rachelkrasner/Desktop/UCB_Data_Analysis/Challenge 1 Kickstarter/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
There were no challenges with this particular dataset. The data presented was clean and easy to manipulate. However, for future reference, it is important to keep track of which filters are "on" in order to be sure that the data set being referenced is indeed the compilation being analyzed; else results will possilby be skewed and/or completely inaccurate. Likewise, double check which cells are being referenced in formulas, especially if one formula is copied across an entire column or row, to prevent future errors.
## Results

- In conclusion, based off of the trends uncovered in Outcomes based on Launch Date, it would be recommended to start a campaign in June for a higher rate of success. It is not recommended to launch campaigns during the months of October and December which have the highest rates of failed projects in the year.

- From analyzing data based on set goals, the highest percentage of successful campaigns had goals of less than $5,000. The next highest category of percent of successful campaigns were in the range of $35,000 to $45,000, but there were fewer overall individual campaigns in this goal category to draw data from.

- There are several limitations to this dataset. For one, by examining campaigns for a multidude of countries instead of focusing on one country at a time, there are possibly many confounding variables which determine whether a campaign is successful or not. For example, it is possible that kickstarter campaigns are more popular in general in places like the US where it is culturally acceptable to ask for money to fund projects, whereas in other locations this is not a common practice. Additionally, some countries have better funding for performing arts through their respective governments and thus, kickstarter campaigns are even less common there. It would therefore be helpful to examine the data more closely based on the country where the campaign will be held. Additionally, it is unclear based on the current dataset how trends have ultimately changed (or not) through time. There was not enough data available for each year listed to understand the changes occurring year to year. Furthermore, it is possible that within the "plays" subcategory, there are nuances regarding which campaigns are more successful. Other defining variables, such as the type of play (comedy, tragedy, drama, abstract, traditional, modern, etc), could also determine which projects appeal to more backers and thereby more likely to be properly funded.
- One type of table and graph which could be insightful is examing data for oucomes,  average donation, and number of backers, as well as country. Several questions can be posed by pulling from these categories, such as: How does the outcome depend on the number of backers and average donation? Is it possible that certain plays are funded by fewer donors with higher individual donations? What encourages backers to donate more or less? Are there higher donations and/or number of backers in certain countries than others? Understanding these relationships will assist with building a stronger kickstarter campaign strategy which can be revised and further implemented with each successive campaign. 
