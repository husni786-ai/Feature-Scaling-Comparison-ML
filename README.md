# 📏 Feature Scaling Comparison: Standardization vs. Normalization

This project provides a foundational Jupyter Notebook demonstrating the critical data preprocessing step of **Feature Scaling** in Machine Learning. It compares two primary scaling methods—**Standardization (Z-Score)** and **Normalization (MinMaxScaler)**—and illustrates how each method affects the performance of a simple classification model (Decision Tree).

---

## 🎯 Project Goals

The objective of this notebook is to implement and compare the effects of different scaling techniques:

1.  **Data Creation:** Define a small, synthetic dataset with common numerical features (e.g., age, salary).
2.  **Scaling Implementation:** Apply both `StandardScaler` (Standardization) and `MinMaxScaler` (Normalization) to the input features.
3.  **Model Training:** Train two instances of a `DecisionTreeClassifier`: one on the original (unscaled) data and one on the scaled data.
4.  **Performance Evaluation:** Compare the accuracy scores of the models to demonstrate how scaling can influence model training.

## 🗃️ Dataset Used

The notebook uses a small, **synthetic Pandas DataFrame** created within the script. The features include:
* `age`: Customer age (numerical).
* `Estimatedsalary`: Customer salary (numerical).
* `Purchased`: The target variable (binary, 0 or 1).

## ⚙️ Technology Stack and Dependencies

The project relies on standard Python libraries for data science and machine learning:

| Library | Role |
| :--- | :--- |
| **`pandas` & `numpy`** | Data structure creation and numerical operations. |
| **`scikit-learn`** | Core ML components: Model selection (`train_test_split`), Scaling (`MinMaxScaler`, `StandardScaler`), and Classification (`DecisionTreeClassifier`). |
| **`seaborn` & `matplotlib`** | Used for data visualization to compare feature distributions before and after scaling (implied). |

### Installation
```bash
pip install pandas numpy scikit-learn seaborn matplotlib

```bash
pip install pandas numpy scikit-learn seaborn matplotlib
