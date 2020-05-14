# Disaster-Tweets-Classification-NLP
Tweets are either disaster related or not disaster related. I hope to identify which ones are disaster related through NLP


Dataset: https://www.kaggle.com/c/nlp-getting-started/data

[**Full report can be found here**](https://github.com/ngocdinh1410/Disaster-Tweets-Classification-NLP/blob/master/Final%20Report_Final%20Draft.docx)

[**Full presentation can be found here**](https://github.com/ngocdinh1410/Disaster-Tweets-Classification-NLP/blob/master/Final%20Presentation_TextAnalytics_Team8.pptx)


**Data Pre-processing**


<li>Remove unnecessary punctuations and stop words</li>
<li>Stemming</li>
<li>Focus on columns tweet and target (0 means irrelevant and 1 means relevant) </li>
<li>80/20 split</li>

**EDA**


![Top 20 most frequent words in relevant Tweet](https://github.com/ngocdinh1410/Disaster-Tweets-Classification-NLP/blob/master/Bar_relevant.png)

![Top 20 most frequent words in not relevant Tweet](https://github.com/ngocdinh1410/Disaster-Tweets-Classification-NLP/blob/master/Bar_notrelevant.png)
![Wordcloud_relevant](https://github.com/ngocdinh1410/Disaster-Tweets-Classification-NLP/blob/master/Wordcloud_relevant.png)

![Wordcloud_not relevant](https://github.com/ngocdinh1410/Disaster-Tweets-Classification-NLP/blob/master/Wordcloud_notrelevant.png)

**Topic Modeling**


![Topic Modeling](https://github.com/ngocdinh1410/Disaster-Tweets-Classification-NLP/blob/master/Topic%20Modeling.png)
![Topic Modeling](https://github.com/ngocdinh1410/Disaster-Tweets-Classification-NLP/blob/master/Topic%20Modeling_2.png)

**Sentiment Analysis**

SA using NLTK Darth Vader


**Classifiers**

<li>Logistic Regression   -- TFIDF</li>
<li>Logistic Regression   -- word2vec</li>
<li>RandomForest</li>
<li>Naive Bayes</li>
