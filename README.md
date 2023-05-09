# IIT2020172_NLP_PROJECT
Event Extraction From Tweets
Extracting and counting most frequent entities from the tweets.

Technology used: Natural Language Processing, Data Pre-processing, Entities Extraction, TextBlob library, Google Translator API and others.

The Approach
Steps involved

Raw data Analysis

Conversion of Raw data to Dataframe

Defining functions for future uses

Translating Tweets to the English language

Data Pre-processing (Cleaning Tweets)

Finding text with spaces
Numbers in the tweets
URL Link
Hashtags
Emojis
Word less than 2 character
And others...
Extracting Entities from the tweets with their frequency

Data Visualization

Here are all the steps in detail:

--> Raw Data Analysis
Raw data analysis is one of the core parts of the solution-building process as it helps in understanding the problem statement in a better way and extracting the idea for building the Skelton of Ideology.

Moreover, it helps in finding out, major issues in the data that needed to be rectified in the data cleansing process.

--> Conversion of Raw data into dataframe
For getting started with the Approach, The main thing is putting data into the mold.
Over here, Conversion of the Raw data(Tweets) into pandas data frame is the process.

--> Defining Functions for future uses
For Optimality, defining functions in the earlier steps helps in Better Implementation.

--> Translating tweets into English Language
During the Data analysis process, some tweets were in the Japanese language.

Thus, to get the best out of the data, Conversion of Japanese tweets into the English Language was Important. With use of Google translate API, It can be done.

--> Data Pre-processing
Data Pre-Processing is one of the critical tasks. There was a ton of debris in the data, and cleaning and identifying them is one of the major tasks.

After cleaning useless elements, All the cleaned data is inserted into column name "clean_tweet",

--> Extracting Entities and counting its frequency
Extracting Entities is one of the big Challenges, There are various methods avilable to extract the entities, Like "tokenization", and "Stemming". But those are limited to the words.

In tokenization there needed to fix a word count for extracting entities, but for this problem statement, There needed the entities of dynamic length. Entities that give the main idea of the tweets.

Thus with the use of TextBlob library's "Noun_phrase extractor", Entities of the Tweets were extracted.

--> Data Visualization
Visualizing the Entities and their count using graphs for better insights.

I created a new data frame with the entities and their frequency count in descending order.

Put the file location and with help of the to_csv function, saved it in the directory.

Conclusion:
Data Cleansing and Entities Extraction were a crucial parts of the solution. Removing unnecessary elements makes tweets ready for further processes, and This part of the process consumes most of the time.

After then, Entities Extraction is a key point in the solution. Finding the right entities defines extracting the right phrases from the tweets on which the core meaning of tweets relies on
