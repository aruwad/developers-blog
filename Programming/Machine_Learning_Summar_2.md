# ML Flow.
### 1. Problem Specification.
- Classification (discrete target variable).
- Regression (continuous target variable).
### 2. Pipeline Construction.
- From start to end of the whole process.
- Component.
  - Each unit of pipeline.
  - Independent process to other components.
  - Asyncronized update to other components.
### 3. Construction of Technical and Concrete Parts.
- Uni Variate Problem/Multi Variate Problem.
### 4. Performance Measurement.
How to determine accuracy.
- RMSE (root mean square error).
  - In regression.
  - L2 norm.
  - $RMSE(X,h)=\sqrt{\frac{1}{m}\displaystyle\sum_{i=1}^{m}(h(x^{(i)})-y^{(i)})^2}$
- MAE (mean absolute error).
  - In regression.
  - L1 norm.
  - $MAE(X,h)=\frac{1}{m}\displaystyle\sum_{i=1}^{m}\left\lvert h(x^{(i)})-y^{(i)}\right\rvert$
### 5. Installation of Anaconda & Virtual Environment.
- Virtual Environment.
  - Independnet Running Environment of Python.
  - Can have different version of package from other virtual environment.
### 6. Data Validation.
Check data is normal.
### 7. Split Test Set.
### 8. EDA (Exploratory Data Analysis) with Train Set.
Analyze data using various ways (mean, std, histogram, etc).
### 9. Data Rendering (including Preprocessing).
- Nominal variable/Numerical variable.
- Unity of unit.
### 10. Model Seclection, Training, Test, Tuning, Final Model.
### 11. Monitoring and Maintenance.
