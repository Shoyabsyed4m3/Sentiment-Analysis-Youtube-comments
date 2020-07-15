# Sentiment Analysis of Youtube Comments
sentiment analysis of comments on a youtube video using deeplearning Neural Networks and "Youtube Data API".

# Scoring Procedure

1. `Positive sentiment: compound score >= 0.7`
2. `Neutral sentiment : score > 0.3 and score < 0.7`
3. `Negative sentiment: score <= 0.3

# Applications
It can be used by youtube content creators and channel owners to analyse the response of audience viewing and commenting on their videos. Since there are millions of comments made on youtube each day it can become difficult to read all the comments on a video, but since it is also important to know the feedback and what people think of a video or a particular content this can be used as youtube report to know if the comments on a video are **Positive, Negative or Neutral**. This is made interactive and easy to understand by concluding the report with **final result** of all the calculations and a **piechart** containing info about percentage of `positive`, `negative` and `neutral` comments.

https://github.com/Shoyabsyed4m3/Sentiment-Analysis-Youtube-comments/blob/master/Output.PNG


# To run this
You will have to install some libraries. `Run:`
1. `pip install tensorflow` or use google colab
2. `pip install httplib2`
3. `pip install google-api-python-client`
4. `pip install csv`
5. `pip install oauth2client`

**You will also have to set up Google Cloud:**
1. Go to "Google Developers Console".
2. Enable "Youtube Data API".
3. Create Credentials.
4. Download the credentials to `client_secrets.json`.





