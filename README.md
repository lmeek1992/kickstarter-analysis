# Kickstarting with Excel

## Louise’s play Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals. 

### Purpose 
Determine if there would have been a better month to launch her campaign for a play.  Also, determine if the fundraising goal impacted whether or not the campaign was successful.     

## Analysis and Challenges 
To perform this analysis I reviewed the request and determined the specific data required.  Louise is working on a theater production and therefore wants to know how her campaign launch fared compared ot others.  Utilizing a pivot table we are able to look at the launches by month for all theater activities. Once completed we are able quickly view the results by building a chart to identify the number that were successful, failed or were canceled in those months.  
 

### Analysis of Outcomes Based on Launch Date
May and June had the most launch dates and also had the higher number of successes.  The winter months are definitley risky for launching a new campaign.  October has the highest number of failures.  December had the lowest number of successes.  

### Analysis of Outcomes Based on Goals - 
There were many ranges that did not have goals set. Therefore we may have some outliers or even a possibility of data being keyed incorrectly.  We need to verify the outliers.  The numbers are definitely skewed.


### Challenges and Difficulties Encountered
The challenge I came across was the lack of data points in a given range. This resulted in errors in the formulas which were easily fixed with the @iferror function in Excel. 
 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date? - 
Campaigns are most successful in the May-June time period.  Launching a campaign in the winter months if very risky.   

- What can you conclude about the Outcomes based on Goals?  
Louise's original goal was 4000 - in that range it appears that 73% are successful - it is not surprising she was able to raise the funds in a short period of time.  The higher the goal the more likely the campaign will fail.

- What are some limitations of this dataset?  There are many other factors that should be considered on why a campaign may or may not succeed. I would look at location and month - are some locations more giving in different time periods.  I would look at what type of entertainment people tend to go to in a location to determine whether or not a paticular campaign type would work better than ohers.  I would look at the years, and what occurred in those years to see if there was a recession of other economic impact. 
  

- What are some other possible tables and/or graphs that we could create? 
1) We viewed it by month, not by year - we may want to filter the year to reflect the economic status of the year she launched her campaign. Changing to view specific years has a huge impact on the results.   
2) We also looked at launch date based on the category of Theater - I would want to filter it to plays to see if there is a difference. - there wasn't a huge change
3) I would want to also filter for locale - and see if that impacts the success or failure of the campaign- a quick review indicates that yes there is an impact
