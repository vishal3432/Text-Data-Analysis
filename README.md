# YouTube Video Analytics  📈 🔍 Dashboard – Text Data Analysis

Overview

This project provides an interactive Power BI dashboard for analyzing YouTube video data. The dashboard visualizes key performance metrics, trends, audience engagement patterns, and sentiment analysis of comments. It supports decision-making for content strategy optimization and marketing impact evaluation.
This Power BI project provides an interactive dashboard for analyzing global YouTube statistics for 2023. It enables users to explore trends, top-performing content, and other key insights related to YouTube performance. 
  
 ![Dashboard Screenshot](https://github.com/vishal3432/Text-Data-Analysis/blob/b008b4f743d93289818742aeb9dd235946df722c/Youtube%20_Analysis_Dashboard.png)
  

---

Problem Statement

YouTube content creators and analysts often struggle to derive meaningful insights from large volumes of video performance data. Key challenges include:

Understanding which content performs best.

Identifying what drives audience engagement.

Analyzing viewer sentiment from comments.

Detecting patterns across categories, channels, and timestamps.



---

Solution

We built a comprehensive, interactive Power BI dashboard using preprocessed YouTube video data. This dashboard offers:

Visual summaries of top-performing videos and channels.

Detailed trend and correlation analysis.

Engagement and sentiment breakdowns using statistical plots and word clouds.

Insights based on metadata, views, likes, dislikes, comments, and timestamps.



---

Dataset

Name: US YouTube Trending Videos

Source: Kaggle Dataset – Trending YouTube Video Statistics

Scope: Contains metadata for thousands of trending YouTube videos in the US, including:

Video ID, Title, Channel, Category

Publish time and trending date

Views, Likes, Dislikes, Comments

Tags, Description, and Comment text




---

Key Features in the Dashboard

1. Top 5 Most Viewed Videos


2. Top Channels by Upload Count


3. Likes vs Dislikes Analysis


4. Rolling Views Over Time


5. Engagement Ratio Distribution


6. Correlation Heatmaps (Views, Likes, Comments)


7. Positive & Negative Word Clouds (from comments)


8. Category-wise Engagement & Like Ratios


9. Scatter and Box Plots for Exploratory Analysis




---

Tools & Frameworks Used

Power BI Desktop – for interactive dashboard design

Python (Pandas, Seaborn, Matplotlib, WordCloud) – for data preprocessing, sentiment analysis, and advanced visualizations

Jupyter Notebook – for exploratory data analysis and script development

Excel/CSV – for intermediate data handling and shaping



---

How It Works

1. Data Cleaning & Preprocessing (Python):

Removed duplicates, missing values

Extracted engagement metrics

Performed text cleaning and sentiment labeling



2. Visualization & Modeling:

Built key visual elements using Power BI and embedded Python visuals.

Performed correlation analysis and time series tracking.

Generated interactive visuals and filters.



3. Export & Deployment:

Finalized dashboard as a shareable Power BI report image.

Available for further enhancements (e.g., drill-throughs, slicers, or real-time refresh with APIs).





---

Conclusion

This YouTube Analytics dashboard helps users discover impactful insights into video performance, audience behavior, and content strategy. It can be adapted or expanded for different datasets or real-time streaming dashboards.


