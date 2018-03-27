# NewsMood
Python script to perform a sentiment analysis of the Twitter activity of various news channels.

In this assignment, I create a Python script to perform a sentiment analysis of the Twitter activity of various news oulets and present my findings visually.

My final output provides a visualized summary of the sentiments expressed in Tweets sent out by the following news organizations: __BBC, CBS, CNN, Fox, and New York times__.

The first plot features the following:

* A scatter plot of sentiments of the last __100__ tweets sent out by each news organization, ranging from -1.0 to 1.0, where a score of 0 expresses a neutral sentiment, -1 the most negative sentiment possible, and +1 the most positive sentiment possible.
* Each plot point reflects the _compound_ sentiment of a tweet.
* Each plot point is sorted by its relative timestamp.

The second plot is a bar plot visualizing the _overall_ sentiments of the last 100 tweets from each organization. I've aggregated the compound sentiments analyzed by VADER.

The final Jupyter notebook shows the following:

* Pulls last 100 tweets from each outlet.
* Performs a sentiment analysis with the compound, positive, neutral, and negative scoring for each tweet. 
* Pulls into a DataFrame the tweet's source acount, its text, its date, and its compound, positive, neutral, and negative sentiment scores.
* Exports the data in the DataFrame into a CSV file.
* Saves PNG images for each plot.

A written description of three observable trends based on the data is included. 

