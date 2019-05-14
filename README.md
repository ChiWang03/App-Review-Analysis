# App-Review-Analysis
Not all notebooks and data are included in this repository, due to research reasons.

This repository includes two Natural Language Processing approaches on Google Play app reviews 
* Topic Modelling 
  * Using different methods in gensim (LDA, LDA MALLET) to see what people are talking about in these apps
  * NMF was also tested but results were not great
* Sentiment Analysis
  * Using different methods to classify sentiment 
  * The best classifier would be used to filter out non-informative text
  * non-informative user-reviews refer to the reviews that have sentiment not matching the scores (score > 3 => positive, == 3 => neutral, < 3 => negative)
  * Sentiment analysis inspired by: https://github.com/bertcarremans/TwitterUSAirlineSentiment/blob/master/source/Predicting%20sentiment%20with%20text%20features.ipynb
 

The notebook goes through the preprocessing of data 
* Lemmatisation
* Stemming
* approaches to filter out different languages
* optimizing and filtering out words that don't belong in the english dictionary



