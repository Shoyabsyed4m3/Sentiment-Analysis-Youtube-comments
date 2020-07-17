# Sentiment Analysis of Youtube Comments
sentiment analysis of comments on a youtube video using deeplearning Neural Networks and "Youtube Data API".
I used Youtube API to extract comments from a youtube video.By using python library 'VADER'  I differentiate the comments it to Negative, Positive and Neutral.

# What is VADER
VADER (Valence Aware Dictionary and sEntiment Reasoner) is a lexicon and rule-based sentiment analysis tool that is specifically attuned to sentiments expressed in social media. VADER uses a combination of A sentiment lexicon is a list of lexical features (e.g., words) which are generally labeled according to their semantic orientation as either positive or negative. VADER not only tells about the Positivity and Negativity score but also tells us about how positive or negative a sentiment is.

# Scoring Procedure

1. `Positive sentiment: compound score >= 0.05`
2. `Neutral sentiment : score > -0.05 and score < 0.05`
3. `Negative sentiment: score <= -0.05

# Applications
It can be used by youtubers and channel owners to analyse the response of audience viewing and commenting on their videos. Since there are millions of comments made on youtube each day it can become difficult to read all the comments on a video, but since it is also important to know the feedback and what people think of a video or a particular content this can be used as youtube report to know if the comments on a video are **Positive, Negative or Neutral**. This is made interactive and easy to understand by concluding the report with **final result** of all the calculations and a **piechart** containing info about percentage of `positive`, `negative` and `neutral` comments.

![Output](https://user-images.githubusercontent.com/63922881/87576304-c94cef80-c6ee-11ea-9ce1-8dd710c16d46.PNG)



# To run this
python Libraries required. `Run:`
1. `pip install vadersentiment
2. `pip install httplib2`
3. `pip install google-api-python-client`
4. `pip install csv`
5. `pip install oauth2client`

**To extract Comments we need Youtube API:**
1. Go to "Google Developers Console".
2. Enable "Youtube Data API".
3. Create Credentials.
4. Download the credentials to `client_secrets.json`.

Go through this link for details
https://python.gotrained.com/youtube-api-extracting-comments/#:~:text=Select%20the%20Credentials%20tab%2C%20click,right%20of%20the%20client%20ID.



