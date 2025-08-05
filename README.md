---
COVID19-Exploratory Data Analysis and Machine Learning
AND
Titanic Dataset - Exploratory Data Analysis and Machine Learning

This project performs comprehensive Exploratory Data Analysis (EDA), Data Preprocessing, and Machine Learning Modeling on the iconic Titanic dataset. The dataset captures the fate of passengers aboard the RMS Titanic, one of the most infamous shipwrecks in history and also file for covid 19 death recovered ratio


---

📌 Objectives

Understand the structure and characteristics of the Titanic dataset also 
Understand the structure and characteristics of the covid19 dataset 

Use 11+ visualization methods to explore relationships between features and survival.

Perform data cleaning and feature engineering.

Train and evaluate multiple machine learning models to predict survival.



---

📊 Exploratory Data Analysis (EDA)

The EDA includes a variety of plots and visualizations to discover insights into the dataset. The following plot types were used:

Bar Plot

Swarm Plot

Line Plot

Scatter Plot

Heatmap

Violin Plot

Box Plot

Histogram

Count Plot

Facet Grid Plot

Pair Plot


🔍 Key Explorations:

Survival rate by gender and class

Age and fare distributions

Correlation heatmap of numeric features

Distribution of passengers across different ports (Embarked)



---

🧹 Data Preprocessing

Key preprocessing steps:

Handling Missing Values: 

Feature Engineering:

Extracted titles 


Binning of continuous variables 


Encoding: Categorical features were encoded using LabelEncoding and/or One-Hot Encoding.

Scaling: Numerical features were scaled for model compatibility.



---

🤖 Machine Learning Models

The dataset was split into training and testing sets, and the following models were trained and evaluated:

Model	Description

Logistic Regression	Linear classification model
Decision Tree	Tree-based classification algorithm
Random Forest	Ensemble of decision trees
Gradient Boosting	Boosted ensemble tree model


✅ Evaluation

Models were evaluated using accuracy score.

Confusion matrices and classification reports may have been used to measure performance.



---

📌 Results

Best performing models: Ensemble methods (Random Forest, Gradient Boosting) showed strong accuracy.



---

🛠 Libraries Used

pandas, numpy

matplotlib, seaborn

scikit-learn

missingno (optional)

plotly (if interactive plots were used)



---

🚀 How to Run

1. Clone the repository or download the .ipynb notebook.


2. Install dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn


3. Run the notebook in Jupyter or Colab.




---

📁 Dataset

The dataset is freely available from Kaggle Titanic Competition and includes information like passenger name, age, sex, ticket class, fare, and survival status.

covid19 dataset is also from kaggle and include large amount of data of different countries recovered and deaath ratio
---

📌 Future Work

Hyperparameter tuning for improved model performance.

Deployment of the best model via a web app.

More advanced feature selection techniques (e.g., PCA, Recursive Feature Elimination).



---

🙏 Acknowledgments

Thanks to the open community for the Titanic dataset and covid.
This notebook is created for learning, exploration, and model experimentation.
