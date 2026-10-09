# TripMate: Travel Planner Recommendation System

A recommendation system that suggests hotels and places for a trip based on the traveller's destination, budget and number of days.

**Status:** In progress (data and feature engineering done, recommendation engine being built)

## Problem
Planning a trip means checking many sites for hotels, places and costs. TripMate aims to give a personalised shortlist from a single input: source, destination, budget and days.

## What's done so far
- Designed my own dataset of hotels, places and transport options for 5 Indian cities (Goa, Mysuru, Gokarna, Manali, Jaipur)
- Data quality checks: null values, duplicates, category balance
- Exploratory data analysis (price and rating patterns)
- Feature engineering: one-hot encoding of categories, scaling of numeric columns

## In progress
- Content-based recommendation engine using cosine similarity, with budget and trip-duration filtering
- Evaluation of recommendation quality
- Streamlit demo

## Tech stack
Python, Pandas, Matplotlib, Scikit-learn, Jupyter

## Project structure
- `data/`: hotels, places and transport CSV files
- `day1.ipynb` to `day5.ipynb`: step-by-step notebooks

## Limitations
The dataset is small and hand-built, so results are for learning and demonstration, not real-world accuracy. Planned next step: scale up with real data.