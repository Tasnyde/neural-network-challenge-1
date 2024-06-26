# 💲 Student Loan Recommendation System

## Overview

This project was for educational purposes and aims to develop a recommendation system for student loan options, helping students find the best financial products based on their personal and educational backgrounds. By leveraging content-based filtering, the system matches students with loan options that suit their financial status, academic pursuits, and future career goals.

## Prerequisites

The starter files consist of the following files:

* `student_loans_with_deep_learning.ipynb`

## Technologies Used

* Python
* Pandas
* scikit-learn
* tensorflow
* sklearn
* pathlib

## Built With

* Visual Studio Code - The source code editor used for development.
* GitHub Copilot - AI assistant that helps in writing better code.
* ChatGPT - AI model for generating documentation and guidance.

## Features

Personalized Recommendations: Offers loan options based on individual financial situations, academic data, and future earnings potential. Secure and Private: Implements robust security measures to protect user data. Bias Mitigation: Ensures fair and unbiased recommendations through regular audits.

## Installation

To set up this project locally, follow these steps: Clone the repository:

* git clone https://github.com/tasnyde/student-loan-recommendation-system.git
* Navigate to the project directory: cd student-loan-recommendation-system
* Install dependencies: Bash pip install -r requirements.txt

## Requirements

* Prepare the Data for Use on a Neural Network Model (15 points)
* Two datasets were created: a target (y) dataset, which includes the "credit\_ranking" column, and a features (X) dataset, which includes the other columns. (5 points)
* The features and target sets have been split into training and testing datasets. (5 points)
* Scikit-learn's StandardScaler was used to scale the features data. (5 points)
* Compile and Evaluate a Model Using a Neural Network (30 points)
* A deep neural network was created with appropriate parameters. (10 points)
* The model was compiled and fit using the accuracy loss function, the adam optimizer, the accuracy evaluation metric, and a small number of epochs, such as 50 or 100. (10 points)
* The model was evaluated using the test data to determine its loss and accuracy. (5 points)
* The model was saved and exported to a keras file named student\_loans.keras. (5 points)
* Predict Loan Repayment Success by Using your Neural Network Model (25 points) The saved model was reloaded. (5 points)
* The reloaded model was used to make binary predictions on the testing data. (10 points)
* A classification report is generated for the predictions and the testing data. (10 points)
* Discuss creating a recommendation system for student loans (30 points)

### For Question 1:

* The response describes the data that should be collected to build a recommendation system for student loan options. (4 points)
* The response explains why they think that data should be collected. (4 points)
* The type of data described is appropriate for a recommendation system for student loan options. (2 points)

### For Question 2:

* The response chose a filtering method. (4 points)
* The student justified the choice of their filtering method. (4 points)
* The choice of filtering method was appropriate for the data selected in the previous question. (2 points)

### For Question 3:

* The response lists two real-world challenges with building a recommendation system for student loans. (4 points)
* The response explains why these challenges would be of concern for a student loan recommendation system. (6 points)

## Data

This project uses synthetic data mimicking real-world scenarios involving student financial profiles and loan details. The data can be retrieved at: "https://static.bc-edx.com/ai/ail-v-1-0/m18/lms/datasets/student-loans.csv"

## Contributing

This project benefits from the contributions of:

* edX Boot Camps LLC - Educational partner providing guidance and resources.

## Authors

* **edX Boot Camps** - _Initial work_
* **Todd Snyder** - _Final work_

## License

This project is not licensed and is available for educational and non-commercial use only


