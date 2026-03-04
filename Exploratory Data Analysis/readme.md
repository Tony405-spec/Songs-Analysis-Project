# Exploratory Data Analysis
This step focuses on analyzing the dataset of music tracks and their performance across various platforms, including streaming services, video sharing sites, and radio airplay. The dataset is structured to provide insights into track popularity, engagement metrics, and other relevant statistics.

## Steps
* Load Dataset: The dataset is loaded into a pandas DataFrame.
* Add Average Engagement Rate: A new column is created to calculate the average engagement rate based on selected engagement metrics.
* Create Sub-dataframes: The main DataFrame is filtered to create several sub-dataframes, each focusing on a specific aspect of music performance.

## Sub-dataframes Created
The following sub-dataframes are created from the main dataset:

* Music Streaming Services Dataframe: Contains streaming metrics from platforms like Spotify and Deezer.
* Video Sharing and Streaming Platform Dataframe: Focuses on YouTube metrics, including views and engagement rates.
* Short-form Video Content Platform Dataframe: Includes metrics from TikTok, such as posts, likes, and views.
* Radio Airplay Monitoring Dataframe: Contains data on radio airplay, including spins and airplay counts.
* Music Identification and Discovery Dataframe: Focuses on metrics from services like Shazam.
