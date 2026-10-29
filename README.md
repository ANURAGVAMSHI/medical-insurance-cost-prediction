# Medical Insurance Cost Prediction

## Project Overview
This project uses machine learning to predict medical insurance charges based on personal and lifestyle-related features such as age, sex, BMI, number of children, smoking status, and region.

## Objectives
- Explore and analyse the insurance dataset.
- Preprocess categorical features using one-hot encoding.
- Train a Linear Regression model.
- Evaluate model performance using Mean Absolute Error (MAE) and R² score.

## Technologies Used
- Python
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab

## Dataset
The dataset contains customer information and corresponding medical insurance charges.

**Target variable:** `charges`

**Features:** `age`, `sex`, `bmi`, `children`, `smoker`, and `region`.

Dataset source and licence: Add the original dataset source and licence information here.

## Machine Learning Workflow
1. Load and explore the dataset.
2. Check for missing values and understand feature distributions.
3. Encode categorical variables.
4. Split the data into training and testing sets.
5. Train a Linear Regression model.
6. Generate predictions on the test set.
7. Evaluate the model using MAE and R² score.

## Model Performance
- **R² Score:** 0.7836
- **Mean Absolute Error (MAE):** 4181.19

The model explains approximately 78.36% of the variation in the target variable on the test set. The MAE represents the average absolute difference between actual and predicted insurance charges, in the dataset's charge units.

## How to Run
1. Clone or download this repository.
2. Open `medical_insurance_prediction.ipynb` in Google Colab or Jupyter Notebook.
3. Ensure `insurance.csv` is available at the path used in the notebook.
4. Run the notebook cells in order.

## Future Improvements
- Compare Linear Regression with Random Forest Regression.
- Tune model hyperparameters.
- Improve preprocessing and model evaluation.
- Build a simple interface for making predictions.

## Disclaimer
This project is for educational purposes only. Predictions are estimates and should not be treated as professional insurance or medical advice.
