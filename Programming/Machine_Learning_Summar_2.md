# ML Flow.
### 1. Problem Specification.
- Classification (discrete target variable).
- Regression (continuous target variable).
### 2. Pipeline Construction.
- From start to end of whole process.
- Component.
  - Each step of pipeline.
  - Independent process to other components.
  - Asyncronized update to other components.
### 3. Construction of Technical and Concrete Parts.
- Models.
- Uni Variate Problem/Multi Variate Problem.
### 4. Selection of Performance Measurement.
How to determine accuracy.
- RMSE (Root Mean Square Error).
  - In regression.
  - L2 norm.
  - $RMSE(X,h)=\sqrt{\frac{1}{m}\displaystyle\sum_{i=1}^{m}(h(x^{(i)})-y^{(i)})^2}$
- MAE (Mean Absolute Error).
  - In regression.
  - L1 norm.
  - $MAE(X,h)=\frac{1}{m}\displaystyle\sum_{i=1}^{m}\left\lvert h(x^{(i)})-y^{(i)}\right\rvert$
### 5. Installation of Virtual Environment.
- Virtual Environment.
  - Running Environment of Python Independednt to Each Other.
  - Can have different versions of packages from other virtual environments.
### 6. Data Validation.
Checking normality and correctness of data itself (regardless of problem).
- Pandas: head(), info(), value_counts(), describe(), hist(), etc.
### 7. Split Test Set from Train Set.
### 8. EDA (Exploratory Data Analysis) with Train Set.
Analysis of data using various ways (mean, std, histogram, etc).
- Matplotlib.
### 9. Data Rendering (including Preprocessing).
- Nominal Variable/Numerical Variable Cheking.
- Unity of Various Unit.
### 10. Model Seclection, Training, Test, Performance Improvement (Tuning), Final Model Release.
### 11. Monitoring and Maintenance.
