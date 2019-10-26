# Movie_Recommendation_Engine_in_Python
A simple movie recommendation engine to recommend movies based on your interests or similar to movies that you are interested in.

# Data collection
This is the first and most crucial step for building a recommendation engine. The data can be collected by two means: explicitly and implicitly. Explicit data is information that is provided intentionally, i.e. input from the users such as movie ratings. Implicit data is information that is not provided intentionally but gathered from available data streams like search history, clicks, order history, etc.

# Data Storage
The amount of data dictates how good the recommendations of the model can get. For example, in a movie recommendation system, the more ratings users give to movies, the better the recommendations get for other users.

# Content Based Filtering
This algorithm recommends products which are similar to the ones that a user has liked in the past.The content-based filtering algorithm finds the cosine of the angle between the profile vector and item vector, i.e. cosine similarity

# Collaborative Filtering
The collaborative filtering algorithm uses “User Behavior” for recommending items. This is one of the most commonly used algorithms in the industry as it is not dependent on any additional information.

# Python Implementation
First, we’ll import our standard libraries and read the dataset in Python. We use libraries such as Pandas, Numpy, sklearn etc..
