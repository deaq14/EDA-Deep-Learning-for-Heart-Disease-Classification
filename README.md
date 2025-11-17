# 🫀 Heart Disease Prediction – EDA & TensorFlow

This project performs an **Exploratory Data Analysis (EDA)** and builds a **Machine Learning model with TensorFlow** to predict the presence of heart disease. The work is developed in a Jupyter Notebook:  
`EDA_&_tensorflow_HeartDisease_prediction.ipynb`

---

##  Dataset

- Source: [Heart Failure Dataset on Kaggle](https://www.kaggle.com/datasets/tan5577/heart-failure-dataset/data)  
- File used: `heart.csv`  
- Contains clinical variables such as age, sex, blood pressure, cholesterol, maximum heart rate, chest pain type, among others.  
- The target column is **Heart Disease** (binary: 0 = no disease, 1 = disease).

---

## Libraries Used

- **pandas** → data manipulation and cleaning  
- **numpy** → numerical operations  
- **matplotlib** and **seaborn** → visualization and exploratory analysis  
- **tensorflow / keras** → building and training the classification model  

---

##  Project Workflow

1. **EDA (Exploratory Data Analysis)**  
   - Inspection of data types, missing values, and variable distributions.  
   - Visualization of relationships between features and the target label.  
   - Correlation analysis and identification of relevant patterns.

2. **Preprocessing**  
   - Scaling of numerical variables.  
   - One-hot encoding of categorical variables.  
   - Train/test split with stratification.

3. **Modeling with TensorFlow**  
   - Multilayer Perceptron (MLP) with dense layers and regularization.  
   - Training with validation and *early stopping*.  
   - Metrics: Accuracy and AUC.

4. **Model Evaluation**  
   - Classification report (precision, recall, F1-score).  
   - Confusion matrix (counts and normalized).  
   - ROC curve to assess performance.

---

## Results

- The model achieves solid classification performance between patients with and without heart disease.  
- The confusion matrix and ROC curve provide clear insights into model accuracy and misclassifications.  

---

## How to Run

1. Clone this repository or download the notebook.  
2. Download the dataset from Kaggle and place the file `heart.csv` in the same directory as the notebook.  
3. Install the required dependencies:  

   ```bash
   pip install pandas numpy matplotlib seaborn tensorflow
