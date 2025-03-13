### 🚀 Simple Linear Regression - Predicting CO2 Emissions  

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)  
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-0.24%2B-orange)  
![Data Science](https://img.shields.io/badge/Data%20Science-Regression-green)

## 📌 Overview  
This project demonstrates **Simple Linear Regression** using Python to analyze the relationship between vehicle engine size and CO₂ emissions. The dataset contains fuel consumption ratings and estimated CO₂ emissions for vehicles in Canada.  

## 📂 Dataset  
The dataset used is `FuelConsumptionCo2.csv`, which includes attributes like:  
- **Engine Size**  
- **Cylinders**  
- **Fuel Consumption (City, Highway, Combined)**  
- **CO₂ Emissions (g/km)**  

## ⚙️ Installation & Requirements  
Ensure you have Python and the necessary libraries installed:  

```bash
pip install numpy pandas matplotlib scikit-learn
```

## 📊 Steps in the Project  
### 1️⃣ Data Exploration  
- Load dataset using `pandas`  
- Visualize relationships between variables  

### 2️⃣ Data Preprocessing  
- Select key features (`Engine Size`, `Fuel Consumption`, `CO₂ Emissions`)  
- Split data into **Training (80%)** and **Testing (20%)**  

### 3️⃣ Model Training & Evaluation  
- Train a **Linear Regression** model using `scikit-learn`  
- Evaluate the model using:  
  - **Mean Absolute Error (MAE)**  
  - **Mean Squared Error (MSE)**  
  - **R² Score**  

## 📈 Results  
- **Engine Size vs. CO₂ Emissions**: Moderate correlation  
- **Fuel Consumption vs. CO₂ Emissions**: Stronger correlation  
- **Model Performance**: Regression using **Fuel Consumption** as a feature performed better than using **Engine Size** alone.  

## 📌 Key Takeaways  
✅ Fuel Consumption is a stronger predictor of CO₂ emissions than Engine Size.  
✅ Evaluating different features helps improve model accuracy.  
✅ Linear Regression is a great starting point for predictive modeling.  

## 🏆 Future Enhancements  
🔹 Try **Multiple Linear Regression** with multiple features  
🔹 Implement **Polynomial Regression** for better fitting  
🔹 Use **Feature Engineering** for better model accuracy  

---

💡 **Author**: [Nivash R N](https://www.linkedin.com/in/nivash-r-n/)  
🔗 **Portfolio**: [rnnivash.github.io/My_Port/](https://rnnivash.github.io/My_Port/)  
📧 **Contact**: hello.nivashinsights@gmail.com  
