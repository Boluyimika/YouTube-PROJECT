## YouTube Data Analytics Project
## Table of content
1. [Overview](#Overview)
2. [Objective](#Objective)
3. [Metadata](#Metadata)
4. [Files](#Files)
5. [Key_Metrics](#Key_Metrics)
6. [Methodology](#Methodology)
7. [Workflow](#Workflow)
8. [Skills](Skills)
9. [ Visualizations](#Visualizations)
10. [Analysis](#Analysis)
11. [Insights_for_Actionable_Strategy](#Insights_for_Actionable_Strategy)
11. [Conclusion](#Conclusion)

## Overview
This project analyzes data from 100 different YouTube channels focused on data analytics. The data was collected using the googleapiclient.discovery library and includes information such as subscribers, total comments, and posts (videos) for each channel.

## Objective
The goal of this analysis is to rank YouTube channels in the data analytics niche based on three key metrics:
- Subscribers (Followers): The total number of subscribers for each channel.
- Comments: The total number of comments across all videos on each channel.
- Posts (Videos): The total number of videos (posts) published by each channel.
  
## Metadata
- Channel Data: Contains information on the total number of subscribers, videos, and the channel title.
- Video Data: Includes video-level statistics such as the number of likes and comments.
## Files
- youtube_channel_stats.csv: Contains information on 100 data analytics YouTube channels.
- youtube_video_stats_combined.csv: Contains video-level statistics for these channels.

## Key_Metrics

1. Top 10 Channels by Subscribers (Followers): This ranking highlights the channels with the largest follower base, indicating their popularity within the data analytics community.

2. Top 10 Channels by Total Comments: This metric shows the channels that generate the most engagement in the form of comments on their videos.

3. Top 10 Channels by Total Posts (Videos): This ranks channels based on the total number of videos posted, reflecting their activity level.


## Methodology
Data was collected using the YouTube Data API via googleapiclient.discovery. The following steps were performed:

- Data Collection: Data on subscribers, likes, comments, and video count was gathered for each channel.
- Data Cleaning: Missing values were handled appropriately, with non-available metrics filled in as 0 where necessary.
- Data Aggregation: Video-level statistics were aggregated at the channel level to compute total comments and video count.
- Ranking: Channels were ranked based on the key metrics described above.
## Workflow
1. Scraping Channel Data: Scrape subscriber counts, video counts, and engagement metrics from channel pages.
2. APIs for Comments: Use the YouTube Data API to fetch detailed comment metrics efficiently.
3. Data Cleaning: Deduplicate and preprocess scraped data for analysis.
4. Visualization: Use the cleaned data for creating the charts.

## Skills
### Web Scraping Skills
- Data Collection: To gather information about channels (e.g., subscribers, total posts, and comments) directly from websites.
- Tools: Python Libraries:
- BeautifulSoup: For parsing HTML and extracting specific data.
- Scrapy: For large-scale scraping tasks.
- APIs: YouTube Data API For data collection using googleapiclient.discovery

###   Automation: Writing scripts to scrape multiple pages or channels efficiently.
- Cleaning and Structuring Data:Organizing the scraped data into structured formats like CSV files 

### Data Analysis Skills
- Data Wrangling: Cleaning, structuring, and preparing the data for analysis.
Tools: Python (e.g., Pandas), Excel, or SQL.

- Exploratory Data Analysis (EDA):

   -Identifying key metrics like subscribers, comments, and posts.
   -Performing descriptive statistics to rank the top 10 channels.
###  Data Visualization Skills
- Visualization Tools: Libraries such as Matplotlib or Seaborn (used for the bar charts).
Creating clear, visually appealing charts to highlight trends and comparisons.
- Design Principles:Choosing appropriate chart types (horizontal bar charts for easy comparison).
Applying contrasting colors for better visual distinction.
- Labeling & Annotation: Adding clear titles, axis labels, and consistent color schemes to enhance interpretation.
  
### Critical Thinking & Insights Generation
-Comparison and Pattern Identification: Analyzing the relationships between subscribers, comments, and posts across the charts.
- Identifying outliers and trends like high engagement vs. low posting frequency.
  
- Insight Derivation:Translating raw data into actionable recommendations (e.g., engagement strategies for specific channels).
### Programming Skills
Python Programming: Data manipulation with Pandas.
Chart creation with libraries like Matplotlib, Seaborn, or Plotly.
Automation: Using Python scripts to extract, transform, and visualize data efficiently.

### Soft Skills
- Attention to Detail: Ensuring the visualizations align with the data correctly.
- Communication: Presenting complex data in a way that is easy for stakeholders to understand.
- Storytelling: Crafting a narrative that connects the metrics (subscribers, comments, and posts) to actionable insights.


  ## Visualizations
  ![SubscriberCount](https://github.com/Boluyimika/YouTube-PROJECT/blob/main/SubscriberCount.png?raw=true)
---
  ![TotalComment](https://github.com/Boluyimika/YouTube-PROJECT/blob/main/TotalComments.png?raw=true)
  ---
  ![TotalPosts](https://github.com/Boluyimika/YouTube-PROJECT/blob/main/TotalPosts.png?raw=true)
---
Click [Here](https://github.com/Boluyimika/YouTube-PROJECT/blob/main/YouTubescript.ipynb) to check the code

## Analysis
### Chart 1: Top 10 Channels Ranked by Subscribers
**Observations**:

- freeCodeCamp.org dominates with the highest number of subscribers, far exceeding the others.

- CodeWithHarry follows as the second most subscribed channel but with a significant gap from the top.

- Other notable channels like Simplilearn and Programming with Mosh are well-subscribed, indicating popularity and relevance.
  
**Insights**:

- Channels with high subscriber counts likely have strong engagement, trusted content, and diverse audiences.
- New learners might gravitate towards these channels due to their established credibility.

  ---
  
### Chart 2: Top 10 Channels Ranked by Total Comments
**Observations**:

- codebasics leads in the number of comments, indicating strong audience interaction.
- Alex The Analyst and Simplilearn also perform well in terms of engagement.
- Channels like Pragmatic Works and CareerFoundry show decent comment activity, suggesting targeted audience interest.

  
**Insights**:

- High comment numbers reflect an engaged audience that actively participates in discussions, asks questions, or shares feedback.
- codebasics, despite not leading in subscribers, stands out as a community-driven platform.
  
### Chart 3: Top 10 Channels Ranked by Total Posts
**Observations**:

- Simplilearn has posted the most videos by far, indicating a consistent content strategy.
-Pragmatic Works is the second-highest, with substantial video uploads.
- codebasics maintains a strong content pipeline, ranking third.
  
**Insights**:

- A high number of posts suggest active and ongoing content creation, but this doesn’t always correlate with subscriber count or engagement.
- Channels with fewer posts but higher engagement (e.g., codebasics) might focus on quality over quantity.

  ---
###  Comparison Across Charts

- freeCodeCamp.org ranks highest in subscribers but isn’t a leader in comments or posts. This suggests a passive but broad audience base.
- codebasics excels in comments while maintaining a moderate number of posts, showcasing its focus on audience interaction.

- Simplilearn is highly active with the most posts, ranking well in subscribers and comments, indicating a comprehensive content and engagement strategy.

  ---

##  Insights_for_Actionable_Strategy:

1. High Subscribers, Low Engagement (e.g., freeCodeCamp.org): Leverage community-building initiatives like live Q&As, challenges, or interactive tutorials.
2. High Engagement, Moderate Subscribers (e.g., codebasics): Scale niche success by promoting content to untapped audiences through collaborations and advertisements.
3. Consistent Balance (e.g., Simplilearn): Reinforce balanced strategies with periodic audience surveys or tailored series based on trends.
   
## Conclusion
This project provides insights into the most popular and active YouTube channels in the data analytics space. By ranking channels based on key metrics, it gives a clear understanding of channel engagement and influence in the data analytics community.

## Future Work
Extend the analysis to include other metrics like video likes and views.
Explore sentiment analysis on the comments to gauge audience reaction.
## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/Boluyimika/YouTube-PROJECT.git
