# Movie-Recommender

**Recommender Systems**:are **Machine learning** systems that help users discover new product and services.Recommender systems aim to predict user's interests and recommend product items that quite likely are interesting for them

**Types of Recommender System**

**1,Collaborative filtering**:is based on gathering and analyzing data on user's behaviour.This includes
the user's online activities and predicting what they will like based on the similarity with other users.

**2,Content-Based Filtering**:Content-based filtering methods are based on the description of a product and a profile of the user's preferred choices.In this recommendation system,products are described using keywords.

for example: A user watched a action movie and enjoyed it,then recommend him other action movies having 
same rating or the movies that have same story,and actors.


The central assumption of content-based-filtering is that you will also like a similar item if you like a particular item

![image](https://user-images.githubusercontent.com/55338522/155136391-1f29d80a-98b1-43ed-86e2-cadfc29059b4.png)

**3,**Hybrid Recommendations Systems**: In hyrid recommendation systems,products are recommended using
both content-based and callobrative filtering simultaneously to suggest a broader range of products to customers.
**Netflix** is an excellent case in point of hybrid recommendation system.it makes recommendations by juxtaposing user's watching and searching habits and finding similar users on that platform.

**About the Project**
It is a content-based recommender sytem that uses **Cosine similarity** to find 5 similar movies to recommend.this project uses **Bag of words** for text vectorization. 

**Cosine Similarity** is a metric used to measure how similar two items are.Mathematically it measures the cosine of the angle between two vectors projected in a multi-dimensional space.The output value ranges from 0-1.0 means no similarity,where as 1 means that both the items are 100% similar.

**Dataset Used:** https://www.kaggle.com/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv

**Demo**
![Screenshot (112)](https://user-images.githubusercontent.com/55338522/155141306-4862bba0-9627-42bd-baf6-28b08fb23724.png)




 
