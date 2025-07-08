# 📈 Multiple Linear Regression – Startup Profit Prediction

This project demonstrates **Multiple Linear Regression** to predict startup profit based on different expenses and the state of operation. The model is built using core Python libraries.
---

## 📁 Dataset Overview

- File: `startup_data.xlsx.csv`
- Columns:
  - `R&D Spend`
  - `Administration`
  - `Marketing Spend`
  - `State` (Categorical)
  - `Profit` (Target)

---

## 📌 Project Workflow

1. **Import Libraries**
   - Used `pandas`, `numpy`, and `matplotlib`.

2. **Load Dataset**
   - Loaded the dataset and viewed column names using `.columns`.

3. **Preprocessing**
   - Divided the dataset into independent (X) and dependent (y) variables.
   - Checked unique values in the `State` column.
   - Applied **manual OneHotEncoding** to the `State` column.
   - Dropped the original `State` and merged the encoded columns.

4. **Data Splitting**
   - Split the dataset manually into training and testing sets (e.g., slicing).

5. **Model Training**
   - Built a **Multiple Linear Regression** model using basic Python logic or formulas.

6. **Prediction**
   - Predicted profit for testing data and for user input values.

7. **Visualization**
   - Plotted actual vs predicted values for better understanding.

8. **User Input**
   - User can input R&D Spend, Administration, Marketing Spend, and State.
   - Output:
     ```
     Your profit close to {predicted_value}
     ```

---

## 📊 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`

---
