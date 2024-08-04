# Taxi Fare Analysis Using Regression
## Overview

This project performs regression analysis on taxi fare data to understand the relationships between various factors and taxi fares. Using Python's pandas, Matplotlib, and Seaborn libraries, the project analyzes and visualizes taxi trip data to build predictive models for estimating taxi fares based on trip attributes.
## Features

* Load and preprocess taxi trip data from a CSV file
* Perform exploratory data analysis (EDA) and visualize data relationships
* Implement regression models to predict taxi fares
* Generate plots to visualize regression results and model performance

## Prerequisites

* Python 3.7 or higher
* pip (Python package installer)

## Installation

1. Clone the repository:

          git clone https://github.com/yourusername/Taxi_fare_analysis.git

2. Navigate to the project directory:

          cd Taxi_fare_analysis

3. Create a virtual environment (optional but recommended):

          python -m venv venv

4. Activate the virtual environment:

Windows:

          venv\Scripts\activate

MacOS/Linux:

          source venv/bin/activate

5. Install the required packages:

          pip install -r requirements.txt

## Data

* CSV File: The project expects a CSV file with taxi trip data. Ensure the CSV file includes columns such as Pickup_DateTime, Dropoff_DateTime, Pickup_Latitude, Pickup_Longitude, Dropoff_Latitude, Dropoff_Longitude, Passenger_Count, and Fare_Amount. Place this file in the data directory and name it taxi_trips.csv.

## Results

* Regression Analysis: Results of the regression analysis including Mean Squared Error (MSE) and performance metrics.
* Visualizations: Interactive plots showing the relationships between features and taxi fares, and regression model performance.
    
## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

* Pandas for data manipulation and analysis.
* Matplotlib and Seaborn for data visualization.
* Scikit-learn for regression modeling and evaluation.
