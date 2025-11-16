Titanic Survival Prediction — CodSoft Data Science Internship

This project predicts whether a passenger survived the Titanic disaster using a Machine Learning model trained on passenger details such as age, gender, passenger class, fare, and family size.

 Project Workflow
Import Required Libraries
Load and Explore Dataset
Data Pre-processing
Handling Missing Values
Label / One-Hot Encoding
Feature Selection
Train–Test Split
Logistic Regression Model Training
Accuracy Evaluation
Save Trained Model
Generate Predictions (CSV Output)

 Repository Files
File Name	Description
Untitled4.ipynb	Jupyter Notebook containing full project code
titanic_survival_model.pkl	Serialized (saved) trained ML model
titanic_prediction_results.csv	Generated predictions on test data

 Technologies Used
Python
Pandas
NumPy
Scikit-Learn
Jupyter Notebook / Google Colab

How to Run This Project
Clone the repository
git clone https://github.com/SaiDeepthi30/CODSOFT.git
Open the Jupyter notebook:
jupyter notebook Untitled4.ipynb
Run all cells to train and evaluate the model.
To use the saved model:
import pickle
model = pickle.load(open("titanic_survival_model.pkl", "rb"))

Internship Information:
This project is Task-1 of the CodSoft Data Science Internship — November Batch.

 Future Enhancements (Optional to add)
Try different ML models (Random Forest / XGBoost)
Build a GUI or web app using Streamlit
Deploy on Hugging Face / Heroku

