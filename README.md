This project predicts whether a hotel booking will be canceled based on customer and booking details. It uses various machine learning models to classify bookings and offers a simple web-based interface for real-time predictions.

Project Structure
app.py: The main Python script that runs the web application. Users can input booking details and get a prediction on whether a booking will be canceled.
decision_tree_model.pkl: Pre-trained Decision Tree model saved as a pickle file to be used in the app for predictions.
Jupyter Notebooks:
DecisionTreeClassification.ipynb: A notebook implementing Decision Tree classification.
EnsembleLearningMethods.ipynb: Demonstrates several ensemble learning methods (e.g., Bagging, Random Forest, and Boosting) to improve model accuracy.
ExtraTreesOverFitting.ipynb: Focuses on overfitting issues and how extra trees can help overcome this.
IterativeImputerModel.ipynb: Shows how to handle missing data using iterative imputation techniques.
MeanMedianModel.ipynb: Uses mean and median imputation for missing data and compares model performance.
SeveralClassificationModels.ipynb: Implements various classification models (Logistic Regression, Decision Trees, Random Forest, etc.) and compares their performance.
requirements.txt: Contains a list of Python packages required to run the project.
