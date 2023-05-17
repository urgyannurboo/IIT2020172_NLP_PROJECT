# Event Extraction From Tweets
This project aims to extract events from a collection of tweets using Natural Language Processing (NLP) techniques. It involves cleaning and preprocessing the tweets, translating them into English,extracting and counting most frequent entities from the tweets.
# Requirements
pandas
numpy
json
re
nltk
matplotlib
seaborn
googletrans
textblob
Make sure to install these libraries before running the code
# Installation
Clone the repository to your local machine using the following command:
git clone https://github.com/urgyannurboo/IIT2020172_NLP_PROJECT.git .
Run the Code.ipynb file to see the implementation
# Dataset
The dataset used in this project should be in JSON format, with each tweet represented as a dictionary object. The JSON file should contain the following columns:
tweet_author: Represents the author or user who posted the tweet.
tweet_text: Contains the text content of the tweet.
# Implementation
The code starts by importing the required libraries and downloading the necessary NLTK corpora.
It reads the tweet data from the tweets.json file and creates a Pandas DataFrame for further processing.
The tweets are cleaned by removing hashtags, URLs, user mentions, punctuations, and stopwords. The text is then converted to lowercase.
The cleaned tweets are translated to English using the Google Translate API.
Entities (noun phrases) are extracted from the clean tweets using the TextBlob library.
The extracted entities are flattened into a single list, and the frequency of each entity is counted.
The most frequent entities are stored in a DataFrame and visualized using a bar graph.
# Results
The project generates a CSV file named Results.csv containing the most frequent entities extracted from the tweets. Additionally, a bar graph is displayed to visualize the top entities.
# Conclusion:
Data Cleansing and Entities Extraction were a crucial parts of the solution. Removing unnecessary elements makes tweets ready for further processes, and This part of the process consumes most of the time.
After then, Entities Extraction is a key point in the solution. Finding the right entities defines extracting the right phrases from the tweets on which the core meaning of tweets relies on
