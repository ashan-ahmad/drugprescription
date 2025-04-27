# Drug Prescription Prediction using Decision Trees

This project demonstrates the use of Decision Trees to predict the appropriate drug for a patient based on their medical attributes. The dataset contains information about patients who suffered from the same illness and their responses to five different drugs: Drug A, Drug B, Drug C, Drug X, and Drug Y.

## Project Overview

The goal of this project is to build a machine learning model that can predict the most suitable drug for a patient based on their features such as Age, Sex, Blood Pressure, and Cholesterol levels. The project involves the following steps:

1. **Data Loading and Exploration**: Load the dataset and explore its structure and contents.
2. **Data Preprocessing**: Perform label encoding for categorical variables and handle missing values if any.
3. **Data Visualization**: Analyze the distribution of drugs and the correlation between features and the target variable.
4. **Modeling**: Train a Decision Tree Classifier to predict the drug.
5. **Evaluation**: Evaluate the model's performance using accuracy metrics.
6. **Visualization**: Visualize the decision tree to interpret the model's decision-making process.

## Dataset

The dataset used in this project is publicly available and contains the following features:
- **Age**: Age of the patient.
- **Sex**: Gender of the patient (Male/Female).
- **BP**: Blood Pressure levels (High/Low/Normal).
- **Cholesterol**: Cholesterol levels (High/Normal).
- **Na_to_K**: Sodium to Potassium ratio in the blood.
- **Drug**: The drug prescribed to the patient (Target variable).

## Libraries Used

The following Python libraries are used in this project:
- `numpy`
- `pandas`
- `matplotlib`
- `sklearn`

## Key Features

- **Data Preprocessing**: Label encoding for categorical variables and mapping target labels to numerical values.
- **Correlation Analysis**: Analyze the correlation between input features and the target variable.
- **Decision Tree Modeling**: Train and evaluate a Decision Tree Classifier with different depths.
- **Visualization**: Visualize the decision tree and the distribution of drug categories.

## How to Run

1. Clone the repository to your local machine.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Open the Jupyter Notebook file `Drug_Prescription.ipynb`.
4. Run the cells sequentially to execute the code and view the results.

## Results

The Decision Tree model achieves a high accuracy in predicting the appropriate drug for patients. The decision tree visualization provides insights into the criteria used by the model for classification.

## Future Improvements

- Experiment with other machine learning models like Random Forests or Gradient Boosting.
- Perform hyperparameter tuning to optimize the Decision Tree model.
- Add more features to the dataset for better predictions.

## Acknowledgments

The dataset used in this project is provided by IBM Developer Skills Network as part of their Machine Learning course.

## License

This project is licensed under the MIT License. Feel free to use and modify the code as needed.
