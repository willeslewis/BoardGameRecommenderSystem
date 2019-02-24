# BoardGameRecommenderSystem

This repo contains data analysis and machine learning scripts utilizing data that I scraped from the [BoardGameGeek website](https://boardgamegeek.com/) using their XML2 api. While I believe in reproducible work, I have obscured my scraping notebook in order to protect their site from misuse from people adusting timing parameters in my program. When scraping, I made requests once every 10 seconds through their api which is in correspondence with their terms and conditions. Currently the repo has three subdirectories as follows:

- DataAcquisition: This is where I keep my scraping program on my local machine. On github this program is missing, but a notebook which I used to check that I scraped all the ratings and comments is included to give a sense of how I investigated data collection quality. The scraped dataset is not made available.

- DataAnalysis: This repo contains programs used to put the data into a form used by the matrix factorization (and later other) algorithm used to make recommendations. It also contains a notebook which provides exploratory analysis and insite into properties of the dataset

- RecommederSystems: This contains notebooks where I program and explore machine learning recommender systems. Currently it contains a matrix factorization recommender. Coming soon are a Neural Collaborative Autoencoder and a method based on likelihood ratios. See individual notebooks for any relevant references used.
