# OptiPrice Prognosticator

This project implements a real-time dynamic fare prediction system for ride-sharing using machine learning. It uses XGBoost for regression and Gradio for a simple, interactive interface. The model takes into account demand-supply ratio, loyalty status, peak booking times, and vehicle type to predict ride fares with high accuracy.

---

## 🎯 Objective

To predict dynamic ride fares based on:
- Number of riders vs drivers (demand-supply)
- Ride duration and booking time
- Customer loyalty status
- Vehicle type (Economy, Premium, Luxury)
- Historical cost patterns
---

## 🧰 Technologies Used

- Python  
- XGBoost  
- Scikit-learn  
- Pandas & NumPy  
- Gradio (for UI)  
- Matplotlib & Seaborn (for analysis)

---

## 📊 Model Performance

| Metric               | Value     |
|----------------------|-----------|
| Mean Absolute Error  | **5.16**  |
| Root Mean Squared Error | **9.92** |
| R² Score             | **1.00**  |
| Base Fare RMSE       | **515.61** |
| Improvement Over Base | **98.08%** |

✅ The model drastically outperforms a simple base fare estimate based on ride duration.

### 📷 Output Preview

![Output Preview](output_preview.jpg)

