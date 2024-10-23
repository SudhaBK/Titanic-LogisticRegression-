Titanic Survival Prediction
Project Description
This Streamlit app predicts Titanic passenger survival chances using logistic regression and random forest classification. It provides a user-friendly interface for inputting passenger attributes.
Features
User input fields for passenger attributes
Prediction display
Logistic regression and random forest model integration
Dependencies
pandas==1.4.2
numpy==1.22.4
scikit-learn==1.1.2
streamlit==1.12.0
seaborn==0.11.2
Usage
Clone the repository.
Install dependencies: pip install -r requirements.txt
Run the app: streamlit run Main.py
Project Structure
Main.py: Streamlit app code
Models.py: Model training code
logistic_regression_model.pkl: Trained logistic regression model file
best_model.pkl: Trained random forest model file
requirements.txt: Dependencies list
README.md: Project description
Titanic_train.csv and Titanic_test.csv: Datasets
predictions.csv: Model predictions output
Performance Metrics
Training Accuracy: 82.72%
Validation Accuracy: 81.01%
Precision: XX.XX% (calculate and insert)
Recall: XX.XX% (calculate and insert)
Future Development Plans
Implement ensemble methods (e.g., Gradient Boosting)
Incorporate additional passenger attributes
Deploy on cloud platforms (e.g., AWS, Google Cloud)
Author
Sudha BK
License
MIT
