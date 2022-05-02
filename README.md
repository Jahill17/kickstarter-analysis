# Kickstarting with Excel

## Performing analysis on Kickstarter data to uncover trends

### Purpose
The purpose of this analysis is to provide a recommendation to Louise based on a large set of kickstarter data.  The analysis will provide Louise the correlations among campaigns success in relation to their launch dates, capaign type, and their funding goals. Ultimately Louise will have a better understanding of what type of kickstarter campaigns are best to pursue along with the ideal campaign funding goal.

## Analysis and Challenges
Multiple steps were taken as part of this analysis.  This required making multiple pivot tables and pivotcharts to tell the appropriate story.  

### Analysis of Outcomes Based on Launch Date
One of the first actions performed as part of this challenge was creating a pivot table and graph in Excel to visualize campaign outcomes as either successful, failed, or canceled based on launch date.
The following image is a line with markers chart that shows theater outcomes based on launch month.  A limitation of this chart is that a reader does not get a holistic view of all important data such as how high or low given fundraising goals were.  
![Theater_Outcomes_vs_Launch.png](https://github.com/Jahill17/kickstarter-analysis/blob/24a36bb03a0cf55aa47ab6d24f6c7e504d68e9c8/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
To decrease the likelines of coming to an improper conclusion based solely on the theater outcomes by launch date chart, a second pivot table and chart was created that showed play outcomes based on goals. 
![Outcomes_vs_Goals.png](https://github.com/Jahill17/kickstarter-analysis/blob/24a36bb03a0cf55aa47ab6d24f6c7e504d68e9c8/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
A challenge that could have occurred while analyzing the outcomes based on launch date would be incorrectly setting up the x and y axis, which would make reading and interpreting the chart more difficult. A challenge that could have occurred during the creation of the outcomes based on goals chart would be incorrectly using countifs or sum functions; these formulas summarize what's needed from the raw data in order to display outcomes based on play goals.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

A conclusion made about the Theater Outcomes by Launch Date data is that the summer months had the most successful number of theater campaigns, with May being the peak. An outside factor that could be a contributing factor is people are generally happier when the weather is better, and in the US the weather is typically best from May-August; if people are happier, they might be more likely to donate to campaigns.  A second conclusion that can be drawn is December is the worst month to launch a theater campaign.  I believe December is the worst month to launch because it has the lowest number of theater campaign launches of any month and the number of successful and failed campaigns are almost equal.  An outside factor as to why this could be the case is holiday season falls in December, and many individuals could be less likely to donate money due to spending time or money on friends and family. 

- What can you conclude about the Outcomes based on Goals?

A conclusion made about the outcomes based on goals is that generally if the fundraising goal is too high, it is less likely to be successful compared to those that are lower.  Aside from the fundraising goal ranges of 35k-40k and 40k-45k, the percent of failed campaigns outweighed the percent of successful campaigns once the goal crossed the 20k threshold. At 20k the number of successful and failed campaigns were equivalent.

- What are some limitations of this dataset?

Some limitations of the specific dataset as it relates to plays could be that only part of the story is being told by these two charts.  When looking at the outcomes based on goals chart we only see percentages of succesful/failed/canceled, and not the number of actual campaigns.  From looking at the outcomes based on goals chart is is unknown whether the fundraising tiers that were more successful had fewer or more campaigns that fell into the goal range.  Another potential limitation could be including outlier data that is skewing results.

- What are some other possible tables and/or graphs that we could create?

A possible graph that would be helpful to see is the specific number of successful, failed, and canceled projects.  It would help determine if the 67% success rate for the 35k-40k and 40k-45k ranges are legitimate or if the population is too low to conclude fundraising campaigns within those ranges are 67% likely to be successful.
As it relates to the outcomes by launch date it would be beneficial to see how long it took for each campaign to become successful.  May had the most successful play campaigns but seeing how long it took to achieve would be important as well.  
