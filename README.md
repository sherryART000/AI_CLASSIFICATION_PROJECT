# Lung Cancer Prediction System using Machine Learning with GUI
An end-to-end Machine Learning application for predicting pulmonary disease (lung cancer) based on patient medical information. The project includes data preprocessing, model training, evaluation, and a desktop Graphical User Interface (GUI) built with **Tkinter** for real-time predictions.


# Project Overview
Early detection of lung cancer can significantly improve treatment outcomes. This project applies Machine Learning techniques to classify whether a patient is likely to have pulmonary disease using medical and lifestyle-related features.
The project follows the complete Machine Learning pipeline, starting from loading and preprocessing the dataset, training a classification model, evaluating its performance, and finally deploying it through an interactive GUI.

# Features

*  Load and explore the dataset
*  Data preprocessing
*  Check for missing values
*  Encode categorical target values using LabelEncoder
*  Train a Gaussian Naive Bayes classifier
*  Evaluate model performance
*  Generate a Confusion Matrix
*  Display a Classification Report
*  Interactive GUI using Tkinter
*  Predict pulmonary disease instantly from user input
  
# Technologies Used
* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Tkinter
* Jupyter Notebook

 # Dataset

The dataset contains **5,000 patient records** with **18 attributes**, including:
* Age
* Gender
* Smoking
* Finger Discoloration
* Mental Stress
* Exposure to Pollution
* Long-Term Illness
* Energy Level
* Immune Weakness
* Breathing Issue
* Alcohol Consumption
* Throat Discomfort
* Oxygen Saturation
* Chest Tightness
* Family History
* Smoking Family History
* Stress Immune
* Pulmonary Disease (Target)

The target variable is:
* **YES** → Pulmonary Disease
* **NO** → No Pulmonary Disease

# Machine Learning Pipeline

1. Import required libraries
2. Load the dataset
3. Explore the data
4. Check for missing values
5. Encode categorical labels
6. Split the dataset into training and testing sets
7. Train the Gaussian Naive Bayes model
8. Evaluate the model
9. Display the Confusion Matrix
10. Generate the Classification Report
11. Build a GUI for user interaction

# Machine Learning Model
The project uses:
**Gaussian Naive Bayes (GaussianNB)**
Gaussian Naive Bayes is suitable for continuous numerical features and provides fast and efficient classification with relatively low computational cost.

# Model Evaluation
The model performance is evaluated using:
* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Classification Report

# Graphical User Interface (GUI)
The application includes a desktop GUI built with **Tkinter**, allowing users to:
* Enter patient medical information
* Submit the data
* Receive an instant prediction
* View whether pulmonary disease is predicted
This makes the project easy to use without interacting directly with the notebook.

# How to Run
# Clone the repository
```bash
git clone https://github.com/sherryART000/AI_CLASSIFICATION_PROJECT.git
```

# Navigate to the project folder
```bash
cd AI_CLASSIFICATION_PROJECT
```

# Install dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

# Run the notebook
```bash
jupyter notebook
```
Open **lung_cancer with gui.ipynb** and run all cells.

# Project Structure
AI_CLASSIFICATION_PROJECT/
│
├── lung_cancer with gui.ipynb
├── README.md
└── Dataset (CSV)

# Future Improvements
* Compare multiple Machine Learning algorithms (Random Forest, XGBoost, SVM, Logistic Regression)
* Perform hyperparameter tuning
* Save the trained model using Joblib or Pickle
* Deploy the project as a web application using Flask or Streamlit
* Add probability scores for predictions
* Improve the GUI design and user experience


Author
**Sherry Adel**
Faculty of Computers and Artificial Intelligence
Interested in:
* Machine Learning
* Natural Language Processing (NLP)
* Artificial Intelligence
* Data Science

GitHub:
https://github.com/sherryART000
