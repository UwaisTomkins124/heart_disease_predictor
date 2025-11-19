
# ❤️ Heart Disease Risk Predictor

**A machine learning project that predicts the likelihood of developing heart disease using Logistic Regression.**

### 🎯 Purpose
This project aims to raise awareness about cardiovascular health, especially within African communities where routine checkups are often inaccessible or overlooked. By using data and machine learning, it encourages early attention to heart health and demonstrates how technology can aid in early diagnosis.

### 📊 Key Results (v1.0)
In this first iteration, I focused on **safety** (minimizing missed diagnoses). By analyzing the Cleveland Heart Disease dataset, the model achieved:
* **ROC-AUC Score:** `0.95` (Excellent ability to distinguish between sick and healthy patients).
* **Optimal Threshold:** `0.40` (Shifted from the default 0.50 to be more sensitive).
* **Recall:** `~0.82` (High sensitivity to ensure we catch positive cases).
* **Precision:** `~0.81` (Reliable predictions).

### 💡 Features
* **Risk Prediction:** Estimates the probability of heart disease based on clinical features.
* **Optimized Sensitivity:** Uses a custom decision threshold (0.40) to prioritize patient safety.
* **Manual Preprocessing:** Explicit step-by-step feature engineering for educational clarity.

### 📂 Project Structure
* **`EDA.ipynb`**: Exploratory Data Analysis. Visualizing correlations (e.g., Chest Pain vs. Disease) and understanding the dataset distributions.
* **`preprocessing_and_modelling.ipynb`**: Data cleaning, feature scaling, model training (Logistic Regression), and threshold tuning.

### 🛠️ Languages and Packages
* **Core:** Python 3.9+ (Tested on 3.13.5)
* **Data & Math:** `pandas`, `numpy`
* **Machine Learning:** `scikit-learn` (Logistic Regression)
* **Visualization:** `matplotlib`, `seaborn`

### 🧩 Project Roadmap

| Version | Focus | Description |
| :--- | :--- | :--- |
| **v1.x** | 🏗️ **Baseline** | Logistic Regression baseline. v1.1 will refactor code into Pipelines for cleaner inference. |
| **v2.x** | 🌳 **Trees** | Implementation of Tree-based models (Random Forest, XGBoost) to improve accuracy and handle non-linear data. |
| **v3.x** | 🧠 **Deep Learning** | Neural Networks (Keras/TensorFlow) for complex pattern recognition, plus a **Streamlit UI** for public interaction. |

### 💻 How to Run
1.  **Clone the repository:**
    \`\`\`bash
    git clone https://github.com/UwaisTomkins124/heart_disease_predictoredictor.git
    cd heart-disease-predictor
    \`\`\`

2.  **Install dependencies:**
    \`\`\`bash
    pip install -r requirements.txt
    \`\`\`

3.  **Run the Notebooks:**
    Launch Jupyter Lab or VS Code to explore \`EDA.ipynb\` for insights or \`preprocessing_and_modelling.ipynb\` for the model logic.
EOF
