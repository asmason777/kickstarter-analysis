# Kickstarting with Excel
---
## Overview of Project

### Purpose
Louise came close to reaching her target budget for her play Fever but fell short by just $400. Louise would like to compare her results with other crowdfunding projects by looking at their respective launch dates and funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
To compare Louise's launch date to other theater crowdfunding launch dates, a pivot table was created that shows launch date for all projects by month. Also, a column was added in Excel to show the year that the campaign occurred. This made it possible to not only filter results for all years but specifically for 2015 - the year Louise's campaign occurred. We then charted the results:

[![Theater-Outcomes-vs-Launch.png](https://i.postimg.cc/T1vRQHpg/Theater-Outcomes-vs-Launch.png)](https://postimg.cc/njTbh2Kh)

[![Theater-Outcomes-by-Launch-Date-2015.png](https://i.postimg.cc/MK49zH39/Theater-Outcomes-by-Launch-Date-2015.png)](https://postimg.cc/hfLLrDBm)

By adjusting the filters to include all production types, we are also able to see the composite success rate of all campaign genres. This allows us to have a broad overview of both all-time data as well as 2015 data to check to see if any anomalies may have occurred in 2015 that may have affected Louise's results. Charts were again created to better illustrate the findings:

[![All-Category-Outcomes-by-Launch-Date-All-Years.png](https://i.postimg.cc/NMpxSjr7/All-Category-Outcomes-by-Launch-Date-All-Years.png)](https://postimg.cc/S2Y8zqdJ)

[![All-Category-Outcomes-by-Launch-Date-2015.png](https://i.postimg.cc/8ccbSgR8/All-Category-Outcomes-by-Launch-Date-2015.png)](https://postimg.cc/2LpWQJ9T)

### Analysis of Outcomes Based on Goals
With regards to fundraising goals, a new worksheet was created to extract funding data specifically from other plays where the time frame for funding had ended. By grouping the funding amounts into different ranges, we can better compare the results including how Louise's play Fever did versus other plays with similar funding goals. We then added columns so we could compare the success percentage of each funding amount grouping. This information was then brought into a chart to provide a better visualization of the results.

[![Outcomes-vs-Goals.png](https://i.postimg.cc/26zGvCxZ/Outcomes-vs-Goals.png)](https://postimg.cc/hJ5VRW6D)

### Challenges and Difficulties Encountered
The first challenge I encountered was in extracting the play data by using the COUNTIFS function in Excel. I was unsure if there was a way to add a range for the respective funding goal groupings using just one argument or if I had to use two separate ones. After spending several minutes on google, the solution that worked for me was to add two separate criteria. I also made the mistake of putting the equal sign before the greater-than sign so that also had to be reversed before I could get the function to work properly. Below is a screenshot of the COUNTIFS function I used with the two arguments:

[![COUNTSIF-function-formula.gif](https://i.postimg.cc/g2qxcpCL/COUNTSIF-function-formula.gif)](https://postimg.cc/TK1dQzYT)

However, the most challenging part of this assignment was adding the imbedded charts into my Readme document. Having worked some years ago with HTML, I assumed that I could link the picture located in desktop folder in a similar manner. Perhaps this is possible but per visiting several different on-line forums, I only found two solutions: 1) adding the picture to the corresponding Github repository and then linking it from there or 2) using the website PostImage.org to host my picture(s) for free. I chose the latter option as, at least for my first assignment, I do not want to “clutter” my repository.

## Results
When determining the results by launch date I looked primarily at four different sets of data: 1) success rate of theater campaigns for all years, 2) success rate of theater campaigns for 2015 only, 3) success rate of all campaign types for all years and 4) success rate of all campaign types for 2015 only. The most obvious trend across all the information was that campaigns initiated mid-year, especially May and June, yielded the greatest number of successes. December universally was the worst month to start a campaign and the only month to generally have more failed than successful campaigns.

The other notable outcome was that the success-to-failure-and-canceled ratio in 2015 was worse than the overall average for both for the theater category as well as for all campaign types. For example, the success rate for theater campaigns for all years (not including 2015) was 62.9% as opposed to only 58.7% for 2015 alone – a drop of 4.2 percent. This trend was even more notable when considering all campaign genres. For the latter, the success rate plummeted by a whopping 10.7 percent in 2015 from 57 to 46.3%. Based on these findings, 2015 appears to have been a less effective year for fundraising and may explain that while Louise began her crowdfunding in the month with the greatest number of successes (June), 2015 was a below average year for successful campaigns.

[![Theater-Outcomes-Data.gif](https://i.postimg.cc/d1WdsFTj/Theater-Outcomes-Data.gif)](https://postimg.cc/gXZrsfsx)

The outcomes based on funding goal also provide another set of data by which to analyze Louise’s results. Not surprisingly, a great majority of plays had funding goals less than $5,000 and most of those fell into Louise’s funding range with goals between $1,000 to $4,999. Lower funding goals also heavily correlated to more success and the general trend is that as funding goal amount increased, overall success percentage decreased. It is also notable that for funding goals greater than or equal to $25,000, the results become somewhat skewed because of the limited number of plays that fell into these higher funding categories. Ultimately, Louise’s goal of $2,885 appears to have been a realistic goal. Plays in the goal funding range of $1,000 to $4,999 had a success rate of approximately 73 percent. Had fundraising for 2015 not yielded below average results, she very well might have met her funding goal which she only missed by $400. 

Reviewing Louise’s results based on launch date and funding goals provide a good starting point, but to get more specific feedback, likely more in-depth analysis is needed. For example, I noted in my research that 2015 appeared to be a below average year for funding and more research would be needed to understand why that was the case. Also, regarding funding goals, it might be helpful to look at factors such as the funding time-period as it relates to the prospective budget. Ultimately, many other factors might also come in play that would increase or limit a fundraising effort including local interest, popularity of the director and/or actors, interest in play theme among many others.

Finally, there are many other ways in which the data could be used to quantity Louise’s results. We could drill down further and instead of filtering launch date by category we could look directly at the subcategory “plays” to get a better comparison. This data could be used to create a chart to compare year-over-year results to see if there are any identifiable trends that might affect future fundraising efforts. Another way to look at the funding data would be to create a table that groups not by success or failure but by percentage funded. This information would be helpful in identifying which plays received no or little interest and might also illustrate which ones needed a longer fundraising period. Louise came close to reaching her stated goal in only four weeks and had she extended her funding deadline by one more week she may have reached her goal. 
