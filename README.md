# League Rank Prediction for Top Eleven

## Overview
This project aims to predict the end-of-season league ranks for users in the game Top Eleven. By analyzing historical gameplay data, the model developed provides a fair and challenging experience by forecasting the competitive standings of each user within their league.

## Files
- `1. Train model (DS Challenge).ipynb`: Jupyter notebook containing the model training process.
- `2. Scoring model (DS Challenge).ipynb`: Jupyter notebook for scoring the model and generating predictions.
- `jobfair_train.csv`: Training dataset with features and league ranks.
- `jobfair_test.csv`: Test dataset for which league ranks need to be predicted.
- `league_rank_predictions.csv`: Output file with predicted league ranks.

## Model Development
The project followed a thorough machine learning pipeline including:
- Data preprocessing and feature engineering to adapt the dataset for model training.
- Evaluation of different regression models using cross-validation to select the best performer based on Mean Absolute Error (MAE).
- Implementation of a RandomForestRegressor which demonstrated high accuracy in league rank predictions.

## Production Readiness
In the production environment, a specialized pipeline was implemented to ensure consistent preprocessing of test data. The code is structured to be robust and easily adaptable, ensuring it meets real-world operational requirements.

## Predictions and Evaluation
The best model is used to predict league ranks on a withheld test set. These predictions are then ranked to reflect the actual league standings format. The final predictions are evaluated using MAE to ensure accuracy and reliability.

## Usage
To replicate the prediction process or to apply the model to new data, follow these steps:
1. Load the trained model using the provided Jupyter notebook.
2. Preprocess the new test data using the established pipeline to match the training data format.
3. Use the model to predict league ranks and assign ranks within each league.

## Contributions
This project is open for contributions. Please ensure to maintain the coding and documentation standards as described in this repository.

## Contact
For any queries or discussions related to this project, please reach out via the Issues section in this GitHub repository.

## Acknowledgements
This project was developed for the Data Science Challenge at Nordeus - Job Fair 2023. Gratitude is extended to all the participants and organizers for their support and contributions to this endeavor.
