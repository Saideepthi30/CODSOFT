 Sales Prediction — CodSoft Data Science Internship
This project predicts product sales based on advertising spending across TV, Radio, and Newspaper using a Machine Learning model trained on the Sales dataset.

 Project Workflow:
Import Required Libraries
Load and Explore Dataset
Data Pre-processing
Handling Missing/Null Values
Feature Scaling (if required)
Train–Test Split
Linear Regression Model Training
Performance Evaluation (R² Score & Error Metrics)
Save Trained Model
Predict Sales and Export Output (CSV)

 Repository Files:
File Name	Description
Untitled10.ipynb	Jupyter Notebook containing the full project code
sales_prediction_model.pkl	Serialized (saved) trained ML model
sales_prediction_results.csv	Prediction results generated from the trained model

 Technologies Used:
Python
Pandas
NumPy
Scikit-Learn
Matplotlib / Seaborn
Jupyter Notebook / Google Colab

 How to Run This Project:
 Clone the Repository
bash
Copy code
git clone https://github.com/Saideepthi30/CODSOFT.git
 Open and Run Notebook
bash
Copy code
jupyter notebook Untitled10.ipynb
Run all notebook cells to train and evaluate the model.
 Use the Saved Model
python
Copy code
import pickle
model = pickle.load(open("sales_prediction_model.pkl", "rb"))

 Internship Information:
This project is Task-4 of the CodSoft Data Science Internship — November Batch.

 Future Enhancements :
Try other ML models (Random Forest, XGBoost, Lasso, Ridge Regression)
Hyperparameter tuning and cross-validation
Add interactive dashboard using Streamlit 

