# Kickstarting with Excel

## Overview of Project

### Purpose
#### The purpose of this analysis was to determine the best possible setup, which is most likely to produce a successfully funded kickstarter campaign for Louise’s play Fever. This was done by analyzing parameters such as launch date that are specific to kickstarter campaigns for theatre presentations and funding goals for kickstarters in general.  

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
#### Using an analysis based on the launch date of a theatre kickstarter campaign, we were able to determine that campaigns launched in the late spring and early summer time, specifically May and June, were most likely to be successful in reaching their funding goals. Furthermore, the closer to December the launch date of a campaign was, the less likely it was to reach its goal, presumably due to potential donors having limited expendable income closer to Christmas. Interesting to note that February and October have mild spikes in success rates, although these pale in comparison to the success of the May and June start dates. See this graph of theatre campaign success rate vs the launch date of each campaign for a visual representation of the data:  ![Here](https://github.com/asadca4u/Kickstarter-analysis/blob/master/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
#### In addition, we looked at the percentage of kickstarter campaigns in general that successfully reached their funding goals based on how much funding was asked for. Initially, Louise set a goal of 10,000 dollars for her campaign, however there is a marked drop off in success rates from greater than 70 per cent for campaigns under 5000 dollars to just over 50 percent success for campaigns over 5000 dollars, but less than 10,000 dollars. This indicates that Louise would be 20 percent more likely to succeed in funding her play if she was able to do it for less than 5000 dollars. It is interesting to note that there is a large spike in success for campaigns that ask for between 35,000 and 40,000 dollars to just under 70 percent, however this is most likely for more expensive consumer products, such as electronics that require more capital for research and development as well as production and meeting regulatory standards. This much higher range would not be relevant for Louise and her play. See this graph of kickstarter campaign outcomes based on the range of goals that were set: ![Here](https://github.com/asadca4u/Kickstarter-analysis/blob/master/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
#### Although I did not experience any major challenges when completing this analysis, I have noticed that Louise would be well served by further refining this analysis to provide the rate of successful outcomes for kickstarters with goals under 10,000 dollars, as this would be relevant. There is a relatively sharp decline from 4999 dollars to 9999 dollars, and Louise may still be able to find success in funding her campaign in this range, while getting closer to her initial goal of 10,000 dollars. Indeed, also sorting based on theatre campaigns alone, rather than all kickstarters in general, would give Louise a better indication of her campaign's likelihood of success, although I suspect that this would overlap heavily with the under 10,000 dollar ranges. 

## Results

### What are two conclusions you can draw about the Outcomes based on Launch Date?
#### The first conclusion I can draw about outcomes based on launch date is that May and June are the best months to begin a campaign for a theatre production. The second conclusion is that December, and the winter time more generally, is the worst time to begin a campaign. 

### What can you conclude about the Outcomes based on Goals?
#### I can conclude that campaigns that seek under 5000 dollars are the most likely to succeed, whereas campaigns that seek over 5000, up to a value of 35,000 are least likely to succeed. Campaigns that seek between 35,000 and 40,000 are also likely to succeed, however this range is not relevant to Louise's campaign as it is much higher than her estimated cost of 10,000 dollars. 

### What are some limitations of this dataset?
#### The dataset that underlies the analysis of outcomes based on goals is limited by its lack of specificity for the type of campaign Louise is running. The data of a successful kickstarter for a mobile video game, for example, is much less relevant to this analysis than data exclusively for theatre campaigns, or similar productions like tv shows and films. 
	
### What are some other possible tables and/or graphs that we could create?
#### One possible alternative table would be an analysis of the amount of backers as well as the average donation for different types of kickstarter campaigns. This way Louise could tailor the perks received at each donation level to be at a level that is close to the average donation people are willing to give to a kickstarter campaign. 
