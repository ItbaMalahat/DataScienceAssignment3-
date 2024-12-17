# DataScienceAssignment3-
EDA on Netflix Movie and TV shows using Spark

Small Explanation: Netflix Dataset Analysis Using Apache Spark
This project uses Apache Spark in a Dockerized environment to perform Exploratory Data Analysis (EDA) on the Netflix dataset. The dataset contains information about TV shows and movies available on Netflix, such as title, type, release year, and more.

Process Overview
Environment Setup:

Use Docker to run a Spark container.
Pull the Spark Python Docker image (apache/spark-py) for running Spark jobs.
Dataset Preparation:

Download the Netflix dataset (netflix_titles.csv) from Kaggle.
Data Analysis:

Load the dataset into Spark using PySpark.
Analyze key metrics such as content type distribution, release year trends, and handle missing values.
Execution:

Use spark-submit to run the analysis script inside the Docker container.
Results:

Insights into Netflix content types (Movies vs TV Shows), release year trends, and overall data health.
