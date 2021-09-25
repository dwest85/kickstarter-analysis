# Kickstarter Analysis Project

## Overview of Project
Performing analysis on data to uncover trends for Louise's future Kickstarter campaign to maximize the outcome of acheiving a succesfully pledged campaign.

### Purpose
The purpose for this analysis project was to gain insight based off of the relation of past failed and successful kickstarter campaigns. This data will help Louise drive her own campaign strategy using several pieces of visulaization in the hopes of maximizing the chance of running a successfull campaign. This information will also allow Louise to rank her own success vs the success of similar kickstarter campaign projects.

## Analysis and Challenges
Breaking down the information into easily digestable data was the first challenge (example: color coding the outcomes). Filtering this data using several different filters, as well as pivot tables allowed for more readable data. 

VLOOKUPS were also helpful with pulling very specific data quickly to pair up against Louise's campaign strategy (similar theater kickstarters that Louise selected as well as their goals and pledged data.)
![V_Lookups_Chart](https://github.com/dwest85/kickstarter-analysis/blob/main/images/v_lookups_example.JPG)

Descriptive statistics also helped root out a strong potential kickstarter goal based off of the Successful and Failed Kickstarter information.
![Descriptive_Statistics]()

Also, functions, such as =COUNTIFS() helped break down large groups of data in order to easily track and use the information (such as Outcomes Based on Goal data).
![COUNTIFS_Function]()

### Analysis of Outcomes Based on Launch Date
Based off of information filtered through the completed Launch Date visualization chart, the best time to launch the kickstarter would be between May and June. Our data showed that these months had the most successful theater campaigns pledged. 

### Analysis of Outcomes Based on Goals
Based off of the information pulled from our goal visualization data, theater campaigns had the most amount of success with pledged goals that fell between $1000 to $4999. There was a hard decline in the percentage of successful campaigns from $5000 upwards. 

## Results
Based on the insight gained after pulling data from past successful and failed kickstarter theatre projects, I recommend Louise try for a kickstarter pledge goal of under $2000. This is half of the originally planned goal, which I feel is necessary to have the largest chance of success based on the data analyzed. This conclusion was based on insight pulled from vlookups, pivot table insight, charts, graphs, plots, as well as descriptive statistics.

- What are two conclusions you can draw about the Outcomes based on Launch Date?
That the best time of the year to start a Theater-based kickstarter campaign is around May and June. A bad time to run a Theater-based campaign would be between October and December, as there is a large decline in the amount of successful campaigns pledged.

- What can you conclude about the Outcomes based on Goals?
Campaigns with lower financial goals had a larger success rate, with a decline occurring around the $5000 mark.

- What are some limitations of this dataset?
A major limitation is not knowing what the individual backers received for pledging money to a specific campaign. Having data on the perks offered to backers might have created additional insight on how to successful market for the campaign.

- What are some other possible tables and/or graphs that we could create?
Histograms and pie charts could have helped break down the data more specifically for anaylyzing the campaign strategy.