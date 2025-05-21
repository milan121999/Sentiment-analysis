# Sentiment-analysis
This project analyzes customer reviews of Panda Express across four U.S. states to uncover sentiment trends and improve customer experience. Using Natural Language Processing (NLP) techniques, the goal was to understand regional sentiment drivers and recommend business strategies.

## Introduction
Panda Express, the largest Asian fast-food chain in the U.S., has faced inconsistent customer satisfaction across locations. The project explores Yelp reviews to identify what customers value or dislike, enabling data-backed insights for improving service quality and targeted marketing efforts.

## Objective
* Analyze location-specific sentiments to uncover regional experience trends
* Evaluate the effectiveness of rule-based sentiment analysis vs. unsupervised topic modeling (BERTopic) to capture nuanced customer sentiment across locations.
* Provide actionable insights to enhance customer retention and brand perception

## Dataset
The dataset was sourced from the Yelp Open Dataset via Kaggle, filtered for Panda Express locations in Arizona, California, Indiana, and Florida. After cleaning, the data included ~1,840 reviews across 50 business IDs, featuring variables such as star ratings, review text, and user feedback votes.

## Python Libraries Used
* Pandas – for data cleaning and transformation
* NLTK & Scikit-learn – for basic sentiment analysis and text preprocessing
* BERTopic – for context-aware topic modeling and sentiment grouping
* Matplotlib & Seaborn – for visualizing sentiment trends and review patterns

## Conclusion
The analysis revealed a high concentration of 1-star reviews, primarily driven by negative experiences with service quality and order accuracy. BERTopic proved more effective than traditional polarity-based sentiment analysis in extracting context-aware insights, uncovering themes such as staff responsiveness, wait times, and food consistency. Based on these findings, we recommend targeted staff training, improved digital ordering systems, and promotional campaigns centered around top-rated menu items (e.g., Orange Chicken) tailored to location-specific feedback.

