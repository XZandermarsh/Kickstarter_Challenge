# Kickstarting with Excel

## Overview of Project
* This is an analysis of Kickstarter campaign data.

### Purpose
* The purpose of this project is to analyze various attributes of Kickstarter campaigns to understand if there are any indicators of success/failure.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
* For this portion of the analysis, the launch date and end date for each campaign had to be converted into a readable data format via a formula in Excel. The Category/Subcategory field also had to be split into two separate fields for proper grouping, using Excel's "Text to Columns" feature

* After converting the dates into the correct format, a Pivot Table was used to aggregate the campaigns into the month in which the campaign was created. The intent was to compare the number of successful and failed campaigns by the month they launched in and observe any trends. 

* There were no challenges faced in this particular analysis, but one potential challenge could have been if the data had large spikes in certain months but not an overall trend. This could have occured if the data set was smaller (such as only having data for one year). This could lead to uncertainty about whether a particular month is best/worst to launch a campaign because one would not expect high/low months to be adjacent. For example, the chart below would be the result if only 2011-2012 data were used, and April and November appear to be the best months, which is not an expected result, and does not match the overall trend, outlined in the results section. There were also no failures in these two years, so they success rate (%) would actually appear to be 100%.

![alt text](https://github.com/XZandermarsh/Kickstarter_Challenge/blob/master/Results%20by%20Start%20Month%202011%202012.png "Theater Outcomes vs Launch Date (2011-2012)")

### Analysis of Outcomes Based on Goals

### Challenges and Difficulties Encountered

## Results

### Outcomes Based on Launch Date
* The data suggests that May has the highest number of successful Kickstarter campaigns, with June being a close second.
* December had by far the lowest number of successful campaigns.
* This trend is present for the overall data, and also within the Theater parent category, as you can see by the chart below:
![alt text](https://github.com/XZandermarsh/Kickstarter_Challenge/blob/master/Theater_Outcomes_vs_Launch.png "Theater Outcomes vs Launch Date")

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
