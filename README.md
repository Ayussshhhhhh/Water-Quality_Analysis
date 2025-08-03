# Water-Quality_Analysis
This project develops a machine learning model to predict whether water is potable (safe for human consumption) based on various water quality parameters. The model analyzes features such as pH, Hardness, Solids, Chloramines, Sulfate, Conductivity, Organic_carbon, Trihalomethanes, and Turbidity.

# Dataset

The dataset used is the "Water Quality" dataset from Kaggle, available at Kaggle Dataset. It includes:





Features: pH, Hardness, Solids, Chloramines, Sulfate, Conductivity, Organic_carbon, Trihalomethanes, Turbidity



Target Variable: Potability (0 for non-potable, 1 for potable)



Number of Rows: 3276 (original), reduced to 2011 after handling missing values

# Model

The notebook (Data Model WQA.ipynb) includes:





Data Preprocessing: Cleaning data by removing rows with missing values and standardizing features.



Exploratory Data Analysis (EDA): Visualizations like correlation heatmaps, histograms, pair plots, and count plots to explore feature relationships and distributions.



Machine Learning Models: Training and evaluating multiple classification models, including Logistic Regression, Support Vector Machine (SVM), Decision Tree, Random Forest, Gradient Boosting, AdaBoost, and K-Nearest Neighbors (KNN).



Model Performance: The Gradient Boosting Classifier performed best, achieving:





Accuracy: 98.75%



Precision: 97.22%



Recall: 100%



F1-Score: 98.59%



Visualizations: Includes a confusion matrix and ROC curve for the Gradient Boosting Classifier, with an ROC AUC score of 98.90%.

# How to Use





Clone this repository to your local machine.



Install required Python libraries: pandas, numpy, scikit-learn, matplotlib, seaborn.

pip install pandas numpy scikit-learn matplotlib seaborn



Download the dataset from Kaggle and place water_potability.csv in your working directory.



Open and run the Data Model WQA.ipynb notebook in a Jupyter environment.
