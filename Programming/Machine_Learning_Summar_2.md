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
- In Regard of Models.
- Uni Variate Problem/Multi Variate Problem.
### 4. Selection of Performance Measurement.
How to determine accuracy.
- RMSE (Root Mean Square Error).
  - In regression.
  - $L_2$ norm.
  - $RMSE(X,h)=\sqrt{\frac{1}{m}\displaystyle\sum_{i=1}^{m}(h(x^{(i)})-y^{(i)})^2}$
- MAE (Mean Absolute Error).
  - In regression.
  - $L_1$ norm.
  - $MAE(X,h)=\frac{1}{m}\displaystyle\sum_{i=1}^{m}\left\lvert h(x^{(i)})-y^{(i)}\right\rvert$
 > $L_k$ norm.
 > - Scalar: one number.
 > - Vector: one assembly of scalars (e.g. $v = <1, -1, 2>$).
 > - Norm $(L_K$ norm): one-number representation of vector.
 >    - $L_k$ norm of $v$ = $(\lvert v_1 \rvert+\dots +\lvert v_d \rvert^k)^\frac{1}{k}$ (d: number of elements of vector)
### 5. Installation of Virtual Environment.
- Virtual Environment.
  - Independent Running Environment by Project.
  - Can have different versions of packages from other virtual environments.
### 6. Data Validation.
Checking normality and correctness of data itself (regardless of problem).
### 7. Split Test Set from Train Set.
### 8. EDA (Exploratory Data Analysis) with Train Set.
Analysis of data using various ways (mean, std, histogram, etc).
- Using Pandas, Numpy, Matplotlib Libraries.
### 9. Data Rendering (including Preprocessing).
- Nominal Variable/Numerical Variable Cheking.
- Unity of Various Unit.
### 10. Model Seclection, Training, Test, Performance Improvement (Tuning), Final Model Release.
### 11. Monitoring and Maintenance.
