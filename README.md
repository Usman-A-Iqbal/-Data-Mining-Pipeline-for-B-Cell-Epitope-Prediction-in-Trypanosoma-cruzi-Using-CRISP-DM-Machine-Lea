# Data Mining Pipeline for B-Cell Epitope Prediction in Trypanosoma cruzi Using CRISP-DM: Machine Learning, EDA, Preprocessing, Hyperparameter Tuning & Evaluation


Developed a computational pipeline, in Python, to predict potential B-cell epitopes for Trypanosoma cruzi, the parasite responsible for Chagas’ disease. This project utilised the CRISP-DM methodology.

## Exploratory Data Analysis (EDA) & Pre-processing
• Conducted comprehensive EDA to uncover patterns and correlations in the dataset. Cleaned and split the data, extracted relevant features & performed a range of class balancing techniques (including undersampling, oversampling & SMOTE).

•  This graph shows the number of missing values per column in the high dimensional dataset
<img width="602" alt="image" src="https://github.com/user-attachments/assets/3eabc5c9-ff5a-4499-843e-e54e1f78ac4d">

•  This graph shows the number of missing values per row in the high dimensional dataset
<img width="617" alt="image" src="https://github.com/user-attachments/assets/cc60e69d-6173-438c-adf1-c94abae4b60f">

•  This graph shows the difference between the maxima and minima between the features in the high dimensional dataset. It helps determine the scaling of the dataset.
<img width="487" alt="image" src="https://github.com/user-attachments/assets/401ffc7f-b58d-4711-bf29-d355586fde64">

• This image shows the class imbalance identified in the dataset.
<img width="524" alt="image" src="https://github.com/user-attachments/assets/7a220a80-e5f7-40ee-93df-48246ea6e94f">


• Dimensionality reduction was performed using feature selection (filter method). This graph shows the relevant features extracted using Information Gain - the top ten used for modelling.
<img width="606" alt="image" src="https://github.com/user-attachments/assets/e4eff02a-3ca9-4f72-bd67-ac8f2e5da589">

• This graph shows the the top 15 most important features used to diffrentiate between the classes in the Random forest model. In this case Feature selection was performed utalising an Embedded method.

<img width="608" alt="image" src="https://github.com/user-attachments/assets/87c7a448-427f-4c71-b70f-a7ee1bee2d79">

## Model Development

• Implemented various machine learning models, such as Decision Tree, Random Forest, Support Vector Machine, Logistic Regression and an artificial neural network, to predict new B-cell epitopes. Evaluated model performance using metrics including balanced accuracy, precision, recall, and F1-score.

## Epitope Prediction
• Developed a Pipeline with the best-performing model using a Functional programming approach in Python and applied the trained model to predict potential epitopes in T. cruzi proteins.

<img width="425" alt="image" src="https://github.com/user-attachments/assets/f63c8d7d-b768-42cd-b08e-81c268399f85">


# Tools and Technologies 

## Python
## Scikit-Learn
## Pandas
## NumPy
## Matplotlib
## Jupyter Notebook
## Google Colab 
## GPU hardware acceleration
## CRISP-DM methodology

