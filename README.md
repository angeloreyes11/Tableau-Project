# Final-Project-Tableau

## Project/Goals

With over 17 thousand FIFA players and 70 different attributes attached to each player, my main focus for this project was to analyze, gain insight and create visualizations that will help me filter out top players from low level players. Growing up playing FIFA your eyes immediately get drawn to player stats and team stats. You would be wanting to play your friends using the best statistical team in the game. That was the primary objective for while completing this project. It was to display the best of the best players of FIFA 2018. 

How can we do that?
 - Explore and to get familiarize with each data we are dealing with. (ie. All different attributes for each player)
 - Condense it into categories easier to read and interpret. (ie. Position stats such as ST, CM, LW, CB, RB, and soo on are combined into Forward, Defender,     Goalkeeper)
 - Build data visualizations to help achieve my project objective. This is done using show-me tables, heatmaps and analytical data visualization such as clusters.
 - Create dashboards and stories to create a flow to illustrate and answer our desired questions about this data set.

## Process

## Step 1: Data Loading and Analyzation 

- Out of the 5 options for our project we chose the FIFA 18 Player Ratings.
- Using the data set provided, navigate through Tableau to download said data set into the workbook.
- Within the data source tab, familiarize through each different columns of data to distinguish which we can use for analyzation. 

## Step 2: Build Visualization Graphs and Table

- Using Tableau worksheet, create interactive data graphs and tables with the given data.
- Include filters options to interact with the visualization.
- Integrate parameters and calculated fields to combine sets of data into smaller, more readable attribute.

## Step 3: Formulate Questions 

- Once we understand the data we have, create questions that we want to answer.
- What are some graphs or tables that we have generated that might answer these questions? Any anylitical models we can use to further explain the data?

## Step 4: Create Dashboards and Stories

- Using Tableau Dashboards, create an interactive dashboard that represent a better story and flow.
- Here we are to answer the questions we want to answer using the graphs or tables we generated. 

## Results

The chosen data list of FIFA 18 Player Rankings which was one of the options for option 2. Visualizations were created in the goal of asking a handfull of questions. 

1. Who are the top performing players in FIFA 18 and what makes them soo good?

- To analyze this question, a simple overall to name comparisson is needed to graph players in an axis in their respective overall stat. To sort the players from the highest ranking to lowest, a sorting must be done using the overall attribute.
- The harder part of this task it that there are more than 20 different attributes associated with each player. Therefore I had to combine those different stats into 6 different categories:

  a. "Defending" - Interceptions, Heading Accuracy, Def. Awareness, Stangind Tackle, and Sliding Tackle.
  b. "Handling"* - Agility, Balance, Reactions, Ball Control, Dribbling, and Composure.
  c. "Pace" - Acceleration, and Sprint Speed.
  d. "Passing" - Vision, Crossing, Free Kick Accuracy, Short Pass, Long Pass, and Curve.
  e. "Physical" - Jumping, Stamina, Strength, and Aggression.
  f. "Shooting" - Positioning, Finishing, Shot Power, Long Shots, Volleys, and Penalties.

- Instead of players being a point in the graph, a pie chart was instead used to show these 6 different categories. These was done in order to have a more understanding why these players are good as each player excels in their own different attributes. 

2. Who are the top earning players in FIFA 18 and does their overall scores reflect their salaries?

Top 10 highest earning players in order from highest paid to lowest are: 

 a. Christiano Ronaldo - 565,000 (Overall = 94)
 b. Lionel Messi - 565,000 (Overall = 93)
 c. Luis Suarez - 510,000 (Overall = 92)
 d. Gareth Bale - 370,000 (Overall = 89)
 e. R. Lewandowski - 355,000 (Overall = 91)
 f. T. Kroos - 340,000 (Overall = 90)
 g. L Modric - 340,000 (Overall = 89)
 h. S. Aguero - 325,000 (Overall = 89)
 i. Sergio Ramos - 310,000 (Overall = 90)
 j. K. Benzema - 295,000 (Overall = 86)
 k. E. Hazard - 295,000 (Overall = 90)
 
The prediction that their overall rating matches their given salaries were someone true, however we can see that it does not completely follow that trend. As both Ronaldo and Messi both have the highest salaries in the game however their overall score are different. As well as Bale although having a lower overall rating than Lewandowski, he is getting paid more. 

This was done using a graph the plots wages with their overall ratings. Here the ratings are displayed as circles. The larger the circle the higher their overall score is. 

3. Which countries produces the most proffessional players and which countries have the highest ranking overall (Good indicator who will do good in the FIFA world cup 2018)

- Using a meat map from Tableau's autogenerated Latitude and Longitude measurements, we can see how many players each country produces using the ID data. While to see the highest rating countries, we used the overall rating data.

The Top 3 countries who produced the most proffessional players are: 

 a. England
 b. Germany
 c. Spain 

Top 3 highest rating countries: 

 a. Portugal
 b. Argentina
 c. Brazil and Germany

England produces a lot of professional players that go on and play for professional football clubs, however they did not crack the top 3 in terms of overall ratings. While Portugal tops in terms of rating, most likely being skewed by outliers like Ronaldo, but they don't produce as many professional players as the other countries. 
    
4. Which are the highest ranking players on their respective positions?

In football, there are 11 players that usually share the field. The most basic formation/positions are as follows: ST, RW, LW, CM, CAM, CDM, RB, LB, RCB, LCB, GK.

ST - C. Ronaldo
RW - L. Messi & C. Ronaldo
LW - L. Messi & C. Ronaldo
CM - T - Kroos 
CAM - L. Messi
CDM - A. Vidal
RB - S. Ramos
LB - S. Ramos
RCB - S. Ramos 
LCB - S. Ramos 
GK - M. Neuer

Since there are a lot of different positions, and each player can play multiple positions. We have to create a filter that sorts them out to these individual positions. We have created a Parameter in order to do so. With this we can see who are the top players in that respected roles. Now you can build a super team in FIFA 18 if you wanted to using these data! 

    
5. Finally, the most important question everyone wants to know is: Who is better, Christiano Ronaldo or Lionel Messi?

Using the same graph as we used to answer question 1, we can see the break down of Christiano Ronaldo and Lionel Messi's stats. Overall they are pretty similar in rating, with Ronaldo beating out Messi by 1 point. But while taking a look at the data, it looks like Ronaldo beats out Messi in Physical attributes 82 to 62. 

     
## Challenges 

The main challenge I had for this project was combining different attributes into a more condensed and easier to read categories. This helped me tackle in my data visualization and analyzing since there were lesser numbers to compare. 

## Future Goals

If I had more time with this project, I would import more images such as club logos. I would also create a better Tableau Story instead of combining my worksheet into one dashboard. 

