# Linear Regression Model for Bike Rentals Prediction

This project aims to build a linear regression model to predict the demand for shared bikes based on various features like temperature, humidity, season, and weather conditions. The model helps in understanding how these factors influence bike rentals and can be used to optimize bike-sharing services.

## Dataset

The dataset used for this project contains information about bike rentals, including features like temperature, humidity, season, holiday status, day of the week, and weather situation. The target variable is the count of bike rentals.

## Key Inferences

Based on the analysis of the model, the following key inferences were made:

- Temperature and apparent temperature have a strong positive impact on bike rentals, indicating more bikes are rented on warmer days.
- Humidity and windspeed negatively impact bike rentals, meaning rentals decrease as humidity and windspeed increase.
- Seasonality plays a role, with the highest rentals in season 4 and the lowest in season 1.
- Non-holidays see higher rentals compared to holidays.
- Day of the week shows variability in bike rentals, with weekends (especially Saturday) seeing higher rentals compared to weekdays.
- Working days have slightly higher rentals compared to non-working days.
- Weather situations: Favorable weather conditions (weather situation 1) significantly increase rentals, while adverse conditions (weather situation 3) drastically decrease rentals.

## Model Training and Evaluation

The model was trained using a pipeline that included data preprocessing steps such as standard scaling for numerical features and one-hot encoding for categorical features. The trained model was then evaluated using metrics like Mean Absolute Error, Mean Squared Error, and R-squared.

## Usage

To use this model, follow these steps:

1. Install the required dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn

2. Clone the repository:

git clone https://github.com/sting-nd-bull/bike-sharing.git

3. Navigate to the project directory:

cd Bike_Sharing

4. Run the Jupyter notebook to see the model implementation and analysis:

Jupyter Notebook