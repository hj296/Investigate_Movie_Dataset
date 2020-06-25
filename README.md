# Project: Investigate TMDb Movie Database

The analysis shown over here has been performed on TMDB movies dataset (a subset of IMDB dataset on Kaggle)

The dataset contains information about 10K+ movies which includes various important attributes related to the movies, such as popularity, release year, genre, production company, budget_adj, revenue_adj and Profit (calculated field)

List of movies with ‘0’ budget or revenue are removed (as it may skew the data and such movies would be considered as outliers). That leaves us with 3855 rows of data out of 10866 rows. Even though many data are being excluded, the exclusion will help with the data investigation as budget and revenue are the main variables to be studied.

Few Question that can analysed from this data set -

> Which movies had the highest profit in each year?

> Is popularity of a movie related to the revenue being earned by the movie?

> Comparison between two production companies in terms of their revenues & number of movies released each year?

## Conclusion - 
For a movie to be successful it must have following criteria –

1. Average budget of the movie should be around 60 million dollars.

2. Anyone of these should be in the cast: Chris Pratt, Keanu Reeves, Christian Bale.

3. The movie should be directed by the any one of the following directors:
   Christopher Nolan, Colin Trevorrow, Joe Russo.

4. Genre must be: Action, Comedy, Drama, Adventure, Thriller.

## Limitations: -

> The budget and revenue column does not have a specific currency unit, it might be possible different movies have different budgets in different currency according to the country they are made in.

> Dropping the rows and columns with missing values might have also affected the analysis.
