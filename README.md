# netflix-movies-shows

## Problem Statement
This project aims to:

* Perform Exploratory Data Analysis (EDA).
* Understand the type of content available in different countries.
* Determine if Netflix has increasingly focused on TV shows rather than movies in recent years.
* Cluster similar content by matching text-based features.

## Project Summary

The goal of this project is to analyze the Netflix catalog of movies and TV shows, sourced from the third-party search engine Flixable, and group them into relevant clusters. This will aid in enhancing the user experience and prevent subscriber churn for the world's largest online streaming service provider, Netflix, which currently boasts over 220 million subscribers as of 2022-Q2. The dataset includes movies and TV shows as of 2019 and will be analyzed to uncover new insights and trends in the rapidly growing world of streaming entertainment.

## Business Context

This dataset consists of TV shows and movies available on Netflix as of 2019. The dataset, collected from Flixable, shows that the number of TV shows on Netflix has nearly tripled since 2010, while the number of movies has decreased by more than 2,000 titles. Integrating this dataset with external datasets such as IMDb ratings and Rotten Tomatoes can also provide many interesting findings.

## Project Workflow
* Data Preprocessing = Handled missing values, Conducted Exploratory Data Analysis (EDA).
* Content Analysis = Analyzed the type of content available in different countries, Investigated the focus on TV shows versus movies in recent years.
* Feature Engineering = Selected attributes: cast, country, genre, director, rating, and description, Used TFIDF vectorizer to tokenize, preprocess, and vectorize the values.
* Dimensionality Reduction = Applied Principal Component Analysis (PCA) to address the problem of dimensionality.
* Clustering = Constructed clusters using K-Means Clustering , Determined the optimal number of clusters to be 6 using the elbow method and Silhouette score analysis, Created clusters using Agglomerative Hierarchical Clustering, Determined the optimal number of clusters to be 7 by visualizing the dendrogram.
* Recommender System = Generated a similarity matrix using cosine similarity, Constructed a content-based recommender system to provide users with ten recommendations based on the type of show they watched.

## Conclusion 

This analysis revealed key insights into the Netflix catalog. Despite an increasing focus on TV shows, movies still dominate the platform. The clustering approach, leveraging attributes such as cast, country, genre, director, rating, and description, effectively grouped content into meaningful categories. The content-based recommender system, built using cosine similarity, offers personalized recommendations, enhancing user experience. Insights into country-specific content availability can guide strategic content acquisition and production, catering to diverse markets.

By leveraging advanced analytics and machine learning techniques, Netflix can continue to offer a superior streaming experience, ensuring sustained growth and competitive advantage in the entertainment industry.
