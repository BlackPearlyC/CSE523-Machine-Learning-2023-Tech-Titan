Ahmedabad University

School of Engineering & Applied Science

Winter 2023 - Project

Course: CSE523 - Machine Learning

Professor Mahul Raval

Team:

Jainam Shah - AU2040186

Yash Chotaliya - AU2040193

Akshay Parmar - AU2040199

Shubham Bhatt - AU2040206

Dataset Link:

- [Dataset Link](https://drive.google.com/drive/folders/1NtqmvhwNxvG48XcsGT_DUPEZHZSWJReS?usp=share_link)

Description:

In recent years, the increasing availability of data and advances in machine learning techniques have led to the development of highly accurate and effective movie recommendation systems. One popular approach to movie recommendation is collaborative filtering, where a user's preferences are inferred based on the preferences of other users with similar tastes. Collaborative-based movie recommendation systems leverage this approach to provide personalized recommendations to users based on their viewing history, ratings, and reviews. Machine learning algorithms play a critical role in implementing these recommendation systems, enabling the analysis of large datasets and the identification of hidden patterns in user behavior. In this report, we will explore the different techniques used in collaborator-based movie recommendation systems, including neighborhood-based and matrix factorization algorithms, and evaluate their performance in terms of accuracy and scalability. We will also discuss the challenges and limitations of these systems and potential avenues for future research.

One of the biggest advantages of using user-based Collaborative filtering is that the model doesn’t want any information about the movie, like it’s genre, plot, actors, and more. It relies completely on the rating of the user, which is often available in the online movie dataset.

In this project, We have developed a movie recommendation system using a collaborative filtering technique. The plan recommends movies to the user based on the ratings given by other similar users. We have used the Pearson correlation and cosine similarity to calculate user similarity. We have also filtered the movies based on the number of ratings they received and kept the movies with over 100 ratings. Finally, we have used the item scores to recommend top movies to the user. So, we analyzed the model using RMSE, MAE, and precision and recall; we got an average of the model is 80%.