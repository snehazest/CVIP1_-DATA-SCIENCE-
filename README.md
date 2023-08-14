# CVIP1_- DATA-SCIENCE-IMDB Data Analysis & House Prediction 

IMDB Data Analysis- The dataset contains information about several popular movies, including details like the movie title, release year, certificate (rating), runtime, genre, IMDb rating, meta score, director, stars, number of votes, and gross earnings. Analyses and Visualizations
- Handling Null Values: We checked for null values in the dataset and found that the 'Certificate', 'Meta_score', and 'Gross' columns have missing data.

Exploratory Data Analysis:

Genre Distribution: We analyzed the distribution of movie genres using a pie chart to show the proportions of each genre in the dataset. Top Grossing Movies: We plotted the titles of movies with a duration of at least 180 minutes to identify the longest movies. IMDb Ratings vs. Genres: We created a box plot to visualize the IMDb ratings for different genres, specifically focusing on genres with ratings greater than 9. Certificate Distribution: We used a pie chart to visualize the distribution of movie certificates (ratings) in the dataset. Top Grossing Movies with IMDb Ratings > 9:

We plotted a scatter plot to show the gross earnings of movies with IMDb ratings greater than 9, highlighting the relationship between high ratings and earnings. Max Genre Pie Chart:

We created a pie chart to show the distribution of movie genres in the dataset, with the genre having the highest count highlighted. Certificate Pie Chart:

We used another pie chart to visualize the distribution of movie certificates (ratings) in the dataset. These analyses and visualizations provide insights into the genres, ratings, ratings' distribution, earnings, and other attributes of the movies in the dataset. They help us understand trends, patterns, and relationships within the data.
Summary: Building and Evaluating Regression Models


Second project was house prediction for this, I performed data preprocessing, built, and evaluated two regression models — Decision Tree Regression and Linear Regression — using a given dataset. The dataset contains various features related to housing properties, such as the number of bedrooms, bathrooms, square footage, and location.
1. Data Loading and Preprocessing:

Loaded the dataset into a pandas DataFrame (df).
Selected relevant columns, including features of interest and the target variable (price).
Split the dataset into training and testing sets using train_test_split from sklearn.model_selection.
Created separate training and testing sets for features (X_train, X_test) and target (y_train, y_test).
2. Decision Tree Regression:

Imported necessary libraries: pandas, sklearn.model_selection, sklearn.tree, sklearn.metrics.
Created a Decision Tree Regression model using DecisionTreeRegressor from sklearn.tree.
Trained the model on the training data using the fit method.
Made predictions on the test data using the predict method.
Calculated the Mean Squared Error (MSE) and R² score to evaluate the model's performance.
Visualized the predicted vs. actual prices on the test data using a line chart.
3. Linear Regression:

Imported necessary libraries: pandas, sklearn.model_selection, sklearn.linear_model, sklearn.metrics.
Created a Linear Regression model using LinearRegression from sklearn.linear_model.
Trained the model on the training data using the fit method.
Made predictions on the test data using the predict method.
Calculated the Mean Squared Error (MSE) and R² score to evaluate the model's performance.
Visualized the predicted vs. actual prices on the test data using a line chart.
4. Visualization:

Imported matplotlib.pyplot for data visualization.
Created line charts to visualize the predicted vs. actual prices for both the Decision Tree and Linear Regression models.
Added labels and a legend to the plots for better visualization.
Overall, both the Decision Tree Regression and Linear Regression models were trained and evaluated on the same dataset. The evaluation metrics, including MSE and R² score, provided insights into how well each model fits the data. The visualization of predicted vs. actual prices helped visualize the model's performance graphically.

By comparing the performance of these two models, we gained a better understanding of their strengths and limitations in predicting housing prices based on the given features.
