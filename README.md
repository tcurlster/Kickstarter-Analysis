# Kickstarter-Fundraising-Success-Analysis-in-Excel
Analysis of Kickstarter Fundraising Efforts in 2014-2016 using Excel

## Overview of Project
The purpose of this analysis is to understand when is the best time to launch a theater kickstarter projects and what is the most appropriate goal in order to fully fund a play kickstarter.

## Analysis and Challenges
For this analysis, I looked at 2 different scenarios: 1)how theater kickstarters fared in meeting their goal based on what time of year they were launched and 2) how successful play kickstarters were based on the the goal that they set for the kickstarter project. 

For #1, I created a pivot table of all theater kickstarter projects using the month they were created and their outcome (successful, failed, and canceled) to identify which wast the best month (or worst) to launch a theater kickstarter project. For #2, I broke the outcomes of play kickstarter goal amounts into categories ($5,000 iterations) to be able to see which categories of goals had the most (and least) success in being funded. I then created a line charts for each type of outcome to be able to consume the data more easily than looking at the data.

The only issue I encountered while pulling this analysis together was forgetting to include "plays" as a subcategory in my COUNTIFS statement. I couldn't understand why the total number of all kickstarters were so high, but after reviewing my formula I was able to figure out that I was looking at the entire set of kickstarters instead of just "plays". Once I added that aspect into the logic, the numbers made more sense.

##Results
From this analysis, I was able to draw a few conclusions:

- Theater kickstarters are most successful when they are launched within the month of May and tend to fail when they are launched in the month of October.

- Play kickstarters with goals set over $45,000 are most likely to fail.  When goals are set between $35,000 and $45,000 and also under $20,000, play kickstarters tend to have a success rate at 50% and higher.

While this data has helped us draw some conclusions about when to launch a kickstarter and for how much, we do not have insight into what each kickstarter's estimated or actual cost would be to launch the project. The goals of each kickstarter could be over or underestimated and give little meaning to what was actually needed.

Along with the analysis that I created, I could have investigated the percentage of successful theater/play kickstarters by country to see if launching kickstarters in different locations to see if that has an impact on the success rate. I could also have reviewed if having a musical or spaces type of theater kickstarter how more or less success than plays, which could be an alternative option if a play kickstarter did not work out.
