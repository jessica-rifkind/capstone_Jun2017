# capstone_Jun2017
Topic analysis of review text on TripAdvisor and Yelp for major hotel chains

Only for educational purposes

Dependencies:
Beautiful Soup
Gensim
pyLDAvis

Tested Configuration:
Python 2.7.6
 
Files:
-'Review URLs' includes hand collected urls for 35 properties across 5 hotel chains and their corresponding page on TripAdvisor and Yelp
-'TripAdvisor_data_and_topic_model' - scrapes review text of TripAdvisor for the urls in Review URLs file, cleans (including removing replies), processes, runs through LDA and visualizes in pyLDAvis 
-'Yelp_data_and_topic_model' - scrapes review text of Yelp for the urls in Review URLs file, cleans, processes, runs through LDA and visualizes in pyLDAvis 


