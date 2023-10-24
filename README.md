# Bike-Sharing-System-ML-Model

# Problem
<ul><li> Analysis of a bike-sharing system that let people use bikes for a short period of time for a
cost or for free.</li></ul>

# Business Objectives 
<ul>
  <li>  Modelling the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features.Then they can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.</li>
</ul>

# Tech Stack
<ul>
  <li>Python</li>
  <li>Scikit-learn</li>
  <li>Matplotlib</li>
  <li>Seaborn</li>
  <li>Pandas</li>
  <li>NumPy</li>
</ul>

# Dataset Description
<ul>
<li>A sizable dataset on daily bike demand across the American market has been gathered by BoomBikes. Based on a number of parameters, the dataset contains information
regarding the demand for shared bikes.</li>
<li>The dataset might additionally contain extra factors like place, hour of the day, day of the week, and holidays.</li>
<li>Variables such as hum, temp, windspeed, season,holidays,weathersit, cnt are used for the analysis and predictions.</li>
</ul>

# Proposed Analytical/Prediction Model
<ul>
<li>In this analysis, the dependent variable is client demand, and the independent variables are things like temperature, weather, humidity, and wind speed.</li>
<li>We have created a linear regression model to forecast how the demand will change as a result of these attributes.</li>
<li>We divided the data into training and testing sets and trained the model on the training data using the LinearRegression() method.</li>
<li>The model's performance was then assessed using both the testing data and the projected data. Our goal is to demonstrate how successfully the model has been trained to forecast
client demand.</li>
</ul>

# Observation
<ul><li>From R-Sqaured and adj R-Sqaured value of both train and test dataset we could conclude that the above variables can well explain almost 80% of bike demand.</li></ul>




