# An Analysis of Kickstarter Campaigns

## Overview of Project

    Performing data analysis on several thousand crowdfunding projects to uncover any hidden trends. The following includes the analysis and challenges, results, and limitations.

### Purpose

    The client is planning to launch a Kickstarter campaign to finance a new play in the US. Before launching the campaign, the client has requested analysis of historical Kickstarter campaigns to identify any trends regarding successful campaigns for plays. To do this, several thousand crowdfunding projects were analyzed to uncover any hidden trends. 

## Analysis and Challenges

    The file below is where the analysis was performed. This file contains the original dataset and additional analysis. While this dataset contained kickstarter data on thousands of campaigns, the client was primarily interested in plays. As a result, filters were added to accommodate multiple views of the data to include plays.

[Kickstarter_Challenge.xlsx](https://github.com/stovepipe/kickstarter-analysis/blob/main/Kickstarter_Challenge.xlsx.zip)

### Analysis of Outcomes Based on Launch Date

    The graphic below shows the theater campaign outcomes by launch date. The outcomes looked at were "successful", "failed", and "canceled". "Live" outcomes are not reflected in this analysis.

![Theater_Outcomes_vs_Launch.png](https://github.com/stovepipe/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)

    From the chart, we see that the month that launched the most successful theater Kickstarter campaigns was May. Failed campaigns remained fairly steady over the course of a year. 

### Analysis of Outcomes Based on Goals

    The graphic below shows the outcomes of "Play" campaigns by goal amount. The outcomes looked at were "successful", "failed", and "canceled". "Live" outcomes are not reflected in this analysis.

![Outcomes_vs_Goals.png](https://github.com/stovepipe/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

    From the chart, we see that "Play" campaigns were most successfule when the goal amounts were less than $1000. However, there is another range with moderate success between $35000 and $45000.

### Challenges and Difficulties Encountered

    One challenge encountered was accommodating for campaigns that received no pledges resulting in null or zero values. In some analysis, this produced an error that forced the modification of formulas. Able to successfully eliminate errors from calculations, maintaining the visual representation of the data for the client.

    The dataset contained Kickstarter data across many categories and subcategories. Breaking down this data into manipulatable values for segmentation across anlysis resulted in filters being placed on many charts and tables, allowing for greater versatility of worksheet and resources produced from analysis.

## Results

    Based on the Outcomes based on Launch Date, two conclusions can be made. First, regardless of launch date, failed campaigns remain fairly steady throughout the year. However, the most successful campaigns were launched in May. Successfull campaigns diminish as the year progresses after May with less than 50% being successful by the end of the year.

    Based on the Outcomes based on Goals analysis, we can conclude that the most successful campaigns held goal amounts less than $1000. However, there is an additional sweet spot with moderate success for campaigns with goals between $35000 and $45000.

    Limitations on this dataset include years of data captured. The analysis reflects data captured between 2009 and 2017. Not having the most recent data could affect results.

    There are several additional tables and charts that could be developed to further breakdown the data. For example, we could utilize the date ended data to find the length of campaigns to see if there is any relationship between the length of campaigns against outcome. 

    From a quick look over the data, we could also create a table to count how many successful campaigns were featured in the spotlight. There appears to be a relationship between a spotlight and a successful campaign. This would allow some interpretation of the role Kickstarter marketing can play in success. Also allows the client to pursue featuring their campaign in the spotlight. 
