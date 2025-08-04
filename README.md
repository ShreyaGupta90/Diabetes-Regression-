# 🩺 Diabetes Progression Prediction using Linear, Ridge & Lasso Regression

[![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)](https://www.python.org/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  
[![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)]()  
[![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-Regression-orange?logo=scikit-learn)](https://scikit-learn.org/)

---

## 📘 Overview

This project uses the **Diabetes Dataset** from Scikit-learn to build and compare three regression models:

- 📈 Linear Regression  
- 🧩 Ridge Regression (L2 Regularization)  
- ✂️ Lasso Regression (L1 Regularization)  

The goal is to understand how regularization improves model performance by reducing overfitting and enhancing generalization.

---

## 🧠 About the Dataset

The **Diabetes dataset** is a well-known dataset included in `sklearn.datasets`.  
It includes:

- 🧬 442 patient records  
- 🔟 Features: Age, BMI, Blood Pressure, etc.  
- 🎯 Target: Disease progression after one year

```python
from sklearn.datasets import load_diabetes
data = load_diabetes()
```

---

## 🛠️ Models Used

### 🔹 Linear Regression  
Fits a straight line through the data. Easy to interpret but may overfit on complex data.

### 🔹 Ridge Regression (L2)  
Penalizes large coefficients and reduces model complexity. Helps with multicollinearity.

### 🔹 Lasso Regression (L1)  
Can shrink some coefficients to zero, effectively performing feature selection.

---

## 📈 Evaluation Metrics

- ✅ Mean Squared Error (MSE)  
- ✅ R² Score  
- ✅ Coefficients comparison  
- ✅ Actual vs Predicted visualization

---

## 📊 Visual Outputs

| Coefficients Comparison | Actual vs Predicted |
|-------------------------|---------------------|
| ![Coefficients](./visuals/coefficients_plot.png) | ![Predictions](./visuals/prediction_plot.png) |

*Make sure you save your plot images inside a `/visuals/` folder.*

---

## 📦 Requirements

Install required packages:

```bash
pip install numpy pandas matplotlib scikit-learn
```

---

## 🚀 How to Run

Clone this repository:

```bash
git clone https://github.com/ShreyaGupta90/Diabetes-Regression-.git
cd Diabetes-Regression-
```

Run the script or notebook:

```bash
python regression_(diabetes).py
# OR
jupyter notebook Regression_(Diabetes).ipynb
```

---

## 📂 Project Structure

```
📁 diabetes-regression/
├── Regression_(Diabetes).ipynb
├── regression_(diabetes).ipynb
├── README.md
├── requirements.txt
```

---

## 🔗 GitHub Repository

🔗 [github.com/ShreyaGupta90/Diabetes-Regression-](https://github.com/ShreyaGupta90/Diabetes-Regression-)  

---

## 🙋‍♀️ Author

**Shreya Gupta**  
👩‍💻 Aspiring ML Engineer | Python & AI Enthusiast  
📫 [LinkedIn](https://www.linkedin.com/in/shreya-gupta-2a6a292ab)  
📧 [shreyagupta119809@gmail.com](mailto:shreyagupta119809@gmail.com)

---

## 📄 License

This project is licensed under the **MIT License**.  
See the [LICENSE](./LICENSE) file for more details.

---

## 🌟 Support

If you find this helpful, please consider giving it a ⭐  
Feedback and contributions are always welcome 💬✨
