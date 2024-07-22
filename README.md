# iRecommend : A book recommender

This project is a book recommendation website that utilizes collaborative filtering to suggest books to users based on their preferences and the preferences of other users.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Collaborative Filtering Details](#collaborative-filtering-details)

## Introduction

The Book Recommender Website is designed to provide users with personalized book recommendations. By analyzing the reading patterns and preferences of multiple users, the system suggests books that a user might like based on the ratings given by similar users.

## Features

- Personalized book recommendations
- User-friendly interface
- Search functionality for books
- List of popular books

## Technologies Used

- Python
- Flask
- Pandas and NumPy
- Scikit-learn
- HTML/CSS and JavaScript 

## Collaborative Filtering Details
The recommendation engine uses collaborative filtering to provide personalized book recommendations. Collaborative filtering is a technique used to filter or evaluate items by using the preferences of multiple users.

### Key Components:
- User-Item Matrix: A matrix where rows represent users and columns represent items (books). Each cell in the matrix represents the rating given by a user to a book.
- Similarity Calculation: Calculate the similarity between users based on their ratings. Common techniques include cosine similarity and Pearson correlation.
- Recommendation Generation: Generate recommendations by identifying books rated highly by similar users but not yet rated by the target user.
