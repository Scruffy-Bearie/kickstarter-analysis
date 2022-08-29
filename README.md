# An Analysis of Kickstarter Campaigns for Theater Projects

## Part 1: Overview of project

Crowd based funding campaigns, such as those managed through “Kickstarter”, have become a common means for entrepreneurs in many fields, including those in the performing arts, to raise the capital required to fund their projects.  The client for this project, an aspiring playwright who was in need of capital to stage a new production, initially requested a feasibility study to determine if Kickstarter was a suitable platform for achieving their fundraising objectives.  Analysis of Kickstarter campaigns between May of 2009 and March 2017 provided some valuable insights and the client was able to raise most of the capital they required in a short period of time.  Considering the analysis conducted to have been beneficial, and having come close to meeting their fundraising objectives, the client has now requested an examination of the relationship(s) between launch dates and funding goals for successful Kickstarter campaigns within the performing arts – specifically plays performed in theaters.  The following analysis represents an attempt to address said request.

## Part 2: Analysis and Challenges

Initial analysis was performed by comparing Kickstarter campaign outcomes (successful, failed or canceled) for all theater projects, as compared to when the campaign was launched (see Figure 1: Theater Outcomes Based on Launch Date).  As the project launch date in the original data set was recorded in epoch time, displaying the month in which the project was launched represented a challenge.  Through first transforming epoch time to standard time and then applying the appropriate filters, it was possible to produce an analysis that was not only readable but also beneficial.

https://github.com/Scruffy-Bearie/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png

Additional analysis was performed by comparing Kickstarter campaign outcomes (percentage successful, failed or canceled) specifically for “plays” as compared to the campaign fundraising objectives (see Figure 2: Outcomes Based on Goal).  As individual campaign objectives were posted as specific dollar amounts, analysis of groups of campaigns in any useful format represented a challenge.  Through first establishing reasonable ranges of fundraising objectives and then grouping the relevant campaigns into these ranges, it was possible to produce a more digestible analysis.

https://github.com/Scruffy-Bearie/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png

## Part 3: Results

### (i) Theater Outcomes Based on Launch Date

Review of Figure 1: Theater Outcomes Based on Launch Date reveals at least to distinct trends.  First off, that aside from the month of December when the number of successful campaigns is (almost) equal to the number of failed campaigns, the number of successful campaigns is (almost) always greater than the number of failed campaigns.  Secondly, that the difference between the number of successful and failed campaigns is greatest between the months of April and June.  These trends make it possible to conclude that, for the most part, Kickstarter campaigns for theater projects are successful more often than they are not and that campaigns launched between April and June stand the greatest chance of success.

### (ii) Outcomes Based on Goal

Review of Figure 2: Outcomes Based on Goal indicates that for fundraising goals up to $15000, the percentage of successful Kickstarter campaigns is (far) greater than the percentage of failed Kickstarter campaigns.  Moreover, Figure 2 also evidences an unexpected relationship between Outcome and Goal in the $35,000 to $45,000 range where the percentage of successful Kickstarter campaigns is, again, greater than the percentage of failed Kickstarter campaigns.  However, further analysis of the data set reveals that the bulk of the data was generated by campaigns with lower fundraising objectives and the unexpected imbalance between $35,000 and $45,000 is a little misleading.  That said, it is easy to conclude that Kickstarter campaigns for “plays” stand the greatest chance of meeting their fundraising objectives if those objectives are less than $20,000.

### (iii) Summary

Wherein the researcher stands by their analysis and conclusions, it is worth pointing out that said analysis is limited by the scope and format of the existing data set.  As said data set contains only data from Kickstarter campaigns, covers a time period during which all markets were recovering from the mortgage backed security market meltdown and includes fundraising goals posted in different currencies, some trends may not have been evidenced or identified.  Future analysis would benefit from including data from other crowd based funding platforms, including analysis of data filtered by country of origin (with appropriate adjustments for relative value of currency) and further filtering/analysis of data to account for economic climate in the year that individual fundraising campaigns were launched.
