Movie Recommender System

Machine learning algorithms in movie recommender systems are typically based on content-based systems and collaborative filtering systems.
Modern movie recommender systems combine both approaches. To find similarities between movies for content-based systems, we use the cosine similarity function.

 For the collaborative filtering method, we use the matrix factorization technique. For our movie recommender system, we use both techniques. 
 
Matrix factorization is a class of collaborative filtering algorithms used in recommender systems. It became extremely popular during the Netflix Prize challenge. 

To implement matrix factorization, we use a simple Python class named "surprise," which is used for building and testing recommender systems. 

After matrix factorization, we create three sets of features using a sparse matrix, which represents global averages, the top five similar users, and the top five similar movies. 

To create the final model, we will use XGBoost, as it has high accuracy and can outperform other machine learning algorithms. It is highly scalable and can handle large datasets.

 RMSE and MAPE are used as performance metrics. If the RMSE value is less than 2, the final model is considered good, and if MAPE is less than 25, then the final model is considered excellent.

 This project helped me understand how machine learning (ML) algorithms can be used in recommender systems to analyze large amounts of user data to predict their preferences and interests.
