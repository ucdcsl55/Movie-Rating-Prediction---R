**Predicting movie rating using R**

Part 1

The raw data provided for this analysis consists of 651 movies which released prior to 2016. The data source comes from both IMDb and Rotten Tomatoes(RT) websites. Alongside with these 651 movies, there are 32 observation columns (i.e. variables) detailing the title of the movie, movie genre, runtime, MPAA rating, studio production, IMDB rating, RT audience rating, Oscar nominations, Actor/Actress/Director names and many more.
As this dataset consists of 651 randomly selected movies released prior to 2016. And based on the latest statistics in IMDb website, there are approximately 4 millions movie titles. In summary, the sample size is below 10% and may be relatively small to represent the population and also there was no information regarding about any specific sampling method used in this study.
Hence, this is more of an observational study instead of experimental. Any conclusions drawn can only be generalized to the population but cannot infer causality (as causality requires random assignment).

Part 2

As this movie dataset contained various characteristics information about the movie, it might be interesting to know how audiences rate the success of a movie. Do audience responded differently to different type of movies, the length of the movie, the year or month it’s released or more concerns over who casted in the movie? These information may provide some important insights about how popular the movie can be.
Popular movie is likely to attract bigger crowds which leading to higher ratings and hence generating more ticket sales which literally means better revenues to the production studio. In summary, every producers would wish to have better ratings for their movies as, to them this is the key driver to success.
My research question will assess if we can predict the success of a movie based on certain characteristics of a movie. A good prediction model would be valuable to the producers as they will know the likelihood of success of the movie before it is released to the public. In the dataset, there are three variables related to the scoring of a movie - IMDB rating vs two other variables from Rotten Tomatoes (i.e. Audience score/Critics score). In this analysis, I have pre-selected IMDb rating as the response/dependent variable*.

