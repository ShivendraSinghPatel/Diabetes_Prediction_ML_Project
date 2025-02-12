# Diabetes Prediction Using Machine Learning

## Overview
This project aims to predict whether a person has diabetes based on certain medical attributes. The model is trained using a dataset containing medical diagnostic measurements and uses a Support Vector Machine (SVM) classifier to make predictions.

## Dataset
The dataset used in this project is **diabetes.csv**, which contains the following features:
- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skinfold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index
- **DiabetesPedigreeFunction**: Diabetes pedigree function
- **Age**: Age of the person
- **Outcome**: Target variable (0: Non-Diabetic, 1: Diabetic)

## Project Workflow
1. **Data Collection & Analysis**
   - Load the dataset
   - Display summary statistics and data insights
   - Handle missing values (if any)

2. **Data Preprocessing**
   - Standardization using `StandardScaler`
   - Splitting the dataset into training and testing sets

3. **Model Training**
   - Using **Support Vector Machine (SVM)** for classification
   - Training the model on the training dataset

4. **Model Evaluation**
   - Calculating accuracy scores on both training and testing datasets

5. **Making Predictions**
   - Creating a predictive system to test new inputs

## Installation & Usage
### Prerequisites
Ensure you have Python installed along with the necessary libraries:
```sh
pip install numpy pandas scikit-learn
```

### Running the Project
1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/diabetes-prediction.git
   cd diabetes-prediction
   ```
2. Run the Jupyter Notebook:
   ```sh
   jupyter notebook "Diabetes Prediction Project.ipynb"
   ```
3. Follow the steps inside the notebook to train and evaluate the model.

## Results
- The trained model achieves a certain accuracy on both training and test data (Replace with actual results after running the model).
- The predictive system takes user input and classifies the person as diabetic or non-diabetic.

## Future Improvements
- Experiment with other ML algorithms like Random Forest or Neural Networks.
- Perform feature selection to improve model performance.
- Deploy the model as a web application using Flask or FastAPI.

## Author
**Shivendra Singh**



