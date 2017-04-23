
# Analysis 1  
1. Read the data from reviews.csv file stored in data folder and put it in a dataframe.
2. Get all the comments from comment column and remove all the rows with no comments.
3. Read each comment and take out words from them which are not stop words and contains only alphabets.
4. Now find out if the word used is positive or negative by comparing with the words in positive and negative list.
5. Whenever we find any positive word in comment we add the count by 1.
6. Whenever we find any negative word in comment we substract the count by 1.
7. Based on the number of positive or negative words used in the comment, we conclude if the comment is positive or negative or 
   neutral.
8. If the count is greater than 0, the commnent has more postive words and the comment is positive.
9. If the count is less than 0, the commnent has more negative words and the comment is negative.
10.If the count is equal to 0, the comment is neutal.
11.The result is displayed on analysis1.csv to show comment and its sentimental analysis. 


# Analysis 2
1. Read the data from reviews.csv file stored in data folder and put it in a dataframe.
2. Get all the reviewer names from reviewer name column and remove all the rows with no name.
3. Get all the listings of each reviewer and get the frequent used listing of each reviewer.
4. Get the location which is most frequent used by reviewer who gave max reviews.
5. Put the ouput in analysis2.csv to get top reviwers and their most desired neighbourhood.
6. Plot graph of top reviewers and their count.


# Analysis 3
1. Read the data from listings.csv file stored in data folder and put it in a dataframe.
2. Convert all string price into float to calculate mean of price.
3. Get the top 5 most frequent neighbourhood from the neighbourhood column which had most listings.
4. Get the count of each neighbourhood and plot it in graph to see the most populated neighbourhood.
5. Get the mean price of each neighbourhood and plot it in graph and mean price near each neighbourhood.
6. We represented the output in analysis3.csv of top neighbourhood and their mean price.


# Analysis 4
1. Read the data from listings.csv file stored in data folder and put it in a dataframe.
2. Convert all string price into float to calculate mean of price.
3. Get the mean price of all the listings by each host.
4. Get the mean ratings of all the listings of each host.
5. Plot the graph of all the listings mean price of each host.
6. Plot the graph of all the listings mean ratings of each host.
7. We concluded price matters for rating. When price is less there are chanches of good ratings.
8. We represented the output in analysis4.csv of the top hosts and their mean price of their listings and rating of all 
   their listings.


# Analysis 5
1. Read the data from listings.csv file stored in data folder and put it in a dataframe.
2. Read the data from reviews.csv file stored in data folder and put it in a dataframe.
3. Get all the listings id which are present both in listings.csv and reviews.csv
4. Get all the words used in summary by the host for the common listings.
5. Revome the non alpha words and stop words from the list.
6. Get all the words used in reviews by the reviewer for the common listings.
7. Remove the non alpha words and stop words from the list.
8. Match the common words between the summary given by host and the review received from reviewer.
9. Now we put the result in analysis5.csv representing each listing id comment and summary similarity to conclude expectation 
   vs reality.
10.Then we read the anaylis5.csv and group the output based on neighburhood to see where expections and reality degree
   is better by taking the mean of degree of each neighbourhood.  
11.Then we plot the graph for each location what degree of expectation was met.   
