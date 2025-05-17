# Reddit NLP Sentiment

This project analyzes Reddit posts for sentiment using Natural Language Processing (NLP). I used data from the subreddits of different movies to analyze movie sentiment, and compared it to the ratings of critics from [RottenTomates](https://www.rottentomatoes.com/).

![images](inceptionwordcloud.jpg)

## Requirements

To run this project, you will need to install the required packages listed in the `requirements.txt` file:

```bash or powershell (I'm using Windows PowerShell)
pip install -r requirements.txt

## Results
The following are bar graphs, kernel density estimates, LDA topic models, and tsne; from Inception. The VADER images reflect the VADER score, a post sentiment rating score from -1 to 1. Negative one being perceived as a negative as bad and positive 1 being associated with a good review. Any score between -.05 and .05 was placed in the neutral category. The topic models returned a list of popular words for each topic. Chatgpt differentiated the categories between movie topics. 
