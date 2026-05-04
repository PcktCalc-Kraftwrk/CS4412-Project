# CS-4412 Project Repository

## Instructions
Install Jupyter Lab/Jupyter Notebook onto your device. The browser version works fine since it was the one I used.
Download the Excel dataset and the most recent Notebook file onto your device
Upload both files into Jupyter

## This is a data mining project meant to analyze the box office of the top movies and check if there is a pattern between profit and ratings. It starts by combining the highest rated films and the highest grossing films into a single dataset before spliting it based on audience and critical reception. The various pairings of general and critical ratings are treated as their own indiviual datasets, and these datasets are used for bar graph meant to compare the box office of each film instance. By having a direct look at how much money movies audiences loved but critics hated with movies audiences hated but critics loved, we can see which demographic has a stronger impact on a film's profit.

## So far, I have established that profit and reception of the average movie is quite respectable but has become bloated by mega-blockbusters for all audiences and specialized high-class films. The former catagory produces films where groups of people can watch it over and over again without appricating the finer details, while the latter holds cinematic masterpieces that nobody bothers to go out and see. In fact, based on my cluster calculations, these might be the three main types of movies; films for a specialized audience, films for a generalized audience, and films for a sophisticated audience. I might have to reformat this data to get less stretched results, possibly by retroactively applying inflation to older movies' box offices.

## Now that I have finsihed the implementation, I have to update some things. The main thing to bring up is that I got my clustering wrong. After looking over the centroids, I came to the conclusion that there are actually 4 clusters. One for highly praised films with low profits, one for moderately recieved and moderately profitable films, one for profitable films that hold a diverse range of opinions, and one for films that are both popular and profitable. If you noticed the emphasis on profits, that somewhat the point. Graphing profits against reception shows these clusters off the best. However, when you go compare the receptions against each other, the clusters fall apart but the centroids remain viable. ALso I tried to add in a decision tree but failed due to my lack of variables. Once I start to polish this for M4, that will be my main objective. 

## Team Info: Griffin Vines (Solo)

## Sources:

“Top Lifetime Grosses - Box Office Mojo,” Box Office Mojo, 2019. https://www.boxofficemojo.com/chart/ww\_top\_lifetime\_gross/?area=XWW //
GeeksforGeeks, “Data Preprocessing in Python,” GeeksforGeeks, Oct. 29, 2017. https://www.geeksforgeeks.org/data-analysis/data-preprocessing-machine-learning-python/ //
IMDb, “IMDb Top Rated Movies,” IMDb, 2019. https://www.imdb.com/chart/top/ //
J. Chen, “Seaborn Swarmplot Axis Interval Formatting,” Stack Overflow, Jul. 31, 2020. https://stackoverflow.com/questions/63196379/seaborn-swarmplot-axis-interval-formatting //
Rotten Tomatoes, “Rotten Tomatoes: Movies | TV Shows | Movie Trailers | Reviews,” Rotten Tomatoes, 2025. https://www.rottentomatoes.com/ //
Zach, “K-Means Clustering in Python: Step-by-Step Example,” Statology, Aug. 31, 2022. https://www.statology.org/k-means-clustering-in-python/ //
