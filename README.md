# Movie-Recommendation-system-using-Collaborative-filtering-algorithm
## Business Problem 
Netflix is all about connecting people to the movies they love. To help customers find those movies, they developed world-class movie recommendation system: CinematchSM. Its job is to predict whether someone will enjoy a movie based on how much they liked or disliked other movies. Netflix use those predictions to make personal movie recommendations based on each customer’s unique tastes. And while Cinematch is doing pretty well, it can always be made better.
Now there are a lot of interesting alternative approaches to how Cinematch works that netflix haven’t tried. Some are described in the literature, some aren’t. We’re curious whether any of these can beat Cinematch by making better predictions. Because, frankly, if there is a much better approach it could make a big difference to our customers and our business.
Credits: https://www.netflixprize.com/rules.html

## Problem Statement
Netflix provided a lot of anonymous rating data, and a prediction accuracy bar that is 10% better than what Cinematch can do on the same training data set. (Accuracy is a measurement of how closely predicted ratings of movies match subsequent actual ratings.)

## Real world/Business Objectives and constraints 
### Objectives:
1. Predict the rating that a user would give to a movie that he has not yet rated.
2. Minimize the difference between predicted and actual rating (RMSE and MAPE) 
### Constraints:
1. Some form of interpretability.
2. There is no low latency requirement as the recommended movies can be precomputed earlier.

## Type of Data:
* There are 17770 unique movie IDs.
* There are 480189 unique user IDs.
* There are ratings. Ratings are on a five star (integral) scale from 1 to 5.
* There is a date on which the movie is watched by the user in the format YYYY-MM-DD.

## Getting Started
Start by downloading the project and run "NetflixMoviesRecommendation.ipynb" file in ipython-notebook.


## Built With
*	ipython-notebook
*	sklearn
*	seaborn, matplotlib.pyplot
*	numpy, scipy
*	pandas
* XGBoost - Used for making regression models
*	Surprise - used for making recommendation system models

## Acknowledgments
*	Applied AI Course
