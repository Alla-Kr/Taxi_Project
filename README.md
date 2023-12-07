# Taxi_Project (regression task)
## Task
We have to solve a machine learning problem aimed at automating business processes. Let's build a model that will predict the total duration of a taxi trip in New York.

Imagine you order a taxi from one point in New York to another, and the end point does not necessarily have to be within the city. How much will you have to pay for it? It is known that the cost of a taxi in the USA is calculated on the basis of a fixed rate + tariff cost, the value of which depends on time and distance. Tariffs vary depending on the city.

In turn, the travel time depends on many factors such as where you are coming from and where you are going, what time of day you make your trip, weather conditions, and so on.

Thus, if we develop an algorithm that can determine the duration of a trip, we can predict its cost in the most trivial way, for example, simply by multiplying the cost by a given fare.
Taxi services store huge amounts of information about trips, including data such as the final and starting point of the route, the date of the trip and its duration. This data can be used to predict the duration of a trip automatically using artificial intelligence.

**Business task:** determine the characteristics and use them to predict the duration of a taxi trip.

**Technical task:** build a machine learning model that, based on the proposed client characteristics, will predict a numerical attribute - taxi travel time. That is, solve the regression problem.

**Main goals of the project:**
1. Create a data set based on several sources of information
2. Design new features using Feature Engineering and identify the most significant ones when building a model
3. Explore the data provided and identify patterns
4. Build several models and select the best one according to a given metric
5. Design a process for predicting travel times for new data.

### Result
[Jupyter notebook with completed tasks and conclusions](Taxi_Project.ipynb)
