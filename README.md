# Movie Statistics

## Dataset Description

This dataset provides comprehensive movie statistics compiled from multiple sources, including Wikipedia (for details about movie titles, production dates, genres, runtime minutes, and director information), The Numbers (a reliable source for box office statistics), and IMDb (for average ratings, the number of votes, and other movie-related attributes). It offers a rich collection of information and insights into various aspects of movies. Researchers, movie enthusiasts, and data analysts can leverage this dataset for various purposes, including data visualization, predictive modeling, and a deeper understanding of the movie landscape.

## Metadata

This dataset contains the following information:
- Movie_title
- Production_date
- Genres
- Runtime_minutes
- Director_name (primaryName)
- Director_professions (primaryProfession)
- Director_birthYear
- Director_deathYear
- Movie_averageRating: Average rating given by online users for a particular movie
- Movie_numberOfVotes: Number of votes given by online users for a particular movie
- Approval_Index: A normalized indicator (on a scale of 0-10) calculated by multiplying the logarithm of the number of votes by the average user's rating. It provides a concise measure of a movie's overall popularity and approval among online viewers, penalizing both films that got too few reviews and blockbusters that got too many.
- Production_budget ($)
- Domestic_gross ($)
- Worldwide_gross ($)

## Questions

In this Exploratory Data Analysis, I try to question:

What information can we learn from the dataset?
Is there any correlation between movie budgets and gross?
How has the movie industry grown over the years?

## Source

The dataset is from Alessandro Lo Bello at https://www.kaggle.com/datasets/alessandrolobello/the-ultimate-film-statistics-dataset-for-ml.
