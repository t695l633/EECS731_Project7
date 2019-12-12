# EECS731_Project7
Visualizations

# Instructions
Great stories and great visual effects
1. Set up a data science project structure in a new git repository in your GitHub account
2. Download any of the data sets from previous projects
3. Load the data set into panda data frames
4. Formulate one or two ideas on how storytelling and visualization would help describe the data set and establish additional value
5. Build three or more compelling visualizations
6. Document your process and results
7. Commit your notebook, source code, visualizations and other supporting files to the git repository in GitHub

# The Goal
The goal of this project was to show how by creating visualizations, you can tell a story through your data that might otherwise go unnoticed. By breaking down your data sets in specific ways you can extract useful information. In the real world it is important to create compelling visuals because you will lose your audience by simply showing them large quantities of data.

# Storytelling
The three stories I wanted to tell through my data are:

1. NFL games have gotten closer over time as better technology and recruitment methods allows coaches to pick the best players. Since the worst teams get the best draft pics each year, the teams are becoming more even over time.

2. By looking at the bar graph of a specific team, you can tell when certain events happened. I wanted to show that the Chiefs started doing much better with Alex Smith as their new quarterback. By creating a bar graph of Chiefs win ratio each season one can see a significant spike the season Alex Smith was brought on (2013).

3. The Patriots are better than the Chiefs, and by looking at the scores each team had over the past 5 seasons, one can see that the Patriots consistently out perform the Chiefs.

# Visualizations
The three visualizations I created are:

1. A scatter plot from matplot library of average score differences per season. I then graphed a line of best fit onto this plot to show the downward trend of differences, i.e. showing that teams are becoming more even. 

2. A bar chart (also from the matplot library) showing the win ratio of both the Chiefs and the Patriots each season since 1960. If you look at the chart for the Chiefs one can see that in 2013 the Chiefs win ratio spiked and stayed up through 2018. This was due in large part to the fact that the Chiefs drafted Alex Smith as their new quarterback.

3. A box plot showing the number of points scored by the Chiefs and Patriots in each game of their last 5 seasons. From this chart users can see that the Patriots have averaged higher scores in all 5 of the last 5 seasons. I used a Seaborn Group boxplot for this so that I could have box plots of the Chiefs scores per season right next to the Patriots scores per season.
