# Video_Game_Data_Exploration
Data Source: https://www.kaggle.com/rush4ratio/video-game-sales-with-ratings

The ETL process was relatively straightforward. As ever there were some columns that were not needed for this analysis, namely the vote count.
I did note that the ciritc score and user score did not have the same base (critic score was base 10/out of 100). 
I had to change the user score from an object to a float so I could multiply the score by ten, allowing for easier comparison between user and critic scores. 

I also removed all the data ponts without all the data points, the majority of these games were much to old to hprovide useful insight anyway. 
