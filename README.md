# Machine Learning Modeling with the Iris Dataset

This project applies various machine learning algorithms to the Iris dataset to classify different types of iris flowers. The study covers data analysis, visualization, model training, and evaluation.

📊 Dataset
The dataset used contains Iris flower species and consists of the following variables:

SepalLengthCm (Sepal Length)
SepalWidthCm (Sepal Width)
PetalLengthCm (Petal Length)
PetalWidthCm (Petal Width)
Species (Flower Species: Iris-setosa, Iris-versicolor, Iris-virginica)
The dataset contains 150 samples, with 50 instances of each species.

🛠 Methods Used & Key Learnings
🔹 1. Data Preprocessing & Exploratory Data Analysis (EDA)
Checked for missing values.
Visualized the dataset using Seaborn & Matplotlib.
Examined species differences using boxplots, scatter plots, and pair plots.
🔹 2. Machine Learning Models
The dataset was split into 70% training and 30% testing, and the following models were applied:

Logistic Regression
Accuracy: 100%
Support Vector Machine (SVM)
Accuracy: 100%
Random Forest Classifier
Accuracy: 100%
Performance analyzed using Classification Report & Confusion Matrix.
K-Nearest Neighbors (KNN)
Used GridSearchCV to find the best k-value (k=3).
Accuracy: 97.77%
Decision Tree
Trained using the Gini criterion.
Accuracy: 97.77%
Confusion Matrix visualized.
🔹 3. Model Tuning (Hyperparameter Optimization)
GridSearchCV applied to KNN to find optimal parameters.
Random Forest and Decision Tree models were tested with different depth levels.
🚀 Results
Logistic Regression, SVM, and Random Forest achieved 100% accuracy.
KNN and Decision Tree performed well with 97.77% accuracy.
Model results were evaluated using Confusion Matrix, Precision, and Accuracy Score.
📂 Libraries Used
Pandas, NumPy (Data Processing)
Seaborn, Matplotlib (Visualization)
Scikit-Learn (sklearn) (Machine Learning Models, Model Evaluation, GridSearchCV)

