# Movie-Prediction-Using-Collaborative-Filtering
I used database ml-100k which consists of 100,000 ratings for movies with the users and movie details and predict top 5 movies for different users.
I will be using the 'ua.base' file which contains 90,000 ratings and the 'ua.test' file which contains 10,000.
It has 3 columns - user_id, movie_id, user_rating
I divide the dataset into a 90:10 ration of training set and test set.
I then calculate prediction score using - User Based Collaborative Filtering - Based on Top 50 users and Item Based Collaborative Filtering - Based on Top 50 movies with highest rating.
In the next part, I get recommendations for a user based on the highest predicted ratings for a particular user.
For example - I got predictions for the user with user id 77. I am using the predictions from the item-item collaborative filtering model for this to print the list of top 5 movies that are recommended for this particular user.
