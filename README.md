# Movie_Recommender_System
A movie recommender system is an intelligent software application that analyzes a user's movie preferences and recommends movies that the user may like. The system uses various algorithms and techniques such as collaborative filtering, content-based filtering, and hybrid filtering to suggest movies that match the user's tastes.

The collaborative filtering algorithm analyzes the behavior of similar users and makes recommendations based on their preferences. It is based on the assumption that users with similar tastes will like the same movies. The content-based filtering algorithm, on the other hand, analyzes the characteristics of the movies and recommends similar movies based on their attributes such as genre, actors, and plot.

The hybrid filtering algorithm combines both collaborative and content-based filtering techniques to provide better recommendations. It takes into account both the user's behavior and the attributes of the movies to suggest movies that are more likely to be enjoyed by the user.

Movie recommender systems can be used in various settings, such as movie streaming services, e-commerce platforms, and social media platforms. They provide a personalized user experience, save users time in searching for movies, and help users discover new movies that they may not have found on their own.

Overall, movie recommender systems are an excellent tool for movie lovers who want to discover new movies that match their preferences and expand their cinematic horizons.

Final Wordings: 

1. The Dataset consists of around 5000 datapoints.
2. The Recommendation System Used in this is Content Based Recommendation System, which detects and finds similar users and suggest similar contents.
3. In process we have dropped few features for better runnabiltiy and for better usability of Data, so with that features we can also try some other recommender system
4. In Feature Engineering, We can converted, merged few columns which have similar functionality and which results in a combined Dataframe. 
5. Some NLP concepts are used in this projects on the basis of which we are calculating similar contents.
6. Cosine Similarity is used as distance calculator between the content as Euclidian Distance would have cause Curse of Dimensionality issues, since that's why Cosine Similarity is used. Instead of Cosine Similarity, Cosine Distance can also be used.
7. From above point, we have made a Recommender System which we can see runs smoothly and also giving suggestions based on Keywords.
