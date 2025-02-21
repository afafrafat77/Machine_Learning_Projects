# Agricultural Production Optimization Engine  

## Overview  
This project utilizes **Machine Learning** to optimize crop selection based on **soil composition** and **climatic conditions**. The approach involves:  
1. **Clustering crops into seasonal categories** based on shared attributes.  
2. **Predicting the category of a given test sample** using classification models.  

## Dataset  
The dataset includes **22 crop types** (e.g., maize, wheat, mango), with the following features:  
- **Soil Composition**:  
  - Nitrogen (N)  
  - Phosphorus (P)  
  - Potassium (K)  
  - pH  

- **Climate Factors**:  
  - Temperature  
  - Humidity  
  - Rainfall  

## Approach  
### 1. Clustering Phase  
- Crops are grouped into distinct **seasonal categories** based on soil and climate conditions.  
- Clustering methods used: **K-Means**.  

### 2. Classification Phase  
- A **classification model** is trained to predict the category of new crop samples.  
- Models used: **Logistic Regression, Random Forest**.  

## Technologies & Tools Used  
- **Programming Language**: Python  
- **Development Environment**: Jupyter Notebook  
- **Libraries Used**:  
  - Pandas, NumPy - Data Processing  
  - Seaborn, Matplotlib - Data Visualization  
  - Sklearn - Machine Learning Algorithms  

## Usage  
### 1. Clone the Repository  
```bash
git clone https://github.com/afafrafat77/Machine_Learning_Projects/Agricultural-Production-Optimization.git
cd Agricultural-Production-Optimization

