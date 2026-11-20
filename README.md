# Amazon Prime TV Shows and Movies Analysis

## Project Overview
This project focuses on analyzing the Amazon Prime Video content library using Python and data visualization techniques.

The analysis explores movies and TV shows based on release year, genres, age certifications, runtime, production countries, IMDb ratings, IMDb votes, and TMDB ratings and popularity.

## Project Objectives
- Analyze the distribution of Movies and TV Shows.
- Identify popular genres and production countries.
- Explore content release trends over the years.
- Analyze age certifications and content ratings.
- Understand the relationship between ratings, popularity, and audience engagement.

## Dataset Information
The project uses two datasets:
- Titles Dataset – Contains information about movies and TV shows.
- Credits Dataset – Contains information about cast and crew.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Data Cleaning and Preparation
- Created copies of the original datasets.
- Removed duplicate records.
- Cleaned column names.
- Prepared datasets for exploratory data analysis.

## Exploratory Data Analysis (EDA)
Performed data analysis and visualization to understand content distribution, genre patterns, release trends, ratings, and popularity.

## Key Insights
## Key Insights

- **Content Distribution:** Movies make up the majority of the Amazon Prime Video content library, while TV Shows represent a smaller share.

- **Release Year Trends:** The number of titles increases significantly in recent years, with a strong concentration of content released during the 2010s and 2020s.

- **IMDb Ratings:** Most titles have IMDb scores concentrated around 6 to 8, indicating generally moderate to good audience ratings.

- **Movies vs TV Shows Ratings:** TV Shows have a higher median IMDb score than Movies in the box plot comparison.

- **Runtime Analysis:** Movies generally have longer runtimes than TV Show episodes.

- **Age Certification:** The content library includes different age-certification categories, showing that the platform offers content for different audience groups.

- **IMDb and TMDB Ratings:** IMDb scores and TMDB scores show a positive relationship, meaning titles rated highly on one platform tend to receive higher ratings on the other.

- **Audience Engagement:** The IMDb score and vote analysis shows that titles have varying levels of audience engagement, with many titles receiving fewer votes and some receiving substantially more.

- **Data Quality:** The original Titles dataset contained 9,871 rows and the Credits dataset contained 124,235 rows. After removing duplicates, the cleaned datasets contained 9,868 title records and 124,179 credit records.

- **Missing Values:** Some columns, especially seasons, IMDb scores, IMDb votes, and TMDB scores, contained missing values and required data-cleaning treatment.

- **Correlation Analysis:** The correlation heatmap shows a positive relationship between IMDb scores and TMDB scores. Other numerical variables have varying levels of correlation.

## Conclusion
This project provides insights into Amazon Prime Video's content library through data cleaning, exploratory data analysis, and visualization using Python.

## Project File
[View the Jupyter Notebook](Amazon_Prime_TV_Shows_and_Movies.ipynb)
