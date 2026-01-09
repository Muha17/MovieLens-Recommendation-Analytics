# MovieLens-Recommendation-Analytics
An exploratory analysis and feature engineering project on MovieLens data to support personalized movie recommendation systems.

# Overview

This repository contains the analysis of the MovieLens dataset to understand user rating behavior and movie characteristics that influence preferences. The goal is to generate insights and engineer features that support the development of accurate and personalized movie recommendation systems.

The work focuses on data cleaning, feature engineering, and exploratory data analysis to simulate a real-world recommender-system analytics workflow.

# Business Problem

Recommendation platforms depend on understanding how users interact with content over time. Raw rating data often contains noise, bias, and limited contextual information, which can reduce recommendation accuracy.

This project addresses that challenge by transforming raw MovieLens data into structured features that improve personalization and relevance.

# Objectives

Clean and prepare user ratings and movie metadata

Engineer features that improve interpretability and modeling

Analyze genre, rating, and temporal patterns

Generate insights applicable to recommendation system design

# Dataset

Source: [MovieLens](https://drive.google.com/drive/folders/1hsSZ9SSepoj86lXBLZpYR_wdWvGP16s8?usp=sharing)

Data Includes: User ratings, movie titles, genres

Granularity: User–movie interaction level

# Feature Engineering

The following features were created to enhance analysis and modeling:

Release Year: Extracted from movie titles

Movie Age: Years since release

Number of Genres: Total genres associated with each movie

Top Genre: Primary genre per movie

Average Movie Rating: Mean rating per movie

Average User Rating: Mean rating per user (used for normalization)

# Key Insights

User ratings are concentrated between 3.0 and 4.0, indicating consistent and moderate behavior

Film-Noir, Mystery, Crime, and Documentary genres receive the highest average ratings

Horror consistently receives lower ratings

Number of genres has minimal impact on user ratings

Movies aged 51–100 years receive the highest ratings, with a decline for very old titles

# Application to Recommendation Systems

The engineered features and insights support:

Collaborative filtering via normalized user ratings

Content-based recommendations using genre and movie age

Improved similarity measurement between users and items

Reduced bias from individual rating behavior

# Tools & Technologies

Python (Pandas, NumPy, Matplotlib/Seaborn)

Jupyter Notebook

Git & GitHub

# Conclusion

This analysis demonstrates how structured feature engineering and exploratory analysis can significantly improve recommendation system inputs. The resulting insights and features provide a scalable foundation for building accurate, personalized movie recommendation models.
