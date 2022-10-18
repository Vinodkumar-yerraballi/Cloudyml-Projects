# steam_video_games_recomandation
#STEAM VIDEO GAMES RECOMMENDATION SYSTEM
we need to recommend the similar games to the user based on their behaviour

##About dataset
This dataset is a list of user behaviors, with columns: user-id, game-title, behavior-name, value. The behaviors included are 'purchase' and 'play'. The value indicates the degree to which the behavior was performed - in the case of 'purchase' the value is always 1, and in the case of 'play' the value represents the number of hours the user has played the game.

steam-200k - (199999, 5)

###Columns in dataset
user-id

game-title

behavior-name

value

0
#After that do some EDA process
#converting hours to rating

MEMORY BASED COLLABORATIVE FILTERING
Memory-based algorithms approach the collaborative filtering problem by using the entire database.It tries to find users that are similar to the active user (i.e. the users we want to make predictions for), and uses their preferences to predict ratings for the active user.

#COLLABORATIVE FILTERING USING KNN
Collaborative Filtering Using k-Nearest Neighbors (kNN). kNN is a machine learning algorithm to find clusters of similar users based on common ratings, and make predictions using the average rating of top-k nearest neighbors.

#Conclusion
We can use different different methods based on our problem statement and dataset. Here we used collaborative filtering technique to recommend games.We can use this method to recommend alot of other things as well such as music, movies, books, news etc.
