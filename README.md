# TED Talks Recommendation System

## Overview

This project is a Content-Based Recommendation System that recommends TED Talks based on user interests using Natural Language Processing (NLP).

## Dataset

The dataset contains TED Talks information including:

* Speaker Name
* Title
* Talk Description
* Posting Date
* Number of Views

## Project Workflow

### 1. Data Loading

Loaded the TED Talks dataset using Pandas.

### 2. Data Cleaning

* Removed missing values
* Selected relevant columns
* Combined title and description into a single text feature

### 3. Text Preprocessing

* Converted text to lowercase
* Removed stopwords
* Removed punctuation

### 4. Feature Engineering

Applied TF-IDF Vectorization to convert textual data into numerical vectors.

### 5. Similarity Calculation

Used Cosine Similarity to measure similarity between TED Talks.

### 6. Recommendation Engine

Generated recommendations based on user-provided topics and interests.

## Technologies Used

* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* Matplotlib

## Sample Input

Time Management and working hard to become successful in life

## Sample Output

Recommended TED Talks:

* Laura Vanderkam
* Philip Krinks
* Fang Ruan
* Chimamanda Ngozi Adichie
* Nirmalya Kumar

## Future Improvements

* Streamlit Web Application
* Deployment on Render
* Improved Recommendation Ranking
* User Interface Enhancements
