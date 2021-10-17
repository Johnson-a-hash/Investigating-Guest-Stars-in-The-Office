# Investigating-Guest-Stars-in-The-Office
Apply the foundational skills in Introduction to Python and Intermediate Python courses to manipulate and visualize movie and TV data.

In these project, I’ll apply the skills I have learnt in the Introduction to Python and Intermediate Python to solve a real-world data science problem.
The Office is an American Mockumentary sitcom television series that depicts the
everyday lives of office employees in the Scranton, Pennsylvania, branch of the fictional
Dunder Mifflin Paper Company.
In this project, I will take a look at a dataset of The Office episodes, and try to
understand how the popularity and quality of the series varied over time. To do so, I
will use the following dataset: datasets/office_episodes.csv, which was downloaded
from Kaggle https://www.kaggle.com/nehaprabhavalkar/the-office-dataset?select=the_office_series.csv

This project forms part of the cirrculum of Data Insight's Data Science Program on Data Camp


Project task
1. Create a matplotlib scatter plot of the data that contains the following attributes:

Each episode's episode number plotted along the x-axis

Each episode's viewership (in millions) plotted along the y-axis

A color scheme reflecting the scaled ratings (not the regular ratings) of each episode, such that:

Ratings < 0.25 are colored "red"
Ratings >= 0.25 and < 0.50 are colored "orange"
Ratings >= 0.50 and < 0.75 are colored "lightgreen"
Ratings >= 0.75 are colored "darkgreen"

A sizing system, such that episodes with guest appearances have a marker size of 250 and episodes without are sized 25
A title, reading "Popularity, Quality, and Guest Appearances on the Office"
An x-axis label reading "Episode Number"
A y-axis label reading "Viewership (Millions)"

2. Provide the name of one of the guest stars (hint, there were multiple!) who was in the most watched Office episode.
