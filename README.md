# Kickstarting with Excel

**Overview of Project**
-->Louise started a Kickstarter to raise funds for her play Fever. Her Kickstarter has now come to an end and she would like to Analyze the different campaigns that were run and how they faired in relation to their launch date and their funding goals.

**Purpose**
-->To Analyze and the campaigns that were run for the Kickstarter and the impacts that these campaigns' launch dates and funding goals had on the campaigns' success. Additionally we are to visualize this information to ensure that it is easily digestible by Louise and her team. 

**Analysis and Challenges**

**Analysis of Outcomes Based on Launch Date**
	
**Pivot Table Created**
Using the given Kickstarter Data, I used a pivot table to display the data related to the months the campaign was launched and display the overall outcomes (Success, Failure and canceled) from these campaigns. A Parent Category and Years filter were also applied to the pivot table to display the data that only applied to the Theatre category. 

**Visualization**
To visualize a data I created a line graph that displayed the number of successful, failed and canceled campaigns over each month. This graph allowed us to visualize how many campaigns were successful relative to the ones that failed or were canceled. Additionally, I also created a table that displayed the Percent Successful, Percent Failed and 	Percent Canceled campaigns. This allowed me to see the result of each campaign relative to the total campaigns that were run.
See File Outcomes_vs_Goals.png for the Graph.


**Analysis of Outcomes Based on Goals**
	
	**Outcome Based on Goals Table Created**
	Referencing the KickStarter data that was provided, I used the COUNTIF function to pull the number of; Successful, Failed and Canceled projects based on the projects' Goals. The data was organized based on what the Fundraising Goal that the project had. 

	**Visualization**
	Next a Line Graph was made to display the Number of Successful projects, Number of Failed Projects and the Number of Canceled Projects for each Goal cohort. This allowed us to visually see how each campaign performed in each Goal cohort.
	See File Theater_Outcomes_vs_Launch.png for Graph


**Challenges and Difficulties Encountered**
-I did not have the Correct Excel Version downloaded, so in order to perform these actions I had to upgrade this.
-In creating the Pivot tables if you include the Grand Totals and then Filter them out it affects the Data. This realization caused me to start them over again.
-There are some limitations of the data that I felt were important in making my analysis of these campaigns. More is discussed in the "What are some limitations of this dataset?" Section.


**Results**

**What are two conclusions you can draw about the Outcomes based on Launch Date?**

	**Conclusion 1**
	May, June and July appeared to be the optimal months to run the kickstarter campaigns. Based on number of successful campaigns and the percentage of successful campaigns. See File Percent_Successful for Table.
	
	**Conclusion 2**
	December was the least optimal month to run kickstarter campaigns based on the success percentage and number of successful campaigns.

**What can you conclude about the Outcomes based on Goals?**
Projects with lower goals had a higher success rate. For example campaigns with a goal of $4,999 or less had a total success rate of 73% while campaigns with a goal of $5,000 or more had a success rate of just 50%. Additionally, the campaigns with a goal of $4,999 or less were more consistently successful. Almost each month in these two goal cohorts had a success rate of at least 57%, with the exception of December campaigns that were run with a goal of less than $1,000. To see a visualization of this table see file: Successful_Campaign_Goals

**What are some limitations of this dataset?**
In order to analyze the overall effectiveness of the fundraising you will need the cost in dollars it took to run each of these campaigns as well as the time that it costed Louise. A campaign could have surpassed its goal but there is the possibility that it ran over budget or that it took too much time to put together. On the other hand a campaign could have missed its goal but it was quick or was well under budget.

**What are some other possible tables and/or graphs that we could create?**
We can create a table and a bar graph to display the number of successful and failed campaigns based on the Launch Date Month and the Goal of the Campaign. Additionally a table displaying the percentage of successful campaigns based on the Launch Date Month and the Goal range of the Campaign could be constructed to see if certain months outperformed others.
