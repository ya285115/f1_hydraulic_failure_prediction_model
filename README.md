# 🏎️ F1-Grade Hydraulic Failure Prediction System

**Advanced ML Pipeline for Safety-Critical Industrial Applications**

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://python.org)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.3+-orange.svg)](https://scikit-learn.org)
[![F1-Score](https://img.shields.io/badge/F1--Score-34.7%25-green.svg)](https://github.com/yourusername/f1-hydraulic-failure-prediction)

## **Technical Summary**

Advanced machine learning system for hydraulic failure prediction with direct applications to Formula 1 brake systems, power steering, and DRS mechanisms. Implements ensemble learning with statistical validation for safety-critical environments.

### **Key Achievements**
- **Best Model**: Gradient Boosting (F1: 34.7%)
- **Dataset**: 2,205 samples, 17 sensors (UCI standard)  
- **Statistical Validation**: Monte Carlo 95% CI [29.9%, 39.7%]
- **Production Pipeline**: Complete MLOps architecture
- **Feature Engineering**: PCA dimensionality reduction (95% variance retained)

### **Performance Metrics**
| Model | Test F1 | Accuracy | Status |
|-------|---------|----------|--------|
| **Gradient Boosting** | **0.347** | **0.460** | **Best** |
| Decision Tree | 0.330 | 0.424 | - |
| KNN | 0.318 | 0.433 | - |
| CatBoost | 0.317 | 0.449 | - |
| XGBoost | 0.311 | 0.424 | - |

### **Monte Carlo Reliability Analysis**
- **Mean F1**: 34.59% ± 2.53%
- **95% Confidence**: [29.92%, 39.66%]
- **Reliability Status**: Research-grade (requires optimization for production)

## **Technical Architecture**

---
1. **Data Pipeline:**
   - **Input Dataset:** UCI Dataset (Size: 2,205 rows × 17 features).

2. **Feature Engineering:**
   - **Preprocessing:** Applied PCA (Principal Component Analysis) for dimensionality reduction, preserving 95% of the variance.

3. **Model Training:**
   - **Algorithms:** Trained models using 11 machine learning algorithms.
   - **Optimization:** Grid Search CV for hyperparameter tuning.

4. **Validation:**
   - **Monte Carlo Simulation:** Validated models using 500 iterations for robust performance evaluation.
