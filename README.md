# Video_Game_Data_Exploration
Data Source: https://www.kaggle.com/rush4ratio/video-game-sales-with-ratings

The ETL process was relatively straightforward. As ever there were some columns that were not needed for this analysis, namely the vote count.
I did note that the ciritc score and user score did not have the same base (critic score was base 10/out of 100). 
I had to change the user score from an object to a float so I could multiply the score by ten, allowing for easier comparison between user and critic scores. 

I also removed all the data ponts without all the data points, the majority of these games were much to old to hprovide useful insight anyway. 

I performed some very preliminary analysis using Python. It was mostly sanity checking the data checking the number of consoles etc. Along with doing some final data cleaning as I hadn't changed the year column to datetime.

I played some with Tableau but didn't find it especially useful for this dataset. I know tableau is powerful so I should learn to use it better.

The primary analysis was done with Excel, I used pivot tables to isolate data and make graphs from it. There were interesting insights to be found in which regions provide the best sales for companies and some historical sales data acros the CoD franchise.
