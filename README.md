# NETFLIX-MOVIES-AND-TV-SHOWS-CLUSTERING

## Problem statement

This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.

In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

## Data Description
* show_id : Unique ID for every Movie / Tv Show

* type : Identifier - A Movie or TV Show

* title : Title of the Movie / Tv Show

* director : Director of the Movie

* cast : Actors involved in the movie / show

* country : Country where the movie / show was produced

* date_added : Date it was added on Netflix

* release_year : Actual Releaseyear of the movie / show

* rating : TV Rating of the movie / show

* duration : Total Duration - in minutes or number of seasons

* listed_in : Genere

* description: The Summary description

##Data Preprocessing & Feature engineering

1. Checking duplicate values
2. Handling null values
3. date_added columns
4. listed in column

## Exploratory data analysis

1. Understanding what type content is available in different countries
2. Is Netflix has increasingly focusing on TV rather than movies in recent years.
3. Clustering similar content by matching text-based features

## text preprocessing using NLP
1. Word tokenization
2. Punctuation removal
3. Stopwords removal 
4. Stemming
5. Text vectorization

# Dimensionality reduction using PCA

# using wordcloud to find popular geners

## Clustering
1. K-means clustering
2. Hierarchial clustering - Agglomerative clustering

# Topic modeling using LDA

## CONCLUSIONS :
1 . Exploratory Data Analysis
* Majority of content avaiable on Netflix is Movies.
* Growth in the number of movies on Netflix is much higher than tv shows.The highest number of movies and tv shows got added in 2019 and 2020
* October, November, December, and January are months in which many shows and movies get uploaded to the platform.
* Most of the content gets uploaded in the beginning and the middle of the month.
* United States and India are the top countries that produce all of the available content on the platform.
* TV-MA tops the charts, indicating that mature content is more popular on Netflix
* Top Genres on Netflix are found to be : Drama, Comedy, Documentary, Action and Adventure, Romance etc.
2. Analysis of Content produced in different countries
* The United States is a leading producer of both types of content which is obvious as Netflix is US Based company. It is followed by India where most of the content is in the form of movies
* Drama is the most produced genre in a lot of Non-English speaking countries
* Comedy is the most produced genre in English speaking countries like United States of America, United Kingdom and Canada
* Drama and Comedy are the most produced genres in the top countries with exceptions of Japan and South Korea
* Japan is the biggest producer of Anime. Anime is also the most produced in genre in Japan
3. Is Netflix has increasingly focusing on TV rather than movies in recent years.
* We have observed that TV shows signed have been higher than movies in 2016.
* While the no of movies signed were higher, it can be seen that the TV shows signed per year is catching up with the movies signed year by year.
4. Clustering
* k=8 is found to be an optimal value for clusters with highest silhouette score of 0.909 using which we grouped our data into 8 distinct clusters.
* Using dendograms and comparing various distance thresholds, a distance of 20 produced the highest silhouette score of 0.90 with 8 clusters produced the highest silhouette score of 0.90 with 8 clusters
.

# Topic Modelling
Latent Drichlet Allocation is used to model textual data[description, genres, directors and cast] into topics
Seven topics are found to be the most suitable upon comparing Coherence Scores for different topic numbers
The Topics and corresponding top words are given down below:
1. Topic 1

* Comedy
* Drama
* Romance
* Love
* Life

2. Topic 2

* Documentary
* Music
* World
* Seri
* Reality

3. Topic 3

* Drama
* Action & Adventure
* Thriller
* Young
* Family

4. Topic 4

* Crime
* Drama
* Murder
* Thriller
* Comedy

5. Topic 5

* Family
* Comedy
* Kids
* School
* Friend

6. Topic 6

* Action & Adventure
* Drama
* Crime
* Comedy
* Team

7. Topic 7

* Comedy
* Special
* Stand
* anime
* power








