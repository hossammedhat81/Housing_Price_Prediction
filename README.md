# 🏠 House Price Prediction with XGBoost

**Author:** Hossam Medhat Shokry

A comprehensive machine learning project that predicts housing prices using the Boston Housing dataset and XGBoost regression algorithm with advanced data visualization and analysis.

## 📊 Project Overview

This project implements a robust housing price prediction model using XGBoost regression. The analysis includes comprehensive exploratory data analysis, feature engineering, model training, and extensive visualization to understand both model performance and the underlying patterns in housing data.

## 🎯 Key Features

- **Advanced Machine Learning**: XGBoost regression for accurate price predictions
- **Comprehensive Analysis**: Correlation analysis, feature importance, and residual analysis
- **Rich Visualizations**: Multiple chart types including heatmaps, scatter plots, histograms, and box plots
- **Model Evaluation**: R² score, Mean Absolute Error, and visual performance metrics
- **Feature Engineering**: Proper data preprocessing and feature selection

## 🛠️ Technologies Used

### **Core Libraries:**
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computing
- **scikit-learn** - Machine learning algorithms and metrics
- **XGBoost** - Gradient boosting framework

### **Visualization Tools:**
- **matplotlib** - Basic plotting and visualization
- **seaborn** - Statistical data visualization

### **Development Environment:**
- **Jupyter Notebook** - Interactive development environment
- **Python 3.x** - Programming language

## 📈 Dataset Information

**Boston Housing Dataset** contains 506 samples with 14 features:
- **CRIM**: Crime rate per capita
- **ZN**: Proportion of residential land zoned for lots over 25,000 sq.ft.
- **INDUS**: Proportion of non-retail business acres
- **CHAS**: Charles River dummy variable
- **NOX**: Nitric oxides concentration
- **RM**: Average number of rooms per dwelling
- **AGE**: Proportion of owner-occupied units built prior to 1940
- **DIS**: Weighted distances to employment centers
- **RAD**: Index of accessibility to radial highways
- **TAX**: Property tax rate
- **PTRATIO**: Pupil-teacher ratio
- **B**: Proportion of blacks by town
- **LSTAT**: Lower status of the population
- **MEDV**: Median value of homes (Target variable)

## 🔍 Analysis Workflow

### 1. **Data Exploration**
   - Dataset shape and structure analysis
   - Missing value detection
   - Statistical summary and data types

### 2. **Correlation Analysis**
   - Comprehensive correlation matrix
   - Heatmap visualization
   - Feature relationship identification

### 3. **Model Development**
   - Data splitting (80% train, 20% test)
   - XGBoost model training
   - Hyperparameter optimization

### 4. **Model Evaluation**
   - R² Score calculation
   - Mean Absolute Error assessment
   - Training vs Test performance comparison

### 5. **Advanced Visualizations**
   - **Scatter Plots**: Actual vs Predicted prices
   - **Residual Analysis**: Error distribution and patterns
   - **Feature Importance**: Key factors driving predictions
   - **Distribution Comparison**: Price range analysis

## 📊 Model Performance

The XGBoost model demonstrates strong performance with:
- High R² scores on both training and test data
- Low Mean Absolute Error indicating accurate predictions
- Consistent performance across different price ranges

## 📝 Key Insights

1. **Feature Impact**: Room count (RM) and socioeconomic status (LSTAT) are primary price drivers
2. **Model Accuracy**: XGBoost provides excellent prediction accuracy with minimal overfitting
3. **Error Patterns**: Residual analysis shows normally distributed errors indicating good model fit

## 👨‍💻 Author

**Hossam Medhat Shokry**
- Data Science Student
- Machine Learning Enthusiast
- Python Developer



⭐ **Star this repository if you found it helpful!**
