# Reddit NLP Sentiment

This project analyzes Reddit posts for sentiment using Natural Language Processing (NLP) using data from various movie posts on subreddits. Ultimately, analyzing movie sentiment and comparing it to the critic ratings from [RottenTomates](https://www.rottentomatoes.com/).

![images](images/shawshankredemption_wordcloud.jpg)

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
The following are bar graphs, kernel density estimates, LDA topic models, and tsne; from Inception. The VADER images reflect the VADER score, a post sentiment rating score from -1 to 1. Negative one being perceived as a negative as bad and positive 1 being associated with a good review. Any score between -.05 and .05 was placed in the neutral category. The topic models returned a list of popular words for each topic. Local LLM (Chatgpt) differentiated the categories between movie topics. 
