# Linear Regression

Suppose you are the CEO of a restaurant franchise and are considering different cities for opening a new outlet. You would like to expand your business to cities that are likely to generate higher profits.

The franchise already has restaurants in various cities, and you have data on profits and city populations.

You also have information on candidate cities for new locations. For these cities, only the population is known.

Using this data, you can build a linear regression model to help identify which cities may potentially yield higher profits.

## Results

After training the model, we visualize the results with a scatter plot of actual profits vs. city populations, along with the regression line showing the predicted values:

<img width="408" height="284" alt="Screenshot 2025-07-15 at 14 32 35" src="https://github.com/user-attachments/assets/d6b858a1-88a9-477b-b54e-a5359e026cb8" />

The learned parameters (w, b) can now be used to make predictions on profits for new cities.

### Example Predictions

The model expects input in terms of population (in 10,000s). For example:

Population = 35,000
Input to model: np.array([3.5])
Predicted profit: $4,519.77

Population = 70,000
Input to model: np.array([7.0])
Predicted profit: $45,342.45
