# Netflix Movies and TV Shows Analysis Dashboard

## Project Overview

The Netflix Dashboard is an interactive Tableau dashboard created to analyze Netflix movies and TV shows. It provides insights into the total number of titles, content distribution, release years, countries, ratings, and directors.

The dashboard helps users understand Netflix’s content library through interactive visualizations, KPI cards, bar charts, a geographical map, and filters. It highlights content trends and provides a clear overview of Netflix’s movies and TV shows.

## Business Problem

Netflix has a large collection of movies and TV shows from different countries, release years, and content categories. Analyzing this data manually can make it difficult to understand content distribution, identify popular content categories, and explore trends over time.

This project transforms raw Netflix data into an interactive Tableau dashboard that helps users explore the content library and identify meaningful patterns.

The dashboard focuses on:

* Total number of movies and TV shows
* Content distribution by type
* Trends across release years
* Country-wise distribution of Netflix titles
* Content ratings and audience classifications
* Directors associated with movies

## Objective of the Dashboard

The main objective is to build an interactive business intelligence dashboard that provides a clear overview of Netflix’s content library and helps users analyze movies and TV shows efficiently.

The dashboard aims to:

* Compare the number of movies and TV shows available in the dataset.
* Identify the countries contributing the highest number of titles.
* Analyze content trends across different release years.
* Understand the distribution of movies and TV shows by rating.
* Identify directors with the highest number of movies in the dataset.
* Enable interactive exploration through content-type filters.

## Tools & Technologies

* Tableau Desktop – Dashboard development and data visualization.
* Netflix Titles Dataset (CSV) – Source data for movies and TV shows analysis.
* Calculated Fields – KPI calculations and aggregated metrics.
* Data Visualization – KPI cards, bar charts, highlight tables, pie charts, and geographical maps.
* Interactive Filters – Filtering content by movie and TV show type.

## Data Source

Source: netflix_titles.csv

The dataset contains approximately 8,807 rows and 14 fields related to Netflix movies and TV shows.

The dataset includes information about:

* Show ID
* Type (Movie or TV Show)
* Title
* Director
* Cast
* Country
* Date Added
* Release Year
* Rating
* Duration
* Listed In (Genre/Categories)
* Description

The dataset was connected to Tableau Desktop and used to create visualizations for exploring Netflix’s content library.

## Features / Highlights

A. Key Performance Indicators (KPIs)

The dashboard displays the following key metrics:

* Total Titles: 8,807
* Total Movies: 6,131
* Total TV Shows: 2,676
* Total Countries: 746
* Average Release Year: Approximately 2014

These KPIs provide a quick overview of the number and composition of titles in the dataset.

Note: Total Countries and Average Release Year are based on the values displayed in the dashboard. The country count may represent distinct country entries or another calculated measure, depending on the Tableau calculation used.

B. Top 10 Years Analysis

A highlight table compares the number of movies and TV shows across the top release years.

This visualization helps users:

* Compare movie and TV show releases across years.
* Identify years with higher content counts.
* Understand differences in the distribution of movies and TV shows over time.

C. Top 20 Countries by TV Shows

A geographical map displays countries with a high number of TV shows.

This visualization helps users:

* Explore the geographical distribution of TV shows.
* Identify countries contributing more TV show titles.
* Compare content distribution across different locations.

D. Number of Shows by Type

A pie chart compares movies and TV shows in the Netflix dataset.

The chart highlights the difference between the two content types and shows that movies make up the larger share of the dataset.

E. Countries with a High Number of Shows

A bar chart ranks countries based on the number of Netflix titles.

The visualization helps users:

* Identify countries with the highest content counts.
* Compare title distribution across countries.
* Understand the geographical concentration of Netflix content.

F. Movies and TV Shows Rating Analysis

A bar chart displays the distribution of titles across different content ratings, including TV-MA, TV-14, TV-PG, R, PG-13, TV-14 and other available rating categories.

This visualization helps users understand how Netflix titles are distributed across audience classifications.

G. Top Directors by Movies

A bar chart displays directors with high movie counts in the dataset.

It helps users:

* Identify directors associated with multiple movies.
* Compare the number of movies linked to different directors.
* Explore director-related patterns in Netflix’s content library.

H. Interactive Filters

The dashboard includes a content-type filter with options for:

* All
* Movie
* TV Show

This filter allows users to explore the dashboard by content type and compare the available metrics and visualizations.

## Key Insights

The dashboard provides the following insights:

* Content Distribution: Movies account for a larger share of the dataset than TV shows.
* Total Content: The dataset contains 8,807 titles, including 6,131 movies and 2,676 TV shows.
* Release-Year Trends: The highlight table makes it possible to compare movie and TV show counts across release years.
* Geographical Distribution: The country map helps identify locations with higher numbers of Netflix titles and TV shows.
* Content Ratings: The rating chart shows how titles are distributed across different audience classifications.
* Director Analysis: The director chart highlights individuals associated with multiple movies in the dataset.
* Interactive Analysis: The content-type filter allows users to explore movies and TV shows separately.

## Dashboard Components

The dashboard combines multiple visualizations to present the analysis in a single view:

* KPI cards for key metrics
* Highlight table for release-year analysis
* Geographical map for country-wise distribution
* Pie chart for movie versus TV show comparison
* Bar chart for country-wise title counts
* Bar chart for content ratings
* Bar chart for director analysis
* Interactive content-type filter

## Skills Demonstrated

This project demonstrates the following data analytics skills:

* Data visualization using Tableau
* Connecting and exploring CSV datasets
* Data aggregation and KPI creation
* Calculated fields in Tableau
* Geographical data visualization
* Comparative and trend analysis
* Interactive dashboard design
* Business insights and analytical storytelling

## Conclusion

The Netflix Movies and TV Shows Analysis Dashboard provides an interactive overview of Netflix’s content library. By combining KPI cards, charts, a geographical map, and filters, the dashboard makes it easier to explore content distribution by type, release year, country, rating, and director.

This project demonstrates the use of Tableau to convert raw data into meaningful visual insights and develop an interactive dashboard for data exploration and reporting.

