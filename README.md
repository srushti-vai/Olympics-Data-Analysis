# Olympics-Data-Analysis

### Data wrangling processes, which should cover:

### **MAKE SURE TO CLEAN EVERY TIME A NEW DF IS CREATED**

**Cleaning: Removing duplicates, filling missing values, etc.**
athletes_df: 
- mainly age, height, weight (try filling these by stacking and sorting by gender and sport and impute)
- look at height and weight outliers and relate them to the sport that they are from
summer: 
- talk about NA in medals, but don't remove them (or if you want to show removing them, then create a df subset that only has athletes who won a medal)
- talk about duplicate names
- talk about duplicate countries for same event same year as team sports (ex. mens hockey)
winter:
- talk about NA in medals, but don't remove them
- talk about duplicate name and duplicate countries for same year because of team sports


**Filtering subsets of your data with explanations.**
- filter male vs female (weight amd height for various sports)
- filter a df of only the winners (meaning the non NA medal rows) can further subset (using group by) into gold silver bronze to see if any country consistently places
- filter team sports subset and individual sports subset
- filter people who have participated in both winter and summer olympics (its ok if the result is 0, thats what we want to see)
- filter countries who ONLY participate in summer or ONLY participate in winter, not both


**Sorting your data with explanations.**
- sorting by which sport a country is best at (by num of medals)
- sorting by age of athletes (can be done with male, female, and total) to see oldest athletes (used in visualization)
- 


**Merging data in different ways with explanations.**
- merge all three datasets by the athlete name
- merge only winter and summer to do the filter of people who have participated in both seasons, or countries who have only participated in one season
- 


**Visualizing data using at least five types of visualizations (e.g., scatter plots, bar charts, histograms, line charts, boxplots, etc).**
- compare number of athletes vs number of medals won by the country
- if host country perform better at their home games
- compare distribution of medals won by country in winter vs summer (bar graph)
- histogram of number of medals won (as bins on xaxis) and number of countries who have won that many medals (yaxis)
- compare male vs female statistics (ex boxplots to compare male vs female height for volleyball)
- graph age for all athletes and see where most athletes lie
- athlete improvements (using pivot table) (line graph)


**Pivoting or stacking your data with explanations.**
- stack by country and gender to break down biometrics by demographic
- pivot the data by player names and have the columns be the games, and values be the medals to see the change in their winnings and improvement through the years