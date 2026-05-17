# Handwritten-Digit-Classification-using-LDA-and-Logistic-Regression
Machine Learning project for handwritten digit classification using LDA and Logistic Regression. Includes EDA, data preprocessing with StandardScaler, dimensionality reduction using Linear Discriminant Analysis (LDA), visualization, model training, and evaluation using Python and Scikit-learn.
# ✨ Handwritten Digit Classification using LDA and Logistic Regression

## 📌 Project Overview

This project focuses on handwritten digit classification using **Linear Discriminant Analysis (LDA)** and **Logistic Regression**. The model is trained on the **Scikit-learn Digits Dataset**, which contains 8×8 grayscale images representing handwritten digits from 0 to 9.

The project demonstrates a complete Machine Learning workflow including:

* 📊 Exploratory Data Analysis (EDA)
* 🧹 Data Preprocessing using StandardScaler
* 📉 Dimensionality Reduction using LDA
* 🤖 Logistic Regression Model Training
* 📈 Model Evaluation and Visualization

---

# 📂 Dataset Information

* **Dataset:** Scikit-learn Digits Dataset
* **Total Samples:** 1797
* **Features:** 64 pixel-based numerical features
* **Classes:** 10 handwritten digit classes (0–9)

### 🔑 Dataset Keys

* `data` → Feature matrix
* `target` → Digit labels
* `feature_names` → Pixel feature names
* `images` → Original image format
* `DESCR` → Dataset description

---

# ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

# 🚀 Project Workflow

## 1️⃣ Data Loading

The digits dataset was loaded using Scikit-learn’s built-in dataset module.

## 2️⃣ Exploratory Data Analysis (EDA)

EDA techniques were used to understand:

* Feature distributions
* Pixel intensity patterns
* Correlation between features
* Dataset structure and class distribution

### 📊 Visualizations Used

* Histograms
* Heatmaps
* Boxplots
* Pairplots
* LDA Projection Plots

---

## 3️⃣ Data Preprocessing

The dataset was standardized using **StandardScaler** before applying LDA.

### ✅ Why StandardScaler?

* Ensures equal contribution of all features
* Improves model performance
* Helps dimensionality reduction techniques work effectively

---

## 4️⃣ Linear Discriminant Analysis (LDA)

LDA was applied for dimensionality reduction and class separation.

### ✅ Advantages of LDA

* Reduces feature dimensions
* Maximizes class separability
* Improves classification efficiency
* Removes redundant information

---

## 5️⃣ Logistic Regression

A Logistic Regression classifier was trained on the LDA-transformed dataset for multiclass handwritten digit classification.

---

## 6️⃣ Model Evaluation

The model performance was evaluated using:

* ✅ Accuracy Score
* ✅ Confusion Matrix
* ✅ Classification Report

---

# 📈 Results

The model achieved strong classification performance after applying LDA for dimensionality reduction. The combination of LDA and Logistic Regression efficiently classified handwritten digits while reducing dataset complexity.

### 🔑 Key Outcomes

* Improved class separation using LDA
* Reduced feature dimensions efficiently
* Achieved effective multiclass classification performance
* Demonstrated the importance of preprocessing and dimensionality reduction in Machine Learning

---

# 📚 Key Learnings

* Machine Learning workflow implementation
* Dimensionality Reduction using LDA
* Standardization and preprocessing techniques
* Multiclass classification using Logistic Regression
* Data visualization and EDA methods

---

# 🔮 Future Improvements

Possible future enhancements:

* Hyperparameter tuning
* Comparing PCA vs LDA performance
* Deep Learning implementation using CNNs
* Advanced feature engineering techniques

---

# 🏁 Conclusion

This project demonstrates how **Linear Discriminant Analysis (LDA)** can be combined with **Logistic Regression** to efficiently classify handwritten digits. LDA improved class separability while reducing dimensionality, and Logistic Regression achieved strong multiclass classification performance on the transformed dataset.

---

# 👨‍💻 Author

**Mannat**

---

# ⭐ If you found this project useful, consider giving it a star on GitHub!
