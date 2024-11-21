# Capstone-Project
### Wine Variety Predictor
This project aims to predict wine varieties based on their descriptions using Natural Language Processing (NLP) techniques. It leverages machine learning models to classify wines into different varieties, providing an effective approach for improving wine recommendations.

## Objective
The goal of this project is to build a model that accurately predicts the variety of wine based on textual descriptions. The model is trained on a dataset of wine descriptions, and the primary aim is to enhance recommendations by predicting the type of wine.

## Technologies Used
1. Python
2. pandas (Data manipulation)
3. scikit-learn (Machine learning)
4. nltk (Natural Language Processing)
5. TfidfVectorizer (Text vectorization)
6. Random Forest Classifier (Classification model)

## Project Workflow
# Data Collection:
A dataset containing wine descriptions and their corresponding varieties is used for training the model.

# Data Preprocessing:
The textual data is cleaned and preprocessed, including tokenization, stopword removal, and stemming.

# Feature Extraction:
The TfidfVectorizer is used to transform the text descriptions into numerical features that can be input into machine learning models.

# Model Training:
A Random Forest Classifier is trained on the extracted features to classify the wine variety based on its description.

# Model Evaluation:
The model’s performance is evaluated using accuracy, and improvements can be made by tuning hyperparameters.

## Installation
To run this project, you'll need to install the following Python libraries:

bash
pip install pandas scikit-learn nltk

## Usage
1. Clone the repository:
   bash
   git clone https://github.com/your-username/wine-variety-predictor.git
cd wine-variety-predictor
3. Run the script:
bash
python wine_variety_predictor.py
4. Input Data: The script requires a CSV file with columns for wine descriptions and their corresponding varieties for training the model. The file should be structured as follows:
   Description	             Variety
"A rich, bold red wine"	     Merlot
"A crisp, refreshing white"	 Chardonnay
4.Prediction: Once the model is trained, it can predict the variety of wine for a given description by using the predict() function.

### Project Structure
bash
wine-variety-predictor/
│
├── wine_variety_predictor.py  # Main Python script for prediction
├── data/
│   └── wine_data.csv         # Dataset containing wine descriptions and varieties
├── README.md                # Project documentation
└── requirements.txt         # List of dependencies

## Model Performance
1. The model achieves an accuracy of 50% based on initial tests.
2. Future improvements could focus on model tuning, additional feature engineering, and exploring different algorithms.

