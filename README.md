# Spaceship Titanic: Predicting Transported Passengers

This is the repository for the Kaggle competition "Spaceship Titanic: Predicting Transported Passengers". In this project, we will use data science and machine learning techniques to predict which passengers were transported to another dimension after the Spaceship Titanic collided with a spacetime anomaly.

## Introduction

### Problem Summary

Welcome to the year 2912, where your data science skills are needed to solve a cosmic mystery. The Spaceship Titanic, an interstellar ocean liner, collided with a spacetime anomaly, resulting in the disappearance of almost half of its passengers who were transported to an alternate dimension. The challenge is to predict which passengers were transported using the recovered records from the ship's damaged computer system.

### Dataset

The dataset for this competition contains personal records of the passengers aboard the Spaceship Titanic prior to the unfortunate incident with the spacetime anomaly. The repository contains two main files:

- `train.csv`: Contains personal records for approximately two-thirds (~8700) of the passengers, which will be used as training data.
- `test.csv`: Contains personal records for the remaining one-third (~4300) of the passengers, which will be used as test data.

Both files include information such as passenger ID, home planet, cryogenic sleep status, cabin number, destination planet, age, VIP status, and expenses on various luxury facilities onboard the ship.

### Dataset Features

The main features of the dataset include:

- **PassengerId**: Unique identifier for each passenger.
- **Cabin**: Cabin number where the passenger is accommodated.
- **HomePlanet**: Planet of origin for the passenger (Europa, Earth, or Mars).
- **Destination**: Destination planet the passenger was intended to disembark.
- **Age**: Age of the passenger.
- **CryoSleep**: Indicator of whether the passenger opted for cryogenic sleep during the journey.
- **VIP**: Indicator of whether the passenger has paid for a special VIP service during the journey.
- **RoomService**, **FoodCourt**, **ShoppingMall**, **Spa**, **VRDeck**: Passenger's expenses on different luxury amenities.
- **Name**: Passenger's name and surname.
- **Transported**: Target variable indicating whether the passenger was transported to another dimension.

## Methodology

Methodology followed:

1. Exploratory Data Analysis (EDA) to understand the distribution of features and their relationship with the target variable.
2. Data cleaning, addressing missing values, and removing or transforming outliers.
3. Feature engineering to extract maximum information from the available features.
4. Training different classification models and validating them using techniques like cross-validation.
5. Hyperparameter tuning to improve the model's performance.
6. Evaluation of the models and selection of the best-performing model for making predictions on the test set.
7. Generating predictions on the test set and presenting the results.

## Usage
1. Clone the repository.
2. Open the notebook file (`spaceship-titanic.ipynb`) using Jupyter Notebook or JupyterLab.
3. Execute each cell in the notebook sequentially to reproduce the analysis and predictions.
4. Customize the notebook as needed for your own analysis.

## Contributions and Collaboration

If you're interested in contributing to this project, you're welcome to do so! You can fork this repository, work on your own branch, and submit a pull request with your contributions.

## Contact

If you have any questions or want to get in touch regarding this project, you can email me at [josevillalbajimenez@gmail.com].

## Acknowledgments
This notebook was created for the "Prediction of Wild Blueberry Yield" competition. The dataset and competition details can be found at [competition-link].

[competition-link]: [https://www.example.com](https://www.kaggle.com/competitions/playground-series-s3e14)

