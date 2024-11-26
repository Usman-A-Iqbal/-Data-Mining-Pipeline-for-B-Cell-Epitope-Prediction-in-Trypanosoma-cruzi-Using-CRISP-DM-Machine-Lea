# Data Mining Pipeline for B-Cell Epitope Prediction in Trypanosoma cruzi Using CRISP-DM: Machine Learning, EDA, Preprocessing, Hyperparameter Tuning & Evaluation

Developed a computational pipeline, in Python, to predict potential B-cell epitopes for Trypanosoma cruzi, the parasite responsible for Chagas’ disease. This project utilised the CRISP-DM methodology.

• Exploratory Data Analysis (EDA) & Pre-processing: Conducted comprehensive EDA to uncover patterns and correlations in the dataset. Cleaned and split the data, extracted relevant features & performed a range of class balancing techniques (including undersampling, oversampling & SMOTE).

• This image shows the class imbalance idenfified in the dataset.
<img width="524" alt="image" src="https://github.com/user-attachments/assets/7a220a80-e5f7-40ee-93df-48246ea6e94f">


• This graph shows the relevant features extracted using Information Gain - the top ten used for modelling.
<img width="606" alt="image" src="https://github.com/user-attachments/assets/e4eff02a-3ca9-4f72-bd67-ac8f2e5da589">

• Model Development: Implemented various machine learning models, such as Decision Tree, Random Forest, Support Vector Machine, Logistic Regression and an artificial neural network, to predict new B-cell epitopes. Evaluated model performance using metrics including balanced accuracy, precision, recall, and F1-score.

• Epitope Prediction: Developed a Pipeline with the best-performing model using a Functional programming approach in Python and applied the trained model to predict potential epitopes in T. cruzi proteins.



