# Movies-Data-Visualization
## Summary 
I analyzed a data set of movies from 1884 - 2018. I removed movies from below 1990 since most movies in the dataset were produced from the 1990s onwards. I chose to use this dataset to create visualizations because I was most interested in trends of genres of movies that are watched over time. The important columns I used were revenue, budget, title, date, and profit, which I calculated by subtracting budget from revenue. 

## Insights

1) The most profit is generated in June which makes sense since June is the peak of summer and more people have time to watch movies. January, February, August, and September have lower profit generated. Historically, these months are known as dump months. Dump months are the months when movies with lower commercial and critical expections are released. This explains why profit is low for these month. 
<p align="center">
  <img src="https://github.com/sskenny/Movies-Data-Visualization/blob/master/images/AverageProfitGeneratedEachMonth.png"
" title="Average Profit Generated Per Month">
</p>


2) This graph shows the amount of male and female actors in the top profit movies. There are more male actors in almost all movies. Beauty and the Beast has more female actors than male actors. The gender data set had many missing values so the data without missing values shows this pattern. 
<p align="center">
   <img src= "https://github.com/sskenny/Movies-Data-Visualization/blob/master/images/CountActorGenderInTopProfMovie.png"
title="Count of Male and Female Actors in Most Profitable Movies">
</p>


3) The production of documentary films has been continuously increasing from 1990 to 2014. It has increased about 6% and this could be because of new technology, better storytelling, and more interesting subjects.  
<p align="center">
   <img src= "https://github.com/sskenny/Movies-Data-Visualization/blob/master/images/DocumentaryMovieProductionTrend.png"
title="Documentary Movie Production Trend">
</p>


## Data sets
### movies metadat csv: https://www.kaggle.com/rounakbanik/the-movies-dataset#movies_metadata.csv
### credits csv: https://www.kaggle.com/rounakbanik/the-movies-dataset#credits.csv

## Tools And Libraries Used
1. Jupyter Notebook
2. Seaborn, Pandas, Numpy, DateTime
