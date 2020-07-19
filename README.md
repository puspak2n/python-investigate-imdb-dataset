# python-investigate-imdb-dataset
Investigate and visualize imdb movies using python

Introduction
For this exercise, I am using the Imdb-movie dataset. In this dataset, there are list of movies between 1960 and 2015 with their box office collections, cast, genres, and many other details. Being a movie-buff, I am really excited to be working on this dataset.
Plot a histogram of Average Votes and see the distribution.
Find the biggest box office hits by inflation-adjusted Profit every year.
Find correlation between various fields to see if there is anything that comes out of it.
How does the Movie runtime changing over time? (Does any specific genre contributes to the shorter/longer runtime?).
Explore the Keywords field in the dataset to find patterns.
Try to find a correlation between budget and revenue every decade.
Find out the Top 5 Movie Genres by Gross Profit every Decade.



Conclusions
1) In this Analysis we looked at the biggest box office hits by inflation-adjusted Profit every year and the 1977 movie Star wars tops of the list.
2) Then we plotted the correlation between various fielmetrics abd cound that Budget seems to be highy correlated with revenue and also, the year seems to be negatively correlated to Movie runtime.
3) From the Movie runtime trend I found that, the Movie run times in most of the genres seems to be trending down or remained flat in the time period betwen 1960 -2015. "Actions", "Adventure and "Musical" genres seems to be trending downwards the most.
4) The Keywords wordcloud suggests thats there are many movies made by women directors, many moved are made based on Novels and New Your city appears prominately as a keyword in the dataset.
5) Fom the Scatter plot, I found the pattern across the 6 decades that, high budgeted movies seem to be generating more revenues barring a few outliers.
6) The Top 5 Movie Genres by Gross Profit every Decade suggests that Adventure movies have been the most profittable movie genres every decade. Also, the set of Top 5 movie genres have remained the same over the years. Another interesting insight from the dataset is, Science fiction genres has been catching up t the Animation categories and it could easily surpass the animation genres soon..
Assumptions
I have a made a few assumptions while analyzing the dataset:

1) the dataset includes all the movies in the 1965-2015 time period.
3) Inflation adjusted number changes over time, so, it may look diffferent when the dataset is updated with new movies/ years.
3) It's difficult to determine wheather a movie is proffitable based on the dataset. We can only estimate teh gross profit but, we need more details to get the Net profit because some of the expenses and taxes paid etc may not be included in the budget metric.
