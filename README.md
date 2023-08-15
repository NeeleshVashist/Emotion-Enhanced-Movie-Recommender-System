# Emotion-Enhanced-Movie-Recommender-System
Emotion-Enhanced Movie Recommender System is a project developed by Team PyCoders for the AML 3204 - Social Media Analytics course. The project focuses on creating a personalized movie recommendation system using Collaborative Filtering and Hybrid Recommender techniques. It also integrates sentiment analysis of YouTube comments to enhance the user experience.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Methodology](#methodology)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [Acknowledgments](#acknowledgments)

## Introduction

Emotion-Enhanced Movie Recommender System is a recommender system project designed to provide users with personalized movie recommendations based on their preferences and emotions. It leverages collaborative filtering and hybrid techniques to suggest movies to users. Additionally, it incorporates sentiment analysis of YouTube comments related to movies to enhance the recommendations.

## Features

- Collaborative Recommender System: Utilizes collaborative filtering techniques to make movie recommendations based on user-item interactions.
- Hybrid Recommender System: Combines collaborative filtering predictions with sentiment-driven personalization from YouTube comments' sentiment analysis.
- Sentiment Analysis: Incorporates TextBlob and VADER sentiment analysis to understand viewer emotions from YouTube comments.
- User Engagement Enhancement: Provides movie recommendations that resonate emotionally with users, enhancing their overall experience.

## Methodology

The project's methodology includes the following key steps:

1. Data Preparation: Gathering and cleaning movie ratings, metadata, and YouTube comments.
2. Collaborative Recommender System: Implementing matrix factorization, specifically Singular Value Decomposition (SVD), for prediction.
3. Sentiment Analysis: Using TextBlob and VADER to analyze sentiments of YouTube comments related to movies.
4. Hybrid Recommender System: Combining collaborative predictions with sentiment scores to create a personalized recommendation system.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- Libraries: pandas, numpy, scikit-learn, nltk, textblob, vaderSentiment, google-api-python-client
- Jupyter Notebook (I used Jupyter Notebook in this Project)

### Installation

Clone the repository:

   ```bash
   git clone https://github.com/your-username/MovieInsightsHub.git
   ```

### Usage
Follow the installation steps.
Run the main code to execute the recommendation process.
View the generated recommendations and their sentiment-based analysis.

### Contributors
- Neelesh Vashist
- Rohit Kumar
- Mukul Bisht
- Saurabh Singh

### Acknowledgments
We extend our gratitude to Professor Mohammad Saiful Islam for his valuable guidance and insights throughout the project.