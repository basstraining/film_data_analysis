![logo](Happy-Sad-Theatre-Masks.jpg "Two Masks")

# Analysis of ROI and Markets in Film

## Overview
This analysis takes data from IMDb and The Numbers and explores relationships between types of movies and their financials to find out what makes a movie successful. The goal of this study is to provide a hypothetical business with concrete recommendations for the new movie production studio they rolled out.

Through the data and statistical analysis, it is clear that with ROI (Return on Investment) as the main KPI, certain genres consistently perform better than others and certain characteristics of those genres drive strong ROI.


## Business Understanding
$$\dfrac{Total Gross - Production Budget}{Production Budget}=ROI$$

The use of ROI allows for variability in the budget of a given film and focuses on consistent financial gain for the film studio. This appeals to a long term approach that minimizes risk and maximizes returns over the course of many films.

## Data Understanding
The IMDb data was a zipped SQL Database and The Numbers data came as a zipped csv file. From IMDb, the analysis used columns containing data on movie name, start year, runtime in minutes, genres, average rating, and total number of votes. From The Numbers dataset, the analysis used production budget, domestic gross, and worldwide gross.

## Data Preparation
In order to prepare the data for analysis, many columns wer dropped, outlier ROI movies were removed (kept 1%-95%) and only movies with over 5000 votes on IMDb were used. In order to conduct genre specific analysis, sub-dataframes were created that contained movies that were related to that dataframe's genre. Finally, we grouped the selected genres into two dataframes for general movie type, light and dark films.

## Analysis and Recommendations
#### The two types of markets targeted are:
- Audiences interested in Lighthearted films
    - Musical
    - Animation
    - Family
- Audiences interested in Dark or Heavy films
    - Horror
    - Mystery
    - Thriller
  
#### The suggested runtimes for these categories:
- Dark Films: 80-100 minutes
- Light Films: 140-160 minutes

#### Finally, there was a statistically weak correlation between the average audience rating of a given film and its ROI, showing that the quality of a given film is less important than the quanitity of these films being made when it comes to optimizing for ROI.

## Conlusion and Next Steps
- 10 year plan: after dozens of successful films, we can begin to make crossover films between the movie types to target an audience that watched light movies when they were younger but are older and have different tastes
- Research on franchises specifically
	- Do sequels of movies that perform well have higher ROI% than the normal film
- Further: naikling ndown specific percentages for movie creation

## Repo Structure
- Data
- Images
- Notebooks
- Presentation.pdf
- Final.ipynb







