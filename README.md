# An anylysis of Kickstarter Campaigns
Performing  analysis on Kickstarter data to discover trends. 
## Overview of Analysis 
This week we learned the basic fundamentals of analyzing large data sets in Excel using conditional formatting, filters, functions, and pivot charts. After a refreshing review of Excels basic processes I set out to help Louise conquer her analysis-driven campaign. Louise wanted to know how the campaigns compared in relation to the outcomes of their fundraisisng goals and the conclusion of the campaigns. In order to assist Louise I had to make some modifications to the worksheet. 

### Analysis of Outcomes Based on Launch Dates
Our first step was creating a pivot chart to chunk the data we were looking for into a more readable format. Since we were looking for the outcomes of Theatrical campaigns I filtered the "Parent Category" to match "Theater" as well as filtering for the "Year" which consequentely produced the months of the year on the chart. Since we are comparing the outcomes of the campaigns, the date created and count of whether the outcomes were successful, failed, or canceled must be included. 
[Insert Outcomes]

The additon of this pivot chart makes our data easier to digest than the kickstarter  however it is not the full picture. In order to solidify the results of our analysis we needed to add another element. Graphical visualizations allow us to see trends without having to fumble through the numerical values. 
[Insert Line-graph]

Here our results are clear. The successful plays dominated in the early summer months with a natural digression through the fall. What I found interesting was the spike in failed campaigns and absence of canceled campaigns From September to November. After further review the spike makes sense. If the success rates are going down we can assume that the failure rates will go up. Also, there were no canceled shows in October. Apparently regardless of Friday the 13th the show must go on. 

### Analysis of Outcomes Based on Goals
In order to solidify our analysis we had to explore one more detail. The rate or "percentage" at which these outcomes performed. Creating a new table I added the range amounts of the goals and used the COUNTIFS() function to extract the data that met tmy criteria. Using the SUM() function allowd for the generation of the total number projects per outcome. All that was left was to calculate the percentages by dividing the goal from the total number of projects and multiplying the remainder by 100. Creating yet another pivot chart __________ Based on the information recieved from the pivot chart we can conclude that the most successful campaigns were under $5000. 

[Insert Table]

The last and final step is to produce another graph to make our data easier to digest and presentable. 

[Insert Line graph]

##Challenges
Throughout this module I had to overcome several obstacles. One of them was 
##Limitations
