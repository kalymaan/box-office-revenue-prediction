# ![GA Logo](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 4: Choose Your Own Adventure

Problem Statement: In this data science project, our goal is to develop a regression model to predict movie revenue based on a comprehensive dataset containing movie attributes such as budget, genre, release date, and more. The dataset also includes information about production companies, cast, and crew. By accurately predicting revenue, our film production and distribution company aims to make data-driven decisions related to budget allocation, marketing strategies, and release plans. Success will be measured by the model's ability to minimize prediction errors and maximize the explained variance in revenue, ultimately improving the profitability of our movie releases.

Data Dictionary (from Original Dataset):
id: Unique identifier for each movie.
belongs_to_collection: Information about whether the movie belongs to a collection or franchise.
budget: The budget allocated for the movie's production.
genres: The genres associated with the movie.
homepage: The movie's official website, if available.
imdb_id: The IMDb identifier for the movie.
original_language: The original language in which the movie was made.
original_title: The original title of the movie.
overview: A brief overview or synopsis of the movie.
popularity: A measure of the movie's popularity.
poster_path: Path to the movie's poster image.
production_companies: Companies involved in the production of the movie.
production_countries: Countries where the movie was produced.
release_date: The release date of the movie.
runtime: The duration of the movie in minutes.
spoken_languages: Languages spoken in the movie.
status: The current status of the movie (e.g., released or in production).
tagline: A tagline or slogan associated with the movie.
title: The title of the movie.
Keywords: Keywords or phrases associated with the movie.
cast: Information about the movie's cast.
crew: Information about the movie's crew.
**Dummified some of the columns**

Modelling types:
- Multiple linear regression
- Lasso regression
- Random forest regression
- Deceision trees regression

Results:
- Baseline mean for y: 75022033.11 
- Predictions mean for y (Using random forest regressor): 72559718.4791077

Conclusion/Reccomendation:
- Able to fit various models, produced slightly overfit model that gave us .706 R2 on test with 0.87 on train
- Extract relevant/important information and dummify certain columns which were dropped such as cast & production_companies
- Tune more or try other regression models to try and improve performance

Sources:
- Referred back to previous lessons, labs and projects and various sites which are mentioned in the cells they're used