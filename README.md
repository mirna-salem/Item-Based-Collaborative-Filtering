# Item-based-Collaborative-Filtering

Author: Mirna Salem

Date: 09/02/2020

This model was built using the MovieLens dataset to predict the ratings of a user based on the similarities of the items. Recommender systems that use item-based collaborative filtering are used by many large companies. The reasons that they're preferred over user-based collaborative filtering are:
* There's usually less items than people. For example, large-scale businesses like Amazon have a lot more users than items. As a result, the item-item similatrity matrix of will be much smaller and will make computing more efficient.
* User preferences may change whereas an item will always be an item. As a result, you don't have to update the similarity matrix as often.
* Better for new users since there isn't much information about them.

__ml-100k__ : [MovieLens 100K Dataset](https://grouplens.org/datasets/movielens/) that contains several training and testing datasets. I use u1.base and u1.test which are already split into 80% training and 20% testing.

__Item-based Collaborative Filtering.ipynb__ : The Jupyter Notebook file that contains my code.

[To view project on nbviewer, click here.](https://nbviewer.jupyter.org/github/mirna-salem/Item-based-Collaborative-Filtering/blob/master/Item-based%20Collaborative%20Filtering.ipynb)
