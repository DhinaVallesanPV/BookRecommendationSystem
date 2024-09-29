# BookRecommendationSystem
## Overview: The system recommends books based on user interests, using various models and data analysis techniques.

1. Data Cleaning and Preprocessing

Books Table: Removed image URLs, fixed missing and incorrect values, and cleaned publication years and ISBNs.
Users Table: Fixed invalid/missing ages, split location into City, State, and Country, and removed duplicates.
Ratings Table: Validated ratings and ISBNs, cleaned data, and removed duplicates.
2. Recommendation Algorithms

Popularity-Based: Suggested top-rated books overall, by location, or by author/publisher.
Average Weighted Rating: Recommended books based on a weighted formula considering ratings and averages.
Collaborative Filtering: Recommended books using user rating similarities (cosine similarity).
Correlation-Based: Found similar books using a correlation matrix based on ratings.
Nearest Neighbor: Used cosine similarity to find similar books.
Content-Based: Recommended books based on title similarities (TF-IDF).
Hybrid System: Combined collaborative and content-based methods for better recommendations.
3. Libraries Used

pandas, sklearn, matplotlib, seaborn, numpy, scipy, ipython-notebook.
