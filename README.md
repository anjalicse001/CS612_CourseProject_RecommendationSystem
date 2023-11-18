# CS612_CourseProject_RecommendationSystem
Recommendation System: Implement a recommendation system using collaborative filtering or matrix factorization to suggest items to users.

We have used collaborative filtering and non-negative matrix factorization methods on movie data, which consists of 718 users who have rated 8927 movies. We have predicted the recommended movies for users using these two methods.

Observations:
RMSE:
Non-negative matrix factorization: RMSE: 1.933431334650169
Neural Collaborative filtering : RMSE: 0.1999

Comment on the RMSE results:
Non-negative matrix factorization (NMF) is a relatively simple algorithm, and it may not be able to capture the complex relationships between users and movies in the dataset. That's why the RMSE is relatively on the higher side So we have used a more complex algorithm that is neural collaborative filtering which has given excellent RMSE results.

Other RMSE results:
![image](https://github.com/anjalicse001/CS612_CourseProject_RecommendationSystem/assets/26187367/50d514cf-1cba-4743-8679-a1a4588b735a)









