# Predictive-Maintenance-of-Aircraft-Engines-Machine-Learning-Approaches-for-RUL

## Overview  
This project focuses on predictive maintenance for aircraft engines by estimating their Remaining Useful Life (RUL) using machine learning techniques. By leveraging NASA's C-MAPSS dataset, this system provides a scalable, efficient, and interpretable solution to enhance aviation safety, reduce costs, and optimize maintenance schedules.  

## Key Features  
- **Data Storage:** Scalable integration using PostgreSQL for efficient data management.  
- **Real-Time Visualization:** Interactive web application built with Flask for easy result interpretation.  
- **Machine Learning Models:** Tested multiple models, including XGBoost, Random Forest, SVM, and Linear Regression.  
- **Top Performance:** Achieved RMSE of 23.8 and R² of 0.67 with XGBoost.  
- **Explainable AI (XAI):** Feature importance analysis to ensure interpretability and trust in predictions.  

## Dataset  
- **Source:** NASA's C-MAPSS dataset  
- **Details:** Contains sensor data from aircraft engines, simulating various operating conditions.  

## Workflow  
1. **Data Preprocessing:**  
   - Normalization  
   - Noise removal using box plots  
   - Feature engineering  
2. **Model Training:**  
   - Trained and evaluated machine learning models, with XGBoost emerging as the best performer.  
3. **Visualization:**  
   - Flask application for real-time visualization of predictions and feature contributions.  

## Results  
- **Best Model:** XGBoost  
- **Performance Metrics:**  
  - RMSE: 23.8  
  - R²: 0.67  

## Technologies Used  
- **Programming Language:** Python  
- **Data Storage:** PostgreSQL  
- **Web Framework:** Flask  
- **Machine Learning Tools:** Scikit-learn, XGBoost, Pandas, NumPy  
- **Visualization Tools:** Matplotlib, Seaborn  

