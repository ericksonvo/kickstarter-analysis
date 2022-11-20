# An analysis of Kickstarter Campaigns

##Comparing how different campaigns succeeded or failed  based on launch date and funding goals for theaters.  
Purpose of of this analysis is to find key dates and fund goal, to find the best time when to lauch an campaign and the best amount of funding to have an succesful outcome

###Analysis and Challeges


![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/117749494/202919656-b47f5b3d-0cd6-4761-bbce-cfaf3209efd7.PNG)
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/117749494/202929781-7d94dd21-1537-483f-9d8d-e1b339278733.PNG)



###I began my analysis by creating a pivot chart for launch date and outcomes. by using the year() funtion, I was able to separate the data into years only. When creating the Outcome vs Goals spreadsheet and chart. I used the countif() and countis() function. However, some challenges that were faced during this data analysis was to extract the correct data for successful and failed theaters based on goals funded. When I began to organize the data for successful and failed goal funds, I first filtered the "outcomes" columns to succesful campaigns only and used the countif() formula to extract the data into the new spread sheet, I did the same for failed outcomes. When my results came back, I got the same exact numbers for both successful and failed goals. This made my percentage for both 50% at the end. So I had to back track and see what I had done wrong. So, I went back into the data sheet and turned off the filters for the outcomes. With the help from "https://support.microsoft.com/en-us/office/countifs-function-dda3dc6e-f74e-4aee-88bc-aa8c2a866842", I was able to use the countif() function correctly, and it made the rest of the data gathering process easier. 

####Results

1.By examining the Theater outcomes vs launch chart, the best time to launch a campaign for theaters are at the beginning of the year, with the most success being in the month of May. Also, t the worst time to launch a campaign is towards the end of the end of the year, we can see that succesful outcomes begin a downfall trend going towards fall and winter. So inconclusion, best time to lauch a campaign is in the month of May. 

2. When looking at the Outcomes vs Goals chart we can say that having funds between < $1000 and and < $25000 and funds at $40000 - $45000, have the greatest success, however, having goals funds > $50000, has little to no success.

3. Some limitations of this data set is that we do not see how the campaigns were advertised and/or what avenues did the campaigners used to be more successful than others. By seeing how campaigns were advertised and what platforms that were being used to promote the campaigns we can have an better understanding on the differnt ways of promoting that lead to an successful outcome.

Although the the line chart was a good way to express the data. An bar chart would have been another option to show the data. It, in some ways can be easier to read than line charts.
