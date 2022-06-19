# Kickstarting with Excel

## Overview of Project

This project was undertaken to analyze funding campaign data primarily focusing on entertainment compaigns. 

### Purpose

Entertainment projects, and particularly plays, can be costly. One method a playwright may use to obtain funds to get their play to the stage so it can be enjoyed by the public is to obtain funds through a crowdfunding campaign. Kickstarter is a company who's stated mission is to "help bring creative projects to life" and has helped other plays be successfully completed. 

Our client is a playwrigt who has written a play entitled Fever. Our client would like to start a crowdfunding campaign to help fund her play. We will work with existing crowdfunded data from Kickstarter to determine if there are factors that help make a crowdfunded compaign successful. 

## Analysis and Challenges

The two main analyses that were created for the client concern outcomes. Our client is hoping for a successful return. She wants to earn enough money using a crowdfunded campaign to be able to bring her play to the stage. The main challenges are removing the 'noise' or additional data from the daataset that is not relevent to our client's situation. 

### Analysis of Outcomes Based on Launch Date

The first analysis conducted for our client was to determine the Outcomes of campaigns based on the launch date. This could help our client determine if there may be a better time to lauch a campaign to ensure a successful result. 

The main parts of this analysis included:
 1. Separating concatenated data. The original dataset contained a single column for Category and Subcategory in which the data was concatented. It was necessary to separate this data into two separate columns to allow easier querying. 
 2. Converting the source data from a UNIX data format to a hunam readable format
 3. Creating a Pivot Table to assist in determining insights for our specific analysis
 4. Creating a Pivot Chart to visualize the data for the client in a user friendly format

### Analysis of Outcomes Based on Goals

The second analysis conducted for our client was to determine the Outcomes of campaigns based on the goals. This could help our client determine if she may not achieve a successful campaign based on the goal of her campaign.  

The main parts of this analysis included:
 1. Separating concatenated data. The original dataset contained a single column for Category and Subcategory in which the data was concatented. It was necessary to separate this data into two separate columns to allow easier querying. 
 2. Creating specific goal categories at $5,000 increments. This helps our client by looking at the overall data logical subsets. 
 3. Creating a Pivot Table to assist in determining insights for our specific analysis
 4. Creating a Pivot Chart to visualize the data for the client in a user friendly format

### Challenges and Difficulties Encountered

The main challenges to be overcome during the analysis was in preparing the data to answer the questions being asked. 

The first data challenge was the field Category and Subcategory. This field was a concatenation of two values that led to many different unique choices. To facilitate the analysis it was necessary to separate this field into two distinct fields of data. This helped with the analysis and removed data that was not relevant to the analysis our client required. 

The second data challenge was the date format of the original data. The data was in a UNIX format that was not human-readable. To overcome this challenge it was necessary to convert the data from UNIX format to a human-readable format. 

![dates](/kickstarter-analysis/Dates.PNG)

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

When conducting the Theater Outcomes based on Launch Date the Chart is quite useful in visualzing the trends. One factor of note is that there is a peak in success for campaigns launched in May. In fact, this is the most month when most successful camtains are launched. Secondly, it can be noticed that number of campaigns that are canceled are quite consistent regardless of the month they are launched. 

- What can you conclude about the Outcomes based on Goals?

The Outcomes based on Goals is a useful analysis for our client since she has a budget and knows she will be asking for $10,000 + in her crowdfunding campaign. From the chart visualization and tabular data in the pivot table it can be concluded that campaigns in the range of $10,000 to $14,999 are successful about 54% of the time. While this is not the highest percentage of successful campaigns it is the range our client will be targeting for her campaign. 

- What are some limitations of this dataset?

The Kickstarter data was useful for the analysis our client requested. However one of the main limitations of the data is the age of it. The most recent data is from 2017 which is now 5 years old. The existing data could be useful in determine crowdfunding trends however the most insight our clinet would receive is from five years ago. 

- What are some other possible tables and/or graphs that we could create?

To assist our client in her analysis the following tables/graphs may help her:
1. Conducting the analysis based on the country in which she will be running her campaign. There could be contry differences. 
2. Conducting an analysis on between date the campaign was created and the data the campaign ended for successful and failed campaigns. This will give our client an idea of the timeframe for successful campaigns.
3. Conducting an analysis of Aveage Donation for successful campaigns for a particular Subcategory. This would provide our client with information concerning the average donation for successful plays.  
