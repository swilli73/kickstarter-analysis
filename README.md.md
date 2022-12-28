# Kickstarting with Excel

## Overview of Project

### The purpose of this analysis was to use the skills I have learned in Microsoft Excel to find the relationship between Kickstarter campaign success and month of launch for theatre productions, as well as the relationship between Kickstarter campaign success and initial goal set for the theatre subcategory of "plays".

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date 

![Theater Outcomes by Launch Date](https://i.gyazo.com/3cc5f41aa1ebf2c2f45a010570bfb709.png)

#### This analysis was performed by first creating a PivotTable that filtered the amount of successful, failed, and cancelled theatre Kickstarters by month so the correlation could be viewed, and then creating a chart from that data so it can be easily read.

### Analysis of Outcomes Based on Goals 

![Outcomes Based on Goals](https://i.gyazo.com/68d6ccb42549dec0e3944bab1967bbef.png)

#### This analysis was performed by first creating a table that consisted of goal ranges, as well as the number of successful, failed, and cancelled "plays" campaigns for each of those ranges. A COUNTIFS formula was used to filter and count the "Kickstarter" data by necessary criteria, such as the number of failed campaigns for play productions which had goals set between $25,000 and $29,000. This was then converted into a chart that showed the correlation between a Kickstarter's goal and its success rate.

### Challenges and Difficulties Encountered

#### This analysis was a great challenge in general. I got to create a PivotTable manually instead of using the module lesson instructions on what categories to put in "rows", "columns", etc., as well as convert one into a chart as well. I was unfamiliar with the COUNTIFS formula and even with the hint video provided, it was a challenge to figure out how to apply that to the data I had to work with. When exporting the chart for "Outcomes Based on Goals", I even initially had a chart that looked completely different than the example and had to go back and correct my formulas.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

May seems to be the month that holds the most success for launching a Kickstarter, as well as December seeming to be the weakest. On a broader scale, around May-August seem to be the best months to launch a kickstarter, while the months preceding and following seem to be weaker times to do so.

- What can you conclude about the Outcomes based on Goals?

A clear conclusion is that it is not reliable to relate Kickstarter goals with their success. The data jumps back and forth too much to be able to look at the chart and see a clear goal range that should be set to expect a successful campaign.

- What are some limitations of this dataset?

Some limitations of this data set is that outliers are not addressed, there are a few that deviate from the goal ranges set. The dataset only shows numbers and dates, while not being able to address why certain Kickstarters receive the success that they do, as well as what types of plays (genres) accrue more interest.

- What are some other possible tables and/or graphs that we could create?

One that shows the success of campaigns based on whether or not they are staff picks, as well as the length of the Kickstarters.

