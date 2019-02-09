# Twitter-Sentiment-Analysis

*What is sentiment analysis?

Sentiment Analysis is the process of ‘computationally’ determining whether a piece of writing is positive, negative or neutral. It’s also known as opinion mining, deriving the opinion or attitude of a speaker.

*Why sentiment analysis?

Business: In marketing field companies use it to develop their strategies, to understand customers’ feelings towards products or brand, how people respond to their campaigns or product launches and why consumers don’t buy some
products.

Politics: In political field, it is used to keep track of political view, to detect consistency and inconsistency between statements and actions at the government level. It can be used to predict election results as well!

Public Actions: Sentiment analysis also is used to monitor and analyse social phenomena, for the spotting of potentially dangerous situations and determining the general mood of the blogosphere.

*Installation (of libraries required for running the code):

Tweepy: tweepy is the python client for the official Twitter API.
Install it using following pip command:
pip install tweepy

TextBlob: textblob is the python library for processing textual data.
Install it using following pip command:
pip install textblob

Also, we need to install some NLTK corpora using following command:
python -m textblob.download_corpora
(Corpora is nothing but a large and structured set of texts.)

*Authentication:
In order to fetch tweets through Twitter API, one needs to register an App through their twitter account. Follow these steps for the same:

1.Open this link and click the button: ‘Create New App’

2.Fill the application details. You can leave the callback url field empty.

3.Once the app is created, you will be redirected to the app page.

4.Open the ‘Keys and Access Tokens’ tab.

5.Copy ‘Consumer Key’, ‘Consumer Secret’, ‘Access token’ and ‘Access Token Secret’.
