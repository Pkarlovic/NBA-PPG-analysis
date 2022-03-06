# NBA-PPG-analysis

For this Project, I take a look at what variable plays the largest part in the average points per game a player can score in the NBA. 

There is no question that the team which scores the most points in a game wins, an age-old answer to Sports. In this analysis we will be observing how the PPG (Points Per Game) relates to other statistics within an NBA game. 

# Gathering Data

Data is gathered by requesting an URL and parsing through the page to scrape statistical data on the statistics for 2020-2021 season.

We then narrowed down our data to variables which related to the amount of points a player scored throughout a game. 

In order to do this we made a quick basketball scraper function to gather data from basketball-reference.com

![image](https://user-images.githubusercontent.com/70538240/156904060-1511d21f-8336-41d6-8c7b-3103539a6f7c.png)

Overall, we found that there is a high correlation between points scored per game and the minutes played, field goals attempted and free throw attempted in a game. I highly recommend checking out the notebook file for a walkthrough of the data analysis. 

