# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this project was to uncover any trends in past kickstater that could help Louise to make better decisions and have a more successful campaing

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
I performed this analysis focusing specifically on the category "Theaters" as it is the most important for Louise purpouse, then I made a Pivot Table that shows the number of campaigns that had success based on month launched, then I made a Line Pivot Chart to better visualize if the Launch Date has any impact in the success of the Theater camapaigns, the result is shown below.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/81272629/115276247-6c141d80-a108-11eb-9cc3-9c9857611bf7.png)

### Analysis of Outcomes Based on Goals
I performed this Analysis taking on account only the campaigns of the subcategory "Plays", I started sorting the number of succesful, failed and canceled campaigns based on different goal ranges, then I calculated the success, failure and cancellation percentage and made a Line Chart to visualize if there is any relation between the goal you set and the outcome of the campaign, the result is shown below.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/81272629/115284141-eac18880-a111-11eb-96ea-852e16c969b9.png)


### Challenges and Difficulties Encountered
One challenge I encountered was that the Launch Date was in Unix Timestamp in the dataset and I had to convert it to human time in order to deliver the results displayed in the graphs. Another challenge was that the dataset doesn't have a subcategory column and I had to use excel tools to make it and perform a more accurate analysis. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
As we can see in the graph, there is a trend that shows that the theaters campaings perform better when they are launched in the months of May and June which may indicate that Louise will have a higher chance of success if she launch her campaing in these months. The graph also indicate that the last 2 months of the year are the worst to launch her campaing as there are 35 camapign success in December compared with 111 campaign success in May.

- What can you conclude about the Outcomes based on Goals?
I can conclude that the "Plays" campaings tend to perform well when their goals are less than $20000, but there are campaigns with a goal range of $35000 to $44900 that have had good results in the past which may indicate that there are other factors that could affect significantly the outcome of the campaign.

- What are some limitations of this dataset?
I think that if we have information about the state from where the campaign was launched we could indicate if that is related with the outcome of the campaign. I also think that with information about if there was an expense in advertising we could indicate if that can influence significantly the chances of success

- What are some other possible tables and/or graphs that we could create?
We could calculate the duration of each campaign and analyze if it has any relation with the success/failure of them. We could also analyze the amount of backers the successful campaign have to determine if it is better strategy to look for big investors or to reach as much people as possible
