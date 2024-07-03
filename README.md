# YTCommentAnalysis

This repository contains code and resources for performing sentiment analysis on YouTube comments. Initially developed as part of an REU (Research Experiences for Undergraduates) project, this toolkit was designed to analyze sentiments related to the Venezuela-Guyana border dispute and Venezuelan refugees in Guyana. However, these tools can be adapted for a wide range of research topics. The goal of this project is to analyze the sentiments expressed in YouTube comments to understand public opinion on various topics. Specifically, this project was used to:

- Collect YouTube comments related to the Venezuela-Guyana border dispute and Venezuelan refugees in Guyana.
- Clean and preprocess the comments for analysis.
- Conduct sentiment analysis to determine the polarity and subjectivity of comments.
- Analyze the correlation between different sentiments and contextual factors.

About the REU Program:

As mentioned before, the code and resources in this repository were initially created as part of a Research Experiences for Undergraduates (REU) project titled "Misinformation in the Venezuela-Guyana Border Dispute and Its Impact on Sentiments Towards Venezuelan Migrants in Guyana." The project was developed at the Virginia Modeling, Simulation, and Analysis Center (VMASC), a part of Old Dominion University. The REU program is funded by the National Science Foundation, with the Summer 2024 program focusing on misinformation detection and analysis. Participants worked closely with faculty mentors and contributed to ongoing research initiatives or created their own projects. This program provided undergraduate students with the opportunity to gain hands-on experience in the field of data science.

Contributions:

Contributions to this project are welcome! If you have suggestions, improvements, or new features to add, please submit a pull request or open an issue.

Features:

- YouTube Data Collection: Scripts to scrape comments from YouTube videos using YouTube Data API.
- Data Cleaning and Preprocessing: Tools to clean and preprocess text data for sentiment analysis.
- Sentiment Analysis: Implementation of sentiment analysis using TextBlob.
- Visualization: Tools for visualizing sentiment distribution and correlation with contextual factors.

Project Overview:

You can complete this project locally or in Google Colab. To get started, follow the instructions below:

1. Clone the Repository: git clone https://github.com/your-username/YouTubeSentimentAnalysis.git
   
2. Install Dependencies: pip install pandas transformers torch textblob langdetect googletrans==4.0.0-rc1 seaborn matplotlib

3. Setup YouTube API:
   Obtain YouTube Data API credentials and set up the API key in your environment.

4. Run Data Collection:
   Use the provided scripts to collect YouTube comments related to your topics of interest.

5. Data Cleaning and Preprocessing:
   Clean and preprocess the collected comments using the provided tools.

6. Conduct Sentiment Analysis:
   Perform sentiment analysis on the preprocessed comments to determine their polarity and subjectivity.

7. Visualization and Analysis:
   Use the provided visualization tools to analyze the sentiment distribution and its correlation with contextual factors.
 
