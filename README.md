# Kickstarter-Analysis
Performing analysis on Kickstarter data to uncover trends

## Overview of Project
  Louise came to us looking for assistance in analyzing data. She has written a play and is looking to use a kickstarter campaign to finance her play. Louise wanted to know how other kickstarters fared, and what they might have done to make them more or less successful. In order to provide her with this information, we used excel to analyze the data, and were able to construct visuals for Louise to decide the best path forward. 
  
### Purpose
  The purpose of our analysis was to provide Louise with a straightforward analysis of the data, so she could make an informed decision on how to proceed. 

## Analysis and Challenges
  This was a large data set to analyze with a lot of extraneous data. In order to get Louise a concise answer, the data needed to separated, altered, and filtered. We were given a lot of information, to move forward, we needed to know what data was relevant and what was not, the relevant data were, the goal amount, the pledged amount, the category and subcategory, the dates associated with production, the precentage funded, and most importantly; was it successful? To start, the category and subcategory were separated in order to isolate "Plays"; the dates of production were translated from Unix time stamps to the more colloqiually used month/day/year form. The date, and outcomes of the kickstarters were compared in the first line graph, shown below. The goal amount, the pledged amount, and the outcome of the kickstarters were analyzed together and a line plot was created to show the relationship, in the second graph shown below. 
    
### Analysis of Outcomes Based on Launch Date
  ![Theatre_Outcomes_vs_Launch](https://user-images.githubusercontent.com/106715300/174501191-b4fa58d6-de5f-4119-b0a1-a6a15fe1273d.png)
  
    In this initial graph, the outcome of the campaign, be it successful, failed, or canceled; is compared with the date of launch. This particular graph is an important piece of information for Louise to examine, as she will want to pick the best time of year to lauch, as there are better and worse months to launch kickstarters. 

### Analysis of Outcomes Based on Goals
  ![Outcomes_vs_Goals](https://user-images.githubusercontent.com/106715300/174501337-7f5855e8-276b-43a6-869f-2c97bed3a3f6.png)

  In this second graph, the goals are compared to the percentage of funding they recieved, compared to their success or failure. This graph will give Louise a concrete idea of how much money she should aim to raise in order to have a successful kickstarter campaign. 
### Challenges and Difficulties Encountered
  There are some challenges with data, comparing between theatre and plays there are small differences. In the category "Theatre" there is a mix of successful, failed, and cancelled productions. However there are no canceled programs under the subcategory of played, which causes the small discrepancy in the data. However the overall trends remain useful to explain the best time of year to start a kickstarter. The other difficulty encountered was differentiating which data should be used in each section of pivot table. Through trial and error a visual that could be easily understood was produced. 
## Results
  From the first graph we can conclude that May is the best month to launch a kickstarter campaign, this is when the success rate is the highest, but the failure rate is also relatively low. It can also be concluded that as the year progresses the success rate of kickstarters decreases, with October being the worst month to start a campaign with the highest failure rate. So if Louise is not able to start her campaign by May, she should try to get it started as soon as possible, if she cannot start it before October, then she should wait until February when the success rate is higher. 
    From the second graph, we learned that if a goal is less than $1,000 is has a much higher rate of failure, over 70%; than if she were to strive for between $1,000 and $5,000. The higher monetary goals also have higher success rates, however there is much less data to say definitively that having such high goals will lead to success. The conclusions to draw here, are the goal needs to be over $1,000 dollars, and recommended between $1,000 and $5,000, to stick within the range of the majority of the data. 
     This lack of data in the high ranges of pledges and goals, is one of the limitations of this data, without more data it cannot be conclusively shown that raising the costs of production raises the success of kickstarter campaigns. Another limitation its outliers, some goals are very low, and the pledged amounts are significantly higher than the goal, in turn the percentages and success are skewed. Another limitation is the limited data in the number of campaigns with higher contributions and goals, with more data points, it would be easier to say if raising the goal amount is a way to create a successful campaign. The final and maybe largest limitation is, really figuring out why some campaigns are so successful, why is it some campaigns raise tens of thousands of dollars? while others barely get off the ground?
      
  
  
- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
