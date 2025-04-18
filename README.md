# ipl-data-analysis
IPL Data Analysis Using Apache Spark
This repository contains an end-to-end data analysis project focused on the Indian Premier League (IPL), leveraging Apache Spark for scalable data processing. The objective is to uncover insights related to matches, players, and team performances using big data technologies.

Introduction
The Indian Premier League (IPL) is one of the most popular T20 cricket leagues in the world. This project applies Apache Spark to analyze IPL datasets, including ball-by-ball events, match details, player performance, and team information. The goal is to derive meaningful insights such as top-performing players, bowling economy, dismissal trends, and scoring patterns across venues.

Data Sources
The analysis is based on the following datasets:

Ball-by-Ball Data: Captures granular delivery-level information for each match.

Match Data: Contains metadata such as team names, match dates, venues, and outcomes.

Player Data: Provides player information including nationality and play styles.

Player Match Data: Tracks individual performance for every match played.

Team Data: Includes information on IPL teams across seasons.

Setup
To get started, ensure the following prerequisites are met:

Apache Spark installed and properly configured.

Python environment with the PySpark library.

Data files (in CSV format) available locally or on cloud storage (e.g., Amazon S3).

Analysis
The project uses PySpark to load, clean, and transform the data. Key operations include:

Reading CSV files into Spark DataFrames.

Performing data cleaning and preprocessing.

Executing aggregations and transformations.

Applying SQL queries for complex analytics.

Key Insights
Top Scoring Batsmen Per Season: Identification of the highest run-scorers across IPL seasons.

Economical Bowlers in Powerplay: Detection of bowlers with the lowest economy rates in the first six overs.

Dismissal Types: Frequency distribution of various dismissal modes.

Scores by Venue: Analysis of average and peak team scores across different IPL venues.

Visualizations
Visualizations were created using Matplotlib and Seaborn to present data trends and comparisons. These include:

Bar charts of top batsmen by season.

Economy rate comparison of bowlers during powerplays.

Dismissal type frequencies.

Average and highest venue-wise scores.

Results
The analysis highlights key aspects of IPL performance data:

Consistent top run-scorers over different seasons.

Bowlers who have been effective during critical powerplay overs.

Common patterns in player dismissals.

Venues that typically see higher or lower scoring matches.

Dependencies
Apache Spark

Python

PySpark

Matplotlib

Seaborn
