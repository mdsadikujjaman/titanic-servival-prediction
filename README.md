# Titanic Survival Prediction - Kaggle Project

This project explores the Titanic dataset from the famous Kaggle competition to predict passenger survival using supervised machine learning algorithms. The goal is to build and optimize models that can accurately classify survivors based on features like age, fare, passenger class, and family relationships.

## 🚀 Project Highlights

- Built a full machine learning pipeline using Python and scikit-learn.
- Performed Exploratory Data Analysis (EDA) with Seaborn and Matplotlib to uncover survival patterns.
- Engineered new features such as `Title` and `FamilySize` from the raw dataset.
- Handled missing values using `SimpleImputer` and feature scaling via `StandardScaler`.
- Compared models including `Random Forest`, `Gradient Boosting`, and `XGBoost` with hyperparameter tuning.
- Achieved strong accuracy and interpretability with voting ensemble techniques.

## 📊 Dataset

- **Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
- `train.csv`: Passenger data including survival label.
- `test.csv`: Data used for final predictions (without survival label).

## 📌 Key Steps

### 🔍 Exploratory Data Analysis
- Visualizations of survival by class, gender, age, embarkation port, and fare.
- Correlation heatmaps for numeric features.

### 🛠️ Feature Engineering
- Extracted `Title` from `Name`.
- Created `FamilySize` = `SibSp + Parch + 1`.
- Combined rare titles into common groups.
- Dropped non-informative columns (`Ticket`, `Cabin`, `PassengerId`).

### 🧠 Modeling
- Trained and compared the following classifiers:
  - Random Forest
  - Gradient Boosting
  - XGBoost
  - Voting Classifier (Ensemble)
- Evaluated with cross-validation and `accuracy_score`.

## 🛠️ Tools & Technologies
- Python (Pandas, NumPy)
- scikit-learn
- Seaborn & Matplotlib
- XGBoost
- Jupyter / Kaggle Notebooks

## 📈 Results
- Best model: **Voting Classifier** (Random Forest + Gradient Boosting + XGBoost)
- Achieved ~**84% accuracy** on validation set.
- Visualized model performance and data patterns throughout.

##Visualizations

<img width="892" height="412" alt="Image" src="https://github.com/user-attachments/assets/b927219e-df02-4be7-9ab1-e0daf00c8b9f" />
<img width="634" height="476" alt="Image" src="https://github.com/user-attachments/assets/476ffe73-ad05-49d4-b60e-8e587831de33" />
<img width="626" height="457" alt="Image" src="https://github.com/user-attachments/assets/0360feec-6e8d-46f4-9ce7-7bfca3af7f72" />
<img width="645" height="628" alt="Image" src="https://github.com/user-attachments/assets/06fe1617-d0d5-4054-8674-1507c5e81310" />


## 🔧 How to Run
1. Clone this repository or download the notebook.
2. Open in Jupyter Notebook or upload to [Kaggle Notebooks](https://www.kaggle.com/code).
3. Make sure to upload Titanic dataset files (`train.csv`, `test.csv`) in the same environment.
4. Run all cells to train and evaluate models.

## 🧑‍💻 Author
**Md Sadikujjaman Shihab**  
[My Kaggle Profile](https://www.kaggle.com/mdsadikujjamanshihab)

---

## 📜 License
This project is licensed under the MIT License.
