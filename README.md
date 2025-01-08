# Spotify-2023-
![Uploading image.png…]()

Spotify is an audio streaming and media service provider owned by Daniel Ek and Martin Lorentzon since 2006 and listed through a holding company, Spotify Technology S.A on the NewYork Stock Exchange in the form of American depositary receipts.
Spotify offers digital copyright restricted recorded audio content including more than 100 million songs and 6 million podcast titles from record labels and media companies.

# Introduction 
This dataset was downloaded from kaggle and as a Spotify user myself,  I decided to make more sense of the dataset by cleaning and visualizing it. The aim objective of this project is to show my data visualisation skills in PowerBI.
Dataset herePICTURE

# Data Analysis Process
A series of steps must be carried out to interpret this information. Finding these procedure is crucial because each step is important in ensuring that the data is processed correctly to provide relevant and useful information. The steps I did in this process are listed below:

- Objectives
- Data Cleaning and Transformation 
- Dashboard Structure and Design in PowerPoint
- Data visualisation and Dashboard creation with PowerBI new visuals 
- Insights

## Objectives
This analysis will focus on
- g
-
-
-

## Data Cleaning and Transformation 
This data was thoroughly cleaned and transformed with Power Query Editor in PowerBI. The dataset contains columns and 4 rows and it was cleaned. The track_name data type was changed to text only had and removed errors in Streams column. In the key column, null values were replaced with "none" because it's a text data type. creating new columns from existing columns. The in_shazam_charts column had null values and was replaced with zero because it's a numerical type. A new date column was then created from released year, month and date in the format mm/dd/yyyy and I deleted the three existing columns.
PICTURE

I created a date table using DAX from the date column named "Calender" and sorted the MonthName and Day name so it will be in a  chronological order when used for visuals.
PICTURE

Then in the model view, I joined the date column in the Spotify dataset to the date in the calender table which is a one to many relationship.
PICTURE 

## Dashboard Structure and Design in PowerPoint
This was made by creating text boxes, using the right colour and gradient, and importing images and color. After that, I grouped and saved as a picture.
PICTURE 

## Data visualisation and Dashboard creation with PowerBI new visuals

For the visualisation, I imported the picture to PowerBI and used it as a dashboard to display my findings and communicate the analysis.
This report contains a single page. You can interact with the report here
PICTURE 

## Analysis and Insights
- KPIs
At the top, key performance indicators (KPIs) such as total streams, tracks and average streams are displayed.
The total Streams from 1930 to 2023 is 489 billion with the number of tracks on the streaming platform 952 and average streams per tracks being 514M.
PICTURE

- Streams by date
The trend shows a noticeable increase in streams in the 20s compared to the 19s. This indicates the widely use technology and innovation which wasn't well used in the earlier years. Nowadays people are more creative in the music/media industry
 PICTURE

- Tracks and Streams by Month
I used a table visual to compare the tracks and streams by each month. January produced the most tracks (133) with average number of streams (727.51M). However September had the most average streams (734.64M) while having produced low tracks (56) when compared to january and even May (126) tracks.
PICTURE

- Daily Streams for all tracks
Friday has the highest day stream for all tracks, followed by Thursday. This indicates that most listeners prefer to stream on Fridays.
PICTURE 

- Artist Most Streamed tracks
I used the new slicer visual to display the Top 1 streamed tracks and added the artist name. I also used a multi-row card to display the Top 1 track name, release date, number of streams, rows and key.
The Most Streamed track is Blinding lights, a song by the Weeknd with more than 3.7B streams.
PICTURE 

A new visual card also showed the music info of the Top 1 track
PICTURE 

- Top 5 Most Streamed tracks 
It is evident now that the most streamed track is Blinding lights but we also have the question of what comes next after it and by how many number of streams. Shape of your by Ed Sheeran is the 2nd most streamed track (3.6B), followed by Someone you loved (2.9B), Dance  Monkey (2.9B) and Sunflower (2.8B). It's observed that these songs have been topping the charts for years long before Blinding lights was produced.
PICTURE 





- View Interactive Dashboard here PICTURE
