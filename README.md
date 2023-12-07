# NETFLIX_Movies_And_TV_Shows_Clustering
## INTRODUCTION

### Problem Statement
This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine, in 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly trioled since 2010. The streaming service's number of movies has decreased by more than 2,000 titles ince 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

### DATASET INFORMATION
I have made project on Netflix Tv shows and Movies on the basis of pre-stored data, if a person wants to invest or starts his/her business in Entertainment industry this project will mainly helps in selecting the category for the type of content and it's categories. Here is the link to dataset which was used

link :- https://drive.google.com/file/d/1xJGllnE12mAggLuRo8b0oNSshUlG8GvF/view

### Graphs

The goal of this project is to analyze the Netflix catalog of movies and TV shows, which was sourced from the third-party search engine Flixable, and group them into relevant clusters. This will aid in enhancing the user experience and prevent subscriber churn for the world's largest online streaming service provider. And for that here are few of the charts from the presented project.
First is ratio between Tv shows and movies. 

![image](https://github.com/jaydeepjadav/Unsupervised-ML-project/assets/120647862/1c124e87-e535-42bb-9369-92cb780cfef5)

Here is another graph which shows the count of ratio between Tv shows and movies with respect to time they were released on Netflix.

![image](https://github.com/jaydeepjadav/Unsupervised-ML-project/assets/120647862/63ce4b8b-9fbf-4b9a-a2bc-56a8f83725b5)

Here are two graphs:-

1 - data of length of movies, that is duration of movies to get idea what should be the ideal duration of the movies

2 - data of average number of seasons Tv shows have.

![image](https://github.com/jaydeepjadav/Unsupervised-ML-project/assets/120647862/a5cb7735-7ccd-4dbb-8940-592436666149)
![image](https://github.com/jaydeepjadav/Unsupervised-ML-project/assets/120647862/25e2f700-44bd-467f-94ac-b40053973733)

From below graph it gets easier to understand in which month the average number of content has be released. 

![image](https://github.com/jaydeepjadav/Unsupervised-ML-project/assets/120647862/0b798ba2-659a-4508-818c-1e3f4ce521ed)

Movies: 30% of the movies are netflix originals and remaining 70% movies are added on netflix which were released by different modes.
TV shows: 50% of the TV shows are netflix originals and remaining 50% TV shows are added on netflix which were released by different modes.

![image](https://github.com/jaydeepjadav/Unsupervised-ML-project/assets/120647862/57b803a9-7015-44c0-9bb9-1e35ce6ba102)

### Conclusion
Netflix have ~70% of movies and 30% of TV_shows in 2019.

The report which shows that the number of TV shows on Netflix has nearly tripled since 2010.

Netflix focuses to add new content majorly towards end of current year and start of new year.

There are almost ~30% of netflix original movies and ~50 % TV-shows.

All of this insights will be neccesary for business development and SWOT analysis.

Conclusion for clustering.

I tried 5 models for ML i.e.

K-means clustering

Elbow curve

DBSCAN

K-means clustering shows that '6' will be optimum no of clusters with the silhoutte score of 0.468 with less negative values.

Thus K-means clustering will be best for this data set.

Cosine based recommender system was working really well.
