# Kickstarting with Excel

## Overview of Project
Client's play came close to its Kickstarter fundraising goal in a short amount of time and wants
an analysis of similar Kickstarter campaigns in relation to their launch dates and funding goals.
Using Excel, I gathered available data to share insights into similar projects for the client.

## Analysis and Challenges
Analysis was done using Excel. Two tables and charts were created for this specific project.

### ![Theater Outcomes vs Launch](https://github.com/HexHaunter/Kickstarter-Analysis/blob/main/Resources/Theater%20Outcomes%20Vs%20Launch.png?raw=true)



![Outcomes Vs. Goals](https://github.com/HexHaunter/Kickstarter-Analysis/blob/main/Resources/Outcomes%20Vs%20Goals.png?raw=true)


### Analysis of Outcomes Based on Launch Date
To gather the correct information I had to create a new column to get the year of the launch date,
then I created a pivot table to display the launch month, against the amount of successful, failed, 
and cancelled theater projects. I made it into an easy to read line chart.

### Analysis of Outcomes Based on Goals
To create a better understanding of how a project's goal related to thier success, I created a new sheet
and table in excel that checked different goal amounts against the number and percentage of successful,
failed, and canceled projects. This was then made into a line chart for easy visualization.

### Challenges and Difficulties Encountered
The only challenges that I personally had was familiarizing myself with Excel as I haven't used it in
over a decade. Luckily, Excel is rather intuitive to use, and I caught on quickly.

## Results
Based on the analysis of Outcomes Based on Launch Date; from May to July is the best time to launch a 
campagin, with it getting riskier in the following months. The worst month to launch is December, 
with a pretty even split between sucessful and failed/canceled campaigns.

As for the analysis of Outcomes based on Goals; it would seem that campaigns with goals of $5,000 and under,
are much more successful than ones with higher goals. 

All this being said, the dataset is still limited. For instance, although May seems to be the best time
to launch a campaign, we also don't know how long campaigns last for. Another chart showing how long campaigns
last vs how successful they are, might give us more insight. There's also limitations by outliers which aren't
accounted for in the Outcomes Vs Goals chart. There's a significant spike in success from the $35,000 to
$44,999 range, but these are only a total of 9 plays, with 6 of them being successful. You could single out these
9 and see what's different about them, perhaps they had much higher average donations, or the campaign lasted
a while, but whatever the reason, they don't fit the rest of the trend that continues for the next two goal
categories.
