# Kickstarting with Excel

## Overview of Project

### This is a Microsoft Excel based analysis for Louise to use to compare her campaign to similar campaigns. The analysis looks at how many theater campaigns were successful/failed/cancelled based on the month of their launch, and also looks at the success rate of plays based on their funding goal.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
For the analysis looking at the campaign outcome based on the launch date the data was filtered down to the category of Theater. The data includes all subcategories and years, and groups the data based on the month the campaign was launched along with the outcome of the campaign.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/90863226/134787699-2ba44331-f39b-4e62-98e2-01a1bbb938e7.png)


### Analysis of Outcomes Based on Goals
For the analysis looking at the campaign outcome based on the funding goal the data was limited to only campaigns with a subcategory of "play" and grouped into by goal amount into buckets in $5K increments.  The percentage of success vs failed vs cancelled was calculated for each bucket and charted on the below line graph.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/90863226/134787695-13444319-b347-4028-a65d-43d0be86f9c8.png)


### Challenges and Difficulties Encountered

I did not encounter any challenges and difficulties with this particular analysis, but could see how somoeone new at Excel might have a difficult time figuring out how to easily and efficiently fill out the Outcomes Based on Goals chart using nested formulas.

## Results

### Conclusions

  - Outcomes based on Launch Date
   
    - May, June & July are the best months to launch a new campaign
   
    - Nearly half of the campaigns launched in Dec fail

  - Outcomes based on Goals

    - Goals greater than $45K tend to fail

### Dataset limitations

  - The goal/pledged amounts are in multiple currencies, so when comparing goal amounts you aren't comparing apples to apples unless you either filter to or group by like currencies

  - I am unsure the exact source of the data, but I beleive we are only looking at crowdfunded campaigns from one website/data source, so it may not be a diverse enough sample of data

### Additional tables and/or graphs that could be useful

  - Modify the current graphs to call out Louise's campaign on each, using some sort of notation, reference line, or a single mark, so Louise can see with one glance how her campaign did against the other campaigns

  - A bar graph looking at the correlation between staff picks and success/failure rates
    
  - A Scatterplot chart with Goal and Backers (or average donation) as the x/y axis, each theater campaign being a detail mark on the chart and the outcome being the color of the mark
  
  - A line graph similar to the Outcomes Based on Goal chart, but looking at Outcome based on campaign length
