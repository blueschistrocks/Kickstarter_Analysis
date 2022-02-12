# Kickstarting with Excel

## Overview of Project
Louise (client) has requested that the Kickstarter Crowdfunding campaign data (data) be analyzed to determine how different campaign goals performed based on their launch dates and their proposed funding goals. 

### Purpose
The purpose of the analysis was to determine the time of year and funding goals that would be appropriate for theatrical play production funding campaigns. The analysis of the client provided data was preformed using Microsoft Excel.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
To analyze the data for funding outcomes based on launch date the data was filtered in two ways using Excel’s Pivot Table tool: by campaign launch month for all years aggregated between 2009 and 2017 and by campaign launch year.  The filtered data was then graphed by funding outcome counts (i.e. successful, failed and canceled) based on launch dates and by campaign launch year.  The graph titled [Theater Outcomes Based on Launch Month](Theater_Outcomes_vs_Launch_month.png) and [Theater Outcomes Based on Launch Year](Theater_Outcomes_vs_Launch_yr.png) are provided for review.


### Analysis of Outcomes Based on Goals
Using Excel’s COUNTIFS() function the funding goals for the successful, failed and canceled campaigns were sorted based on funding goal ranges (i.e. $1,000 to $4,999, $5,000 to $9,000, etc.).  The percentage of successful, failed and canceled campaigns were calculated for each funding goal range. The percentages were graphed over the funding ranges.  The graph titled [Outcomes Based on Goal]( Outcomes_vs_Goals.png) is provided for review. In addition, a table of funding ranges titled [Tabulated Ranges of Funding Goals - Theatrical Play Productions]( Funding Goal Ranges.pdf) is provided for review.  

### Challenges and Difficulties Encountered

The challenging aspect of this project was keeping track of the various excel tabs from the lessons and the challenge project.  It may be helpful to save different copies of the files between the lessons and the challenge project.  

## Results

### Results of Analysis of Outcomes Based on Launch Date

Based on a review of the filtered and the graphical presentation of the data it appears that that the month of May had the most successful funding campaigns, with the month of December having the lowest number of successful campaigns.  The number of failed and canceled campaigns were relatively consistent in every month. A further review of the data filtered by year indicates that successful and failed campaigns followed a relatively similar pattern each year with some variation between 2011 and 2013. However, it does appear that significantly more funding campaign were started between 2014 and 2016. The graphical representation of the data appears to indicate that the amount of funding campaigns reduced significantly in 2017, however this is due to a lack of data for 2017.   

### Results of Analysis of Outcomes Based on Goals

Based on a review of the tabulated and graphical presentation of the campaign funding data it appears that that funding ranges between less than $1,000 and $5,000 had a higher percentage of success and the funding ranges between $32,500 and $42,500.  It should be noted that there were a larger number of campaigns with funding ranges between less than a $1,000 and $5,000 than the campaigns with funding ranges between $32,500 and $42,500.  A statistical analysis of the funding goals may be useful in further analysis of the funding ranges. It should be noted that the funding goals in the data package were in various denominations.  See the section below regarding additional analysis with all currencies converted to US dollar. 

### Recommendations Based on Analysis

It is recommended that funding campaigns for theatrical play productions be started between mid-April and mid-June and funding goals range from $1,000 to $5,000.

## Additional Analysis and Data Presentations

Below is a discussion of additional analyses conducted or recommended. 

### Results of Addition Analysis of Outcomes Based on Goals (U.S. Dollar)

The funding goals were converted to US dollar using the latest exchange rates provided by Oanda Corporation at https://www1.oanda.com/currency/converter/, accessed on February 8, 2022.  An Excel IF function was used to covert the non-U.S. dollar currencies to U.S. Dollar.  Using Excel’s COUNTIFS() function the funding goals were analyzed similar to the above analysis of outcomes based on goals.  The percentages were graphed over the funding ranges.  The graph titled [Outcomes Based on Goal (All Currency Converted to USD)](Outcomes_vs_Goals(USD).png) is provided for review. In addition, a table of funding ranges titled [Tabulated Ranges of Funding Goals (USD) - Theatrical Play Productions]( Funding Goal Ranges (USD).pdf) is provided for review.  

Based on a review of the analysis it appears that outcomes based on funding goals did not change significantly, however the percentage of failed campaigns appeared to drop slightly in the $25,000 to $29,000 funding goal range.  

Louise may decide that she wants to produce a theatrical production in the U.S. only or in other specific countries.  An analysis by county may be useful in determining the appropriate funding start dates and funding ranges.   Graphs showing funding outcomes in select countries would be helpful in determining how successful campaign funding start dates varied depending on the country.  In addition, a graph of successful funding ranges by county would be useful for Louise.

