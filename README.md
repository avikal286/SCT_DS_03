# SCT_DS_03
Build a decision tree classifier to predict weather the customer will purchase a product or service based on their demographic and behavioral data use a data set sucha as bank marketing dataset from the ucl ml respiratory
# 🎯 Customer Purchase Prediction using Decision Tree Classifier

This project uses the **Bank Marketing Dataset** to build a **Decision Tree Classifier** that predicts whether a customer will purchase a product/service (subscribe to a term deposit) based on their **demographic** and **behavioral** data.

---

## 🔍 Features Used

| Type         | Features |
|--------------|----------|
| Demographic  | `age`, `job`, `marital`, `education` |
| Financial    | `balance`, `housing`, `loan` |
| Contact Info | `contact`, `month`, `day` |
| Campaign     | `duration`, `campaign`, `pdays`, `previous`, `poutcome` |

---

## 🛠️ Technologies Used

- Python
- Pandas
- scikit-learn
- Matplotlib

---

## 🧪 ML Workflow

1. **Data Loading**
2. **Exploratory Data Analysis (EDA)**
3. **Preprocessing**
   - Label encoding of categorical columns
   - Handling missing values (if any)
4. **Train-Test Split (80:20)**
5. **Model Building using `DecisionTreeClassifier`**
6. **Model Evaluation**
   - Accuracy
   - Classification Report
7. **Tree Visualization using `plot_tree`**
8. **Predicting a New Customer's Outcome**

---

## 📊 Model Performance

- **Accuracy:** *~85-90%* (varies based on parameters)
- **Evaluation Metrics:** Precision, Recall, F1-Score for both classes (Yes/No)

---

## 🌲 Tree Visualization

The final decision tree graph is plotted using:
```python
plot_tree(clf, feature_names=X.columns, class_names=['No', 'Yes'], filled=True)
