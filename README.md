
# 🧠 Sonar Object Prediction AI Model

Predict whether an object detected by sonar is a **mine** or **rock** using machine learning techniques.

This project uses **Logistic Regression** on a sonar frequency dataset to classify underwater objects based on the sonar signal's attributes.

---

## 📊 Overview

* **Dataset**: [Sonar dataset](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+%28sonar,+mines+vs.+rocks%29) from the UCI ML Repository.
* **Model**: Logistic Regression using `scikit-learn`
* **Purpose**: Classify sonar signals as either a *mine* or a *rock* based on 60 frequency-based attributes.
* **Tool Used**: Jupyter Notebook (`.ipynb`) for step-by-step data analysis and modeling.

---

## 📁 File Structure

```
Sonar-Object-Prediction-AI-Model/
├── Submarine_Sonar_LogisticRegression_Model.ipynb  # Main notebook
├── sonar data.csv                                  # Dataset
└── README.md                                       # Project documentation
```

---

## 🔍 Dataset Details

* **Instances**: 208
* **Attributes**: 60 continuous features + 1 target label
* **Labels**:

  * `M` = Mine
  * `R` = Rock

Each instance represents sonar signal returns bounced off an object, with 60 features representing the energy within a particular frequency band.

---

## 🚀 Project Workflow

1. **Data Loading**
   Read CSV file using pandas and inspect the structure.

2. **Exploratory Data Analysis (EDA)**

   * Check for null values
   * Visualize label distribution
   * Convert labels (`M`/`R`) to binary numeric values

3. **Data Preprocessing**

   * Normalize input features
   * Split data into training and test sets

4. **Model Building**

   * Implement **Logistic Regression** using scikit-learn
   * Fit on training data

5. **Evaluation**

   * Accuracy score
   * Classification report
   * Confusion matrix

6. **Prediction Example**

   * Input a custom sonar signal array
   * Predict class and interpret output

---

## 📈 Results

* Achieved **\~82% accuracy** on test data using Logistic Regression.
* Can reliably distinguish sonar signals from mines vs. rocks.
* Lightweight and interpretable baseline model.

---

## 📦 Requirements

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

Or simply run the notebook in Google Colab or Jupyter Lab.

---

## 🧠 Concepts Used

* Logistic Regression
* Data normalization
* Train-test split
* Binary classification
* Confusion matrix & classification report

---

## 🧪 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/vedantmpatil/Sonar-Object-Prediction-AI-Model.git
   cd Sonar-Object-Prediction-AI-Model
   ```

2. Open the notebook:

   ```bash
   jupyter notebook Submarine_Sonar_LogisticRegression_Model.ipynb
   ```

3. Run all cells and interact with the prediction section.

---

## 🌐 References

* UCI Machine Learning Repository: [Sonar Dataset](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+%28sonar,+mines+vs.+rocks%29)
* [Scikit-learn documentation](https://scikit-learn.org/stable/)

---

## 🙌 Author

**Vedant Patil**
📫 [GitHub Profile](https://github.com/vedantmpatil)

---


