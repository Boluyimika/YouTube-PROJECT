## YouTube Data Analytics Project
## Overview
This project analyzes data from 100 different YouTube channels focused on data analytics. The data was collected using the googleapiclient.discovery library and includes information such as subscribers, total comments, and posts (videos) for each channel.

## Objective
The goal of this analysis is to rank YouTube channels in the data analytics niche based on three key metrics:

Subscribers (Followers): The total number of subscribers for each channel.
Comments: The total number of comments across all videos on each channel.
Posts (Videos): The total number of videos (posts) published by each channel.
## Data Sources
Channel Data: Contains information on the total number of subscribers, videos, and the channel title.
Video Data: Includes video-level statistics such as the number of likes and comments.
## Key Metrics
Top 10 Channels by Subscribers (Followers):

This ranking highlights the channels with the largest follower base, indicating their popularity within the data analytics community.


Top 10 Channels by Total Comments:

This metric shows the channels that generate the most engagement in the form of comments on their videos.


Top 10 Channels by Total Posts (Videos):

This ranks channels based on the total number of videos posted, reflecting their activity level.


## Methodology
Data was collected using the YouTube Data API via googleapiclient.discovery. The following steps were performed:

Data Collection: Data on subscribers, likes, comments, and video count was gathered for each channel.
Data Cleaning: Missing values were handled appropriately, with non-available metrics filled in as 0 where necessary.
Data Aggregation: Video-level statistics were aggregated at the channel level to compute total comments and video count.
Ranking: Channels were ranked based on the key metrics described above.
## Tools Used
Python: For data processing and analysis.
Pandas: For data manipulation.
Seaborn & Matplotlib: For data visualization.
YouTube Data API: For data collection using googleapiclient.discovery.
## Files
youtube_channel_stats.csv: Contains information on 100 data analytics YouTube channels.
youtube_video_stats_combined.csv: Contains video-level statistics for these channels.
SubscriberCount.png, TotalComments.png, TotalPosts.png: Visualizations for the top 10 channels based on subscribers, comments, and posts.
## Conclusion
This project provides insights into the most popular and active YouTube channels in the data analytics space. By ranking channels based on key metrics, it gives a clear understanding of channel engagement and influence in the data analytics community.

## Future Work
Extend the analysis to include other metrics like video likes and views.
Explore sentiment analysis on the comments to gauge audience reaction.
## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/Boluyimika/YouTube-PROJECT.git
