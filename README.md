# Multi-Layer Perceptron for Predicting Child Poverty Levels

This project implements a Multi-Layer Perceptron (MLP) from scratch to analyze U.S. Census demographic data. The primary goal is to predict child poverty levels in U.S. counties based on demographic, economic, and social measurements. The project leverages data from the U.S. Census Bureau to uncover key factors that influence poverty dynamics.

---

## About the Dataset

### Domain:
- **Poverty Prediction**: Understanding child poverty levels and the underlying demographic and economic factors contributing to them.
- **Purpose**: Enabling data-driven decisions for policy-making and intervention strategies aimed at reducing poverty.

### Dataset Overview:
- **Data Type**: Tabular data containing numeric and categorical variables.
- **Task**: Regression to predict child poverty levels.
- **Attributes**:
  - **Features**: Includes age distribution, household income, employment status, education levels, housing characteristics, and family structure.
  - **Target Variable**: Child poverty level in U.S. counties.

### Data Source:
- US Census Demographic Data: https://www.kaggle.com/datasets/muonneutrino/us-census-demographic-data/data

---

## Project Objectives

1. **Custom Multi-Layer Perceptron Implementation**:
   - Built using Python with a focus on scalability and interpretability.
   - Designed to handle tabular data with a mix of numeric and categorical features.
   - Supports activation functions, regularization techniques, and optimization algorithms.

2. **Comparative Analysis**:
   - Benchmarked the custom MLP against other machine learning models, such as linear regression and decision trees.
   - Evaluated performance using training time, accuracy, and generalization metrics.

3. **Feature Importance Analysis**:
   - Investigated the contribution of individual features to the prediction task.
   - Explored the impact of socio-economic and demographic variables on poverty levels.

4. **Visualization**:
   - Generated charts and plots to illustrate data distributions, model predictions, and performance metrics.

---

## Key Questions Explored

1. **Which demographic features have the strongest influence on child poverty levels?**
   - Explored using feature importance scores and correlation analysis.

2. **How does the custom MLP compare to standard regression models?**
   - Benchmarked using metrics like mean squared error (MSE) and R-squared values.

3. **What regularization and optimization techniques yield the best results?**
   - Evaluated using validation plots and learning curves.

---

### Data Preprocessing:
1. **Scaling**: Standardized numeric features to improve model performance.
2. **Encoding**: One-hot encoding applied to categorical variables.
3. **Splitting**: Dataset divided into 80% training and 20% testing data for model validation.

---

## Results

1. **Custom MLP**:
   - Achieved competitive performance compared to other machine learning models.
   - Demonstrated the ability to capture complex relationships in the data.
   - Regularization techniques helped improve generalization.

2. **Comparative Analysis**:
   - Highlighted the strengths and weaknesses of the MLP versus simpler models like linear regression.
   - Showcased the flexibility and scalability of the MLP for large datasets.

---

## Tools and Libraries Used

- **Python**: Programming language.
- **Jupyter Notebook**: Interactive coding environment.
- **NumPy**: Numerical operations.
- **Pandas**: Data manipulation.
- **Matplotlib/Seaborn**: Data visualization.
- **Scikit-learn**: Model comparison and benchmarking.

---

## Project Structure

```plaintext
.
├── Multi-Layer-Perceptron.ipynb        # Main Jupyter Notebook
├── README.md                          # Project documentation
```

---

## How to Run

### 1. Clone the Repository:
```bash
git clone https://github.com/multi-layer-perceptron/predicting-poverty.git
cd predicting-poverty
```

### 2. Install Dependencies:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### 3. Run the Notebook:
- **Open Jupyter Notebook**:
```bash
jupyter notebook Multi-Layer-Perceptron.ipynb
```
- Run all cells to reproduce the analysis.

