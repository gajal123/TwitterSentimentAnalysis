# Twitter-Sentiment-Analysis

It is used to understand how the public feels about something at a particular moment in time and also track
 how those opinion change over time

Essential may analyze sentiment about:
 
  * Product
  * Service
  * Competitors
  * Reputation
 
# Prerequisites

 * Hadoop
 * Hive
 * Flume
 * Java
 * StopWord
 * Affinn Dictionary
 * Twitter App 

# Steps For Sentiment Analysis

 * Load Data to Hive tables 
 * Filteration – remove URL links (e.g. http://example.com), Twitter user names (e.g. @alex – with symbol @ indicating a user name),
 * Tokenization –  Segment text by splitting it by spaces and punctuation marks, and form a bag of words.
 * Removing stop words – we remove articles (“a”, “an”, “the”) from the bag of words.
 * Comparing with Sentiword/Afinn Dictionary –we compare the articles with Dictionary to predict that the word is negative,positive or neutral.

# TODO
 
 * Add Visualization Tools.
 * Make a Gui Version.
 * Apply Machine Learning Techniques.


Look into the Readme folder to learn more about How to load and Analyse.
