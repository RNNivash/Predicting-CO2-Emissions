### 🚀 Predicting CO₂ Emissions using Linear Regression  

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)  
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-0.24%2B-orange)  
![Data Science](https://img.shields.io/badge/Data%20Science-Regression-green)

## 📌 Overview  
This project applies **Simple and Multiple Linear Regression** to analyze the relationship between vehicle attributes and **CO₂ emissions**. Using Python and `scikit-learn`, we build and evaluate predictive models to understand the key factors affecting emissions.  

## 📂 Dataset  
The dataset `FuelConsumptionCo2.csv` includes the following key features:  
- **Engine Size**  
- **Cylinders**  
- **Fuel Consumption (City, Highway, Combined)**  
- **CO₂ Emissions (g/km)**  

📌 **[Dataset Source](http://open.canada.ca/data/en/dataset/98f1a129-f628-4ce4-b24d-6f16bf24dd64)**  

## ⚙️ Installation & Requirements  
Ensure you have Python and the necessary libraries installed:  

```bash
pip install numpy pandas matplotlib scikit-learn
```

## 📊 Project Workflow  
### 1️⃣ Data Exploration  
- Load dataset using `pandas`  
- Analyze correlations using visualizations  

### 2️⃣ Data Preprocessing  
- Select relevant features  
- Split data into **Training (80%)** and **Testing (20%)**  

### 3️⃣ Model Training & Evaluation  
#### ✅ **Simple Linear Regression**  
- Uses **Engine Size** to predict CO₂ Emissions  
- Evaluation Metrics:  
  - **Mean Absolute Error (MAE)**  
  - **Mean Squared Error (MSE)**  
  - **R² Score**  

#### ✅ **Multiple Linear Regression**  
- Uses multiple predictors:  
  - **Engine Size**, **Cylinders**, **Fuel Consumption (Combined)**  
- Improves prediction accuracy compared to Simple Linear Regression  

## 📈 Results & Key Takeaways  
- **Simple Linear Regression**: Shows a moderate correlation between **Engine Size** and **CO₂ Emissions**  
- **Multiple Linear Regression (MLR)** provides a more accurate model by incorporating multiple variables  
- **MLR outperforms Simple Regression**, as fuel consumption and number of cylinders significantly impact emissions  
- **R² Score Comparison**: MLR achieves a higher score, indicating better predictive power  

## 🏆 Future Enhancements  
🔹 Experiment with feature selection techniques to improve model performance  
🔹 Apply **Polynomial Regression** for non-linear relationships  
🔹 Implement **Regularization (Ridge & Lasso Regression)** to handle multicollinearity  

---

💡 **Author**: [Nivash R N](https://www.linkedin.com/in/nivash-r-n/)  
🔗 **Portfolio**: [rnnivash.github.io/My_Port/](https://rnnivash.github.io/My_Port/)  
