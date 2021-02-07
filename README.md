# Donald Trump Communication Analysis Twitter

![trump](https://resize-parismatch.lanmedia.fr/r/625,417,forcex,center-middle/img/var/news/storage/images/paris-match/actu/international/donald-trump-accuse-de-trahison-sans-precedent-par-les-procureurs-democrates-1723046/28411958-1-fre-FR/Donald-Trump-accuse-de-trahison-sans-precedent-par-les-procureurs-democrates.jpg)

The aim of this project is to analyze Donald Trump’s communication on Twitter using a dataset with all Donald trump tweets from 2009 to 2020 in the form of a text file.
Each line of this text file is in the form: text_of_the_tweet;date_of_the_tweet
Each tweet can be an original tweet or a retweet, each retweet starts with the keyword ‘RT’
The exploration of this dataset is done by using Spark, because the analysis should also be able to apply on very large data sets distributed on a Hadoop cluster, for instance to analyze the communication of other public figures.

The analysis was done in the form of an exploration of the dataset, trying to understand the correlation of the insights with the actual events that took place during the last decade involving Donald Trump.

The notebook is divided into the following parts:
- display of top positive and top negative words (using the two dictionaries positive-words.txt and negative-words.txt)
- calculation of the sentiment score
- display of top contextual words
- display of topics related to two particular "hot topics": covid 19 and the presidential election
- the most used hashtags
- most used tags
- a temporal analysis of the number of tweets per hour and per year
