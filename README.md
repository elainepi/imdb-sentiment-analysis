This is a binary classification task aiming to compare 2 different models when performing a sentiment analysis of IMDB movie reviews. 

The dataset is very well balanced and already divided into training and test sets, each of them totalling 25.000 movie reviews. For both sets, reviews are equally divided between positive and negative (12.500 each). Usual data cleaning was applied (removal of punctuation and stop-words, stemming, setting all words to lower case) to improve the quality of the data and, consequentially, of the models. 
The original data set and the cleaned version of it were added to this repository. 

The main notebook contains two different models to implement the sentiment analysis. They were chosen considering a trade-off between quality of the learning curves and running time. Other models that were also tested are present in the appendix of this repository. 

A pdf file contains further explanation on the methods and insights used to perform this task. 
