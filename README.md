# House-Price-Prediction-using-Regression
This project focuses on predicting housing prices based on property-related features using multiple machine learning regression techniques.

## Objective
The objective of this project is to analyze a housing dataset and build a predictive model that can accurately estimate property prices. The project covers the entire machine learning process, from Exploratory Data Analysis (EDA) and data preprocessing to model evaluation and comparison.

## Dataset Information
This project uses the USA_Housing.csv dataset, which contains 5000 entries with the following features:
- Avg. Area Income: Average income of residents in the city of the house.
- Avg. Area House Age: Average age of houses in the same city.
- Avg. Area Number of Rooms: Average number of rooms for houses in the same city.
- Avg. Area Number of Bedrooms: Average number of bedrooms for houses in the same city.
- Area Population: Population of the city where the house is located.
- Price: Price at which the house was sold (Target Variable).
- Address: Address of the house.

## Tech Stack
The following libraries and tools were uses:
- **Pandas & NumPy**: For data manipulation and numerical analysis.
- **Matplotlib & Seabord**: For data visualization and identifying patterns.
- **Scikit-Learn**: For building and evaluating regression models
- **XGBoost**: For advanced gradient boosting implementation

## Project Workflow
1. **Exploratory Data Analysis (EDA)**:
- Checked for missing values and Duplicates
- Visualized data distributions
- Identified Outliers using Boxplots
2. **Model Building**:
- Split the data into training and test sets
- Implemented several regression algorithms:
- - Linear Regression
  - Decision Tree Regressor
  - Gradient Boost Regressor
  - XGBoost Regressor
3. **Evaluation**: Models were evaluated using Mean Squared Error(MSE), Root Mean Squared Error(RMSE), Mean Absolute Error(MAE), and R-Squared (R2) scores.

### Results
- **Linear Regression**: Achieved R2 score of 0.91 of Training Data
- **Decision Tree**: Achieved a Training accuracy of 89% and Test accuracy of 77% 
