# CS-4412 Project Repository

## This is a data mining project meant to analyze the box office of the top movies and check if there is a pattern between profit and ratings. It starts by combining the highest rated films and the highest grossing films into a single dataset before spliting it based on audience and critical reception. The various pairings of general and critical ratings are treated as their own indiviual datasets, and these datasets are used for bar graph meant to compare the box office of each film instance. By having a direct look at how much money movies audiences loved but critics hated with movies audiences hated but critics loved, we can see which demographic has a stronger impact on a film's profit.

## So far, I have established that profit and reception of the average movie is quite respectable but has become bloated by mega-blockbusters for all audiences and specialized high-class films. The former catagory produces films where groups of people can watch it over and over again without appricating the finer details, while the latter holds cinematic masterpieces that nobody bothers to go out and see. In fact, based on my cluster calculations, these might be the three main types of movies; films for a specialized audience, films for a generalized audience, and films for a sophisticated audience. I might have to reformat this data to get less stretched results, possibly by retroactively applying inflation to older movies' box offices.

## Now that I have finsihed the implementation, I have to update some things. The main thing to bring up is that I got my clustering wrong. After looking over the centroids, I came to the conclusion that there are actually 4 clusters. One for highly praised films with low profits, one for moderately recieved and moderately profitable films, one for profitable films that hold a diverse range of opinions, and one for films that are both popular and profitable. If you noticed the emphasis on profits, that somewhat the point. Graphing profits against reception shows these clusters off the best. However, when you go compare the receptions against each other, the clusters fall apart but the centroids remain viable. ALso I tried to add in a decision tree but failed due to my lack of variables. Once I start to polish this for M4, that will be my number #1 objective. 

## Team Info: Griffin Vines (Solo)

## Sources:
https://www.boxofficemojo.com/chart/top_lifetime_gross/?ref_=bo_cso_ac \\
https://www.rottentomatoes.com/ \\
https://www.imdb.com/chart/top/?ref_=hm_nv_menu \\
