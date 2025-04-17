📊 Twitter Analytics Dashboard
This project focuses on analyzing and visualizing Twitter data using Power BI. It delivers insights into tweet engagement, user interaction types, media views, and performance patterns over time, helping stakeholders understand trends and effectiveness in social media activity.

🚀 Project Objectives
Analyze tweet-level engagement metrics such as likes, retweets, replies, impressions, and clicks.

Understand how users interact with tweets through media, hashtags, profile views, and URLs.

Segment tweets based on categories such as link content, hashtag usage, and media presence.

Implement conditional visualizations that respond to tweet content and engagement thresholds.

Filter visuals based on time windows, tweet characteristics, and contextual relevance.

🛠️ Tools Used
Power BI Desktop

DAX (Data Analysis Expressions)

Twitter Engagement Dataset

✅ Tasks Performed
📌 KPIs (Card Visuals)
Sum of Media Views

Overall Impressions on the Post

Engagement Rate

Count of Tweets Engaged

📈 Gauges
Sum of Likes

Max of Retweets

📊 Bar & Column Charts
Sum of URL Clicks by Tweet (Clustered Bar)

Sum of Replies, Retweets, and Likes by Tweet Category (Clustered Column)

Sum of Hashtag Clicks, URL Clicks, and User Profile Clicks by Tweet (Clustered Bar)

Sum of Total Clicks by Click Type and Tweet

📉 Line Charts
Sum of Impressions by Week

Count of Tweets by Week (Also in Bar Format)

📋 Pie Chart
Distribution of Hashtag Clicks, URL Clicks, and User Profile Clicks

📦 Grouped Comparison Charts
Sum of Media Engagements and Media Views by Week (Clustered Bar)

📂 Advanced Logic-Based Visuals
🧠 Conditional Visualization: Tweet Category
Tweets were classified into:

Tweets with Links

Tweets with Media

Tweets with Hashtags

Other

Based on SEARCH(), CONTAINSSTRING(), and click metrics.

⏱️ Time-Based Conditional Graph
A visual comparing replies, retweets, and likes was shown only if tweets satisfied all of the following:

Media Engagement > Median

Media Views are Even

Tweet Text Length > 20

Tweet does not contain the letter 's'

Posted between 7–11 AM IST or 3–5 PM IST

Months: June to August 2020

Date: Odd-numbered

A card visual displays an appropriate message if no tweets satisfy these conditions, such as:

"The graph is empty because no tweets meet the conditions."
"The graph is empty because the word count is less than 40."

🧩 Filters and Interactivity
Month Selection slicer (June, July, August, etc.)

Dynamic text cards that guide users based on tweet content filters

Visual-Level Filters for specific graphs (e.g., filtering on a measure ShowTweetInGraph = 1)

📍 Key Insights
High media views do not always correlate with high user engagement.

A significant proportion of clicks are through URLs and hashtags.

Tweet engagement varies heavily by day of the week and time of posting.

Complex conditions significantly reduce the pool of tweets for deeper analysis.

🧠 Learnings
Advanced DAX for logical filtering

Time-zone conversion in Power BI

Conditional visuals and fallback messaging

Interactive dashboard storytelling

