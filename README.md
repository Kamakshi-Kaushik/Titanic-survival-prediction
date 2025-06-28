# Titanic-survival-prediction
Predicting Titanic survival prediction using ML models ( random forest, logistic regression, decision tree)
# 🚢 Titanic Survival Prediction (Kaggle Competition)

This project explores the classic **Titanic - Machine Learning from Disaster** dataset from Kaggle to build predictive models that estimate which passengers survived.

## 🎯 Objective
To analyze the Titanic dataset and predict passenger survival using classification models such as:

- Random Forest (Tuned)
- Logistic Regression (Tuned)
- Decision Tree (Tuned)

---

## 📂 Dataset

- **Source**: [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic/data)
- **Files Used**: `train.csv`, `test.csv`, `gender_submission.csv`

---

## 🧹 Data Cleaning & Feature Engineering

- Handled missing values in Age, Fare, Embarked, and Cabin
- Binned continuous variables (e.g., AgeGroup, FareBand)
- Created new features like:
  - `AgeGroup`
  - `CabinBool` (cabin info available or not)
- Encoded categorical features like `Sex` and `Embarked`

---

## 📊 Exploratory Data Analysis (EDA)

Key patterns found:
- Females had higher survival (~74%)
- Pclass 1 passengers survived more (~62%)
- Babies (<5 years) had high survival (~70%)
- Passengers with cabin info had better outcomes

---

## 🤖 Models Trained

| Model                | Tuning Done | Best Accuracy |
|---------------------|-------------|----------------|
| Random Forest        | ✅ GridSearchCV | ~82% |
| Logistic Regression  | ✅ GridSearchCV | ~78% |
| Decision Tree        | ✅ GridSearchCV | ~76% |

---

## 🔍 Feature Importance (Random Forest)
Top contributing features:
- `Sex`
- `Pclass`
- `AgeGroup`

---

## 📤 Submission

Predictions were generated using the **best-performing model** (Tuned Random Forest) and submitted to Kaggle.

---

## 🧾 Conclusion

- Random Forest delivered the highest accuracy
- Feature engineering greatly impacted model performance
- This project strengthened skills in:
  - Data Cleaning
  - EDA
  - Feature Engineering
  - Model Evaluation & Tuning

---

## 🚀 Future Enhancements

- Add ensemble techniques (Voting, Bagging, Boosting)
- Extract titles from names
- Create a `FamilySize` feature

---

## 📌 Author

**Kamakshi Kaushik**  
Beginner Data Scientist | Passionate Learner

---

## 📎 Useful Links

- 📄 [Kaggle Competition Page](https://www.kaggle.com/competitions/titanic)
## 📊 Results

- ✅ **Validation Accuracy:** 82%
- 📈 **Kaggle Leaderboard Score:** 0.77751  
- 🔗 [Kaggle Competition Link](https://www.kaggle.com/c/titanic)

- 📁 `submission.csv` is available for leaderboard entry
- 
## 📎 Live Notebook on Kaggle
You can view and run the notebook directly on Kaggle here: [Titanic Survival Prediction](https://www.kaggle.com/code/kamakshi19kaushik/titanic-survival-prediction)
