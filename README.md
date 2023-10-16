# NLP-Disaster-Tweets

## Overview
NLP-Disaster-Tweets is a project aimed at leveraging Natural Language Processing (NLP) techniques to analyze and categorize tweets related to disasters and emergencies. In an age where social media is a vital source of real-time information during crises, this project focuses on extracting valuable insights from the massive amount of tweet data generated during disasters.

### The main objectives of this project are:

1. Real-time Disaster Monitoring: Use NLP to identify and categorize tweets related to disasters and emergencies, enabling timely response and resource allocation.

2. Sentiment Analysis: Analyze the sentiment of disaster-related tweets to gauge public sentiment and emotional responses during crises.

3. Information Verification: Develop tools and models to verify the accuracy of information shared in disaster-related tweets, helping prevent the spread of misinformation.

4. Resource Coordination: Assist disaster relief organizations in coordinating resources and assistance based on real-time Twitter data.

5. Research and Insights: Contribute to a deeper understanding of the role of social media in disaster management through research and data-driven insights.

## Key Features
1. Tweet Classification: A classification model to categorize tweets into various disaster-related classes such as earthquakes, wildfires, floods, etc.

2. Sentiment Analysis: Tools and models for sentiment analysis to assess public sentiment in disaster-affected areas.

3. Information Verification: An information verification pipeline that checks the accuracy and credibility of tweet content.

4. Real-time Dashboard: A dashboard or interface for real-time monitoring and visualization of disaster-related tweets.

5. Research and Reports: Documentation and research reports on the project's findings and insights.

## Dataset Description
Each sample in the train and test set has the following information:

1. The text of a tweet
2. A keyword from that tweet (although this may be blank!)
3. The location the tweet was sent from (may also be blank)

### Columns
1. id - a unique identifier for each tweet
2. text - the text of the tweet
3. location - the location the tweet was sent from (may be blank)
4. keyword - a particular keyword from the tweet (may be blank)
5. target - in train.csv only, this denotes whether a tweet is about a real disaster (1) or not (0)
