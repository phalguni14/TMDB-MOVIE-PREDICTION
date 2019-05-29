# TMDB-MOVIE-PREDICTION

In a world... where movies made an estimated $41.7 billion in 2018, the film industry is more popular than ever. But what movies make the most money at the box office? How much does a director matter? Or the budget? For some movies, it's "You had me at 'Hello.'" For others, the trailer falls short of expectations and you think "What we have here is a failure to communicate."

In this competition, we're presented with metadata on over 7,000 past films from The Movie Database to try and predict their overall worldwide box office revenue. Data points provided include cast, crew, plot keywords, budget, posters, release dates, languages, production companies, and countries. You can collect other publicly available data to use in your model predictions, but in the spirit of this competition, use only data that would have been available before a movie's release.

Data Source: https://www.kaggle.com/c/tmdb-box-office-prediction/data Total number of movies:7398 Number of Attributes/Columns in data: 23 Data points include cast, crew, plot keywords, budget, posters, release dates, languages, production companies, and countries.

# Attribute Information:
1.Id - unique identifier for the Movie 2.genres - categories determining the type of the film 3.original_language 4.original_title - title of the film 5.production_companies - directly responsible for fundraising for the production 6.production_countries - countries involved in the production of the film 7.release_date 8.runtime - the time in which the movie is telecasted 9.status - determines whether the movie is released or rumoured 10.tagline - As a variant of a branding slogan, taglines can be used in marketing and advertising 11.keywords - the words mostly used in the film 12.cast - group of actors who make up a film 13.crew - group of people, hired by a production company, for the purpose of producing a film 14.revenue - total collections collected by the film

# Objective
Our task is to predict the international box office revenue for each movie. For each id in the test set, you must predict the value of the revenue variable.The calculated revenue is evaluated based on the Root-Mean-Squared-Logarithmic-Error (RMSLE) between the predicted value and the actual revenue.
