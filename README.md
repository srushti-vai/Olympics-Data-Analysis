# Olympics-Data-Analysis

### Data wrangling processes, which should cover:

### **MAKE SURE TO CLEAN EVERY TIME A NEW DF IS CREATED**

**Cleaning: Removing duplicates, filling missing values, etc.**
athletes_df: 
- DONE: mainly age, height, weight (try filling these by stacking and sorting by gender and sport and impute)
- look at height and weight outliers and relate them to the sport that they are from
summer: 
- talk about NA in medals, but don't remove them (or if you want to show removing them, then create a df subset that only has athletes who won a medal)
- talk about duplicate names
- talk about duplicate countries for same event same year as team sports (ex. mens hockey)
winter:
- talk about NA in medals, but don't remove them
- talk about duplicate name and duplicate countries for same year because of team sports


**Filtering subsets of your data with explanations.**
- DONE: filter male vs female (weight amd height for various sports)
- DONE: filter a df of only the winners (meaning the non NA medal rows) can 
    - further subset (using group by) into gold silver bronze to see if any country consistently places
- XXX: filter team sports subset and individual sports subset
- filter countries who ONLY participate in summer or ONLY participate in winter, not both


**Sorting your data with explanations.**
- sort by number of medals per country
- DONE: sorting by age of athletes (can be done with male, female, and total) to see oldest athletes (used in visualization)
- 


**Merging data in different ways with explanations.**
- DONE: merge all three datasets by the athlete name
- DONE: merge only winter and summer to do the filter of people who have participated in both seasons, or countries who have only participated in one season
- merge winter and athletes, and summer and athletes, then take a subset of each that only has the NOC, Team, and Medals column, and merge these to analyze medals by country


**Visualizing data using at least five types of visualizations (e.g., scatter plots, bar charts, histograms, line charts, boxplots, etc).**
- compare number of athletes vs number of medals won by the country
- if host country perform better at their home games
- XXX: compare distribution of medals won by country in winter vs summer (stacked bar graph)
- DONE: bar graph of top 10 countries with most medals (bar graph)
- DONE: histogram of number of medals won (as bins on xaxis) and number of countries who have won that many medals (yaxis) (histogram)
- compare male vs female statistics (ex boxplots to compare male vs female height for volleyball)
- DONE: graph age for all athletes and see where most athletes lie (density graph)
- DONE: scatter plot representing the differences between winter athletes and summer athletes physiques (scatter plot)
- DONE: creates a box plot of average number of times an athlete wins (not including atheles who have never won) (box plot)
- athlete improvements (using pivot table) (line graph)


**Pivoting or stacking your data with explanations.**
- stack by country and gender to break down biometrics average by demographic (agg func = 'mean')
- DONE: pivot the data by player names and have the columns be the games, and values be the medals to see the change in their winnings and improvement through the years