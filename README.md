# Logistic-Regression-Project

A Logistic Regression project implemented in Python using the Breast Cancer dataset. The project involves data preprocessing, training the model, evaluating performance using confusion matrix, accuracy score, and k-fold cross-validation.

---

## Dataset

- **Name**: Breast Cancer Dataset
- **Description**: This dataset contains features related to breast cancer diagnosis and the target variable:
  - `2`: Benign
  - `4`: Malignant
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer)  
- The dataset file, `breast_cancer.csv`, is included in the repository.

---

## Project Workflow

1. **Importing Libraries**
   - Libraries used: `numpy`, `pandas`, `matplotlib`, and `sklearn`.

2. **Loading the Dataset**
   - The dataset is read using `pandas` and split into features (`X`) and the target (`y`).

3. **Data Splitting**
   - Data is split into training and test sets using an 80/20 ratio.

4. **Training the Logistic Regression Model**
   - Model is trained using `sklearn.linear_model.LogisticRegression`.

5. **Evaluating the Model**
   - Predictions are made on the test set.
   - Evaluation metrics include:
     - **Confusion Matrix**
     - **Accuracy Score**

6. **Cross-Validation**
   - k-Fold Cross Validation is performed to validate model accuracy.

---

## Results

- **Confusion Matrix**:

- **Accuracy Score**: 98.54%
- **Cross-Validation Accuracy**: 96.16% (±2.51%)

---

## Requirements

- Python 3.x
- Libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `sklearn`

---

## Usage

1. Clone the repository:
 ```bash
 git clone https://github.com/your-username/Logistic-Regression-Project.git
 cd Logistic-Regression-Project
 
