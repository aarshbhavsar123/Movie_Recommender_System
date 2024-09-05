# Movie Recommender System

## Overview

This Movie Recommender System is designed to suggest movies to users based on the content of movies they have already watched. It utilizes Python libraries such as **scikit-learn**, **pandas**, and **numpy** for data processing and model training. The recommendation system creates movie tags from various attributes, converts these tags into vectors, and suggests movies based on vector similarity.

## Features

- **Content-Based Recommendations:** Suggests movies based on the content of movies previously watched by the user.
- **Tag-Based Vector Representation:** Creates tags from movie attributes such as name, director, cast, description, keywords, and genre.
- **Similarity Measurement:** Recommends movies based on the smallest angle between vectors in an n-dimensional vector space.

## Libraries Used

- **scikit-learn**: For building and training the recommendation model.
- **pandas**: For data manipulation and preprocessing.
- **numpy**: For numerical operations and vector space calculations.

## Installation

To get started, ensure you have Python installed. Install the required libraries using pip:

```bash
pip install scikit-learn pandas numpy
```
## Usage
- Ensure your dataset includes details such as movie name, director, cast, description, keywords, and genre. Format your dataset as a CSV file or another format compatible with pandas DataFrames.
- Load the dataset and preprocess it to extract relevant content. Generate tags for each movie based on its attributes.
- Convert movie tags into vectors in an n-dimensional vector space and train the recommendation model. Save the trained model using pickle.
- To recommend movies, input a list of movies that the user has watched. Load the trained model and use it to recommend new movies based on vector similarity.
