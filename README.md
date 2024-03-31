# Online Book Recommendation System using Content-based Filtering

This project consists of a Python script that implements an online book recommendation system using content-based filtering. It utilizes the pandas, numpy, matplotlib, and seaborn libraries for data manipulation, analysis, and visualization.

## Overview

The script loads a dataset containing information about books, including titles, authors, average ratings, ISBNs, language codes, and more. It then performs data exploration, statistical analysis, and visualization to uncover insights about book ratings, authors, and languages.

## Features

- Data Loading: The script loads the dataset using pandas and handles error-prone lines to ensure data integrity.

- Data Exploration: A comprehensive exploration of the dataset, including displaying the dataset, checking for null values, providing statistical information, and visualizing the distribution of average ratings.

- Content-based Filtering: Utilizes content-based filtering to recommend similar books based on a selected book title, generating a list of recommended books.

## Usage

1. *Dataset Loading*: The script loads the "books.csv" dataset and preprocesses it to ensure robust data analysis.

2. *Data Exploration*: Detailed data exploration to understand the characteristics and trends within the dataset.

3. *Content-based Filtering*: Employs content-based filtering to recommend books similar to a given book title.

## Model Export

The script exports the trained nearest neighbors model using pickle for deployment in production environments.

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Data Sources

The script uses the "books.csv" dataset, which contains information about books, their authors, ratings, and other attributes.
