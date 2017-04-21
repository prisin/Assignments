
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


# Analysis 2
1. Read the data from reviews.csv file stored in data folder and put it in a dataframe.
2. Get all the reviewer names from reviewer name column and remove all the rows with no name.
3. Get all the listings of each reviewer and get the frequent used listing of each reviewer.
4. Find out which listing is mstly used by each reviewer.
5. Get the location which is most frequent used by each reviewer.


# Analysis 3
1. Read the data from listings.csv file stored in data folder and put it in a dataframe.
2. Convert all string price into float to calculate mean of price.
3. Get the top 5 most frequent neighbourhood from the neighbourhood column.
4. Get the count of each neighbourhood and plot it in graph to see the most populated neighbourhood.
5. Get the mean price of each neighbourhood and plot it in graph and mean price near each neighbourhood.


# Analysis 4
1. Read the data from listings.csv file stored in data folder and put it in a dataframe.
2. Convert all string price into float to calculate mean of price.
3. Get the mean price of all the listings by each host.
4. Get the mean ratings of all the listings of each host.
5. Plot the graph of all the listings mean price of each host.
6. Plot the graph of all the listings mean ratings of each host.
7. We concluded price matters for rating. When price is less there are chanches of good ratings.


# Analysis 5
1. Read the data from listings.csv file stored in data folder and put it in a dataframe.
2. Convert all string price into float to calculate mean of price.
2. Get the mean price of all the listings by each host.
3. Get the count of each neighbourhood and plot it in graph.
4. Get the mean price of each neighbourhood and plot it in graph.