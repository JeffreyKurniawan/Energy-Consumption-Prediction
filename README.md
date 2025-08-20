# Building Energy Consumption Prediction with Solar Panels ⚡🏢🌞  

This project develops machine learning and deep learning models to **predict the energy consumption of a building equipped with solar panels**. The workflow includes data preprocessing, feature engineering, model training, and evaluation across multiple neural network architectures.  

## 🔧 Features  

### Data Preprocessing  
- Label encoding for categorical variables (Holiday, HVACUsage, LightingUsage)  
- One-hot encoding for temporal features (Month, DayOfWeek)  
- Scaling of numerical features using **RobustScaler**  
- Normality testing with **Shapiro-Wilk**  

### Model Architectures Compared  
1. **Sequential Model** – simple feedforward network built with Keras Sequential API  
2. **Functional Model** – flexible architecture built with Keras Functional API  
3. **Modified Sequential Model** – tuned with additional layers, dropout, and activation adjustments  
4. **Modified Functional Model** – functional model with deeper structure and dropout regularization  

### Model Evaluation  
- **Metrics**: RMSE, MAE, R² Score  
- Visualization of predicted vs actual energy consumption  
- Comparison of performance across all four models  

---

## 🧠 Concepts Used  
- Regression with neural networks (Keras/TensorFlow)  
- Supervised learning for energy demand prediction  
- Feature engineering (categorical encoding, scaling, temporal features)  
- Model regularization with dropout layers  
- Evaluation with RMSE, MAE, and R²  
- Comparative analysis of multiple deep learning architectures  

---
