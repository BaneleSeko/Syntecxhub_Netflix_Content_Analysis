# Netflix Content Analysis Using Python

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a Netflix dataset using Python and Pandas.

The analysis explores Netflix content by type, release year, genre, and movie runtime to identify patterns and trends within the dataset.

## Objectives

- Compare Movies and TV Shows
- Analyze Netflix content growth over time
- Identify the top 10 genres
- Analyze the distribution of movie runtimes
- Identify the top 10 release years
- Summarize key findings from the analysis

## Dataset

The dataset contains Netflix titles and information such as:

- Title
- Content type
- Director
- Cast
- Country
- Date added
- Release year
- Rating
- Duration
- Genre/category
- Description

## Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Visual Studio Code

## Analysis Performed

### 1. Movies vs TV Shows

Compared the number of Movies and TV Shows available in the dataset.

### 2. Content Growth Over Time

Analyzed the number of Netflix titles released each year and identified trends in content growth.

### 3. Top 10 Genres

Analyzed the genre/category information and identified the most common categories.

### 4. Movie Runtime Distribution

Extracted movie runtimes and analyzed their distribution using a histogram.

### 5. Top 10 Release Years

Identified the years with the highest number of Netflix titles.

### 6. Movies vs TV Shows Over Time

Compared the release patterns of Movies and TV Shows across different years.

## Key Findings

- Movies make up the larger share of titles in the Netflix dataset compared with TV Shows.
- 2018 was the peak release year, with 1,147 titles.
- International Movies was the most common category, with 2,752 titles.
- Dramas were the second most common category, with 2,427 titles.
- The average movie runtime was approximately 99.58 minutes.
- The median movie runtime was 98 minutes.
- Netflix content growth increased substantially from the 2000s onward, particularly during the 2010s.

## Project Structure

```text
Netflix_Content_Analysis_using_Python/
│
├── analysis.ipynb
├── netflix_dataset.csv
├── netflix_cleaned.csv
└── README.md