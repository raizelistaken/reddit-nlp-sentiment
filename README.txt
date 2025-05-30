﻿﻿# Reddit NLP Sentiment

This project analyzes Reddit posts sentiment using Natural Language Processing (NLP). Sentiment topics are further analyzed using an LLM to distinguish movie topics divvied up by LDA topic modeling. The sentiment scores (pos, neg, neutral, or compound) can be compared to the critic ratings from [RottenTomates](https://www.rottentomatoes.com/).

![Wicked](images/wicked_wordcloud.jpg)

## Requirements

To run this project, you will need to install the required packages listed in the `requirements.txt` file:

```bash or powershell (I'm using Windows PowerShell)
pip install -r requirements.txt
```

## Methods
- **VADER**
    - [Jack](https://jackmckew.dev/sentiment-analysis-text-cleaning-in-python-with-vader.html)
- LDA   
    - [learningLDA](https://www.youtube.com/watch?v=xvqsFTUsOmc&amp%3Bab_channel=PyOhio) 
    - [kagglelearning](https://www.kaggle.com/yohanb/lda-visualized-using-t-sne-and-bokeh)
    - [learning](https://www.machinelearningplus.com/nlp/topic-modeling-visualization-how-to-present-results-lda-models/)
    - [documentation](https://radimrehurek.com/gensim/models/ldamodel.html)
- TSNE 
    - [JoshStamer](https://www.youtube.com/watch?v=NEaUSP4YerM) 
    - [documentation](https://scikit-learn.org/stable/modules/generated/sklearn.manifold.TSNE.html#examples-using-sklearn-manifold-tsne)

## Results
The following are bar graphs, kernel density estimates, LDA topic models, and tsne; from Inception. The VADER images reflect the VADER score, a post sentiment rating score from -1 to 1. Negative one being perceived as a negative / bad and positive one being associated with a good review. Any score between -.05 and .05 was placed in the neutral category. The topic models returned a list of popular words for each topic. Local LLM (Chatgpt) differentiated the categories between movie topics. 


![Inception_bar](images/Inception_freqbargraph.png)

![Inception_kerneldestiny](images/Inceptionsentimentdistribution.jpg)

![Inception_LDA](Inception_lda_vis.html)

![Inception_tsne](images/tsne_inception.jpg)
