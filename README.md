# 🩺 Diabetes Prediction using SVM

This project uses a **Support Vector Machine (SVM)** model to predict whether a person is diabetic or not, based on the PIMA Diabetes dataset.

---

## 📄 Dataset

- **Source:** [Kaggle - PIMA Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Description:** The dataset contains 768 samples with 8 medical features per patient (such as glucose level, BMI, and age). The label indicates whether the person is diabetic (`1`) or non-diabetic (`0`).

---

## ⚙️ Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn

---

## 🚀 Project Workflow

### 1️⃣ Data Loading & Exploration

- Load diabetes data using Pandas.
- Understand feature distributions and outcome counts.

### 2️⃣ Data Preprocessing

- Separate features and labels.
- Standardize the data using `StandardScaler`.

### 3️⃣ Data Splitting

- Split data into training and test sets using `train_test_split`, ensuring balanced classes via stratification.

### 4️⃣ Model Training

- Train an SVM model with a linear kernel on the training data.

### 5️⃣ Model Evaluation

- Evaluate the model’s accuracy on both training and test sets.
- Check for overfitting or underfitting.

### 6️⃣ Prediction on New Data

- Use the trained model to predict diabetes for new custom input data.

---

## ✅ Results

- **Training Accuracy:** High accuracy on training data (as per output).
- **Test Accuracy:** Good generalization on test data.
- **Sample Prediction:** The model correctly predicts unseen input as diabetic or non-diabetic.

---

## 💡 What We Learned

- How to preprocess medical datasets.
- Applying SVM for binary classification tasks.
- Evaluating model performance using accuracy.
- Building a simple prediction system to assist healthcare screening.

---

## 📥 How to Run

1️⃣ **Clone this repository:**

```bash
git clone https://github.com/RONAKBAGRI/Diabetes-Prediction-using-SVM.git
```

2️⃣ **Install dependencies:**
```bash
pip install numpy pandas scikit-learn
```

3️⃣ **Run the notebook:**
```bash
jupyter notebook Diabetes_Prediction.ipynb
```
