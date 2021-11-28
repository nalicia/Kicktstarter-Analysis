# An anylysis of Kickstarter Campaigns
Performing  analysis on Kickstarter data to discover trends. 
## Overview of Analysis 
This week we learned the basic fundamentals of analyzing large data sets in Excel using conditional formatting, filters, functions, and pivot charts. After a refreshing review of Excels basic processes I set out to help Louise conquer her analysis-driven campaign. Louise wanted to know how the campaigns compared in relation to the outcomes of their fundraisisng goals and the conclusion of the campaigns. In order to assist Louise I had to make some modifications to the worksheet. 

### Analysis of Outcomes Based on Launch Dates
Our first step was creating a pivot chart to chunk the data we were looking for into a more readable format. Since we were looking for the outcomes of theatrical campaigns, I filtered the "Parent Category" to match "Theater" as well as filtering for the "Year" which consequently produced the months of the year on the chart. Because we are comparing the outcomes of the campaigns, the launch date and count of whether the outcomes were successful, failed, or canceled must be included. 
[Pivot_Table_of_Theater _Outcomes .zip](https://github.com/nalicia/Kicktstarter-Analysis/files/7614618/Pivot_Table_of_Theater._Outcomes.zip)
The addition of this pivot chart makes our data easier to digest than the kickstarter, however, it is not the full picture. In order to solidify the results of our analysis we needed to add another element; A graph. Graphical visualizations allow us to see trends without having to fumble through the numerical values. 
[Theater_Outcomes_vs_Launch.png.zip](https://github.com/nalicia/Kicktstarter-Analysis/files/7613997/Theater_Outcomes_vs_Launch.png.zip)

Here our results are clear. The successful plays dominated in the early summer months with a natural digression through the fall. What I found interesting was the spike in failed campaigns and absence of canceled campaigns from September to November. After further review the spike makes sense. If the success rates are going down, we can assume that the failure rates will go up. Also, there were no canceled shows in October. Apparently regardless of Friday the 13th the show must go on. 

### Analysis of Outcomes Based on Goals
In order to make our analysis concise we had to explore one more detail. The rate or "percentage" at which these outcomes performed. Creating a new table I added the range amounts of the goals and used the 'COUNTIFS()' function to extract the data that met my criteria. Using the 'SUM()' function allowed for the generation of the total number of projects per outcome. All that was left was to calculate the percentages by dividing the goal from the total number of projects. Then multiplying the remainder by 100. Satisfied with the table, I created a pivot chart.
[Table_of_Outcomes_Based_On_Goals.jpeg.zip](https://github.com/nalicia/Kicktstarter-Analysis/files/7614621/Table_of_Outcomes_Based_On_Goals.jpeg.zip)
[Pivot_Table_Of_Goals.peg.zip](https://github.com/nalicia/Kicktstarter-Analysis/files/7614619/Pivot_Table_Of_Goals.peg.zip)

Based on the information recieved from the pivot chart we can conclude that the most successful campaigns were under $5000. 

The last and final step is to produce another graph to make our data presentable. 
[Outcomes_vs_Goals.png.zip](https://github.com/nalicia/Kicktstarter-Analysis/files/7614609/Outcomes_vs_Goals.png.zip)

## limitations
Looking at the outcomes based on lunch dates, I didn't filter the year however it appeared to only give me one year (It returned January through December). I would think that there would be more data for the other years,instead of compiling them together. If I wanted a deeper analysis I would definitely go through the multiple years to see if the trends are the same. I would complete the in-depth analysis for the launch dates as well as the goals.

## Challenges
During this analysis there were a few problems that I ran into. For starters when I tried converting my short date into just the year using the 'YEAR()' function all of my cells returned 2014 as the value. I tried looking through the kick starter to see if I had added a value, or if I had accidentally deleted a value. Unfortunatly I couldn't find the source. After trying the function over and over again yeilding the same result I decided to make the harrowing decision of completely starting over from module one. Luckily that seemed to do the trick and I was able to return the correct year.  After that I ran into my second problem, when using the 'COUNTIFS()' function I wasn't meeting all of my criteria. I was missing either the tail end or the beginning or even punctuation. This is where I learned that there are so many resources to help you when you get stuck. I use Microsoft specifically but there are countless websites and videos that you can use. And I was grateful to get back on track. Besides these two obstacles I had a great time completing this analysis. I then ran into my thirs and final challenge.  While using git hub Safari crashed before I could commit my changes. Causing me to start from square one. If I've learned anything from these mistakes it is to take your time and save your work.
