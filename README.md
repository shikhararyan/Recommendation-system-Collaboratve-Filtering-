# Collaborative Filtering based Recommendation System

📚 This notebook implements a collaborative filtering-based recommendation system for book recommendations. It analyzes user-item interactions to suggest books that users might be interested in, thus enhancing personalized user experiences in the domain of book recommendation.

## Dataset Overview

The dataset used in this notebook includes information about books, users, and ratings. It consists of the following files:

- `Books.csv`: Contains information about books such as ISBN, title, author, publication year, and publisher.
- `Users.csv`: Includes information about users such as user ID, location, and age.
- `Ratings.csv`: Contains user ratings for various books.

## Preprocessing

The notebook performs preprocessing tasks such as handling missing values and duplicates in the dataset.

## Collaborative Filtering

Collaborative filtering is implemented to recommend books based on user-item interactions. It involves the following steps:

1. Filtering out users who have given ratings to books more than 150 times.
2. Selecting books that have received at least 50 ratings.
3. Creating a pivot table of UserID vs. Books with ratings as values.
4. Calculating cosine similarity between books to measure their similarity.
5. Implementing a function to recommend similar books based on a given input book.

## Usage

To use this notebook, follow these steps:

1. Load the dataset.
2. Preprocess the data to handle missing values and duplicates.
3. Implement collaborative filtering to recommend books based on user-item interactions.

## Dependencies

The notebook requires the following dependencies:

- NumPy
- pandas
- scikit-learn
