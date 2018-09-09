# Twitter-Sentimental-Analysis---Hadoop-MapReduce

## Summary 

1. Built Twitter Sentimental Analysis to find Positive, Negative and Neutral tweets towards a specific subject or product for the most popular tweets over the week.
2. Extracted the live data from Twitter (Tweets for a week) using python and saved as text file.
3. Built a Single-Node cluster and Multi-Node cluster and installed Hadoop configurations.
4. Created HashMap (collection of positive, negative and neutral words and the associated value mentioned either positive or negative direction) to store key and value.
5. Developed Map method to calculate sentiments using toString method.
6. Created a reducer class to display the mapper output and a driver class for MapReduce.
7. Evaluated the tweets collected by the famous football player Cristiano Ronaldo is neither positive nor negative sentiment but he has neutral sentiments because value 0 suggests neutral sentiments
