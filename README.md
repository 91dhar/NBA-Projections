# NBA Predictions Project

**Note: This project is ever-evolving, and updates will be made periodically. New features, improvements, and modifications are expected to enhance the functionality and user experience. Feel free to check back for the latest developments!**

## Overview

The NBA Predictions Project aims to forecast the winners of each NBA game. Utilizing data analysis and predictive modeling, the project provides projections for upcoming games. The predictions will be shared on Twitter via [@rawcodr_](https://twitter.com/rawcodr_). Stay tuned for insights into the outcomes of your favorite NBA matchups!

## Features

### 1. Model Training

- **Target Variable Creation:** Checks for the existence of the 'Win' column and creates a binary target variable ('HomeWin') indicating whether the home team wins.

- **Data Splitting:** Splits the data into training and testing sets for model evaluation.

- **Logistic Regression Model:** Utilizes logistic regression for binary outcome prediction, specifically whether the home team wins or not.

- **Training on Completed Data:** Trains the model on completed data, representing games that have already occurred.

### 2. Model Evaluation

- **Accuracy Evaluation:** Evaluates the accuracy of the binary outcome prediction model on the test set.

- **Console Output:** Prints the accuracy to the console for quick assessment.

### 3. Upcoming Games Prediction

- **Data Preparation:** Provides upcoming game data as a dictionary and converts it into a DataFrame.

- **One-Hot Encoding:** Encodes categorical columns for upcoming games.

- **Prediction Using Logistic Regression:** Uses the trained logistic regression model to predict the winners for upcoming games.

### 4. PrettyTable Display

- **Predictions Display:** Uses PrettyTable to display predictions for upcoming games.

- **Additional Information:** Displays team win-loss records along with the predicted winners.

- **Color Styling:** Utilizes color styling, with headers in blue and predicted winners in green.

### 5. Output

- **Console Display:** Prints the final table to the console, showing matchups and predicted winners.



## Prerequisites

List any dependencies or prerequisites that users need to install before using your project.

- Python 3.x
- Required Python packages (list them)

## Installation

Provide step-by-step instructions on how to install and set up your project.

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-project.git
   cd your-project

Install dependencies:
```pip install -r requirements.txt```

## Usage

### Running the Project

1. Make sure you have Python 3.x installed.

2. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-project.git
   cd your-project

## Acknowledgments

### Data Source

The NBA data used in this project is sourced from [Basketball Reference](https://www.basketball-reference.com/). I express my gratitude for providing valuable data that contributes to the success of this project.

### Contact

If you have any questions or feedback, feel free to reach out:

- Email: abhishekdhar1991@gmail.com
- Twitter: [@rawcodr_](https://twitter.com/rawcodr_)
