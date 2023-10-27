# RuterOblig
Assigment 2 - Ruter Prediction
We chose to predict passenger data for Ruter (use case number 2).
We chose to use a regression algorithm. In the Ruter data, we could see that the bus we chose (150) had a max capacity of 112 passengers.
If the amount of passengers can be from 0-112, we thought that this would create too many discrete categories for a classification model.
With a regression algorithm, we can instead map the input to a continuous function. 
We are using linear regression, but looking at a scatter plot of the data shows that we would need a more advanced model to get high accuracy. 
Just using the average number of passengers as a prediction will probably be almost as accurate as our linear regression model.
